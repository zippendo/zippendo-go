# CreateShippingRuleRequestConditionsInnerOneOf2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** | Condition type discriminator | 
**PriceType** | Pointer to **string** | Whether to compare against subtotal (before discounts) or total (after discounts) | [optional] [default to "total"]
**Min** | **float32** | Minimum cart value (inclusive) | 
**Max** | **float32** | Maximum cart value (inclusive) | 
**ShippingPrice** | **float32** | Shipping price when condition matches | 
**Currency** | **string** | ISO 4217 currency code | 

## Methods

### NewCreateShippingRuleRequestConditionsInnerOneOf2

`func NewCreateShippingRuleRequestConditionsInnerOneOf2(type_ string, min float32, max float32, shippingPrice float32, currency string, ) *CreateShippingRuleRequestConditionsInnerOneOf2`

NewCreateShippingRuleRequestConditionsInnerOneOf2 instantiates a new CreateShippingRuleRequestConditionsInnerOneOf2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateShippingRuleRequestConditionsInnerOneOf2WithDefaults

`func NewCreateShippingRuleRequestConditionsInnerOneOf2WithDefaults() *CreateShippingRuleRequestConditionsInnerOneOf2`

NewCreateShippingRuleRequestConditionsInnerOneOf2WithDefaults instantiates a new CreateShippingRuleRequestConditionsInnerOneOf2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *CreateShippingRuleRequestConditionsInnerOneOf2) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CreateShippingRuleRequestConditionsInnerOneOf2) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CreateShippingRuleRequestConditionsInnerOneOf2) SetType(v string)`

SetType sets Type field to given value.


### GetPriceType

`func (o *CreateShippingRuleRequestConditionsInnerOneOf2) GetPriceType() string`

GetPriceType returns the PriceType field if non-nil, zero value otherwise.

### GetPriceTypeOk

`func (o *CreateShippingRuleRequestConditionsInnerOneOf2) GetPriceTypeOk() (*string, bool)`

GetPriceTypeOk returns a tuple with the PriceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceType

`func (o *CreateShippingRuleRequestConditionsInnerOneOf2) SetPriceType(v string)`

SetPriceType sets PriceType field to given value.

### HasPriceType

`func (o *CreateShippingRuleRequestConditionsInnerOneOf2) HasPriceType() bool`

HasPriceType returns a boolean if a field has been set.

### GetMin

`func (o *CreateShippingRuleRequestConditionsInnerOneOf2) GetMin() float32`

GetMin returns the Min field if non-nil, zero value otherwise.

### GetMinOk

`func (o *CreateShippingRuleRequestConditionsInnerOneOf2) GetMinOk() (*float32, bool)`

GetMinOk returns a tuple with the Min field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMin

`func (o *CreateShippingRuleRequestConditionsInnerOneOf2) SetMin(v float32)`

SetMin sets Min field to given value.


### GetMax

`func (o *CreateShippingRuleRequestConditionsInnerOneOf2) GetMax() float32`

GetMax returns the Max field if non-nil, zero value otherwise.

### GetMaxOk

`func (o *CreateShippingRuleRequestConditionsInnerOneOf2) GetMaxOk() (*float32, bool)`

GetMaxOk returns a tuple with the Max field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMax

`func (o *CreateShippingRuleRequestConditionsInnerOneOf2) SetMax(v float32)`

SetMax sets Max field to given value.


### GetShippingPrice

`func (o *CreateShippingRuleRequestConditionsInnerOneOf2) GetShippingPrice() float32`

GetShippingPrice returns the ShippingPrice field if non-nil, zero value otherwise.

### GetShippingPriceOk

`func (o *CreateShippingRuleRequestConditionsInnerOneOf2) GetShippingPriceOk() (*float32, bool)`

GetShippingPriceOk returns a tuple with the ShippingPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingPrice

`func (o *CreateShippingRuleRequestConditionsInnerOneOf2) SetShippingPrice(v float32)`

SetShippingPrice sets ShippingPrice field to given value.


### GetCurrency

`func (o *CreateShippingRuleRequestConditionsInnerOneOf2) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *CreateShippingRuleRequestConditionsInnerOneOf2) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *CreateShippingRuleRequestConditionsInnerOneOf2) SetCurrency(v string)`

SetCurrency sets Currency field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


