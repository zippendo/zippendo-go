# \OrderChannelsAPI

All URIs are relative to *https://api.zippendo.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateOrderChannel**](OrderChannelsAPI.md#CreateOrderChannel) | **Post** /orgs/{orgId}/order-channels | Create order channel
[**CreateOrderChannelWebhookSecret**](OrderChannelsAPI.md#CreateOrderChannelWebhookSecret) | **Post** /orgs/{orgId}/order-channels/{channelId}/webhook-secret | Create or rotate webhook signing secret
[**DeleteOrderChannel**](OrderChannelsAPI.md#DeleteOrderChannel) | **Delete** /orgs/{orgId}/order-channels/{channelId} | Delete order channel
[**GetOrderChannel**](OrderChannelsAPI.md#GetOrderChannel) | **Get** /orgs/{orgId}/order-channels/{channelId} | Get order channel
[**GetOrderChannelWebhookStatus**](OrderChannelsAPI.md#GetOrderChannelWebhookStatus) | **Get** /orgs/{orgId}/order-channels/{channelId}/webhooks | Get channel webhook status
[**ListOrderChannels**](OrderChannelsAPI.md#ListOrderChannels) | **Get** /orgs/{orgId}/order-channels | List order channels
[**RevokeOrderChannelWebhookSecret**](OrderChannelsAPI.md#RevokeOrderChannelWebhookSecret) | **Delete** /orgs/{orgId}/order-channels/{channelId}/webhook-secret | Revoke webhook signing secret
[**UpdateOrderChannel**](OrderChannelsAPI.md#UpdateOrderChannel) | **Patch** /orgs/{orgId}/order-channels/{channelId} | Update order channel



## CreateOrderChannel

> ListOrderChannels200ResponseDataInner CreateOrderChannel(ctx, orgId).CreateOrderChannelRequest(createOrderChannelRequest).Execute()

Create order channel



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/zippendo/zippendo-go"
)

func main() {
	orgId := "org_8f3kd92ld0" // string | Organization ID
	createOrderChannelRequest := *openapiclient.NewCreateOrderChannelRequest("Anna's webshop", "custom") // CreateOrderChannelRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrderChannelsAPI.CreateOrderChannel(context.Background(), orgId).CreateOrderChannelRequest(createOrderChannelRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrderChannelsAPI.CreateOrderChannel``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateOrderChannel`: ListOrderChannels200ResponseDataInner
	fmt.Fprintf(os.Stdout, "Response from `OrderChannelsAPI.CreateOrderChannel`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateOrderChannelRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createOrderChannelRequest** | [**CreateOrderChannelRequest**](CreateOrderChannelRequest.md) |  | 

### Return type

[**ListOrderChannels200ResponseDataInner**](ListOrderChannels200ResponseDataInner.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateOrderChannelWebhookSecret

> CreateOrderChannelWebhookSecret201Response CreateOrderChannelWebhookSecret(ctx, orgId, channelId).Execute()

Create or rotate webhook signing secret



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/zippendo/zippendo-go"
)

func main() {
	orgId := "clz9k2f0a0000abcd0000zzzz" // string | Organization ID.
	channelId := "clz9k2f0a0001abcd1234efgh" // string | Order channel ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrderChannelsAPI.CreateOrderChannelWebhookSecret(context.Background(), orgId, channelId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrderChannelsAPI.CreateOrderChannelWebhookSecret``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateOrderChannelWebhookSecret`: CreateOrderChannelWebhookSecret201Response
	fmt.Fprintf(os.Stdout, "Response from `OrderChannelsAPI.CreateOrderChannelWebhookSecret`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID. | 
**channelId** | **string** | Order channel ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateOrderChannelWebhookSecretRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**CreateOrderChannelWebhookSecret201Response**](CreateOrderChannelWebhookSecret201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteOrderChannel

> RevokeApiToken200Response DeleteOrderChannel(ctx, orgId, channelId).Execute()

Delete order channel



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/zippendo/zippendo-go"
)

func main() {
	orgId := "clz9k2f0a0000abcd0000zzzz" // string | Organization ID.
	channelId := "clz9k2f0a0001abcd1234efgh" // string | Order channel ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrderChannelsAPI.DeleteOrderChannel(context.Background(), orgId, channelId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrderChannelsAPI.DeleteOrderChannel``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteOrderChannel`: RevokeApiToken200Response
	fmt.Fprintf(os.Stdout, "Response from `OrderChannelsAPI.DeleteOrderChannel`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID. | 
**channelId** | **string** | Order channel ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteOrderChannelRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**RevokeApiToken200Response**](RevokeApiToken200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetOrderChannel

> ListOrderChannels200ResponseDataInner GetOrderChannel(ctx, orgId, channelId).Execute()

Get order channel



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/zippendo/zippendo-go"
)

func main() {
	orgId := "clz9k2f0a0000abcd0000zzzz" // string | Organization ID.
	channelId := "clz9k2f0a0001abcd1234efgh" // string | Order channel ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrderChannelsAPI.GetOrderChannel(context.Background(), orgId, channelId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrderChannelsAPI.GetOrderChannel``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetOrderChannel`: ListOrderChannels200ResponseDataInner
	fmt.Fprintf(os.Stdout, "Response from `OrderChannelsAPI.GetOrderChannel`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID. | 
**channelId** | **string** | Order channel ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetOrderChannelRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**ListOrderChannels200ResponseDataInner**](ListOrderChannels200ResponseDataInner.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetOrderChannelWebhookStatus

> GetOrderChannelWebhookStatus200Response GetOrderChannelWebhookStatus(ctx, orgId, channelId).Execute()

Get channel webhook status



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/zippendo/zippendo-go"
)

func main() {
	orgId := "clz9k2f0a0000abcd0000zzzz" // string | Organization ID.
	channelId := "clz9k2f0a0001abcd1234efgh" // string | Order channel ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrderChannelsAPI.GetOrderChannelWebhookStatus(context.Background(), orgId, channelId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrderChannelsAPI.GetOrderChannelWebhookStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetOrderChannelWebhookStatus`: GetOrderChannelWebhookStatus200Response
	fmt.Fprintf(os.Stdout, "Response from `OrderChannelsAPI.GetOrderChannelWebhookStatus`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID. | 
**channelId** | **string** | Order channel ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetOrderChannelWebhookStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**GetOrderChannelWebhookStatus200Response**](GetOrderChannelWebhookStatus200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListOrderChannels

> ListOrderChannels200Response ListOrderChannels(ctx, orgId).Page(page).Limit(limit).BrandId(brandId).BrandScope(brandScope).Type_(type_).Enabled(enabled).Search(search).Execute()

List order channels



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/zippendo/zippendo-go"
)

func main() {
	orgId := "org_8f3kd92ld0" // string | Organization ID
	page := int32(1) // int32 | Page number (1-based) (optional) (default to 1)
	limit := int32(20) // int32 | Items per page (max 100) (optional) (default to 20)
	brandId := "brnd_8f3kd92ld0" // string | Filter by brand. Pass a brand ID, or \"none\" for records not assigned to any brand. (optional)
	brandScope := "own" // string | How the brand context narrows this list: \"own\" returns only rows assigned to the current brand (requires a brand session, a brand-bound token, or the X-Zippendo-Brand header), \"shared\" returns only unassigned organization-wide rows, \"both\" (default) returns both. The X-Zippendo-Brand-Scope header supplies a default when the parameter is omitted. For strictly brand-owned records (orders, shipments), a brand-scoped request combined with \"shared\" returns no rows, since those records are never visible organization-wide from within a brand context. (optional)
	type_ := "shopify" // string | Filter by channel type. (optional)
	enabled := "true" // string | Filter by enabled state. (optional)
	search := "Anna's Shopify Store" // string | Search by channel name. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrderChannelsAPI.ListOrderChannels(context.Background(), orgId).Page(page).Limit(limit).BrandId(brandId).BrandScope(brandScope).Type_(type_).Enabled(enabled).Search(search).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrderChannelsAPI.ListOrderChannels``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListOrderChannels`: ListOrderChannels200Response
	fmt.Fprintf(os.Stdout, "Response from `OrderChannelsAPI.ListOrderChannels`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiListOrderChannelsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **page** | **int32** | Page number (1-based) | [default to 1]
 **limit** | **int32** | Items per page (max 100) | [default to 20]
 **brandId** | **string** | Filter by brand. Pass a brand ID, or \&quot;none\&quot; for records not assigned to any brand. | 
 **brandScope** | **string** | How the brand context narrows this list: \&quot;own\&quot; returns only rows assigned to the current brand (requires a brand session, a brand-bound token, or the X-Zippendo-Brand header), \&quot;shared\&quot; returns only unassigned organization-wide rows, \&quot;both\&quot; (default) returns both. The X-Zippendo-Brand-Scope header supplies a default when the parameter is omitted. For strictly brand-owned records (orders, shipments), a brand-scoped request combined with \&quot;shared\&quot; returns no rows, since those records are never visible organization-wide from within a brand context. | 
 **type_** | **string** | Filter by channel type. | 
 **enabled** | **string** | Filter by enabled state. | 
 **search** | **string** | Search by channel name. | 

### Return type

[**ListOrderChannels200Response**](ListOrderChannels200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RevokeOrderChannelWebhookSecret

> RevokeOrderChannelWebhookSecret200Response RevokeOrderChannelWebhookSecret(ctx, orgId, channelId).Execute()

Revoke webhook signing secret



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/zippendo/zippendo-go"
)

func main() {
	orgId := "clz9k2f0a0000abcd0000zzzz" // string | Organization ID.
	channelId := "clz9k2f0a0001abcd1234efgh" // string | Order channel ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrderChannelsAPI.RevokeOrderChannelWebhookSecret(context.Background(), orgId, channelId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrderChannelsAPI.RevokeOrderChannelWebhookSecret``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RevokeOrderChannelWebhookSecret`: RevokeOrderChannelWebhookSecret200Response
	fmt.Fprintf(os.Stdout, "Response from `OrderChannelsAPI.RevokeOrderChannelWebhookSecret`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID. | 
**channelId** | **string** | Order channel ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiRevokeOrderChannelWebhookSecretRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**RevokeOrderChannelWebhookSecret200Response**](RevokeOrderChannelWebhookSecret200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateOrderChannel

> ListOrderChannels200ResponseDataInner UpdateOrderChannel(ctx, orgId, channelId).UpdateOrderChannelRequest(updateOrderChannelRequest).Execute()

Update order channel



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/zippendo/zippendo-go"
)

func main() {
	orgId := "clz9k2f0a0000abcd0000zzzz" // string | Organization ID.
	channelId := "clz9k2f0a0001abcd1234efgh" // string | Order channel ID.
	updateOrderChannelRequest := *openapiclient.NewUpdateOrderChannelRequest() // UpdateOrderChannelRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrderChannelsAPI.UpdateOrderChannel(context.Background(), orgId, channelId).UpdateOrderChannelRequest(updateOrderChannelRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrderChannelsAPI.UpdateOrderChannel``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateOrderChannel`: ListOrderChannels200ResponseDataInner
	fmt.Fprintf(os.Stdout, "Response from `OrderChannelsAPI.UpdateOrderChannel`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID. | 
**channelId** | **string** | Order channel ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateOrderChannelRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updateOrderChannelRequest** | [**UpdateOrderChannelRequest**](UpdateOrderChannelRequest.md) |  | 

### Return type

[**ListOrderChannels200ResponseDataInner**](ListOrderChannels200ResponseDataInner.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

