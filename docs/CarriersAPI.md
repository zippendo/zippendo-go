# \CarriersAPI

All URIs are relative to *https://api.zippendo.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ConnectCarrier**](CarriersAPI.md#ConnectCarrier) | **Post** /orgs/{orgId}/carriers | Connect carrier
[**DisconnectCarrier**](CarriersAPI.md#DisconnectCarrier) | **Delete** /orgs/{orgId}/carriers/{carrierId} | Disconnect carrier
[**GetCarrier**](CarriersAPI.md#GetCarrier) | **Get** /orgs/{orgId}/carriers/{carrierId} | Get carrier
[**ListCarrierProductServicePoints**](CarriersAPI.md#ListCarrierProductServicePoints) | **Post** /orgs/{orgId}/carriers/{carrierId}/products/{productId}/service-points | List product service points
[**ListCarrierProducts**](CarriersAPI.md#ListCarrierProducts) | **Get** /orgs/{orgId}/carriers/{carrierId}/products | List carrier products
[**ListCarriers**](CarriersAPI.md#ListCarriers) | **Get** /orgs/{orgId}/carriers | List carriers
[**UpdateCarrier**](CarriersAPI.md#UpdateCarrier) | **Put** /orgs/{orgId}/carriers/{carrierId} | Update carrier



## ConnectCarrier

> ListCarriers200ResponseDataInner ConnectCarrier(ctx, orgId).ConnectCarrierRequest(connectCarrierRequest).Execute()

Connect carrier



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
	orgId := "org_01HZX9K2QF" // string | Organization ID
	connectCarrierRequest := *openapiclient.NewConnectCarrierRequest("PostNord", "postnord", map[string]ListCarriers200ResponseDataInnerConfigValue{"key": *openapiclient.NewListCarriers200ResponseDataInnerConfigValue()}) // ConnectCarrierRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CarriersAPI.ConnectCarrier(context.Background(), orgId).ConnectCarrierRequest(connectCarrierRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CarriersAPI.ConnectCarrier``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ConnectCarrier`: ListCarriers200ResponseDataInner
	fmt.Fprintf(os.Stdout, "Response from `CarriersAPI.ConnectCarrier`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiConnectCarrierRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **connectCarrierRequest** | [**ConnectCarrierRequest**](ConnectCarrierRequest.md) |  | 

### Return type

[**ListCarriers200ResponseDataInner**](ListCarriers200ResponseDataInner.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DisconnectCarrier

> string DisconnectCarrier(ctx, orgId, carrierId).Execute()

Disconnect carrier



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
	orgId := "org_01HZX9K2QF" // string | Organization ID
	carrierId := "carr_01HZX9K2QF" // string | Carrier ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CarriersAPI.DisconnectCarrier(context.Background(), orgId, carrierId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CarriersAPI.DisconnectCarrier``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DisconnectCarrier`: string
	fmt.Fprintf(os.Stdout, "Response from `CarriersAPI.DisconnectCarrier`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 
**carrierId** | **string** | Carrier ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiDisconnectCarrierRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

**string**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCarrier

> ListCarriers200ResponseDataInner GetCarrier(ctx, orgId, carrierId).Execute()

Get carrier



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
	orgId := "org_01HZX9K2QF" // string | Organization ID
	carrierId := "carr_01HZX9K2QF" // string | Carrier ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CarriersAPI.GetCarrier(context.Background(), orgId, carrierId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CarriersAPI.GetCarrier``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCarrier`: ListCarriers200ResponseDataInner
	fmt.Fprintf(os.Stdout, "Response from `CarriersAPI.GetCarrier`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 
**carrierId** | **string** | Carrier ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetCarrierRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**ListCarriers200ResponseDataInner**](ListCarriers200ResponseDataInner.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListCarrierProductServicePoints

> []ListCarrierProductServicePoints200ResponseInner ListCarrierProductServicePoints(ctx, orgId, carrierId, productId).ListCarrierProductServicePointsRequest(listCarrierProductServicePointsRequest).Execute()

List product service points



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
	orgId := "org_01HZX9K2QF" // string | Organization ID
	carrierId := "carr_01HZX9K2QF" // string | Carrier ID
	productId := "PNL13" // string | Carrier product ID
	listCarrierProductServicePointsRequest := *openapiclient.NewListCarrierProductServicePointsRequest("Vesterbrogade 1", "1620", "København", "DK") // ListCarrierProductServicePointsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CarriersAPI.ListCarrierProductServicePoints(context.Background(), orgId, carrierId, productId).ListCarrierProductServicePointsRequest(listCarrierProductServicePointsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CarriersAPI.ListCarrierProductServicePoints``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListCarrierProductServicePoints`: []ListCarrierProductServicePoints200ResponseInner
	fmt.Fprintf(os.Stdout, "Response from `CarriersAPI.ListCarrierProductServicePoints`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 
**carrierId** | **string** | Carrier ID | 
**productId** | **string** | Carrier product ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiListCarrierProductServicePointsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **listCarrierProductServicePointsRequest** | [**ListCarrierProductServicePointsRequest**](ListCarrierProductServicePointsRequest.md) |  | 

### Return type

[**[]ListCarrierProductServicePoints200ResponseInner**](ListCarrierProductServicePoints200ResponseInner.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListCarrierProducts

> []ListCarrierProducts200ResponseInner ListCarrierProducts(ctx, orgId, carrierId).Execute()

List carrier products



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
	orgId := "org_01HZX9K2QF" // string | Organization ID
	carrierId := "carr_01HZX9K2QF" // string | Carrier ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CarriersAPI.ListCarrierProducts(context.Background(), orgId, carrierId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CarriersAPI.ListCarrierProducts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListCarrierProducts`: []ListCarrierProducts200ResponseInner
	fmt.Fprintf(os.Stdout, "Response from `CarriersAPI.ListCarrierProducts`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 
**carrierId** | **string** | Carrier ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiListCarrierProductsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**[]ListCarrierProducts200ResponseInner**](ListCarrierProducts200ResponseInner.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListCarriers

> ListCarriers200Response ListCarriers(ctx, orgId).Page(page).Limit(limit).BrandId(brandId).BrandScope(brandScope).Execute()

List carriers



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
	orgId := "org_01HZX9K2QF" // string | Organization ID
	page := int32(1) // int32 | Page number (1-based) (optional) (default to 1)
	limit := int32(20) // int32 | Items per page (max 100) (optional) (default to 20)
	brandId := "brnd_8f3kd92ld0" // string | Filter by brand. Pass a brand ID, or \"none\" for records not assigned to any brand. (optional)
	brandScope := "own" // string | How the brand context narrows this list: \"own\" returns only rows assigned to the current brand (requires a brand session, a brand-bound token, or the X-Zippendo-Brand header), \"shared\" returns only unassigned organization-wide rows, \"both\" (default) returns both. The X-Zippendo-Brand-Scope header supplies a default when the parameter is omitted. For strictly brand-owned records (orders, shipments), a brand-scoped request combined with \"shared\" returns no rows, since those records are never visible organization-wide from within a brand context. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CarriersAPI.ListCarriers(context.Background(), orgId).Page(page).Limit(limit).BrandId(brandId).BrandScope(brandScope).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CarriersAPI.ListCarriers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListCarriers`: ListCarriers200Response
	fmt.Fprintf(os.Stdout, "Response from `CarriersAPI.ListCarriers`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiListCarriersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **page** | **int32** | Page number (1-based) | [default to 1]
 **limit** | **int32** | Items per page (max 100) | [default to 20]
 **brandId** | **string** | Filter by brand. Pass a brand ID, or \&quot;none\&quot; for records not assigned to any brand. | 
 **brandScope** | **string** | How the brand context narrows this list: \&quot;own\&quot; returns only rows assigned to the current brand (requires a brand session, a brand-bound token, or the X-Zippendo-Brand header), \&quot;shared\&quot; returns only unassigned organization-wide rows, \&quot;both\&quot; (default) returns both. The X-Zippendo-Brand-Scope header supplies a default when the parameter is omitted. For strictly brand-owned records (orders, shipments), a brand-scoped request combined with \&quot;shared\&quot; returns no rows, since those records are never visible organization-wide from within a brand context. | 

### Return type

[**ListCarriers200Response**](ListCarriers200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateCarrier

> ListCarriers200ResponseDataInner UpdateCarrier(ctx, orgId, carrierId).UpdateCarrierRequest(updateCarrierRequest).Execute()

Update carrier



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
	orgId := "org_01HZX9K2QF" // string | Organization ID
	carrierId := "carr_01HZX9K2QF" // string | Carrier ID
	updateCarrierRequest := *openapiclient.NewUpdateCarrierRequest() // UpdateCarrierRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CarriersAPI.UpdateCarrier(context.Background(), orgId, carrierId).UpdateCarrierRequest(updateCarrierRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CarriersAPI.UpdateCarrier``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateCarrier`: ListCarriers200ResponseDataInner
	fmt.Fprintf(os.Stdout, "Response from `CarriersAPI.UpdateCarrier`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 
**carrierId** | **string** | Carrier ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateCarrierRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updateCarrierRequest** | [**UpdateCarrierRequest**](UpdateCarrierRequest.md) |  | 

### Return type

[**ListCarriers200ResponseDataInner**](ListCarriers200ResponseDataInner.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

