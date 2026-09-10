# GetOrder200ResponseOrderLinesInner

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
**PackedQuantity** | **int32** | Quantity already allocated to outbound shipments. | 

## Methods

### NewGetOrder200ResponseOrderLinesInner

`func NewGetOrder200ResponseOrderLinesInner(name string, quantity int32, packedQuantity int32, ) *GetOrder200ResponseOrderLinesInner`

NewGetOrder200ResponseOrderLinesInner instantiates a new GetOrder200ResponseOrderLinesInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetOrder200ResponseOrderLinesInnerWithDefaults

`func NewGetOrder200ResponseOrderLinesInnerWithDefaults() *GetOrder200ResponseOrderLinesInner`

NewGetOrder200ResponseOrderLinesInnerWithDefaults instantiates a new GetOrder200ResponseOrderLinesInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSku

`func (o *GetOrder200ResponseOrderLinesInner) GetSku() string`

GetSku returns the Sku field if non-nil, zero value otherwise.

### GetSkuOk

`func (o *GetOrder200ResponseOrderLinesInner) GetSkuOk() (*string, bool)`

GetSkuOk returns a tuple with the Sku field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSku

`func (o *GetOrder200ResponseOrderLinesInner) SetSku(v string)`

SetSku sets Sku field to given value.

### HasSku

`func (o *GetOrder200ResponseOrderLinesInner) HasSku() bool`

HasSku returns a boolean if a field has been set.

### SetSkuNil

`func (o *GetOrder200ResponseOrderLinesInner) SetSkuNil(b bool)`

 SetSkuNil sets the value for Sku to be an explicit nil

### UnsetSku
`func (o *GetOrder200ResponseOrderLinesInner) UnsetSku()`

UnsetSku ensures that no value is present for Sku, not even an explicit nil
### GetName

`func (o *GetOrder200ResponseOrderLinesInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *GetOrder200ResponseOrderLinesInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *GetOrder200ResponseOrderLinesInner) SetName(v string)`

SetName sets Name field to given value.


### GetQuantity

`func (o *GetOrder200ResponseOrderLinesInner) GetQuantity() int32`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *GetOrder200ResponseOrderLinesInner) GetQuantityOk() (*int32, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *GetOrder200ResponseOrderLinesInner) SetQuantity(v int32)`

SetQuantity sets Quantity field to given value.


### GetUnitPrice

`func (o *GetOrder200ResponseOrderLinesInner) GetUnitPrice() float32`

GetUnitPrice returns the UnitPrice field if non-nil, zero value otherwise.

### GetUnitPriceOk

`func (o *GetOrder200ResponseOrderLinesInner) GetUnitPriceOk() (*float32, bool)`

GetUnitPriceOk returns a tuple with the UnitPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPrice

`func (o *GetOrder200ResponseOrderLinesInner) SetUnitPrice(v float32)`

SetUnitPrice sets UnitPrice field to given value.

### HasUnitPrice

`func (o *GetOrder200ResponseOrderLinesInner) HasUnitPrice() bool`

HasUnitPrice returns a boolean if a field has been set.

### SetUnitPriceNil

`func (o *GetOrder200ResponseOrderLinesInner) SetUnitPriceNil(b bool)`

 SetUnitPriceNil sets the value for UnitPrice to be an explicit nil

### UnsetUnitPrice
`func (o *GetOrder200ResponseOrderLinesInner) UnsetUnitPrice()`

UnsetUnitPrice ensures that no value is present for UnitPrice, not even an explicit nil
### GetTotalPrice

`func (o *GetOrder200ResponseOrderLinesInner) GetTotalPrice() float32`

GetTotalPrice returns the TotalPrice field if non-nil, zero value otherwise.

### GetTotalPriceOk

`func (o *GetOrder200ResponseOrderLinesInner) GetTotalPriceOk() (*float32, bool)`

GetTotalPriceOk returns a tuple with the TotalPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPrice

`func (o *GetOrder200ResponseOrderLinesInner) SetTotalPrice(v float32)`

SetTotalPrice sets TotalPrice field to given value.

### HasTotalPrice

`func (o *GetOrder200ResponseOrderLinesInner) HasTotalPrice() bool`

HasTotalPrice returns a boolean if a field has been set.

### SetTotalPriceNil

`func (o *GetOrder200ResponseOrderLinesInner) SetTotalPriceNil(b bool)`

 SetTotalPriceNil sets the value for TotalPrice to be an explicit nil

### UnsetTotalPrice
`func (o *GetOrder200ResponseOrderLinesInner) UnsetTotalPrice()`

UnsetTotalPrice ensures that no value is present for TotalPrice, not even an explicit nil
### GetCurrency

`func (o *GetOrder200ResponseOrderLinesInner) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *GetOrder200ResponseOrderLinesInner) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *GetOrder200ResponseOrderLinesInner) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *GetOrder200ResponseOrderLinesInner) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### SetCurrencyNil

