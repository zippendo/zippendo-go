# Zippendo Go SDK

Official Go client for the [Zippendo](https://zippendo.com) shipping & logistics API. Requires
Go 1.18+.

## Install

```sh
go get github.com/zippendo/zippendo-go
```

## Authentication

Create an API token in your Zippendo dashboard (**Settings → API tokens**) — a Bearer token prefixed
with `zipp_`. Supply it via the request context:

```go
import (
	"context"
	"os"

	zippendo "github.com/zippendo/zippendo-go"
)

client := zippendo.NewAPIClient(zippendo.NewConfiguration())
ctx := context.WithValue(context.Background(), zippendo.ContextAccessToken, os.Getenv("ZIPPENDO_API_TOKEN"))
```

The base URL defaults to `https://api.zippendo.com`.

## Resources & services

The API is split into resource services on the client — `ShipmentsAPI`, `OrdersAPI`, `CarriersAPI`,
`AddressesAPI`, `RulesAPI`, `WebhooksAPI`, `TokensAPI`, and more.

## The `orgId` parameter

Every call takes an `orgId` (your organization ID, found in the dashboard). It is explicit on each
call by design: one API token can be granted access to multiple organizations, and `orgId` selects
which one the request acts on.

## Brands

A **brand** is a sub-account inside an organization: one company running several consumer-facing
labels (say Pitaya and Kiwi) keeps each label's orders and shipments separate, with its own company
name, address and logo on the documents its shipments produce. Scope a request to one brand with the
`X-Zippendo-Brand` header, whose value is the brand's ID or slug.

The header is not a method parameter — it applies uniformly to every operation, so set it once as a
default header on the `Configuration` and every call inherits it:

```go
cfg := zippendo.NewConfiguration()
cfg.AddDefaultHeader("X-Zippendo-Brand", "pitaya") // brand ID or slug
client := zippendo.NewAPIClient(cfg)

shipments, _, err := client.ShipmentsAPI.ListShipments(ctx, "org_8f3kd92ld0").Limit(50).Execute()
if err != nil {
	panic(err)
}
fmt.Println(shipments.GetTotal()) // only Pitaya's shipments; new shipments are stamped with the brand
```

Omit the header and the request covers the whole organization — the behaviour of every existing
token.

An API token created with a `brandId` is permanently confined to that brand and needs no header at
all. Sending `X-Zippendo-Brand` naming a *different* brand on such a token is refused with
`403 BRAND_ACCESS_DENIED`; the binding is never widened. A brand that does not exist in the
organization gives `404 BRAND_NOT_FOUND`.

Creating, updating and deleting brands is done in the Zippendo dashboard — there are no brand
management endpoints in this SDK.

## Listing & pagination

List endpoints accept `.Page(...)` (1-based) and `.Limit(...)`, and return a page with `GetData()`
plus `GetTotal()`, `GetPage()`, `GetLimit()`, and `GetTotalPages()`:

```go
result, _, err := client.ShipmentsAPI.ListShipments(ctx, "org_8f3kd92ld0").Page(1).Limit(50).Execute()
if err != nil {
	panic(err)
}
fmt.Println(result.GetData())                         // []Shipment
fmt.Println(result.GetTotal(), result.GetTotalPages())
```

## Creating resources

```go
lines := []zippendo.CreateOrderRequestOrderLinesInner{*zippendo.NewCreateOrderRequestOrderLinesInner("T-shirt", 2)}
body := zippendo.NewCreateOrderRequest("1001", "chan_7d2k1", lines)

order, _, err := client.OrdersAPI.CreateOrder(ctx, "org_8f3kd92ld0").CreateOrderRequest(*body).Execute()
if err != nil {
	panic(err)
}
fmt.Println(order.GetId())
```

See [`./docs`](./docs) for the full request/response shape of every operation.

## Error handling

Non-2xx responses return an error and an `*http.Response`. The body is Zippendo's canonical
`{ code, error, message }`:

```go
_, httpRes, err := client.ShipmentsAPI.GetShipment(ctx, "org_8f3kd92ld0", "shp_missing").Execute()
if err != nil {
	if apiErr, ok := err.(*zippendo.GenericOpenAPIError); ok {
		fmt.Println(httpRes.StatusCode, string(apiErr.Body())) // {"code":"SHIPMENT_NOT_FOUND", ...}
	}
}
```

## Configuration

Point the client at a different environment:

```go
cfg := zippendo.NewConfiguration()
cfg.Servers = zippendo.ServerConfigurations{{URL: "https://staging.api.zippendo.com"}}
client := zippendo.NewAPIClient(cfg)
```

## Reference

Full per-endpoint and per-model documentation is in [`./docs`](./docs). Hosted reference:
<https://www.zippendo.com/docs/api-reference/overview>.

## License

[MIT](./LICENSE.md)
