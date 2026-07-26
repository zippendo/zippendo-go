# CreateShippingRuleRequestConditionsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** | Condition type discriminator | 
**Min** | **float32** | Minimum cart value (inclusive) | 
**Max** | **float32** | Maximum cart value (inclusive) | 
**ShippingPrice** | **float32** | Flat shipping price | 
**Currency** | **string** | ISO 4217 currency code | 
**PriceType** | Pointer to **string** | Whether to compare against subtotal (before discounts) or total (after discounts) | [optional] [default to "total"]
**Operator** | **string** | Comparison operator | 
**Value** | **int32** | Quantity value to compare against | 

## Methods

### NewCreateShippingRuleRequestConditionsInner

`func NewCreateShippingRuleRequestConditionsInner(type_ string, min float32, max float32, shippingPrice float32, currency string, operator string, value int32, ) *CreateShippingRuleRequestConditionsInner`

NewCreateShippingRuleRequestConditionsInner instantiates a new CreateShippingRuleRequestConditionsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateShippingRuleRequestConditionsInnerWithDefaults

`func NewCreateShippingRuleRequestConditionsInnerWithDefaults() *CreateShippingRuleRequestConditionsInner`

NewCreateShippingRuleRequestConditionsInnerWithDefaults instantiates a new CreateShippingRuleRequestConditionsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *CreateShippingRuleRequestConditionsInner) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CreateShippingRuleRequestConditionsInner) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CreateShippingRuleRequestConditionsInner) SetType(v string)`

SetType sets Type field to given value.


### GetMin

`func (o *CreateShippingRuleRequestConditionsInner) GetMin() float32`

GetMin returns the Min field if non-nil, zero value otherwise.

### GetMinOk

`func (o *CreateShippingRuleRequestConditionsInner) GetMinOk() (*float32, bool)`

GetMinOk returns a tuple with the Min field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMin

`func (o *CreateShippingRuleRequestConditionsInner) SetMin(v float32)`

SetMin sets Min field to given value.


### GetMax

`func (o *CreateShippingRuleRequestConditionsInner) GetMax() float32`

GetMax returns the Max field if non-nil, zero value otherwise.

### GetMaxOk

`func (o *CreateShippingRuleRequestConditionsInner) GetMaxOk() (*float32, bool)`

GetMaxOk returns a tuple with the Max field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMax

`func (o *CreateShippingRuleRequestConditionsInner) SetMax(v float32)`

SetMax sets Max field to given value.


### GetShippingPrice

`func (o *CreateShippingRuleRequestConditionsInner) GetShippingPrice() float32`

GetShippingPrice returns the ShippingPrice field if non-nil, zero value otherwise.

### GetShippingPriceOk

`func (o *CreateShippingRuleRequestConditionsInner) GetShippingPriceOk() (*float32, bool)`

GetShippingPriceOk returns a tuple with the ShippingPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingPrice

`func (o *CreateShippingRuleRequestConditionsInner) SetShippingPrice(v float32)`

SetShippingPrice sets ShippingPrice field to given value.


### GetCurrency

`func (o *CreateShippingRuleRequestConditionsInner) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *CreateShippingRuleRequestConditionsInner) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *CreateShippingRuleRequestConditionsInner) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetPriceType

`func (o *CreateShippingRuleRequestConditionsInner) GetPriceType() string`

GetPriceType returns the PriceType field if non-nil, zero value otherwise.

### GetPriceTypeOk

`func (o *CreateShippingRuleRequestConditionsInner) GetPriceTypeOk() (*string, bool)`

GetPriceTypeOk returns a tuple with the PriceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceType

`func (o *CreateShippingRuleRequestConditionsInner) SetPriceType(v string)`

SetPriceType sets PriceType field to given value.

### HasPriceType

`func (o *CreateShippingRuleRequestConditionsInner) HasPriceType() bool`

HasPriceType returns a boolean if a field has been set.

### GetOperator

`func (o *CreateShippingRuleRequestConditionsInner) GetOperator() string`

GetOperator returns the Operator field if non-nil, zero value otherwise.

### GetOperatorOk

`func (o *CreateShippingRuleRequestConditionsInner) GetOperatorOk() (*string, bool)`

GetOperatorOk returns a tuple with the Operator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperator

`func (o *CreateShippingRuleRequestConditionsInner) SetOperator(v string)`

SetOperator sets Operator field to given value.


### GetValue

`func (o *CreateShippingRuleRequestConditionsInner) GetValue() int32`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *CreateShippingRuleRequestConditionsInner) GetValueOk() (*int32, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *CreateShippingRuleRequestConditionsInner) SetValue(v int32)`

SetValue sets Value field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