`func (o *GetOrder200ResponseOrderLinesInner) SetCurrencyNil(b bool)`

 SetCurrencyNil sets the value for Currency to be an explicit nil

### UnsetCurrency
`func (o *GetOrder200ResponseOrderLinesInner) UnsetCurrency()`

UnsetCurrency ensures that no value is present for Currency, not even an explicit nil
### GetWeight

`func (o *GetOrder200ResponseOrderLinesInner) GetWeight() float32`

GetWeight returns the Weight field if non-nil, zero value otherwise.

### GetWeightOk

`func (o *GetOrder200ResponseOrderLinesInner) GetWeightOk() (*float32, bool)`

GetWeightOk returns a tuple with the Weight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeight

`func (o *GetOrder200ResponseOrderLinesInner) SetWeight(v float32)`

SetWeight sets Weight field to given value.

### HasWeight

`func (o *GetOrder200ResponseOrderLinesInner) HasWeight() bool`

HasWeight returns a boolean if a field has been set.

### SetWeightNil

`func (o *GetOrder200ResponseOrderLinesInner) SetWeightNil(b bool)`

 SetWeightNil sets the value for Weight to be an explicit nil

### UnsetWeight
`func (o *GetOrder200ResponseOrderLinesInner) UnsetWeight()`

UnsetWeight ensures that no value is present for Weight, not even an explicit nil
### GetWeightUnit

`func (o *GetOrder200ResponseOrderLinesInner) GetWeightUnit() string`

GetWeightUnit returns the WeightUnit field if non-nil, zero value otherwise.

### GetWeightUnitOk

`func (o *GetOrder200ResponseOrderLinesInner) GetWeightUnitOk() (*string, bool)`

GetWeightUnitOk returns a tuple with the WeightUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeightUnit

`func (o *GetOrder200ResponseOrderLinesInner) SetWeightUnit(v string)`

SetWeightUnit sets WeightUnit field to given value.

### HasWeightUnit

`func (o *GetOrder200ResponseOrderLinesInner) HasWeightUnit() bool`

HasWeightUnit returns a boolean if a field has been set.

### SetWeightUnitNil

`func (o *GetOrder200ResponseOrderLinesInner) SetWeightUnitNil(b bool)`

 SetWeightUnitNil sets the value for WeightUnit to be an explicit nil

### UnsetWeightUnit
`func (o *GetOrder200ResponseOrderLinesInner) UnsetWeightUnit()`

UnsetWeightUnit ensures that no value is present for WeightUnit, not even an explicit nil
### GetVariantId

`func (o *GetOrder200ResponseOrderLinesInner) GetVariantId() string`

GetVariantId returns the VariantId field if non-nil, zero value otherwise.

### GetVariantIdOk

`func (o *GetOrder200ResponseOrderLinesInner) GetVariantIdOk() (*string, bool)`

GetVariantIdOk returns a tuple with the VariantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVariantId

`func (o *GetOrder200ResponseOrderLinesInner) SetVariantId(v string)`

SetVariantId sets VariantId field to given value.

### HasVariantId

`func (o *GetOrder200ResponseOrderLinesInner) HasVariantId() bool`

HasVariantId returns a boolean if a field has been set.

