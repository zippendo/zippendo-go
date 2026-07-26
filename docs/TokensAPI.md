# \TokensAPI

All URIs are relative to *https://api.zippendo.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateApiToken**](TokensAPI.md#CreateApiToken) | **Post** /orgs/{orgId}/api-tokens | Create API keys
[**GetApiToken**](TokensAPI.md#GetApiToken) | **Get** /orgs/{orgId}/api-tokens/{tokenId} | Get API keys
[**ListApiTokens**](TokensAPI.md#ListApiTokens) | **Get** /orgs/{orgId}/api-tokens | List API keys
[**RevokeApiToken**](TokensAPI.md#RevokeApiToken) | **Delete** /orgs/{orgId}/api-tokens/{tokenId} | Revoke API keys
[**UpdateApiToken**](TokensAPI.md#UpdateApiToken) | **Patch** /orgs/{orgId}/api-tokens/{tokenId} | Update API keys
[**VerifyApiToken**](TokensAPI.md#VerifyApiToken) | **Post** /api-tokens/verify | Verify API keys



## CreateApiToken

> CreateApiToken201Response CreateApiToken(ctx, orgId).CreateApiTokenRequest(createApiTokenRequest).Execute()

Create API keys



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
	orgId := "org_4d8af01qw2" // string | Organization ID
	createApiTokenRequest := *openapiclient.NewCreateApiTokenRequest("Warehouse integration", []string{"read:shipments"}) // CreateApiTokenRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TokensAPI.CreateApiToken(context.Background(), orgId).CreateApiTokenRequest(createApiTokenRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TokensAPI.CreateApiToken``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateApiToken`: CreateApiToken201Response
	fmt.Fprintf(os.Stdout, "Response from `TokensAPI.CreateApiToken`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateApiTokenRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createApiTokenRequest** | [**CreateApiTokenRequest**](CreateApiTokenRequest.md) |  | 

### Return type

[**CreateApiToken201Response**](CreateApiToken201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetApiToken

> ListApiTokens200ResponseDataInner GetApiToken(ctx, orgId, tokenId).Execute()

Get API keys



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
	orgId := "org_4d8af01qw2" // string | Organization ID
	tokenId := "tok_6e2fa83ij9" // string | API Token ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TokensAPI.GetApiToken(context.Background(), orgId, tokenId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TokensAPI.GetApiToken``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetApiToken`: ListApiTokens200ResponseDataInner
	fmt.Fprintf(os.Stdout, "Response from `TokensAPI.GetApiToken`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 
**tokenId** | **string** | API Token ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetApiTokenRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**ListApiTokens200ResponseDataInner**](ListApiTokens200ResponseDataInner.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListApiTokens

> ListApiTokens200Response ListApiTokens(ctx, orgId).Page(page).Limit(limit).Execute()

List API keys



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
	orgId := "org_4d8af01qw2" // string | Organization ID
	page := int32(1) // int32 | Page number (1-based) (optional) (default to 1)
	limit := int32(20) // int32 | Items per page (max 100) (optional) (default to 20)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TokensAPI.ListApiTokens(context.Background(), orgId).Page(page).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TokensAPI.ListApiTokens``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListApiTokens`: ListApiTokens200Response
	fmt.Fprintf(os.Stdout, "Response from `TokensAPI.ListApiTokens`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiListApiTokensRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **page** | **int32** | Page number (1-based) | [default to 1]
 **limit** | **int32** | Items per page (max 100) | [default to 20]

### Return type

[**ListApiTokens200Response**](ListApiTokens200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RevokeApiToken

> RevokeApiToken200Response RevokeApiToken(ctx, orgId, tokenId).Execute()

Revoke API keys



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
	orgId := "org_4d8af01qw2" // string | Organization ID
	tokenId := "tok_6e2fa83ij9" // string | API Token ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TokensAPI.RevokeApiToken(context.Background(), orgId, tokenId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TokensAPI.RevokeApiToken``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RevokeApiToken`: RevokeApiToken200Response
	fmt.Fprintf(os.Stdout, "Response from `TokensAPI.RevokeApiToken`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 
**tokenId** | **string** | API Token ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiRevokeApiTokenRequest struct via the builder pattern


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


## UpdateApiToken

> ListApiTokens200ResponseDataInner UpdateApiToken(ctx, orgId, tokenId).UpdateApiTokenRequest(updateApiTokenRequest).Execute()

Update API keys



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
	orgId := "org_4d8af01qw2" // string | Organization ID
	tokenId := "tok_6e2fa83ij9" // string | API Token ID
	updateApiTokenRequest := *openapiclient.NewUpdateApiTokenRequest("Warehouse integration") // UpdateApiTokenRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TokensAPI.UpdateApiToken(context.Background(), orgId, tokenId).UpdateApiTokenRequest(updateApiTokenRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TokensAPI.UpdateApiToken``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateApiToken`: ListApiTokens200ResponseDataInner
	fmt.Fprintf(os.Stdout, "Response from `TokensAPI.UpdateApiToken`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 
**tokenId** | **string** | API Token ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateApiTokenRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updateApiTokenRequest** | [**UpdateApiTokenRequest**](UpdateApiTokenRequest.md) |  | 

### Return type

[**ListApiTokens200ResponseDataInner**](ListApiTokens200ResponseDataInner.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## VerifyApiToken

> VerifyApiToken200Response VerifyApiToken(ctx).VerifyApiTokenRequest(verifyApiTokenRequest).Execute()

Verify API keys



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
	verifyApiTokenRequest := *openapiclient.NewVerifyApiTokenRequest("zipp_live_8f3kd92ld0a7b6c5d4e3f2a1") // VerifyApiTokenRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TokensAPI.VerifyApiToken(context.Background()).VerifyApiTokenRequest(verifyApiTokenRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TokensAPI.VerifyApiToken``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `VerifyApiToken`: VerifyApiToken200Response
	fmt.Fprintf(os.Stdout, "Response from `TokensAPI.VerifyApiToken`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiVerifyApiTokenRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **verifyApiTokenRequest** | [**VerifyApiTokenRequest**](VerifyApiTokenRequest.md) |  | 

### Return type

[**VerifyApiToken200Response**](VerifyApiToken200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

