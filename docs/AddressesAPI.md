# \AddressesAPI

All URIs are relative to *https://api.zippendo.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateAddress**](AddressesAPI.md#CreateAddress) | **Post** /orgs/{orgId}/addresses | Create address
[**DeleteAddress**](AddressesAPI.md#DeleteAddress) | **Delete** /orgs/{orgId}/addresses/{addressId} | Delete address
[**GetAddress**](AddressesAPI.md#GetAddress) | **Get** /orgs/{orgId}/addresses/{addressId} | Get address
[**ListAddresses**](AddressesAPI.md#ListAddresses) | **Get** /orgs/{orgId}/addresses | List addresses
[**UpdateAddress**](AddressesAPI.md#UpdateAddress) | **Put** /orgs/{orgId}/addresses/{addressId} | Update address



## CreateAddress

> ListAddresses200ResponseDataInner CreateAddress(ctx, orgId).CreateAddressRequest(createAddressRequest).Execute()

Create address



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
	createAddressRequest := *openapiclient.NewCreateAddressRequest("Hovedlager", "Mette Hansen", "Vesterbrogade 1", "1620", "København", "+4533123456", "DK", "lager@example.dk") // CreateAddressRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AddressesAPI.CreateAddress(context.Background(), orgId).CreateAddressRequest(createAddressRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AddressesAPI.CreateAddress``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateAddress`: ListAddresses200ResponseDataInner
	fmt.Fprintf(os.Stdout, "Response from `AddressesAPI.CreateAddress`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateAddressRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createAddressRequest** | [**CreateAddressRequest**](CreateAddressRequest.md) |  | 

### Return type

[**ListAddresses200ResponseDataInner**](ListAddresses200ResponseDataInner.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteAddress

> string DeleteAddress(ctx, orgId, addressId).Execute()

Delete address



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
	addressId := "addr_01HZX9K2QF" // string | Address ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AddressesAPI.DeleteAddress(context.Background(), orgId, addressId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AddressesAPI.DeleteAddress``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteAddress`: string
	fmt.Fprintf(os.Stdout, "Response from `AddressesAPI.DeleteAddress`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 
**addressId** | **string** | Address ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteAddressRequest struct via the builder pattern


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


## GetAddress

> ListAddresses200ResponseDataInner GetAddress(ctx, orgId, addressId).Execute()

Get address



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
	addressId := "addr_01HZX9K2QF" // string | Address ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AddressesAPI.GetAddress(context.Background(), orgId, addressId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AddressesAPI.GetAddress``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAddress`: ListAddresses200ResponseDataInner
	fmt.Fprintf(os.Stdout, "Response from `AddressesAPI.GetAddress`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 
**addressId** | **string** | Address ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAddressRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**ListAddresses200ResponseDataInner**](ListAddresses200ResponseDataInner.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListAddresses

> ListAddresses200Response ListAddresses(ctx, orgId).Page(page).Limit(limit).Type_(type_).CountryCode(countryCode).Search(search).BrandId(brandId).BrandScope(brandScope).Execute()

List addresses



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
	type_ := "sender" // string | Filter by address type (sender, pickup, return) (optional)
	countryCode := "DK" // string | Filter by ISO 3166-1 alpha-2 country code. (optional)
	search := "Copenhagen" // string | Search by address name, contact or city. (optional)
	brandId := "brnd_8f3kd92ld0" // string | Filter by brand. Pass a brand ID, or \"none\" for records not assigned to any brand. (optional)
	brandScope := "own" // string | How the brand context narrows this list: \"own\" returns only rows assigned to the current brand (requires a brand session, a brand-bound token, or the X-Zippendo-Brand header), \"shared\" returns only unassigned organization-wide rows, \"both\" (default) returns both. The X-Zippendo-Brand-Scope header supplies a default when the parameter is omitted. For strictly brand-owned records (orders, shipments), a brand-scoped request combined with \"shared\" returns no rows, since those records are never visible organization-wide from within a brand context. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AddressesAPI.ListAddresses(context.Background(), orgId).Page(page).Limit(limit).Type_(type_).CountryCode(countryCode).Search(search).BrandId(brandId).BrandScope(brandScope).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AddressesAPI.ListAddresses``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListAddresses`: ListAddresses200Response
	fmt.Fprintf(os.Stdout, "Response from `AddressesAPI.ListAddresses`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiListAddressesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **page** | **int32** | Page number (1-based) | [default to 1]
 **limit** | **int32** | Items per page (max 100) | [default to 20]
 **type_** | **string** | Filter by address type (sender, pickup, return) | 
 **countryCode** | **string** | Filter by ISO 3166-1 alpha-2 country code. | 
 **search** | **string** | Search by address name, contact or city. | 
 **brandId** | **string** | Filter by brand. Pass a brand ID, or \&quot;none\&quot; for records not assigned to any brand. | 
 **brandScope** | **string** | How the brand context narrows this list: \&quot;own\&quot; returns only rows assigned to the current brand (requires a brand session, a brand-bound token, or the X-Zippendo-Brand header), \&quot;shared\&quot; returns only unassigned organization-wide rows, \&quot;both\&quot; (default) returns both. The X-Zippendo-Brand-Scope header supplies a default when the parameter is omitted. For strictly brand-owned records (orders, shipments), a brand-scoped request combined with \&quot;shared\&quot; returns no rows, since those records are never visible organization-wide from within a brand context. | 

### Return type

[**ListAddresses200Response**](ListAddresses200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateAddress

> ListAddresses200ResponseDataInner UpdateAddress(ctx, orgId, addressId).UpdateAddressRequest(updateAddressRequest).Execute()

Update address



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
	addressId := "addr_01HZX9K2QF" // string | Address ID
	updateAddressRequest := *openapiclient.NewUpdateAddressRequest() // UpdateAddressRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AddressesAPI.UpdateAddress(context.Background(), orgId, addressId).UpdateAddressRequest(updateAddressRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AddressesAPI.UpdateAddress``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateAddress`: ListAddresses200ResponseDataInner
	fmt.Fprintf(os.Stdout, "Response from `AddressesAPI.UpdateAddress`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 
**addressId** | **string** | Address ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateAddressRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updateAddressRequest** | [**UpdateAddressRequest**](UpdateAddressRequest.md) |  | 

### Return type

[**ListAddresses200ResponseDataInner**](ListAddresses200ResponseDataInner.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