### SetVariantIdNil

`func (o *GetOrder200ResponseOrderLinesInner) SetVariantIdNil(b bool)`

 SetVariantIdNil sets the value for VariantId to be an explicit nil

### UnsetVariantId
`func (o *GetOrder200ResponseOrderLinesInner) UnsetVariantId()`

UnsetVariantId ensures that no value is present for VariantId, not even an explicit nil
### GetProductId

`func (o *GetOrder200ResponseOrderLinesInner) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *GetOrder200ResponseOrderLinesInner) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *GetOrder200ResponseOrderLinesInner) SetProductId(v string)`

SetProductId sets ProductId field to given value.

### HasProductId

`func (o *GetOrder200ResponseOrderLinesInner) HasProductId() bool`

HasProductId returns a boolean if a field has been set.

### SetProductIdNil

`func (o *GetOrder200ResponseOrderLinesInner) SetProductIdNil(b bool)`

 SetProductIdNil sets the value for ProductId to be an explicit nil

### UnsetProductId
`func (o *GetOrder200ResponseOrderLinesInner) UnsetProductId()`

UnsetProductId ensures that no value is present for ProductId, not even an explicit nil
### GetImageUrl

`func (o *GetOrder200ResponseOrderLinesInner) GetImageUrl() string`

GetImageUrl returns the ImageUrl field if non-nil, zero value otherwise.

### GetImageUrlOk

`func (o *GetOrder200ResponseOrderLinesInner) GetImageUrlOk() (*string, bool)`

GetImageUrlOk returns a tuple with the ImageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageUrl

`func (o *GetOrder200ResponseOrderLinesInner) SetImageUrl(v string)`

SetImageUrl sets ImageUrl field to given value.

### HasImageUrl

`func (o *GetOrder200ResponseOrderLinesInner) HasImageUrl() bool`

HasImageUrl returns a boolean if a field has been set.

### SetImageUrlNil

`func (o *GetOrder200ResponseOrderLinesInner) SetImageUrlNil(b bool)`

 SetImageUrlNil sets the value for ImageUrl to be an explicit nil

### UnsetImageUrl
`func (o *GetOrder200ResponseOrderLinesInner) UnsetImageUrl()`

UnsetImageUrl ensures that no value is present for ImageUrl, not even an explicit nil
### GetHsCode

`func (o *GetOrder200ResponseOrderLinesInner) GetHsCode() string`

GetHsCode returns the HsCode field if non-nil, zero value otherwise.

### GetHsCodeOk

`func (o *GetOrder200ResponseOrderLinesInner) GetHsCodeOk() (*string, bool)`

GetHsCodeOk returns a tuple with the HsCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHsCode

`func (o *GetOrder200ResponseOrderLinesInner) SetHsCode(v string)`

SetHsCode sets HsCode field to given value.

### HasHsCode

`func (o *GetOrder200ResponseOrderLinesInner) HasHsCode() bool`

HasHsCode returns a boolean if a field has been set.

### SetHsCodeNil

`func (o *GetOrder200ResponseOrderLinesInner) SetHsCodeNil(b bool)`

 SetHsCodeNil sets the value for HsCode to be an explicit nil

### UnsetHsCode
`func (o *GetOrder200ResponseOrderLinesInner) UnsetHsCode()`

UnsetHsCode ensures that no value is present for HsCode, not even an explicit nil
### GetCountryOfOrigin

`func (o *GetOrder200ResponseOrderLinesInner) GetCountryOfOrigin() string`

GetCountryOfOrigin returns the CountryOfOrigin field if non-nil, zero value otherwise.

### GetCountryOfOriginOk

`func (o *GetOrder200ResponseOrderLinesInner) GetCountryOfOriginOk() (*string, bool)`

GetCountryOfOriginOk returns a tuple with the CountryOfOrigin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryOfOrigin

`func (o *GetOrder200ResponseOrderLinesInner) SetCountryOfOrigin(v string)`

SetCountryOfOrigin sets CountryOfOrigin field to given value.

### HasCountryOfOrigin

