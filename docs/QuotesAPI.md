# \QuotesAPI

All URIs are relative to *https://api.zippendo.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateShippingQuote**](QuotesAPI.md#CreateShippingQuote) | **Post** /orgs/{orgId}/shipping-quote | Calculate shipping rates



## CreateShippingQuote

> CreateShippingQuote200Response CreateShippingQuote(ctx, orgId).CreateShippingQuoteRequest(createShippingQuoteRequest).Execute()

Calculate shipping rates



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
	createShippingQuoteRequest := *openapiclient.NewCreateShippingQuoteRequest(*openapiclient.NewCreateShippingQuoteRequestDestination("DK"), []openapiclient.CreateShippingQuoteRequestItemsInner{*openapiclient.NewCreateShippingQuoteRequestItemsInner("Uld trøje", int32(2), float32(500), float32(29900))}, "DKK") // CreateShippingQuoteRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.QuotesAPI.CreateShippingQuote(context.Background(), orgId).CreateShippingQuoteRequest(createShippingQuoteRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `QuotesAPI.CreateShippingQuote``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateShippingQuote`: CreateShippingQuote200Response
	fmt.Fprintf(os.Stdout, "Response from `QuotesAPI.CreateShippingQuote`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateShippingQuoteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createShippingQuoteRequest** | [**CreateShippingQuoteRequest**](CreateShippingQuoteRequest.md) |  | 

### Return type

[**CreateShippingQuote200Response**](CreateShippingQuote200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

