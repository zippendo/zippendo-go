# CreateOrderRequestOrderLinesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Sku** | Pointer to **NullableString** | Stock keeping unit identifier. | [optional] 
**Name** | **string** | Product name. | 
**Quantity** | **int32** | Quantity ordered. | 
**UnitPrice** | Pointer to **NullableFloat32** | Price per unit. | [optional] 
**TotalPrice** | Pointer to **NullableFloat32** | Total price for the line. | [optional] 
**Currency** | Pointer to **NullableString** | ISO 4217 currency code. | [optional] 
**Weight** | Pointer to **NullableFloat32** | Item weight in the given unit. | [optional] 
**WeightUnit** | Pointer to **NullableString** | Unit of the weight value. | [optional] 
**VariantId** | Pointer to **NullableString** | Platform variant identifier. | [optional] 
**ProductId** | Pointer to **NullableString** | Platform product identifier. | [optional] 
**ImageUrl** | Pointer to **NullableString** | Product image URL. | [optional] 
**HsCode** | Pointer to **NullableString** | Harmonized System customs code (6-13 digits). | [optional] 
**CountryOfOrigin** | Pointer to **NullableString** | ISO 3166-1 alpha-2 country of origin. | [optional] 
**ProvinceOfOrigin** | Pointer to **NullableString** | ISO 3166-2 province of origin. | [optional] 
**Barcode** | Pointer to **NullableString** | Item barcode (EAN/UPC). | [optional] 
**RequiresShipping** | Pointer to **NullableBool** | Whether the item requires shipping. | [optional] 
**Taxable** | Pointer to **NullableBool** | Whether the item is taxable. | [optional] 
**GiftCard** | Pointer to **NullableBool** | Whether the item is a gift card. | [optional] 
**Vendor** | Pointer to **NullableString** | Vendor or brand name. | [optional] 

## Methods

### NewCreateOrderRequestOrderLinesInner

`func NewCreateOrderRequestOrderLinesInner(name string, quantity int32, ) *CreateOrderRequestOrderLinesInner`

NewCreateOrderRequestOrderLinesInner instantiates a new CreateOrderRequestOrderLinesInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateOrderRequestOrderLinesInnerWithDefaults

`func NewCreateOrderRequestOrderLinesInnerWithDefaults() *CreateOrderRequestOrderLinesInner`

NewCreateOrderRequestOrderLinesInnerWithDefaults instantiates a new CreateOrderRequestOrderLinesInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSku

`func (o *CreateOrderRequestOrderLinesInner) GetSku() string`

GetSku returns the Sku field if non-nil, zero value otherwise.

### GetSkuOk

`func (o *CreateOrderRequestOrderLinesInner) GetSkuOk() (*string, bool)`

GetSkuOk returns a tuple with the Sku field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSku

`func (o *CreateOrderRequestOrderLinesInner) SetSku(v string)`

SetSku sets Sku field to given value.

### HasSku

`func (o *CreateOrderRequestOrderLinesInner) HasSku() bool`

HasSku returns a boolean if a field has been set.

### SetSkuNil

`func (o *CreateOrderRequestOrderLinesInner) SetSkuNil(b bool)`

 SetSkuNil sets the value for Sku to be an explicit nil

### UnsetSku
`func (o *CreateOrderRequestOrderLinesInner) UnsetSku()`

UnsetSku ensures that no value is present for Sku, not even an explicit nil
### GetName

`func (o *CreateOrderRequestOrderLinesInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateOrderRequestOrderLinesInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateOrderRequestOrderLinesInner) SetName(v string)`

SetName sets Name field to given value.


### GetQuantity

