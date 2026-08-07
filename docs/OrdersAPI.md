# \OrdersAPI

All URIs are relative to *https://api.zippendo.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateOrder**](OrdersAPI.md#CreateOrder) | **Post** /orgs/{orgId}/orders | Create order
[**DeleteOrder**](OrdersAPI.md#DeleteOrder) | **Delete** /orgs/{orgId}/orders/{orderId} | Delete order
[**GetOrder**](OrdersAPI.md#GetOrder) | **Get** /orgs/{orgId}/orders/{orderId} | Get order
[**ListOrders**](OrdersAPI.md#ListOrders) | **Get** /orgs/{orgId}/orders | List orders
[**UpdateOrder**](OrdersAPI.md#UpdateOrder) | **Patch** /orgs/{orgId}/orders/{orderId} | Update order



## CreateOrder

> CreateOrder201Response CreateOrder(ctx, orgId).CreateOrderRequest(createOrderRequest).Execute()

Create order



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
	createOrderRequest := *openapiclient.NewCreateOrderRequest("#1042", "clz9k2f0a0001abcd1234efgh", []openapiclient.CreateOrderRequestOrderLinesInner{*openapiclient.NewCreateOrderRequestOrderLinesInner("Wool Sweater", int32(2))}) // CreateOrderRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrdersAPI.CreateOrder(context.Background(), orgId).CreateOrderRequest(createOrderRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrdersAPI.CreateOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateOrder`: CreateOrder201Response
	fmt.Fprintf(os.Stdout, "Response from `OrdersAPI.CreateOrder`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createOrderRequest** | [**CreateOrderRequest**](CreateOrderRequest.md) |  | 

### Return type

[**CreateOrder201Response**](CreateOrder201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteOrder

> RevokeApiToken200Response DeleteOrder(ctx, orgId, orderId).Execute()

Delete order



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
	orderId := "clz9k2f0a0003abcd9012mnop" // string | Order ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrdersAPI.DeleteOrder(context.Background(), orgId, orderId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrdersAPI.DeleteOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteOrder`: RevokeApiToken200Response
	fmt.Fprintf(os.Stdout, "Response from `OrdersAPI.DeleteOrder`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID. | 
**orderId** | **string** | Order ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteOrderRequest struct via the builder pattern


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


## GetOrder

> GetOrder200Response GetOrder(ctx, orgId, orderId).Execute()

Get order



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
	orderId := "clz9k2f0a0003abcd9012mnop" // string | Order ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrdersAPI.GetOrder(context.Background(), orgId, orderId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrdersAPI.GetOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetOrder`: GetOrder200Response
	fmt.Fprintf(os.Stdout, "Response from `OrdersAPI.GetOrder`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID. | 
**orderId** | **string** | Order ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**GetOrder200Response**](GetOrder200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListOrders

> ListOrders200Response ListOrders(ctx, orgId).Page(page).Limit(limit).BrandId(brandId).Status(status).OrderChannelId(orderChannelId).Search(search).Execute()

List orders



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
	status := "processing" // string | Order fulfilment status derived from its shipments. (optional)
	orderChannelId := "clz9k2f0a0001abcd1234efgh" // string | Filter by order channel ID. (optional)
	search := "Anna" // string | Search by order number or customer name/email. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrdersAPI.ListOrders(context.Background(), orgId).Page(page).Limit(limit).BrandId(brandId).Status(status).OrderChannelId(orderChannelId).Search(search).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrdersAPI.ListOrders``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListOrders`: ListOrders200Response
	fmt.Fprintf(os.Stdout, "Response from `OrdersAPI.ListOrders`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiListOrdersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **page** | **int32** | Page number (1-based) | [default to 1]
 **limit** | **int32** | Items per page (max 100) | [default to 20]
 **brandId** | **string** | Filter by brand. Pass a brand ID, or \&quot;none\&quot; for records not assigned to any brand. | 
 **status** | **string** | Order fulfilment status derived from its shipments. | 
 **orderChannelId** | **string** | Filter by order channel ID. | 
 **search** | **string** | Search by order number or customer name/email. | 

### Return type

[**ListOrders200Response**](ListOrders200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateOrder

> CreateOrder201Response UpdateOrder(ctx, orgId, orderId).UpdateOrderRequest(updateOrderRequest).Execute()

Update order



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
	orderId := "clz9k2f0a0003abcd9012mnop" // string | Order ID.
	updateOrderRequest := *openapiclient.NewUpdateOrderRequest() // UpdateOrderRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrdersAPI.UpdateOrder(context.Background(), orgId, orderId).UpdateOrderRequest(updateOrderRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrdersAPI.UpdateOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateOrder`: CreateOrder201Response
	fmt.Fprintf(os.Stdout, "Response from `OrdersAPI.UpdateOrder`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID. | 
**orderId** | **string** | Order ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updateOrderRequest** | [**UpdateOrderRequest**](UpdateOrderRequest.md) |  | 

### Return type

[**CreateOrder201Response**](CreateOrder201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

