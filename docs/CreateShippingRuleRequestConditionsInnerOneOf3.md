# CreateShippingRuleRequestConditionsInnerOneOf3

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** | Condition type discriminator | 
**Operator** | **string** | Comparison operator | 
**Value** | **int32** | Quantity value to compare against | 
**ShippingPrice** | **float32** | Shipping price when condition matches | 
**Currency** | **string** | ISO 4217 currency code | 

## Methods

### NewCreateShippingRuleRequestConditionsInnerOneOf3

`func NewCreateShippingRuleRequestConditionsInnerOneOf3(type_ string, operator string, value int32, shippingPrice float32, currency string, ) *CreateShippingRuleRequestConditionsInnerOneOf3`

NewCreateShippingRuleRequestConditionsInnerOneOf3 instantiates a new CreateShippingRuleRequestConditionsInnerOneOf3 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateShippingRuleRequestConditionsInnerOneOf3WithDefaults

`func NewCreateShippingRuleRequestConditionsInnerOneOf3WithDefaults() *CreateShippingRuleRequestConditionsInnerOneOf3`

NewCreateShippingRuleRequestConditionsInnerOneOf3WithDefaults instantiates a new CreateShippingRuleRequestConditionsInnerOneOf3 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *CreateShippingRuleRequestConditionsInnerOneOf3) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CreateShippingRuleRequestConditionsInnerOneOf3) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CreateShippingRuleRequestConditionsInnerOneOf3) SetType(v string)`

SetType sets Type field to given value.


### GetOperator

`func (o *CreateShippingRuleRequestConditionsInnerOneOf3) GetOperator() string`

GetOperator returns the Operator field if non-nil, zero value otherwise.

### GetOperatorOk

`func (o *CreateShippingRuleRequestConditionsInnerOneOf3) GetOperatorOk() (*string, bool)`

GetOperatorOk returns a tuple with the Operator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperator

`func (o *CreateShippingRuleRequestConditionsInnerOneOf3) SetOperator(v string)`

SetOperator sets Operator field to given value.


### GetValue

`func (o *CreateShippingRuleRequestConditionsInnerOneOf3) GetValue() int32`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *CreateShippingRuleRequestConditionsInnerOneOf3) GetValueOk() (*int32, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *CreateShippingRuleRequestConditionsInnerOneOf3) SetValue(v int32)`

SetValue sets Value field to given value.


### GetShippingPrice

`func (o *CreateShippingRuleRequestConditionsInnerOneOf3) GetShippingPrice() float32`

GetShippingPrice returns the ShippingPrice field if non-nil, zero value otherwise.

### GetShippingPriceOk

`func (o *CreateShippingRuleRequestConditionsInnerOneOf3) GetShippingPriceOk() (*float32, bool)`

GetShippingPriceOk returns a tuple with the ShippingPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingPrice

`func (o *CreateShippingRuleRequestConditionsInnerOneOf3) SetShippingPrice(v float32)`

SetShippingPrice sets ShippingPrice field to given value.


### GetCurrency

`func (o *CreateShippingRuleRequestConditionsInnerOneOf3) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *CreateShippingRuleRequestConditionsInnerOneOf3) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *CreateShippingRuleRequestConditionsInnerOneOf3) SetCurrency(v string)`

SetCurrency sets Currency field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


