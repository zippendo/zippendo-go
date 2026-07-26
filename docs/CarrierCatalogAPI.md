# \CarrierCatalogAPI

All URIs are relative to *https://api.zippendo.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ListAvailableCarriers**](CarrierCatalogAPI.md#ListAvailableCarriers) | **Get** /orgs/{orgId}/available-carriers | List available carriers



## ListAvailableCarriers

> []ListAvailableCarriers200ResponseInner ListAvailableCarriers(ctx, orgId).Execute()

List available carriers



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CarrierCatalogAPI.ListAvailableCarriers(context.Background(), orgId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CarrierCatalogAPI.ListAvailableCarriers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListAvailableCarriers`: []ListAvailableCarriers200ResponseInner
	fmt.Fprintf(os.Stdout, "Response from `CarrierCatalogAPI.ListAvailableCarriers`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiListAvailableCarriersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]ListAvailableCarriers200ResponseInner**](ListAvailableCarriers200ResponseInner.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

