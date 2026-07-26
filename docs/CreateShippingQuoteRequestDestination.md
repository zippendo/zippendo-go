# CreateShippingQuoteRequestDestination

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Country** | **string** | ISO 3166-1 alpha-2 country code | 
**PostalCode** | Pointer to **string** | Postal/ZIP code | [optional] 
**Province** | Pointer to **string** | State/province code | [optional] 
**City** | Pointer to **string** | City name | [optional] 
**Address1** | Pointer to **string** | Street address line 1 | [optional] 
**Address2** | Pointer to **string** | Street address line 2 | [optional] 

## Methods

### NewCreateShippingQuoteRequestDestination

`func NewCreateShippingQuoteRequestDestination(country string, ) *CreateShippingQuoteRequestDestination`

NewCreateShippingQuoteRequestDestination instantiates a new CreateShippingQuoteRequestDestination object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateShippingQuoteRequestDestinationWithDefaults

`func NewCreateShippingQuoteRequestDestinationWithDefaults() *CreateShippingQuoteRequestDestination`

NewCreateShippingQuoteRequestDestinationWithDefaults instantiates a new CreateShippingQuoteRequestDestination object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCountry

`func (o *CreateShippingQuoteRequestDestination) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *CreateShippingQuoteRequestDestination) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *CreateShippingQuoteRequestDestination) SetCountry(v string)`

SetCountry sets Country field to given value.


### GetPostalCode

`func (o *CreateShippingQuoteRequestDestination) GetPostalCode() string`

GetPostalCode returns the PostalCode field if non-nil, zero value otherwise.

### GetPostalCodeOk

`func (o *CreateShippingQuoteRequestDestination) GetPostalCodeOk() (*string, bool)`

GetPostalCodeOk returns a tuple with the PostalCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostalCode

`func (o *CreateShippingQuoteRequestDestination) SetPostalCode(v string)`

SetPostalCode sets PostalCode field to given value.

### HasPostalCode

`func (o *CreateShippingQuoteRequestDestination) HasPostalCode() bool`

HasPostalCode returns a boolean if a field has been set.

### GetProvince

`func (o *CreateShippingQuoteRequestDestination) GetProvince() string`

GetProvince returns the Province field if non-nil, zero value otherwise.

### GetProvinceOk

`func (o *CreateShippingQuoteRequestDestination) GetProvinceOk() (*string, bool)`

GetProvinceOk returns a tuple with the Province field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvince

`func (o *CreateShippingQuoteRequestDestination) SetProvince(v string)`

SetProvince sets Province field to given value.

### HasProvince

`func (o *CreateShippingQuoteRequestDestination) HasProvince() bool`

HasProvince returns a boolean if a field has been set.

### GetCity

`func (o *CreateShippingQuoteRequestDestination) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *CreateShippingQuoteRequestDestination) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *CreateShippingQuoteRequestDestination) SetCity(v string)`

SetCity sets City field to given value.

### HasCity

`func (o *CreateShippingQuoteRequestDestination) HasCity() bool`

HasCity returns a boolean if a field has been set.

### GetAddress1

`func (o *CreateShippingQuoteRequestDestination) GetAddress1() string`

GetAddress1 returns the Address1 field if non-nil, zero value otherwise.

### GetAddress1Ok

`func (o *CreateShippingQuoteRequestDestination) GetAddress1Ok() (*string, bool)`

GetAddress1Ok returns a tuple with the Address1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress1

`func (o *CreateShippingQuoteRequestDestination) SetAddress1(v string)`

SetAddress1 sets Address1 field to given value.

### HasAddress1

`func (o *CreateShippingQuoteRequestDestination) HasAddress1() bool`

HasAddress1 returns a boolean if a field has been set.

### GetAddress2

`func (o *CreateShippingQuoteRequestDestination) GetAddress2() string`

GetAddress2 returns the Address2 field if non-nil, zero value otherwise.

### GetAddress2Ok

`func (o *CreateShippingQuoteRequestDestination) GetAddress2Ok() (*string, bool)`

GetAddress2Ok returns a tuple with the Address2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress2

`func (o *CreateShippingQuoteRequestDestination) SetAddress2(v string)`

SetAddress2 sets Address2 field to given value.

### HasAddress2

`func (o *CreateShippingQuoteRequestDestination) HasAddress2() bool`

HasAddress2 returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