`func (o *CreateOrderRequestOrderLinesInner) GetQuantity() int32`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *CreateOrderRequestOrderLinesInner) GetQuantityOk() (*int32, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *CreateOrderRequestOrderLinesInner) SetQuantity(v int32)`

SetQuantity sets Quantity field to given value.


### GetUnitPrice

`func (o *CreateOrderRequestOrderLinesInner) GetUnitPrice() float32`

GetUnitPrice returns the UnitPrice field if non-nil, zero value otherwise.

### GetUnitPriceOk

`func (o *CreateOrderRequestOrderLinesInner) GetUnitPriceOk() (*float32, bool)`

GetUnitPriceOk returns a tuple with the UnitPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPrice

`func (o *CreateOrderRequestOrderLinesInner) SetUnitPrice(v float32)`

SetUnitPrice sets UnitPrice field to given value.

### HasUnitPrice

`func (o *CreateOrderRequestOrderLinesInner) HasUnitPrice() bool`

HasUnitPrice returns a boolean if a field has been set.

### SetUnitPriceNil

`func (o *CreateOrderRequestOrderLinesInner) SetUnitPriceNil(b bool)`

 SetUnitPriceNil sets the value for UnitPrice to be an explicit nil

### UnsetUnitPrice
`func (o *CreateOrderRequestOrderLinesInner) UnsetUnitPrice()`

UnsetUnitPrice ensures that no value is present for UnitPrice, not even an explicit nil
### GetTotalPrice

`func (o *CreateOrderRequestOrderLinesInner) GetTotalPrice() float32`

GetTotalPrice returns the TotalPrice field if non-nil, zero value otherwise.

### GetTotalPriceOk

`func (o *CreateOrderRequestOrderLinesInner) GetTotalPriceOk() (*float32, bool)`

GetTotalPriceOk returns a tuple with the TotalPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPrice

`func (o *CreateOrderRequestOrderLinesInner) SetTotalPrice(v float32)`

SetTotalPrice sets TotalPrice field to given value.

### HasTotalPrice

`func (o *CreateOrderRequestOrderLinesInner) HasTotalPrice() bool`

HasTotalPrice returns a boolean if a field has been set.

### SetTotalPriceNil

`func (o *CreateOrderRequestOrderLinesInner) SetTotalPriceNil(b bool)`

 SetTotalPriceNil sets the value for TotalPrice to be an explicit nil

### UnsetTotalPrice
`func (o *CreateOrderRequestOrderLinesInner) UnsetTotalPrice()`

UnsetTotalPrice ensures that no value is present for TotalPrice, not even an explicit nil
### GetCurrency

`func (o *CreateOrderRequestOrderLinesInner) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *CreateOrderRequestOrderLinesInner) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *CreateOrderRequestOrderLinesInner) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *CreateOrderRequestOrderLinesInner) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### SetCurrencyNil

`func (o *CreateOrderRequestOrderLinesInner) SetCurrencyNil(b bool)`

 SetCurrencyNil sets the value for Currency to be an explicit nil

### UnsetCurrency
`func (o *CreateOrderRequestOrderLinesInner) UnsetCurrency()`

UnsetCurrency ensures that no value is present for Currency, not even an explicit nil
### GetWeight

`func (o *CreateOrderRequestOrderLinesInner) GetWeight() float32`

GetWeight returns the Weight field if non-nil, zero value otherwise.

### GetWeightOk

`func (o *CreateOrderRequestOrderLinesInner) GetWeightOk() (*float32, bool)`

GetWeightOk returns a tuple with the Weight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeight

`func (o *CreateOrderRequestOrderLinesInner) SetWeight(v float32)`

SetWeight sets Weight field to given value.

### HasWeight

`func (o *CreateOrderRequestOrderLinesInner) HasWeight() bool`

HasWeight returns a boolean if a field has been set.

### SetWeightNil

`func (o *CreateOrderRequestOrderLinesInner) SetWeightNil(b bool)`

 SetWeightNil sets the value for Weight to be an explicit nil

### UnsetWeight
`func (o *CreateOrderRequestOrderLinesInner) UnsetWeight()`

UnsetWeight ensures that no value is present for Weight, not even an explicit nil
### GetWeightUnit

`func (o *CreateOrderRequestOrderLinesInner) GetWeightUnit() string`

GetWeightUnit returns the WeightUnit field if non-nil, zero value otherwise.

### GetWeightUnitOk

`func (o *CreateOrderRequestOrderLinesInner) GetWeightUnitOk() (*string, bool)`

GetWeightUnitOk returns a tuple with the WeightUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeightUnit

`func (o *CreateOrderRequestOrderLinesInner) SetWeightUnit(v string)`

SetWeightUnit sets WeightUnit field to given value.

### HasWeightUnit

