# \ShipmentsAPI

All URIs are relative to *https://api.zippendo.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**BatchSendShipments**](ShipmentsAPI.md#BatchSendShipments) | **Post** /orgs/{orgId}/shipments/batch-send | Batch send shipments
[**BatchSplitShipment**](ShipmentsAPI.md#BatchSplitShipment) | **Post** /orgs/{orgId}/shipments/{shipmentId}/batch-split-shipment | Batch split shipment
[**CreateReturnShipment**](ShipmentsAPI.md#CreateReturnShipment) | **Post** /orgs/{orgId}/shipments/{shipmentId}/create-return | Create return shipment
[**CreateShipment**](ShipmentsAPI.md#CreateShipment) | **Post** /orgs/{orgId}/shipments | Create shipment
[**DeleteShipment**](ShipmentsAPI.md#DeleteShipment) | **Delete** /orgs/{orgId}/shipments/{shipmentId} | Delete shipment
[**GetShipment**](ShipmentsAPI.md#GetShipment) | **Get** /orgs/{orgId}/shipments/{shipmentId} | Get shipment
[**GetShipmentDocumentContent**](ShipmentsAPI.md#GetShipmentDocumentContent) | **Get** /orgs/{orgId}/shipments/{shipmentId}/documents/{documentId}/content | Download shipment document
[**ListShipments**](ShipmentsAPI.md#ListShipments) | **Get** /orgs/{orgId}/shipments | List shipments
[**SendShipment**](ShipmentsAPI.md#SendShipment) | **Post** /orgs/{orgId}/shipments/{shipmentId}/send | Send shipment
[**SplitShipment**](ShipmentsAPI.md#SplitShipment) | **Post** /orgs/{orgId}/shipments/{shipmentId}/split-shipment | Split shipment
[**SplitShipmentParcel**](ShipmentsAPI.md#SplitShipmentParcel) | **Post** /orgs/{orgId}/shipments/{shipmentId}/split-parcel | Split parcels
[**TrackShipment**](ShipmentsAPI.md#TrackShipment) | **Get** /orgs/{orgId}/shipments/{shipmentId}/tracking | Get shipment tracking
[**UpdateShipment**](ShipmentsAPI.md#UpdateShipment) | **Patch** /orgs/{orgId}/shipments/{shipmentId} | Update shipment



## BatchSendShipments

> BatchSendShipments200Response BatchSendShipments(ctx, orgId).BatchSendShipmentsRequest(batchSendShipmentsRequest).Execute()

Batch send shipments



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
	batchSendShipmentsRequest := *openapiclient.NewBatchSendShipmentsRequest([]string{"ShipmentIds_example"}) // BatchSendShipmentsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShipmentsAPI.BatchSendShipments(context.Background(), orgId).BatchSendShipmentsRequest(batchSendShipmentsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShipmentsAPI.BatchSendShipments``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BatchSendShipments`: BatchSendShipments200Response
	fmt.Fprintf(os.Stdout, "Response from `ShipmentsAPI.BatchSendShipments`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiBatchSendShipmentsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **batchSendShipmentsRequest** | [**BatchSendShipmentsRequest**](BatchSendShipmentsRequest.md) |  | 

### Return type

[**BatchSendShipments200Response**](BatchSendShipments200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## BatchSplitShipment

> BatchSplitShipment201Response BatchSplitShipment(ctx, orgId, shipmentId).BatchSplitShipmentRequest(batchSplitShipmentRequest).Execute()

Batch split shipment



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
	orgId := "org_1a2b3c4d" // string | Organization identifier.
	shipmentId := "shp_4d9e7a2f" // string | Shipment identifier.
	batchSplitShipmentRequest := *openapiclient.NewBatchSplitShipmentRequest("prc_5a6b7c8d", []openapiclient.BatchSplitShipmentRequestShipmentsInner{*openapiclient.NewBatchSplitShipmentRequestShipmentsInner([]openapiclient.BatchSplitShipmentRequestShipmentsInnerOrderLinesInner{*openapiclient.NewBatchSplitShipmentRequestShipmentsInnerOrderLinesInner("ol_9c1d2e3f", int32(1))})}) // BatchSplitShipmentRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShipmentsAPI.BatchSplitShipment(context.Background(), orgId, shipmentId).BatchSplitShipmentRequest(batchSplitShipmentRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShipmentsAPI.BatchSplitShipment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BatchSplitShipment`: BatchSplitShipment201Response
	fmt.Fprintf(os.Stdout, "Response from `ShipmentsAPI.BatchSplitShipment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization identifier. | 
**shipmentId** | **string** | Shipment identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiBatchSplitShipmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **batchSplitShipmentRequest** | [**BatchSplitShipmentRequest**](BatchSplitShipmentRequest.md) |  | 

### Return type

[**BatchSplitShipment201Response**](BatchSplitShipment201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateReturnShipment

> CreateShipment201Response CreateReturnShipment(ctx, orgId, shipmentId).Execute()

Create return shipment



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
	orgId := "org_1a2b3c4d" // string | Organization identifier.
	shipmentId := "shp_4d9e7a2f" // string | Shipment identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShipmentsAPI.CreateReturnShipment(context.Background(), orgId, shipmentId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShipmentsAPI.CreateReturnShipment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateReturnShipment`: CreateShipment201Response
	fmt.Fprintf(os.Stdout, "Response from `ShipmentsAPI.CreateReturnShipment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization identifier. | 
**shipmentId** | **string** | Shipment identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateReturnShipmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**CreateShipment201Response**](CreateShipment201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateShipment

> CreateShipment201Response CreateShipment(ctx, orgId).CreateShipmentRequest(createShipmentRequest).Execute()

Create shipment



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
	createShipmentRequest := *openapiclient.NewCreateShipmentRequest("outbound", *openapiclient.NewCreateShipmentRequestCarrierSettings("car_pn_001", "prod_mypack_home", []string{"Services_example"}, map[string]CreateShippingRuleRequestAdditionalParametersValue{"key": *openapiclient.NewCreateShippingRuleRequestAdditionalParametersValue("sp_pn_4521", "Føtex Nørrebro", "Nørrebrogade 20, 2200 København N")})) // CreateShipmentRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShipmentsAPI.CreateShipment(context.Background(), orgId).CreateShipmentRequest(createShipmentRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShipmentsAPI.CreateShipment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateShipment`: CreateShipment201Response
	fmt.Fprintf(os.Stdout, "Response from `ShipmentsAPI.CreateShipment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateShipmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createShipmentRequest** | [**CreateShipmentRequest**](CreateShipmentRequest.md) |  | 

### Return type

[**CreateShipment201Response**](CreateShipment201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteShipment

> RevokeApiToken200Response DeleteShipment(ctx, orgId, shipmentId).Execute()

Delete shipment



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
	orgId := "org_1a2b3c4d" // string | Organization identifier.
	shipmentId := "shp_4d9e7a2f" // string | Shipment identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShipmentsAPI.DeleteShipment(context.Background(), orgId, shipmentId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShipmentsAPI.DeleteShipment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteShipment`: RevokeApiToken200Response
	fmt.Fprintf(os.Stdout, "Response from `ShipmentsAPI.DeleteShipment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization identifier. | 
**shipmentId** | **string** | Shipment identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteShipmentRequest struct via the builder pattern


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


## GetShipment

> CreateShipment201Response GetShipment(ctx, orgId, shipmentId).Execute()

Get shipment



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
	orgId := "org_1a2b3c4d" // string | Organization identifier.
	shipmentId := "shp_4d9e7a2f" // string | Shipment identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShipmentsAPI.GetShipment(context.Background(), orgId, shipmentId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShipmentsAPI.GetShipment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetShipment`: CreateShipment201Response
	fmt.Fprintf(os.Stdout, "Response from `ShipmentsAPI.GetShipment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization identifier. | 
**shipmentId** | **string** | Shipment identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetShipmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**CreateShipment201Response**](CreateShipment201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetShipmentDocumentContent

> GetShipmentDocumentContent(ctx, orgId, shipmentId, documentId).Disposition(disposition).Filename(filename).Execute()

Download shipment document



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
	orgId := "org_1a2b3c4d" // string | Organization identifier.
	shipmentId := "shp_4d9e7a2f" // string | Shipment identifier.
	documentId := "doc_8f3a2b1c" // string | Document identifier.
	disposition := "inline" // string | Render the document inline (default) or force a download. (optional) (default to "inline")
	filename := "label" // string | Suggested filename (without extension) for attachment downloads. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ShipmentsAPI.GetShipmentDocumentContent(context.Background(), orgId, shipmentId, documentId).Disposition(disposition).Filename(filename).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShipmentsAPI.GetShipmentDocumentContent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization identifier. | 
**shipmentId** | **string** | Shipment identifier. | 
**documentId** | **string** | Document identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetShipmentDocumentContentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **disposition** | **string** | Render the document inline (default) or force a download. | [default to &quot;inline&quot;]
 **filename** | **string** | Suggested filename (without extension) for attachment downloads. | 

### Return type

 (empty response body)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListShipments

> ListShipments200Response ListShipments(ctx, orgId).Page(page).Limit(limit).BrandId(brandId).Execute()

List shipments



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShipmentsAPI.ListShipments(context.Background(), orgId).Page(page).Limit(limit).BrandId(brandId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShipmentsAPI.ListShipments``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListShipments`: ListShipments200Response
	fmt.Fprintf(os.Stdout, "Response from `ShipmentsAPI.ListShipments`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiListShipmentsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **page** | **int32** | Page number (1-based) | [default to 1]
 **limit** | **int32** | Items per page (max 100) | [default to 20]
 **brandId** | **string** | Filter by brand. Pass a brand ID, or \&quot;none\&quot; for records not assigned to any brand. | 

### Return type

[**ListShipments200Response**](ListShipments200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SendShipment

> CreateShipment201Response SendShipment(ctx, orgId, shipmentId).Execute()

Send shipment



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
	orgId := "org_1a2b3c4d" // string | Organization identifier.
	shipmentId := "shp_4d9e7a2f" // string | Shipment identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShipmentsAPI.SendShipment(context.Background(), orgId, shipmentId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShipmentsAPI.SendShipment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SendShipment`: CreateShipment201Response
	fmt.Fprintf(os.Stdout, "Response from `ShipmentsAPI.SendShipment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization identifier. | 
**shipmentId** | **string** | Shipment identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiSendShipmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**CreateShipment201Response**](CreateShipment201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SplitShipment

> SplitShipment201Response SplitShipment(ctx, orgId, shipmentId).SplitShipmentRequest(splitShipmentRequest).Execute()

Split shipment



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
	orgId := "org_1a2b3c4d" // string | Organization identifier.
	shipmentId := "shp_4d9e7a2f" // string | Shipment identifier.
	splitShipmentRequest := *openapiclient.NewSplitShipmentRequest("prc_5a6b7c8d") // SplitShipmentRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShipmentsAPI.SplitShipment(context.Background(), orgId, shipmentId).SplitShipmentRequest(splitShipmentRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShipmentsAPI.SplitShipment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SplitShipment`: SplitShipment201Response
	fmt.Fprintf(os.Stdout, "Response from `ShipmentsAPI.SplitShipment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization identifier. | 
**shipmentId** | **string** | Shipment identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiSplitShipmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **splitShipmentRequest** | [**SplitShipmentRequest**](SplitShipmentRequest.md) |  | 

### Return type

[**SplitShipment201Response**](SplitShipment201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SplitShipmentParcel

> SplitShipmentParcel200Response SplitShipmentParcel(ctx, orgId, shipmentId).SplitShipmentParcelRequest(splitShipmentParcelRequest).Execute()

Split parcels



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
	orgId := "org_1a2b3c4d" // string | Organization identifier.
	shipmentId := "shp_4d9e7a2f" // string | Shipment identifier.
	splitShipmentParcelRequest := *openapiclient.NewSplitShipmentParcelRequest([]openapiclient.SplitShipmentParcelRequestParcelsInner{*openapiclient.NewSplitShipmentParcelRequestParcelsInner([]openapiclient.BatchSplitShipmentRequestShipmentsInnerOrderLinesInner{*openapiclient.NewBatchSplitShipmentRequestShipmentsInnerOrderLinesInner("ol_9c1d2e3f", int32(1))})}) // SplitShipmentParcelRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShipmentsAPI.SplitShipmentParcel(context.Background(), orgId, shipmentId).SplitShipmentParcelRequest(splitShipmentParcelRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShipmentsAPI.SplitShipmentParcel``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SplitShipmentParcel`: SplitShipmentParcel200Response
	fmt.Fprintf(os.Stdout, "Response from `ShipmentsAPI.SplitShipmentParcel`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization identifier. | 
**shipmentId** | **string** | Shipment identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiSplitShipmentParcelRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **splitShipmentParcelRequest** | [**SplitShipmentParcelRequest**](SplitShipmentParcelRequest.md) |  | 

### Return type

[**SplitShipmentParcel200Response**](SplitShipmentParcel200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TrackShipment

> TrackShipment200Response TrackShipment(ctx, orgId, shipmentId).Execute()

Get shipment tracking



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
	orgId := "org_1a2b3c4d" // string | Organization identifier.
	shipmentId := "shp_4d9e7a2f" // string | Shipment identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShipmentsAPI.TrackShipment(context.Background(), orgId, shipmentId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShipmentsAPI.TrackShipment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TrackShipment`: TrackShipment200Response
	fmt.Fprintf(os.Stdout, "Response from `ShipmentsAPI.TrackShipment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization identifier. | 
**shipmentId** | **string** | Shipment identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiTrackShipmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**TrackShipment200Response**](TrackShipment200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateShipment

> CreateShipment201Response UpdateShipment(ctx, orgId, shipmentId).UpdateShipmentRequest(updateShipmentRequest).Execute()

Update shipment



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
	orgId := "org_1a2b3c4d" // string | Organization identifier.
	shipmentId := "shp_4d9e7a2f" // string | Shipment identifier.
	updateShipmentRequest := *openapiclient.NewUpdateShipmentRequest() // UpdateShipmentRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShipmentsAPI.UpdateShipment(context.Background(), orgId, shipmentId).UpdateShipmentRequest(updateShipmentRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShipmentsAPI.UpdateShipment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateShipment`: CreateShipment201Response
	fmt.Fprintf(os.Stdout, "Response from `ShipmentsAPI.UpdateShipment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization identifier. | 
**shipmentId** | **string** | Shipment identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateShipmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updateShipmentRequest** | [**UpdateShipmentRequest**](UpdateShipmentRequest.md) |  | 

### Return type

[**CreateShipment201Response**](CreateShipment201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

