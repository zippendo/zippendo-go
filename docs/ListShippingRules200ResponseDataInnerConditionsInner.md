# ListShippingRules200ResponseDataInnerConditionsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** | Condition type discriminator | 
**Min** | **float32** | Minimum cart value (inclusive) | 
**Max** | **float32** | Maximum cart value (inclusive) | 
**ShippingPrice** | **float32** | Flat shipping price | 
**Currency** | **string** | ISO 4217 currency code | 
**PriceType** | **string** | Whether to compare against subtotal (before discounts) or total (after discounts) | [default to "total"]
**Operator** | **string** | Comparison operator | 
**Value** | **int32** | Quantity value to compare against | 

## Methods

### NewListShippingRules200ResponseDataInnerConditionsInner

`func NewListShippingRules200ResponseDataInnerConditionsInner(type_ string, min float32, max float32, shippingPrice float32, currency string, priceType string, operator string, value int32, ) *ListShippingRules200ResponseDataInnerConditionsInner`

NewListShippingRules200ResponseDataInnerConditionsInner instantiates a new ListShippingRules200ResponseDataInnerConditionsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListShippingRules200ResponseDataInnerConditionsInnerWithDefaults

`func NewListShippingRules200ResponseDataInnerConditionsInnerWithDefaults() *ListShippingRules200ResponseDataInnerConditionsInner`

NewListShippingRules200ResponseDataInnerConditionsInnerWithDefaults instantiates a new ListShippingRules200ResponseDataInnerConditionsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *ListShippingRules200ResponseDataInnerConditionsInner) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ListShippingRules200ResponseDataInnerConditionsInner) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ListShippingRules200ResponseDataInnerConditionsInner) SetType(v string)`

SetType sets Type field to given value.


### GetMin

`func (o *ListShippingRules200ResponseDataInnerConditionsInner) GetMin() float32`

GetMin returns the Min field if non-nil, zero value otherwise.

### GetMinOk

`func (o *ListShippingRules200ResponseDataInnerConditionsInner) GetMinOk() (*float32, bool)`

GetMinOk returns a tuple with the Min field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMin

`func (o *ListShippingRules200ResponseDataInnerConditionsInner) SetMin(v float32)`

SetMin sets Min field to given value.


### GetMax

`func (o *ListShippingRules200ResponseDataInnerConditionsInner) GetMax() float32`

GetMax returns the Max field if non-nil, zero value otherwise.

### GetMaxOk

`func (o *ListShippingRules200ResponseDataInnerConditionsInner) GetMaxOk() (*float32, bool)`

GetMaxOk returns a tuple with the Max field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMax

`func (o *ListShippingRules200ResponseDataInnerConditionsInner) SetMax(v float32)`

SetMax sets Max field to given value.


### GetShippingPrice

`func (o *ListShippingRules200ResponseDataInnerConditionsInner) GetShippingPrice() float32`

GetShippingPrice returns the ShippingPrice field if non-nil, zero value otherwise.

### GetShippingPriceOk

`func (o *ListShippingRules200ResponseDataInnerConditionsInner) GetShippingPriceOk() (*float32, bool)`

GetShippingPriceOk returns a tuple with the ShippingPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingPrice

`func (o *ListShippingRules200ResponseDataInnerConditionsInner) SetShippingPrice(v float32)`

SetShippingPrice sets ShippingPrice field to given value.


### GetCurrency

`func (o *ListShippingRules200ResponseDataInnerConditionsInner) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *ListShippingRules200ResponseDataInnerConditionsInner) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *ListShippingRules200ResponseDataInnerConditionsInner) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetPriceType

`func (o *ListShippingRules200ResponseDataInnerConditionsInner) GetPriceType() string`

GetPriceType returns the PriceType field if non-nil, zero value otherwise.

### GetPriceTypeOk

`func (o *ListShippingRules200ResponseDataInnerConditionsInner) GetPriceTypeOk() (*string, bool)`

GetPriceTypeOk returns a tuple with the PriceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceType

`func (o *ListShippingRules200ResponseDataInnerConditionsInner) SetPriceType(v string)`

SetPriceType sets PriceType field to given value.


### GetOperator

`func (o *ListShippingRules200ResponseDataInnerConditionsInner) GetOperator() string`

GetOperator returns the Operator field if non-nil, zero value otherwise.

### GetOperatorOk

`func (o *ListShippingRules200ResponseDataInnerConditionsInner) GetOperatorOk() (*string, bool)`

GetOperatorOk returns a tuple with the Operator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperator

`func (o *ListShippingRules200ResponseDataInnerConditionsInner) SetOperator(v string)`

SetOperator sets Operator field to given value.


### GetValue

`func (o *ListShippingRules200ResponseDataInnerConditionsInner) GetValue() int32`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *ListShippingRules200ResponseDataInnerConditionsInner) GetValueOk() (*int32, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *ListShippingRules200ResponseDataInnerConditionsInner) SetValue(v int32)`

SetValue sets Value field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