`func (o *CreateOrderRequestOrderLinesInner) HasWeightUnit() bool`

HasWeightUnit returns a boolean if a field has been set.

### SetWeightUnitNil

`func (o *CreateOrderRequestOrderLinesInner) SetWeightUnitNil(b bool)`

 SetWeightUnitNil sets the value for WeightUnit to be an explicit nil

### UnsetWeightUnit
`func (o *CreateOrderRequestOrderLinesInner) UnsetWeightUnit()`

UnsetWeightUnit ensures that no value is present for WeightUnit, not even an explicit nil
### GetVariantId

`func (o *CreateOrderRequestOrderLinesInner) GetVariantId() string`

GetVariantId returns the VariantId field if non-nil, zero value otherwise.

### GetVariantIdOk

`func (o *CreateOrderRequestOrderLinesInner) GetVariantIdOk() (*string, bool)`

GetVariantIdOk returns a tuple with the VariantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVariantId

`func (o *CreateOrderRequestOrderLinesInner) SetVariantId(v string)`

SetVariantId sets VariantId field to given value.

### HasVariantId

`func (o *CreateOrderRequestOrderLinesInner) HasVariantId() bool`

HasVariantId returns a boolean if a field has been set.

### SetVariantIdNil

`func (o *CreateOrderRequestOrderLinesInner) SetVariantIdNil(b bool)`

 SetVariantIdNil sets the value for VariantId to be an explicit nil

### UnsetVariantId
`func (o *CreateOrderRequestOrderLinesInner) UnsetVariantId()`

UnsetVariantId ensures that no value is present for VariantId, not even an explicit nil
### GetProductId

`func (o *CreateOrderRequestOrderLinesInner) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *CreateOrderRequestOrderLinesInner) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *CreateOrderRequestOrderLinesInner) SetProductId(v string)`

SetProductId sets ProductId field to given value.

### HasProductId

`func (o *CreateOrderRequestOrderLinesInner) HasProductId() bool`

HasProductId returns a boolean if a field has been set.

### SetProductIdNil

`func (o *CreateOrderRequestOrderLinesInner) SetProductIdNil(b bool)`

 SetProductIdNil sets the value for ProductId to be an explicit nil

### UnsetProductId
`func (o *CreateOrderRequestOrderLinesInner) UnsetProductId()`

UnsetProductId ensures that no value is present for ProductId, not even an explicit nil
### GetImageUrl

`func (o *CreateOrderRequestOrderLinesInner) GetImageUrl() string`

GetImageUrl returns the ImageUrl field if non-nil, zero value otherwise.

### GetImageUrlOk

`func (o *CreateOrderRequestOrderLinesInner) GetImageUrlOk() (*string, bool)`

GetImageUrlOk returns a tuple with the ImageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageUrl

`func (o *CreateOrderRequestOrderLinesInner) SetImageUrl(v string)`

SetImageUrl sets ImageUrl field to given value.

### HasImageUrl

`func (o *CreateOrderRequestOrderLinesInner) HasImageUrl() bool`

HasImageUrl returns a boolean if a field has been set.

### SetImageUrlNil

`func (o *CreateOrderRequestOrderLinesInner) SetImageUrlNil(b bool)`

 SetImageUrlNil sets the value for ImageUrl to be an explicit nil

### UnsetImageUrl
`func (o *CreateOrderRequestOrderLinesInner) UnsetImageUrl()`

UnsetImageUrl ensures that no value is present for ImageUrl, not even an explicit nil
### GetHsCode

`func (o *CreateOrderRequestOrderLinesInner) GetHsCode() string`

GetHsCode returns the HsCode field if non-nil, zero value otherwise.

### GetHsCodeOk

`func (o *CreateOrderRequestOrderLinesInner) GetHsCodeOk() (*string, bool)`

GetHsCodeOk returns a tuple with the HsCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHsCode

`func (o *CreateOrderRequestOrderLinesInner) SetHsCode(v string)`

SetHsCode sets HsCode field to given value.

### HasHsCode

`func (o *CreateOrderRequestOrderLinesInner) HasHsCode() bool`

HasHsCode returns a boolean if a field has been set.

### SetHsCodeNil