`func (o *GetOrder200ResponseOrderLinesInner) HasCountryOfOrigin() bool`

HasCountryOfOrigin returns a boolean if a field has been set.

### SetCountryOfOriginNil

`func (o *GetOrder200ResponseOrderLinesInner) SetCountryOfOriginNil(b bool)`

 SetCountryOfOriginNil sets the value for CountryOfOrigin to be an explicit nil

### UnsetCountryOfOrigin
`func (o *GetOrder200ResponseOrderLinesInner) UnsetCountryOfOrigin()`

UnsetCountryOfOrigin ensures that no value is present for CountryOfOrigin, not even an explicit nil
### GetProvinceOfOrigin

`func (o *GetOrder200ResponseOrderLinesInner) GetProvinceOfOrigin() string`

GetProvinceOfOrigin returns the ProvinceOfOrigin field if non-nil, zero value otherwise.

### GetProvinceOfOriginOk

`func (o *GetOrder200ResponseOrderLinesInner) GetProvinceOfOriginOk() (*string, bool)`

GetProvinceOfOriginOk returns a tuple with the ProvinceOfOrigin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvinceOfOrigin

`func (o *GetOrder200ResponseOrderLinesInner) SetProvinceOfOrigin(v string)`

SetProvinceOfOrigin sets ProvinceOfOrigin field to given value.

### HasProvinceOfOrigin

`func (o *GetOrder200ResponseOrderLinesInner) HasProvinceOfOrigin() bool`

HasProvinceOfOrigin returns a boolean if a field has been set.

### SetProvinceOfOriginNil

`func (o *GetOrder200ResponseOrderLinesInner) SetProvinceOfOriginNil(b bool)`

 SetProvinceOfOriginNil sets the value for ProvinceOfOrigin to be an explicit nil

### UnsetProvinceOfOrigin
`func (o *GetOrder200ResponseOrderLinesInner) UnsetProvinceOfOrigin()`

UnsetProvinceOfOrigin ensures that no value is present for ProvinceOfOrigin, not even an explicit nil
### GetBarcode

`func (o *GetOrder200ResponseOrderLinesInner) GetBarcode() string`

GetBarcode returns the Barcode field if non-nil, zero value otherwise.

### GetBarcodeOk

`func (o *GetOrder200ResponseOrderLinesInner) GetBarcodeOk() (*string, bool)`

GetBarcodeOk returns a tuple with the Barcode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBarcode

`func (o *GetOrder200ResponseOrderLinesInner) SetBarcode(v string)`

SetBarcode sets Barcode field to given value.

### HasBarcode

`func (o *GetOrder200ResponseOrderLinesInner) HasBarcode() bool`

HasBarcode returns a boolean if a field has been set.

### SetBarcodeNil

`func (o *GetOrder200ResponseOrderLinesInner) SetBarcodeNil(b bool)`

 SetBarcodeNil sets the value for Barcode to be an explicit nil

### UnsetBarcode
`func (o *GetOrder200ResponseOrderLinesInner) UnsetBarcode()`

UnsetBarcode ensures that no value is present for Barcode, not even an explicit nil
### GetRequiresShipping

`func (o *GetOrder200ResponseOrderLinesInner) GetRequiresShipping() bool`

GetRequiresShipping returns the RequiresShipping field if non-nil, zero value otherwise.

### GetRequiresShippingOk

`func (o *GetOrder200ResponseOrderLinesInner) GetRequiresShippingOk() (*bool, bool)`

GetRequiresShippingOk returns a tuple with the RequiresShipping field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequiresShipping

`func (o *GetOrder200ResponseOrderLinesInner) SetRequiresShipping(v bool)`

SetRequiresShipping sets RequiresShipping field to given value.

### HasRequiresShipping

`func (o *GetOrder200ResponseOrderLinesInner) HasRequiresShipping() bool`

HasRequiresShipping returns a boolean if a field has been set.

### SetRequiresShippingNil

`func (o *GetOrder200ResponseOrderLinesInner) SetRequiresShippingNil(b bool)`

 SetRequiresShippingNil sets the value for RequiresShipping to be an explicit nil

