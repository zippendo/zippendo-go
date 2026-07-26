# CreateShippingQuoteRequestItemsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | Item name | 
**Sku** | Pointer to **NullableString** | SKU identifier | [optional] 
**Quantity** | **int32** | Quantity | 
**Grams** | **float32** | Weight in grams | 
**Price** | **float32** | Price in cents | 
**ProductId** | Pointer to **NullableString** | Product ID | [optional] 
**VariantId** | Pointer to **NullableString** | Variant ID | [optional] 

## Methods

### NewCreateShippingQuoteRequestItemsInner

`func NewCreateShippingQuoteRequestItemsInner(name string, quantity int32, grams float32, price float32, ) *CreateShippingQuoteRequestItemsInner`

NewCreateShippingQuoteRequestItemsInner instantiates a new CreateShippingQuoteRequestItemsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateShippingQuoteRequestItemsInnerWithDefaults

`func NewCreateShippingQuoteRequestItemsInnerWithDefaults() *CreateShippingQuoteRequestItemsInner`

NewCreateShippingQuoteRequestItemsInnerWithDefaults instantiates a new CreateShippingQuoteRequestItemsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateShippingQuoteRequestItemsInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateShippingQuoteRequestItemsInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateShippingQuoteRequestItemsInner) SetName(v string)`

SetName sets Name field to given value.


### GetSku

`func (o *CreateShippingQuoteRequestItemsInner) GetSku() string`

GetSku returns the Sku field if non-nil, zero value otherwise.

### GetSkuOk

`func (o *CreateShippingQuoteRequestItemsInner) GetSkuOk() (*string, bool)`

GetSkuOk returns a tuple with the Sku field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSku

`func (o *CreateShippingQuoteRequestItemsInner) SetSku(v string)`

SetSku sets Sku field to given value.

### HasSku

`func (o *CreateShippingQuoteRequestItemsInner) HasSku() bool`

HasSku returns a boolean if a field has been set.

### SetSkuNil

`func (o *CreateShippingQuoteRequestItemsInner) SetSkuNil(b bool)`

 SetSkuNil sets the value for Sku to be an explicit nil

### UnsetSku
`func (o *CreateShippingQuoteRequestItemsInner) UnsetSku()`

UnsetSku ensures that no value is present for Sku, not even an explicit nil
### GetQuantity

`func (o *CreateShippingQuoteRequestItemsInner) GetQuantity() int32`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *CreateShippingQuoteRequestItemsInner) GetQuantityOk() (*int32, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *CreateShippingQuoteRequestItemsInner) SetQuantity(v int32)`

SetQuantity sets Quantity field to given value.


### GetGrams

`func (o *CreateShippingQuoteRequestItemsInner) GetGrams() float32`

GetGrams returns the Grams field if non-nil, zero value otherwise.

### GetGramsOk

`func (o *CreateShippingQuoteRequestItemsInner) GetGramsOk() (*float32, bool)`

GetGramsOk returns a tuple with the Grams field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrams

`func (o *CreateShippingQuoteRequestItemsInner) SetGrams(v float32)`

SetGrams sets Grams field to given value.


### GetPrice

`func (o *CreateShippingQuoteRequestItemsInner) GetPrice() float32`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *CreateShippingQuoteRequestItemsInner) GetPriceOk() (*float32, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *CreateShippingQuoteRequestItemsInner) SetPrice(v float32)`

SetPrice sets Price field to given value.


### GetProductId

`func (o *CreateShippingQuoteRequestItemsInner) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *CreateShippingQuoteRequestItemsInner) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *CreateShippingQuoteRequestItemsInner) SetProductId(v string)`

SetProductId sets ProductId field to given value.

### HasProductId

`func (o *CreateShippingQuoteRequestItemsInner) HasProductId() bool`

HasProductId returns a boolean if a field has been set.

### SetProductIdNil

`func (o *CreateShippingQuoteRequestItemsInner) SetProductIdNil(b bool)`

 SetProductIdNil sets the value for ProductId to be an explicit nil

### UnsetProductId
`func (o *CreateShippingQuoteRequestItemsInner) UnsetProductId()`

UnsetProductId ensures that no value is present for ProductId, not even an explicit nil
### GetVariantId

`func (o *CreateShippingQuoteRequestItemsInner) GetVariantId() string`

GetVariantId returns the VariantId field if non-nil, zero value otherwise.

### GetVariantIdOk

`func (o *CreateShippingQuoteRequestItemsInner) GetVariantIdOk() (*string, bool)`

GetVariantIdOk returns a tuple with the VariantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVariantId

`func (o *CreateShippingQuoteRequestItemsInner) SetVariantId(v string)`

SetVariantId sets VariantId field to given value.

### HasVariantId

`func (o *CreateShippingQuoteRequestItemsInner) HasVariantId() bool`

HasVariantId returns a boolean if a field has been set.

### SetVariantIdNil

`func (o *CreateShippingQuoteRequestItemsInner) SetVariantIdNil(b bool)`

 SetVariantIdNil sets the value for VariantId to be an explicit nil

### UnsetVariantId
`func (o *CreateShippingQuoteRequestItemsInner) UnsetVariantId()`

UnsetVariantId ensures that no value is present for VariantId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