`func (o *CreateOrderRequestOrderLinesInner) SetHsCodeNil(b bool)`

 SetHsCodeNil sets the value for HsCode to be an explicit nil

### UnsetHsCode
`func (o *CreateOrderRequestOrderLinesInner) UnsetHsCode()`

UnsetHsCode ensures that no value is present for HsCode, not even an explicit nil
### GetCountryOfOrigin

`func (o *CreateOrderRequestOrderLinesInner) GetCountryOfOrigin() string`

GetCountryOfOrigin returns the CountryOfOrigin field if non-nil, zero value otherwise.

### GetCountryOfOriginOk

`func (o *CreateOrderRequestOrderLinesInner) GetCountryOfOriginOk() (*string, bool)`

GetCountryOfOriginOk returns a tuple with the CountryOfOrigin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryOfOrigin

`func (o *CreateOrderRequestOrderLinesInner) SetCountryOfOrigin(v string)`

SetCountryOfOrigin sets CountryOfOrigin field to given value.

### HasCountryOfOrigin

`func (o *CreateOrderRequestOrderLinesInner) HasCountryOfOrigin() bool`

HasCountryOfOrigin returns a boolean if a field has been set.

### SetCountryOfOriginNil

`func (o *CreateOrderRequestOrderLinesInner) SetCountryOfOriginNil(b bool)`

 SetCountryOfOriginNil sets the value for CountryOfOrigin to be an explicit nil

### UnsetCountryOfOrigin
`func (o *CreateOrderRequestOrderLinesInner) UnsetCountryOfOrigin()`

UnsetCountryOfOrigin ensures that no value is present for CountryOfOrigin, not even an explicit nil
### GetProvinceOfOrigin

`func (o *CreateOrderRequestOrderLinesInner) GetProvinceOfOrigin() string`

GetProvinceOfOrigin returns the ProvinceOfOrigin field if non-nil, zero value otherwise.

### GetProvinceOfOriginOk

`func (o *CreateOrderRequestOrderLinesInner) GetProvinceOfOriginOk() (*string, bool)`

GetProvinceOfOriginOk returns a tuple with the ProvinceOfOrigin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvinceOfOrigin

`func (o *CreateOrderRequestOrderLinesInner) SetProvinceOfOrigin(v string)`

SetProvinceOfOrigin sets ProvinceOfOrigin field to given value.

### HasProvinceOfOrigin

`func (o *CreateOrderRequestOrderLinesInner) HasProvinceOfOrigin() bool`

HasProvinceOfOrigin returns a boolean if a field has been set.

### SetProvinceOfOriginNil

`func (o *CreateOrderRequestOrderLinesInner) SetProvinceOfOriginNil(b bool)`

 SetProvinceOfOriginNil sets the value for ProvinceOfOrigin to be an explicit nil

### UnsetProvinceOfOrigin
`func (o *CreateOrderRequestOrderLinesInner) UnsetProvinceOfOrigin()`

UnsetProvinceOfOrigin ensures that no value is present for ProvinceOfOrigin, not even an explicit nil
### GetBarcode

`func (o *CreateOrderRequestOrderLinesInner) GetBarcode() string`

GetBarcode returns the Barcode field if non-nil, zero value otherwise.

### GetBarcodeOk

`func (o *CreateOrderRequestOrderLinesInner) GetBarcodeOk() (*string, bool)`

GetBarcodeOk returns a tuple with the Barcode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBarcode

`func (o *CreateOrderRequestOrderLinesInner) SetBarcode(v string)`

SetBarcode sets Barcode field to given value.

### HasBarcode

`func (o *CreateOrderRequestOrderLinesInner) HasBarcode() bool`

HasBarcode returns a boolean if a field has been set.

### SetBarcodeNil

`func (o *CreateOrderRequestOrderLinesInner) SetBarcodeNil(b bool)`

 SetBarcodeNil sets the value for Barcode to be an explicit nil

### UnsetBarcode
`func (o *CreateOrderRequestOrderLinesInner) UnsetBarcode()`

UnsetBarcode ensures that no value is present for Barcode, not even an explicit nil
### GetRequiresShipping

`func (o *CreateOrderRequestOrderLinesInner) GetRequiresShipping() bool`

