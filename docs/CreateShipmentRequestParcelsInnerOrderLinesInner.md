# CreateShipmentRequestParcelsInnerOrderLinesInner

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

### NewCreateShipmentRequestParcelsInnerOrderLinesInner

`func NewCreateShipmentRequestParcelsInnerOrderLinesInner(quantity int32, ) *CreateShipmentRequestParcelsInnerOrderLinesInner`

NewCreateShipmentRequestParcelsInnerOrderLinesInner instantiates a new CreateShipmentRequestParcelsInnerOrderLinesInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateShipmentRequestParcelsInnerOrderLinesInnerWithDefaults

`func NewCreateShipmentRequestParcelsInnerOrderLinesInnerWithDefaults() *CreateShipmentRequestParcelsInnerOrderLinesInner`

NewCreateShipmentRequestParcelsInnerOrderLinesInnerWithDefaults instantiates a new CreateShipmentRequestParcelsInnerOrderLinesInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetSku

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) GetSku() string`

GetSku returns the Sku field if non-nil, zero value otherwise.

### GetSkuOk

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) GetSkuOk() (*string, bool)`

GetSkuOk returns a tuple with the Sku field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSku

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) SetSku(v string)`

SetSku sets Sku field to given value.

### HasSku

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) HasSku() bool`

HasSku returns a boolean if a field has been set.

### SetSkuNil

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) SetSkuNil(b bool)`

 SetSkuNil sets the value for Sku to be an explicit nil

### UnsetSku
`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) UnsetSku()`

UnsetSku ensures that no value is present for Sku, not even an explicit nil
### GetQuantity

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) GetQuantity() int32`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) GetQuantityOk() (*int32, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) SetQuantity(v int32)`

SetQuantity sets Quantity field to given value.


### GetDescription

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetUnitPrice

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) GetUnitPrice() float32`

GetUnitPrice returns the UnitPrice field if non-nil, zero value otherwise.

### GetUnitPriceOk

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) GetUnitPriceOk() (*float32, bool)`

GetUnitPriceOk returns a tuple with the UnitPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPrice

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) SetUnitPrice(v float32)`

SetUnitPrice sets UnitPrice field to given value.

### HasUnitPrice

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) HasUnitPrice() bool`

HasUnitPrice returns a boolean if a field has been set.

### SetUnitPriceNil

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) SetUnitPriceNil(b bool)`

 SetUnitPriceNil sets the value for UnitPrice to be an explicit nil

### UnsetUnitPrice
`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) UnsetUnitPrice()`

UnsetUnitPrice ensures that no value is present for UnitPrice, not even an explicit nil
### GetCurrency

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### SetCurrencyNil

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) SetCurrencyNil(b bool)`

 SetCurrencyNil sets the value for Currency to be an explicit nil

### UnsetCurrency
`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) UnsetCurrency()`

UnsetCurrency ensures that no value is present for Currency, not even an explicit nil
### GetVatPercent

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) GetVatPercent() float32`

GetVatPercent returns the VatPercent field if non-nil, zero value otherwise.

### GetVatPercentOk

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) GetVatPercentOk() (*float32, bool)`

GetVatPercentOk returns a tuple with the VatPercent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVatPercent

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) SetVatPercent(v float32)`

SetVatPercent sets VatPercent field to given value.

### HasVatPercent

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) HasVatPercent() bool`

HasVatPercent returns a boolean if a field has been set.

### SetVatPercentNil

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) SetVatPercentNil(b bool)`

 SetVatPercentNil sets the value for VatPercent to be an explicit nil

### UnsetVatPercent
`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) UnsetVatPercent()`

UnsetVatPercent ensures that no value is present for VatPercent, not even an explicit nil
### GetLocation

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) GetLocation() string`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) GetLocationOk() (*string, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) SetLocation(v string)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### SetLocationNil

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) SetLocationNil(b bool)`

 SetLocationNil sets the value for Location to be an explicit nil

### UnsetLocation
`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) UnsetLocation()`

UnsetLocation ensures that no value is present for Location, not even an explicit nil
### GetCountryOfOrigin

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) GetCountryOfOrigin() string`

GetCountryOfOrigin returns the CountryOfOrigin field if non-nil, zero value otherwise.

### GetCountryOfOriginOk

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) GetCountryOfOriginOk() (*string, bool)`

GetCountryOfOriginOk returns a tuple with the CountryOfOrigin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryOfOrigin

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) SetCountryOfOrigin(v string)`

SetCountryOfOrigin sets CountryOfOrigin field to given value.

### HasCountryOfOrigin

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) HasCountryOfOrigin() bool`

HasCountryOfOrigin returns a boolean if a field has been set.

### GetTarrifNumber

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) GetTarrifNumber() string`

GetTarrifNumber returns the TarrifNumber field if non-nil, zero value otherwise.

### GetTarrifNumberOk

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) GetTarrifNumberOk() (*string, bool)`

GetTarrifNumberOk returns a tuple with the TarrifNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTarrifNumber

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) SetTarrifNumber(v string)`

SetTarrifNumber sets TarrifNumber field to given value.

### HasTarrifNumber

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) HasTarrifNumber() bool`

HasTarrifNumber returns a boolean if a field has been set.

### SetTarrifNumberNil

`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) SetTarrifNumberNil(b bool)`

 SetTarrifNumberNil sets the value for TarrifNumber to be an explicit nil

### UnsetTarrifNumber
`func (o *CreateShipmentRequestParcelsInnerOrderLinesInner) UnsetTarrifNumber()`

UnsetTarrifNumber ensures that no value is present for TarrifNumber, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


