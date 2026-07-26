# ListShippingRules200ResponseDataInnerConditionsInnerOneOf1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** | Condition type discriminator | 
**PriceType** | **string** | Whether to compare against subtotal (before discounts) or total (after discounts) | [default to "total"]
**Operator** | **string** | Comparison operator | 
**Value** | **float32** | Price value to compare against | 
**ShippingPrice** | **float32** | Shipping price when condition matches | 
**Currency** | **string** | ISO 4217 currency code | 

## Methods

### NewListShippingRules200ResponseDataInnerConditionsInnerOneOf1

`func NewListShippingRules200ResponseDataInnerConditionsInnerOneOf1(type_ string, priceType string, operator string, value float32, shippingPrice float32, currency string, ) *ListShippingRules200ResponseDataInnerConditionsInnerOneOf1`

NewListShippingRules200ResponseDataInnerConditionsInnerOneOf1 instantiates a new ListShippingRules200ResponseDataInnerConditionsInnerOneOf1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListShippingRules200ResponseDataInnerConditionsInnerOneOf1WithDefaults

`func NewListShippingRules200ResponseDataInnerConditionsInnerOneOf1WithDefaults() *ListShippingRules200ResponseDataInnerConditionsInnerOneOf1`

NewListShippingRules200ResponseDataInnerConditionsInnerOneOf1WithDefaults instantiates a new ListShippingRules200ResponseDataInnerConditionsInnerOneOf1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf1) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf1) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf1) SetType(v string)`

SetType sets Type field to given value.


### GetPriceType

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf1) GetPriceType() string`

GetPriceType returns the PriceType field if non-nil, zero value otherwise.

### GetPriceTypeOk

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf1) GetPriceTypeOk() (*string, bool)`

GetPriceTypeOk returns a tuple with the PriceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceType

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf1) SetPriceType(v string)`

SetPriceType sets PriceType field to given value.


### GetOperator

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf1) GetOperator() string`

GetOperator returns the Operator field if non-nil, zero value otherwise.

### GetOperatorOk

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf1) GetOperatorOk() (*string, bool)`

GetOperatorOk returns a tuple with the Operator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperator

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf1) SetOperator(v string)`

SetOperator sets Operator field to given value.


### GetValue

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf1) GetValue() float32`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf1) GetValueOk() (*float32, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf1) SetValue(v float32)`

SetValue sets Value field to given value.


### GetShippingPrice

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf1) GetShippingPrice() float32`

GetShippingPrice returns the ShippingPrice field if non-nil, zero value otherwise.

### GetShippingPriceOk

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf1) GetShippingPriceOk() (*float32, bool)`

GetShippingPriceOk returns a tuple with the ShippingPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingPrice

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf1) SetShippingPrice(v float32)`

SetShippingPrice sets ShippingPrice field to given value.


### GetCurrency

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf1) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf1) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *ListShippingRules200ResponseDataInnerConditionsInnerOneOf1) SetCurrency(v string)`

SetCurrency sets Currency field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


