# ListShippingRules200ResponseDataInnerConditionsInnerOneOf2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** | Condition type discriminator | 
**PriceType** | **string** | Whether to compare against subtotal (before discounts) or total (after discounts) | [default to "total"]
**Min** | **float32** | Minimum cart value (inclusive) | 
**Max** | **float32** | Maximum cart value (inclusive) | 
**ShippingPrice** | **float32** | Shipping price when condition matches | 
**Currency** | **string** | ISO 4217 currency code | 

## Methods

### NewListShippingRules200ResponseDataInnerConditionsInnerOneOf2

`func NewListShippingRules200ResponseDataInnerConditionsInnerOneOf2(type_ string, priceType string, min float32, max float32, shippingPrice float32, currency string, ) *ListShippingRules200ResponseDataInnerConditionsInnerOneOf2`

NewListShippingRules200ResponseDataInnerConditionsInnerOneOf2 instantiates a new ListShippingRules200ResponseDataInnerConditionsInnerOneOf2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListShippingRules200ResponseDataInnerConditionsInnerOneOf2WithDefaults

`func NewListShippingRules200ResponseDataInnerConditionsInnerOneOf2WithDefaults() *ListShippingRules200ResponseDataInnerConditionsInnerOneOf2`

NewListShippingRules200ResponseDataInnerConditionsInnerOneOf2WithDefaults instantiates a new ListShippingRules200ResponseDataInnerConditionsInnerOneOf2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf2) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf2) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf2) SetType(v string)`

SetType sets Type field to given value.


### GetPriceType

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf2) GetPriceType() string`

GetPriceType returns the PriceType field if non-nil, zero value otherwise.

### GetPriceTypeOk

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf2) GetPriceTypeOk() (*string, bool)`

GetPriceTypeOk returns a tuple with the PriceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceType

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf2) SetPriceType(v string)`

SetPriceType sets PriceType field to given value.


### GetMin

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf2) GetMin() float32`

GetMin returns the Min field if non-nil, zero value otherwise.

### GetMinOk

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf2) GetMinOk() (*float32, bool)`

GetMinOk returns a tuple with the Min field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMin

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf2) SetMin(v float32)`

SetMin sets Min field to given value.


### GetMax

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf2) GetMax() float32`

GetMax returns the Max field if non-nil, zero value otherwise.

### GetMaxOk

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf2) GetMaxOk() (*float32, bool)`

GetMaxOk returns a tuple with the Max field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMax

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf2) SetMax(v float32)`

SetMax sets Max field to given value.


### GetShippingPrice

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf2) GetShippingPrice() float32`

GetShippingPrice returns the ShippingPrice field if non-nil, zero value otherwise.

### GetShippingPriceOk

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf2) GetShippingPriceOk() (*float32, bool)`

GetShippingPriceOk returns a tuple with the ShippingPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingPrice

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf2) SetShippingPrice(v float32)`

SetShippingPrice sets ShippingPrice field to given value.


### GetCurrency

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf2) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf2) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf2) SetCurrency(v string)`

SetCurrency sets Currency field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


