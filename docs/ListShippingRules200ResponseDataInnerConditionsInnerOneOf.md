# ListShippingRules200ResponseDataInnerConditionsInnerOneOf

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** | Condition type discriminator | 
**Min** | **float32** | Minimum weight in kg (inclusive) | 
**Max** | **float32** | Maximum weight in kg (inclusive) | 
**ShippingPrice** | **float32** | Shipping price when condition matches | 
**Currency** | **string** | ISO 4217 currency code | 

## Methods

### NewListShippingRules200ResponseDataInnerConditionsInnerOneOf

`func NewListShippingRules200ResponseDataInnerConditionsInnerOneOf(type_ string, min float32, max float32, shippingPrice float32, currency string, ) *ListShippingRules200ResponseDataInnerConditionsInnerOneOf`

NewListShippingRules200ResponseDataInnerConditionsInnerOneOf instantiates a new ListShippingRules200ResponseDataInnerConditionsInnerOneOf object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListShippingRules200ResponseDataInnerConditionsInnerOneOfWithDefaults

`func NewListShippingRules200ResponseDataInnerConditionsInnerOneOfWithDefaults() *ListShippingRules200ResponseDataInnerConditionsInnerOneOf`

NewListShippingRules200ResponseDataInnerConditionsInnerOneOfWithDefaults instantiates a new ListShippingRules200ResponseDataInnerConditionsInnerOneOf object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf) SetType(v string)`

SetType sets Type field to given value.


### GetMin

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf) GetMin() float32`

GetMin returns the Min field if non-nil, zero value otherwise.

### GetMinOk

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf) GetMinOk() (*float32, bool)`

GetMinOk returns a tuple with the Min field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMin

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf) SetMin(v float32)`

SetMin sets Min field to given value.


### GetMax

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf) GetMax() float32`

GetMax returns the Max field if non-nil, zero value otherwise.

### GetMaxOk

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf) GetMaxOk() (*float32, bool)`

GetMaxOk returns a tuple with the Max field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMax

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf) SetMax(v float32)`

SetMax sets Max field to given value.


### GetShippingPrice

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf) GetShippingPrice() float32`

GetShippingPrice returns the ShippingPrice field if non-nil, zero value otherwise.

### GetShippingPriceOk

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf) GetShippingPriceOk() (*float32, bool)`

GetShippingPriceOk returns a tuple with the ShippingPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingPrice

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf) SetShippingPrice(v float32)`

SetShippingPrice sets ShippingPrice field to given value.


### GetCurrency

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf) SetCurrency(v string)`

SetCurrency sets Currency field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


