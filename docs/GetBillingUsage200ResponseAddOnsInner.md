# GetBillingUsage200ResponseAddOnsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** | Type of billing add-on | 
**Quantity** | **float32** | Number of add-on units purchased | 
**UnitPrice** | **float32** | Price per unit per month, in øre | 
**TotalPrice** | **float32** | Total price per month, in øre | 

## Methods

### NewGetBillingUsage200ResponseAddOnsInner

`func NewGetBillingUsage200ResponseAddOnsInner(type_ string, quantity float32, unitPrice float32, totalPrice float32, ) *GetBillingUsage200ResponseAddOnsInner`

NewGetBillingUsage200ResponseAddOnsInner instantiates a new GetBillingUsage200ResponseAddOnsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetBillingUsage200ResponseAddOnsInnerWithDefaults

`func NewGetBillingUsage200ResponseAddOnsInnerWithDefaults() *GetBillingUsage200ResponseAddOnsInner`

NewGetBillingUsage200ResponseAddOnsInnerWithDefaults instantiates a new GetBillingUsage200ResponseAddOnsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *GetBillingUsage200ResponseAddOnsInner) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *GetBillingUsage200ResponseAddOnsInner) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *GetBillingUsage200ResponseAddOnsInner) SetType(v string)`

SetType sets Type field to given value.


### GetQuantity

`func (o *GetBillingUsage200ResponseAddOnsInner) GetQuantity() float32`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *GetBillingUsage200ResponseAddOnsInner) GetQuantityOk() (*float32, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *GetBillingUsage200ResponseAddOnsInner) SetQuantity(v float32)`

SetQuantity sets Quantity field to given value.


### GetUnitPrice

`func (o *GetBillingUsage200ResponseAddOnsInner) GetUnitPrice() float32`

GetUnitPrice returns the UnitPrice field if non-nil, zero value otherwise.

### GetUnitPriceOk

`func (o *GetBillingUsage200ResponseAddOnsInner) GetUnitPriceOk() (*float32, bool)`

GetUnitPriceOk returns a tuple with the UnitPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPrice

`func (o *GetBillingUsage200ResponseAddOnsInner) SetUnitPrice(v float32)`

SetUnitPrice sets UnitPrice field to given value.


### GetTotalPrice

`func (o *GetBillingUsage200ResponseAddOnsInner) GetTotalPrice() float32`

GetTotalPrice returns the TotalPrice field if non-nil, zero value otherwise.

### GetTotalPriceOk

`func (o *GetBillingUsage200ResponseAddOnsInner) GetTotalPriceOk() (*float32, bool)`

GetTotalPriceOk returns a tuple with the TotalPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPrice

`func (o *GetBillingUsage200ResponseAddOnsInner) SetTotalPrice(v float32)`

SetTotalPrice sets TotalPrice field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


