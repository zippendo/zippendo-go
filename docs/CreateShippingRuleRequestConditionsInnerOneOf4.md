# CreateShippingRuleRequestConditionsInnerOneOf4

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** | Condition type discriminator | 
**ShippingPrice** | **float32** | Flat shipping price | 
**Currency** | **string** | ISO 4217 currency code | 

## Methods

### NewCreateShippingRuleRequestConditionsInnerOneOf4

`func NewCreateShippingRuleRequestConditionsInnerOneOf4(type_ string, shippingPrice float32, currency string, ) *CreateShippingRuleRequestConditionsInnerOneOf4`

NewCreateShippingRuleRequestConditionsInnerOneOf4 instantiates a new CreateShippingRuleRequestConditionsInnerOneOf4 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateShippingRuleRequestConditionsInnerOneOf4WithDefaults

`func NewCreateShippingRuleRequestConditionsInnerOneOf4WithDefaults() *CreateShippingRuleRequestConditionsInnerOneOf4`

NewCreateShippingRuleRequestConditionsInnerOneOf4WithDefaults instantiates a new CreateShippingRuleRequestConditionsInnerOneOf4 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *CreateShippingRuleRequestConditionsInnerOneOf4) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CreateShippingRuleRequestConditionsInnerOneOf4) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CreateShippingRuleRequestConditionsInnerOneOf4) SetType(v string)`

SetType sets Type field to given value.


### GetShippingPrice

`func (o *CreateShippingRuleRequestConditionsInnerOneOf4) GetShippingPrice() float32`

GetShippingPrice returns the ShippingPrice field if non-nil, zero value otherwise.

### GetShippingPriceOk

`func (o *CreateShippingRuleRequestConditionsInnerOneOf4) GetShippingPriceOk() (*float32, bool)`

GetShippingPriceOk returns a tuple with the ShippingPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingPrice

`func (o *CreateShippingRuleRequestConditionsInnerOneOf4) SetShippingPrice(v float32)`

SetShippingPrice sets ShippingPrice field to given value.


### GetCurrency

`func (o *CreateShippingRuleRequestConditionsInnerOneOf4) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *CreateShippingRuleRequestConditionsInnerOneOf4) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *CreateShippingRuleRequestConditionsInnerOneOf4) SetCurrency(v string)`

SetCurrency sets Currency field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