### UnsetRequiresShipping
`func (o *GetOrder200ResponseOrderLinesInner) UnsetRequiresShipping()`

UnsetRequiresShipping ensures that no value is present for RequiresShipping, not even an explicit nil
### GetTaxable

`func (o *GetOrder200ResponseOrderLinesInner) GetTaxable() bool`

GetTaxable returns the Taxable field if non-nil, zero value otherwise.

### GetTaxableOk

`func (o *GetOrder200ResponseOrderLinesInner) GetTaxableOk() (*bool, bool)`

GetTaxableOk returns a tuple with the Taxable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxable

`func (o *GetOrder200ResponseOrderLinesInner) SetTaxable(v bool)`

SetTaxable sets Taxable field to given value.

### HasTaxable

`func (o *GetOrder200ResponseOrderLinesInner) HasTaxable() bool`

HasTaxable returns a boolean if a field has been set.

### SetTaxableNil

`func (o *GetOrder200ResponseOrderLinesInner) SetTaxableNil(b bool)`

 SetTaxableNil sets the value for Taxable to be an explicit nil

### UnsetTaxable
`func (o *GetOrder200ResponseOrderLinesInner) UnsetTaxable()`

UnsetTaxable ensures that no value is present for Taxable, not even an explicit nil
### GetGiftCard

`func (o *GetOrder200ResponseOrderLinesInner) GetGiftCard() bool`

GetGiftCard returns the GiftCard field if non-nil, zero value otherwise.

### GetGiftCardOk

`func (o *GetOrder200ResponseOrderLinesInner) GetGiftCardOk() (*bool, bool)`

GetGiftCardOk returns a tuple with the GiftCard field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGiftCard

`func (o *GetOrder200ResponseOrderLinesInner) SetGiftCard(v bool)`

SetGiftCard sets GiftCard field to given value.

### HasGiftCard

`func (o *GetOrder200ResponseOrderLinesInner) HasGiftCard() bool`

HasGiftCard returns a boolean if a field has been set.

### SetGiftCardNil

`func (o *GetOrder200ResponseOrderLinesInner) SetGiftCardNil(b bool)`

 SetGiftCardNil sets the value for GiftCard to be an explicit nil

### UnsetGiftCard
`func (o *GetOrder200ResponseOrderLinesInner) UnsetGiftCard()`

UnsetGiftCard ensures that no value is present for GiftCard, not even an explicit nil
### GetVendor

`func (o *GetOrder200ResponseOrderLinesInner) GetVendor() string`

GetVendor returns the Vendor field if non-nil, zero value otherwise.

### GetVendorOk

`func (o *GetOrder200ResponseOrderLinesInner) GetVendorOk() (*string, bool)`

GetVendorOk returns a tuple with the Vendor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVendor

`func (o *GetOrder200ResponseOrderLinesInner) SetVendor(v string)`

SetVendor sets Vendor field to given value.

### HasVendor

`func (o *GetOrder200ResponseOrderLinesInner) HasVendor() bool`

HasVendor returns a boolean if a field has been set.

### SetVendorNil

`func (o *GetOrder200ResponseOrderLinesInner) SetVendorNil(b bool)`

 SetVendorNil sets the value for Vendor to be an explicit nil

### UnsetVendor
`func (o *GetOrder200ResponseOrderLinesInner) UnsetVendor()`

UnsetVendor ensures that no value is present for Vendor, not even an explicit nil
### GetPackedQuantity

`func (o *GetOrder200ResponseOrderLinesInner) GetPackedQuantity() int32`

GetPackedQuantity returns the PackedQuantity field if non-nil, zero value otherwise.

### GetPackedQuantityOk

`func (o *GetOrder200ResponseOrderLinesInner) GetPackedQuantityOk() (*int32, bool)`

GetPackedQuantityOk returns a tuple with the PackedQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackedQuantity

`func (o *GetOrder200ResponseOrderLinesInner) SetPackedQuantity(v int32)`

SetPackedQuantity sets PackedQuantity field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


