# CreateShippingRuleRequestConditionsInnerOneOf1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** | Condition type discriminator | 
**PriceType** | Pointer to **string** | Whether to compare against subtotal (before discounts) or total (after discounts) | [optional] [default to "total"]
**Operator** | **string** | Comparison operator | 
**Value** | **float32** | Price value to compare against | 
**ShippingPrice** | **float32** | Shipping price when condition matches | 
**Currency** | **string** | ISO 4217 currency code | 

## Methods

### NewCreateShippingRuleRequestConditionsInnerOneOf1

`func NewCreateShippingRuleRequestConditionsInnerOneOf1(type_ string, operator string, value float32, shippingPrice float32, currency string, ) *CreateShippingRuleRequestConditionsInnerOneOf1`

NewCreateShippingRuleRequestConditionsInnerOneOf1 instantiates a new CreateShippingRuleRequestConditionsInnerOneOf1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateShippingRuleRequestConditionsInnerOneOf1WithDefaults

`func NewCreateShippingRuleRequestConditionsInnerOneOf1WithDefaults() *CreateShippingRuleRequestConditionsInnerOneOf1`

NewCreateShippingRuleRequestConditionsInnerOneOf1WithDefaults instantiates a new CreateShippingRuleRequestConditionsInnerOneOf1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *CreateShippingRuleRequestConditionsInnerOneOf1) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CreateShippingRuleRequestConditionsInnerOneOf1) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CreateShippingRuleRequestConditionsInnerOneOf1) SetType(v string)`

SetType sets Type field to given value.


### GetPriceType

`func (o *CreateShippingRuleRequestConditionsInnerOneOf1) GetPriceType() string`

GetPriceType returns the PriceType field if non-nil, zero value otherwise.

### GetPriceTypeOk

`func (o *CreateShippingRuleRequestConditionsInnerOneOf1) GetPriceTypeOk() (*string, bool)`

GetPriceTypeOk returns a tuple with the PriceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceType

`func (o *CreateShippingRuleRequestConditionsInnerOneOf1) SetPriceType(v string)`

SetPriceType sets PriceType field to given value.

### HasPriceType

`func (o *CreateShippingRuleRequestConditionsInnerOneOf1) HasPriceType() bool`

HasPriceType returns a boolean if a field has been set.

### GetOperator

`func (o *CreateShippingRuleRequestConditionsInnerOneOf1) GetOperator() string`

GetOperator returns the Operator field if non-nil, zero value otherwise.

### GetOperatorOk

`func (o *CreateShippingRuleRequestConditionsInnerOneOf1) GetOperatorOk() (*string, bool)`

GetOperatorOk returns a tuple with the Operator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperator

`func (o *CreateShippingRuleRequestConditionsInnerOneOf1) SetOperator(v string)`

SetOperator sets Operator field to given value.


### GetValue

`func (o *CreateShippingRuleRequestConditionsInnerOneOf1) GetValue() float32`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *CreateShippingRuleRequestConditionsInnerOneOf1) GetValueOk() (*float32, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *CreateShippingRuleRequestConditionsInnerOneOf1) SetValue(v float32)`

SetValue sets Value field to given value.


### GetShippingPrice

`func (o *CreateShippingRuleRequestConditionsInnerOneOf1) GetShippingPrice() float32`

GetShippingPrice returns the ShippingPrice field if non-nil, zero value otherwise.

### GetShippingPriceOk

`func (o *CreateShippingRuleRequestConditionsInnerOneOf1) GetShippingPriceOk() (*float32, bool)`

GetShippingPriceOk returns a tuple with the ShippingPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingPrice

`func (o *CreateShippingRuleRequestConditionsInnerOneOf1) SetShippingPrice(v float32)`

SetShippingPrice sets ShippingPrice field to given value.


### GetCurrency

`func (o *CreateShippingRuleRequestConditionsInnerOneOf1) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *CreateShippingRuleRequestConditionsInnerOneOf1) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *CreateShippingRuleRequestConditionsInnerOneOf1) SetCurrency(v string)`

SetCurrency sets Currency field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


