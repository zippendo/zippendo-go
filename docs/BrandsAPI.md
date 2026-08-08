# \BrandsAPI

All URIs are relative to *https://api.zippendo.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ArchiveOrgBrand**](BrandsAPI.md#ArchiveOrgBrand) | **Post** /orgs/{orgId}/brands/{brandId}/archive | Archive brand
[**CheckBrandSlug**](BrandsAPI.md#CheckBrandSlug) | **Get** /orgs/{orgId}/brands/check-slug/{slug} | Check brand slug availability
[**CreateOrgBrand**](BrandsAPI.md#CreateOrgBrand) | **Post** /orgs/{orgId}/brands | Create brand
[**DeleteBrandLogo**](BrandsAPI.md#DeleteBrandLogo) | **Delete** /orgs/{orgId}/brands/{brandId}/logo | Delete brand logo
[**GetBrandLogo**](BrandsAPI.md#GetBrandLogo) | **Get** /orgs/{orgId}/brands/{brandId}/logo | Get brand logo
[**GetOrgBrand**](BrandsAPI.md#GetOrgBrand) | **Get** /orgs/{orgId}/brands/{brandId} | Get brand
[**ListOrgBrands**](BrandsAPI.md#ListOrgBrands) | **Get** /orgs/{orgId}/brands | List brands
[**UnarchiveOrgBrand**](BrandsAPI.md#UnarchiveOrgBrand) | **Post** /orgs/{orgId}/brands/{brandId}/unarchive | Unarchive brand
[**UpdateOrgBrand**](BrandsAPI.md#UpdateOrgBrand) | **Patch** /orgs/{orgId}/brands/{brandId} | Update brand
[**UploadBrandLogo**](BrandsAPI.md#UploadBrandLogo) | **Post** /orgs/{orgId}/brands/{brandId}/logo | Upload brand logo



## ArchiveOrgBrand

> ListOrgBrands200ResponseDataInner ArchiveOrgBrand(ctx, orgId, brandId).Execute()

Archive brand



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
	brandId := "brnd_8f3kd92ld0" // string | Brand ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BrandsAPI.ArchiveOrgBrand(context.Background(), orgId, brandId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BrandsAPI.ArchiveOrgBrand``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ArchiveOrgBrand`: ListOrgBrands200ResponseDataInner
	fmt.Fprintf(os.Stdout, "Response from `BrandsAPI.ArchiveOrgBrand`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 
**brandId** | **string** | Brand ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiArchiveOrgBrandRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**ListOrgBrands200ResponseDataInner**](ListOrgBrands200ResponseDataInner.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CheckBrandSlug

> CheckBrandSlug200Response CheckBrandSlug(ctx, orgId, slug).Execute()

Check brand slug availability



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
	slug := "acme" // string | Brand slug to check

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BrandsAPI.CheckBrandSlug(context.Background(), orgId, slug).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BrandsAPI.CheckBrandSlug``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CheckBrandSlug`: CheckBrandSlug200Response
	fmt.Fprintf(os.Stdout, "Response from `BrandsAPI.CheckBrandSlug`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 
**slug** | **string** | Brand slug to check | 

### Other Parameters

Other parameters are passed through a pointer to a apiCheckBrandSlugRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**CheckBrandSlug200Response**](CheckBrandSlug200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateOrgBrand

> ListOrgBrands200ResponseDataInner CreateOrgBrand(ctx, orgId).CreateOrgBrandRequest(createOrgBrandRequest).Execute()

Create brand



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
	createOrgBrandRequest := *openapiclient.NewCreateOrgBrandRequest("Acme") // CreateOrgBrandRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BrandsAPI.CreateOrgBrand(context.Background(), orgId).CreateOrgBrandRequest(createOrgBrandRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BrandsAPI.CreateOrgBrand``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateOrgBrand`: ListOrgBrands200ResponseDataInner
	fmt.Fprintf(os.Stdout, "Response from `BrandsAPI.CreateOrgBrand`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateOrgBrandRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createOrgBrandRequest** | [**CreateOrgBrandRequest**](CreateOrgBrandRequest.md) |  | 

### Return type

[**ListOrgBrands200ResponseDataInner**](ListOrgBrands200ResponseDataInner.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteBrandLogo

> ListOrgBrands200ResponseDataInner DeleteBrandLogo(ctx, orgId, brandId).Execute()

Delete brand logo



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
	brandId := "brnd_8f3kd92ld0" // string | Brand ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BrandsAPI.DeleteBrandLogo(context.Background(), orgId, brandId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BrandsAPI.DeleteBrandLogo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteBrandLogo`: ListOrgBrands200ResponseDataInner
	fmt.Fprintf(os.Stdout, "Response from `BrandsAPI.DeleteBrandLogo`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 
**brandId** | **string** | Brand ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteBrandLogoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**ListOrgBrands200ResponseDataInner**](ListOrgBrands200ResponseDataInner.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetBrandLogo

> *os.File GetBrandLogo(ctx, orgId, brandId).Execute()

Get brand logo



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
	brandId := "brnd_8f3kd92ld0" // string | Brand ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BrandsAPI.GetBrandLogo(context.Background(), orgId, brandId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BrandsAPI.GetBrandLogo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetBrandLogo`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `BrandsAPI.GetBrandLogo`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 
**brandId** | **string** | Brand ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetBrandLogoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[***os.File**](*os.File.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: image/png, image/jpeg, image/webp

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetOrgBrand

> ListOrgBrands200ResponseDataInner GetOrgBrand(ctx, orgId, brandId).Execute()

Get brand



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
	brandId := "brnd_8f3kd92ld0" // string | Brand ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BrandsAPI.GetOrgBrand(context.Background(), orgId, brandId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BrandsAPI.GetOrgBrand``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetOrgBrand`: ListOrgBrands200ResponseDataInner
	fmt.Fprintf(os.Stdout, "Response from `BrandsAPI.GetOrgBrand`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 
**brandId** | **string** | Brand ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetOrgBrandRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**ListOrgBrands200ResponseDataInner**](ListOrgBrands200ResponseDataInner.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListOrgBrands

> ListOrgBrands200Response ListOrgBrands(ctx, orgId).IncludeArchived(includeArchived).Execute()

List brands



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
	includeArchived := "false" // string | Include archived brands in the response (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BrandsAPI.ListOrgBrands(context.Background(), orgId).IncludeArchived(includeArchived).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BrandsAPI.ListOrgBrands``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListOrgBrands`: ListOrgBrands200Response
	fmt.Fprintf(os.Stdout, "Response from `BrandsAPI.ListOrgBrands`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiListOrgBrandsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **includeArchived** | **string** | Include archived brands in the response | 

### Return type

[**ListOrgBrands200Response**](ListOrgBrands200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UnarchiveOrgBrand

> ListOrgBrands200ResponseDataInner UnarchiveOrgBrand(ctx, orgId, brandId).Execute()

Unarchive brand



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
	brandId := "brnd_8f3kd92ld0" // string | Brand ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BrandsAPI.UnarchiveOrgBrand(context.Background(), orgId, brandId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BrandsAPI.UnarchiveOrgBrand``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UnarchiveOrgBrand`: ListOrgBrands200ResponseDataInner
	fmt.Fprintf(os.Stdout, "Response from `BrandsAPI.UnarchiveOrgBrand`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 
**brandId** | **string** | Brand ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiUnarchiveOrgBrandRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**ListOrgBrands200ResponseDataInner**](ListOrgBrands200ResponseDataInner.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateOrgBrand

> ListOrgBrands200ResponseDataInner UpdateOrgBrand(ctx, orgId, brandId).UpdateOrgBrandRequest(updateOrgBrandRequest).Execute()

Update brand



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
	brandId := "brnd_8f3kd92ld0" // string | Brand ID
	updateOrgBrandRequest := *openapiclient.NewUpdateOrgBrandRequest() // UpdateOrgBrandRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BrandsAPI.UpdateOrgBrand(context.Background(), orgId, brandId).UpdateOrgBrandRequest(updateOrgBrandRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BrandsAPI.UpdateOrgBrand``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateOrgBrand`: ListOrgBrands200ResponseDataInner
	fmt.Fprintf(os.Stdout, "Response from `BrandsAPI.UpdateOrgBrand`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 
**brandId** | **string** | Brand ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateOrgBrandRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updateOrgBrandRequest** | [**UpdateOrgBrandRequest**](UpdateOrgBrandRequest.md) |  | 

### Return type

[**ListOrgBrands200ResponseDataInner**](ListOrgBrands200ResponseDataInner.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UploadBrandLogo

> ListOrgBrands200ResponseDataInner UploadBrandLogo(ctx, orgId, brandId).File(file).Execute()

Upload brand logo



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
	brandId := "brnd_8f3kd92ld0" // string | Brand ID
	file := os.NewFile(1234, "some_file") // *os.File | Image file (PNG, JPG, or WEBP)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BrandsAPI.UploadBrandLogo(context.Background(), orgId, brandId).File(file).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BrandsAPI.UploadBrandLogo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UploadBrandLogo`: ListOrgBrands200ResponseDataInner
	fmt.Fprintf(os.Stdout, "Response from `BrandsAPI.UploadBrandLogo`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 
**brandId** | **string** | Brand ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiUploadBrandLogoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **file** | ***os.File** | Image file (PNG, JPG, or WEBP) | 

### Return type

[**ListOrgBrands200ResponseDataInner**](ListOrgBrands200ResponseDataInner.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

