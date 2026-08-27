# CreateShipment201ResponseParcelsInnerOrderLinesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Unique order line identifier. | [optional] 
**Sku** | Pointer to **NullableString** | Stock keeping unit of the product. Optional — not every webshop assigns SKUs. | [optional] 
**Quantity** | **int32** | Number of units in this order line. | 
**Description** | Pointer to **NullableString** | Human-readable product description. | [optional] 
**UnitPrice** | Pointer to **NullableFloat32** | Price per unit in the order line currency. | [optional] 
**Currency** | Pointer to **NullableString** | ISO 4217 currency code. | [optional] 
**VatPercent** | Pointer to **NullableFloat32** | VAT percentage applied to the unit price. | [optional] 
**Location** | Pointer to **NullableString** | Warehouse picking location. | [optional] 
**CountryOfOrigin** | Pointer to **string** | ISO 3166-1 alpha-2 country of origin. | [optional] 
**TarrifNumber** | Pointer to **NullableString** | Customs tariff (HS) code. | [optional] 

## Methods

### NewCreateShipment201ResponseParcelsInnerOrderLinesInner

`func NewCreateShipment201ResponseParcelsInnerOrderLinesInner(quantity int32, ) *CreateShipment201ResponseParcelsInnerOrderLinesInner`

NewCreateShipment201ResponseParcelsInnerOrderLinesInner instantiates a new CreateShipment201ResponseParcelsInnerOrderLinesInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateShipment201ResponseParcelsInnerOrderLinesInnerWithDefaults

`func NewCreateShipment201ResponseParcelsInnerOrderLinesInnerWithDefaults() *CreateShipment201ResponseParcelsInnerOrderLinesInner`

NewCreateShipment201ResponseParcelsInnerOrderLinesInnerWithDefaults instantiates a new CreateShipment201ResponseParcelsInnerOrderLinesInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetSku

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) GetSku() string`

GetSku returns the Sku field if non-nil, zero value otherwise.

### GetSkuOk

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) GetSkuOk() (*string, bool)`

GetSkuOk returns a tuple with the Sku field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSku

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) SetSku(v string)`

SetSku sets Sku field to given value.

### HasSku

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) HasSku() bool`

HasSku returns a boolean if a field has been set.

### SetSkuNil

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) SetSkuNil(b bool)`

 SetSkuNil sets the value for Sku to be an explicit nil

### UnsetSku
`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) UnsetSku()`

UnsetSku ensures that no value is present for Sku, not even an explicit nil
### GetQuantity

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) GetQuantity() int32`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) GetQuantityOk() (*int32, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) SetQuantity(v int32)`

SetQuantity sets Quantity field to given value.


### GetDescription

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetUnitPrice

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) GetUnitPrice() float32`

GetUnitPrice returns the UnitPrice field if non-nil, zero value otherwise.

### GetUnitPriceOk

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) GetUnitPriceOk() (*float32, bool)`

GetUnitPriceOk returns a tuple with the UnitPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPrice

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) SetUnitPrice(v float32)`

SetUnitPrice sets UnitPrice field to given value.

### HasUnitPrice

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) HasUnitPrice() bool`

HasUnitPrice returns a boolean if a field has been set.

### SetUnitPriceNil

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) SetUnitPriceNil(b bool)`

 SetUnitPriceNil sets the value for UnitPrice to be an explicit nil

### UnsetUnitPrice
`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) UnsetUnitPrice()`

UnsetUnitPrice ensures that no value is present for UnitPrice, not even an explicit nil
### GetCurrency

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### SetCurrencyNil

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) SetCurrencyNil(b bool)`

 SetCurrencyNil sets the value for Currency to be an explicit nil

### UnsetCurrency
`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) UnsetCurrency()`

UnsetCurrency ensures that no value is present for Currency, not even an explicit nil
### GetVatPercent

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) GetVatPercent() float32`

GetVatPercent returns the VatPercent field if non-nil, zero value otherwise.

### GetVatPercentOk

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) GetVatPercentOk() (*float32, bool)`

GetVatPercentOk returns a tuple with the VatPercent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVatPercent

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) SetVatPercent(v float32)`

SetVatPercent sets VatPercent field to given value.

### HasVatPercent

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) HasVatPercent() bool`

HasVatPercent returns a boolean if a field has been set.

### SetVatPercentNil

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) SetVatPercentNil(b bool)`

 SetVatPercentNil sets the value for VatPercent to be an explicit nil

### UnsetVatPercent
`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) UnsetVatPercent()`

UnsetVatPercent ensures that no value is present for VatPercent, not even an explicit nil
### GetLocation

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) GetLocation() string`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) GetLocationOk() (*string, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) SetLocation(v string)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### SetLocationNil

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) SetLocationNil(b bool)`

 SetLocationNil sets the value for Location to be an explicit nil

### UnsetLocation
`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) UnsetLocation()`

UnsetLocation ensures that no value is present for Location, not even an explicit nil
### GetCountryOfOrigin

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) GetCountryOfOrigin() string`

GetCountryOfOrigin returns the CountryOfOrigin field if non-nil, zero value otherwise.

### GetCountryOfOriginOk

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) GetCountryOfOriginOk() (*string, bool)`

GetCountryOfOriginOk returns a tuple with the CountryOfOrigin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryOfOrigin

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) SetCountryOfOrigin(v string)`

SetCountryOfOrigin sets CountryOfOrigin field to given value.

### HasCountryOfOrigin

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) HasCountryOfOrigin() bool`

HasCountryOfOrigin returns a boolean if a field has been set.

### GetTarrifNumber

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) GetTarrifNumber() string`

GetTarrifNumber returns the TarrifNumber field if non-nil, zero value otherwise.

### GetTarrifNumberOk

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) GetTarrifNumberOk() (*string, bool)`

GetTarrifNumberOk returns a tuple with the TarrifNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTarrifNumber

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) SetTarrifNumber(v string)`

SetTarrifNumber sets TarrifNumber field to given value.

### HasTarrifNumber

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) HasTarrifNumber() bool`

HasTarrifNumber returns a boolean if a field has been set.

### SetTarrifNumberNil

`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) SetTarrifNumberNil(b bool)`

 SetTarrifNumberNil sets the value for TarrifNumber to be an explicit nil

### UnsetTarrifNumber
`func (o *CreateShipment201ResponseParcelsInnerOrderLinesInner) UnsetTarrifNumber()`

UnsetTarrifNumber ensures that no value is present for TarrifNumber, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