GetRequiresShipping returns the RequiresShipping field if non-nil, zero value otherwise.

### GetRequiresShippingOk

`func (o *CreateOrderRequestOrderLinesInner) GetRequiresShippingOk() (*bool, bool)`

GetRequiresShippingOk returns a tuple with the RequiresShipping field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequiresShipping

`func (o *CreateOrderRequestOrderLinesInner) SetRequiresShipping(v bool)`

SetRequiresShipping sets RequiresShipping field to given value.

### HasRequiresShipping

`func (o *CreateOrderRequestOrderLinesInner) HasRequiresShipping() bool`

HasRequiresShipping returns a boolean if a field has been set.

### SetRequiresShippingNil

`func (o *CreateOrderRequestOrderLinesInner) SetRequiresShippingNil(b bool)`

 SetRequiresShippingNil sets the value for RequiresShipping to be an explicit nil

### UnsetRequiresShipping
`func (o *CreateOrderRequestOrderLinesInner) UnsetRequiresShipping()`

UnsetRequiresShipping ensures that no value is present for RequiresShipping, not even an explicit nil
### GetTaxable

`func (o *CreateOrderRequestOrderLinesInner) GetTaxable() bool`

GetTaxable returns the Taxable field if non-nil, zero value otherwise.

### GetTaxableOk

`func (o *CreateOrderRequestOrderLinesInner) GetTaxableOk() (*bool, bool)`

GetTaxableOk returns a tuple with the Taxable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxable

`func (o *CreateOrderRequestOrderLinesInner) SetTaxable(v bool)`

SetTaxable sets Taxable field to given value.

### HasTaxable

`func (o *CreateOrderRequestOrderLinesInner) HasTaxable() bool`

HasTaxable returns a boolean if a field has been set.

### SetTaxableNil

`func (o *CreateOrderRequestOrderLinesInner) SetTaxableNil(b bool)`

 SetTaxableNil sets the value for Taxable to be an explicit nil

### UnsetTaxable
`func (o *CreateOrderRequestOrderLinesInner) UnsetTaxable()`

UnsetTaxable ensures that no value is present for Taxable, not even an explicit nil
### GetGiftCard

`func (o *CreateOrderRequestOrderLinesInner) GetGiftCard() bool`

GetGiftCard returns the GiftCard field if non-nil, zero value otherwise.

### GetGiftCardOk

`func (o *CreateOrderRequestOrderLinesInner) GetGiftCardOk() (*bool, bool)`

GetGiftCardOk returns a tuple with the GiftCard field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGiftCard

`func (o *CreateOrderRequestOrderLinesInner) SetGiftCard(v bool)`

SetGiftCard sets GiftCard field to given value.

### HasGiftCard

`func (o *CreateOrderRequestOrderLinesInner) HasGiftCard() bool`

HasGiftCard returns a boolean if a field has been set.

### SetGiftCardNil

`func (o *CreateOrderRequestOrderLinesInner) SetGiftCardNil(b bool)`

 SetGiftCardNil sets the value for GiftCard to be an explicit nil

### UnsetGiftCard
`func (o *CreateOrderRequestOrderLinesInner) UnsetGiftCard()`

UnsetGiftCard ensures that no value is present for GiftCard, not even an explicit nil
### GetVendor

`func (o *CreateOrderRequestOrderLinesInner) GetVendor() string`

GetVendor returns the Vendor field if non-nil, zero value otherwise.

### GetVendorOk

`func (o *CreateOrderRequestOrderLinesInner) GetVendorOk() (*string, bool)`

GetVendorOk returns a tuple with the Vendor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVendor

`func (o *CreateOrderRequestOrderLinesInner) SetVendor(v string)`

SetVendor sets Vendor field to given value.

### HasVendor

`func (o *CreateOrderRequestOrderLinesInner) HasVendor() bool`

HasVendor returns a boolean if a field has been set.

### SetVendorNil

`func (o *CreateOrderRequestOrderLinesInner) SetVendorNil(b bool)`

 SetVendorNil sets the value for Vendor to be an explicit nil

### UnsetVendor
`func (o *CreateOrderRequestOrderLinesInner) UnsetVendor()`

UnsetVendor ensures that no value is present for Vendor, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


