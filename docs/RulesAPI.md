# \RulesAPI

All URIs are relative to *https://api.zippendo.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateShippingRule**](RulesAPI.md#CreateShippingRule) | **Post** /orgs/{orgId}/shipping-rules | Create shipping rule
[**DeleteShippingRule**](RulesAPI.md#DeleteShippingRule) | **Delete** /orgs/{orgId}/shipping-rules/{ruleId} | Delete shipping rule
[**GetShippingRule**](RulesAPI.md#GetShippingRule) | **Get** /orgs/{orgId}/shipping-rules/{ruleId} | Get shipping rule
[**ListShippingRules**](RulesAPI.md#ListShippingRules) | **Get** /orgs/{orgId}/shipping-rules | List shipping rules
[**UpdateShippingRule**](RulesAPI.md#UpdateShippingRule) | **Patch** /orgs/{orgId}/shipping-rules/{ruleId} | Update shipping rule



## CreateShippingRule

> CreateShippingRule201Response CreateShippingRule(ctx, orgId).CreateShippingRuleRequest(createShippingRuleRequest).Execute()

Create shipping rule



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
	createShippingRuleRequest := *openapiclient.NewCreateShippingRuleRequest("Standard DK", "carr_01HZX9K2QF", "PNL13", []string{"EMAIL_NOTIFICATION"}, "addr_01HZX9K2QF", []string{"DK"}, []openapiclient.CreateShippingRuleRequestConditionsInner{openapiclient.createShippingRule_request_conditions_inner{CreateShippingRuleRequestConditionsInnerOneOf: openapiclient.NewCreateShippingRuleRequestConditionsInnerOneOf("weight", float32(0), float32(5), float32(39), "DKK")}}) // CreateShippingRuleRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RulesAPI.CreateShippingRule(context.Background(), orgId).CreateShippingRuleRequest(createShippingRuleRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RulesAPI.CreateShippingRule``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateShippingRule`: CreateShippingRule201Response
	fmt.Fprintf(os.Stdout, "Response from `RulesAPI.CreateShippingRule`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateShippingRuleRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createShippingRuleRequest** | [**CreateShippingRuleRequest**](CreateShippingRuleRequest.md) |  | 

### Return type

[**CreateShippingRule201Response**](CreateShippingRule201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteShippingRule

> DeleteShippingRule200Response DeleteShippingRule(ctx, orgId, ruleId).Execute()

Delete shipping rule



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
	ruleId := "rule_01HZX9K2QF" // string | Shipping Rule ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RulesAPI.DeleteShippingRule(context.Background(), orgId, ruleId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RulesAPI.DeleteShippingRule``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteShippingRule`: DeleteShippingRule200Response
	fmt.Fprintf(os.Stdout, "Response from `RulesAPI.DeleteShippingRule`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 
**ruleId** | **string** | Shipping Rule ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteShippingRuleRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**DeleteShippingRule200Response**](DeleteShippingRule200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetShippingRule

> ListShippingRules200ResponseDataInner GetShippingRule(ctx, orgId, ruleId).Execute()

Get shipping rule



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
	ruleId := "rule_01HZX9K2QF" // string | Shipping Rule ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RulesAPI.GetShippingRule(context.Background(), orgId, ruleId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RulesAPI.GetShippingRule``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetShippingRule`: ListShippingRules200ResponseDataInner
	fmt.Fprintf(os.Stdout, "Response from `RulesAPI.GetShippingRule`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 
**ruleId** | **string** | Shipping Rule ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetShippingRuleRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**ListShippingRules200ResponseDataInner**](ListShippingRules200ResponseDataInner.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListShippingRules

> ListShippingRules200Response ListShippingRules(ctx, orgId).Page(page).Limit(limit).Execute()

List shipping rules



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RulesAPI.ListShippingRules(context.Background(), orgId).Page(page).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RulesAPI.ListShippingRules``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListShippingRules`: ListShippingRules200Response
	fmt.Fprintf(os.Stdout, "Response from `RulesAPI.ListShippingRules`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiListShippingRulesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **page** | **int32** | Page number (1-based) | [default to 1]
 **limit** | **int32** | Items per page (max 100) | [default to 20]

### Return type

[**ListShippingRules200Response**](ListShippingRules200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateShippingRule

> CreateShippingRule201Response UpdateShippingRule(ctx, orgId, ruleId).UpdateShippingRuleRequest(updateShippingRuleRequest).Execute()

Update shipping rule



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
	ruleId := "rule_01HZX9K2QF" // string | Shipping Rule ID
	updateShippingRuleRequest := *openapiclient.NewUpdateShippingRuleRequest() // UpdateShippingRuleRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RulesAPI.UpdateShippingRule(context.Background(), orgId, ruleId).UpdateShippingRuleRequest(updateShippingRuleRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RulesAPI.UpdateShippingRule``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateShippingRule`: CreateShippingRule201Response
	fmt.Fprintf(os.Stdout, "Response from `RulesAPI.UpdateShippingRule`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orgId** | **string** | Organization ID | 
**ruleId** | **string** | Shipping Rule ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateShippingRuleRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updateShippingRuleRequest** | [**UpdateShippingRuleRequest**](UpdateShippingRuleRequest.md) |  | 

### Return type

[**CreateShippingRule201Response**](CreateShippingRule201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

