# CreateOrgBrandRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CompanyName** | Pointer to **NullableString** | Legal entity name printed on this brand&#39;s documents | [optional] 
**VatNumber** | Pointer to **NullableString** | VAT/tax ID for this brand&#39;s shipments and documents | [optional] 
**Customs** | Pointer to **map[string]string** | Customs identifiers keyed by type | [optional] 
**AddressLine1** | Pointer to **NullableString** | Street address line 1 | [optional] 
**AddressLine2** | Pointer to **NullableString** | Street address line 2 | [optional] 
**City** | Pointer to **NullableString** | City | [optional] 
**PostalCode** | Pointer to **NullableString** | Postal code | [optional] 
**Country** | Pointer to **NullableString** | Country (ISO 3166-1 alpha-2) | [optional] 
**PrimaryColor** | Pointer to **NullableString** | Primary brand colour — document title and table headers | [optional] 
**SecondaryColor** | Pointer to **NullableString** | Secondary brand colour — subtitle, section headings, totals accent | [optional] 
**Name** | **string** | Brand display name | 
**Slug** | Pointer to **string** | URL-safe identifier, unique within the org. Derived from the name when omitted. | [optional] 
**UseOrgCustoms** | Pointer to **bool** | Whether this brand ships under the organization&#39;s fiscal identity. True (the default) declares the organization&#39;s VAT number and customs identifiers and ignores the brand&#39;s own. False makes the brand&#39;s own values the sole source — nothing falls back to the organization, so an identifier the brand has not set is not declared at all. | [optional] 

## Methods

### NewCreateOrgBrandRequest

`func NewCreateOrgBrandRequest(name string, ) *CreateOrgBrandRequest`

NewCreateOrgBrandRequest instantiates a new CreateOrgBrandRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateOrgBrandRequestWithDefaults

`func NewCreateOrgBrandRequestWithDefaults() *CreateOrgBrandRequest`

NewCreateOrgBrandRequestWithDefaults instantiates a new CreateOrgBrandRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCompanyName

`func (o *CreateOrgBrandRequest) GetCompanyName() string`

GetCompanyName returns the CompanyName field if non-nil, zero value otherwise.

### GetCompanyNameOk

`func (o *CreateOrgBrandRequest) GetCompanyNameOk() (*string, bool)`

GetCompanyNameOk returns a tuple with the CompanyName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompanyName

`func (o *CreateOrgBrandRequest) SetCompanyName(v string)`

SetCompanyName sets CompanyName field to given value.

### HasCompanyName

`func (o *CreateOrgBrandRequest) HasCompanyName() bool`

HasCompanyName returns a boolean if a field has been set.

### SetCompanyNameNil

`func (o *CreateOrgBrandRequest) SetCompanyNameNil(b bool)`

 SetCompanyNameNil sets the value for CompanyName to be an explicit nil

### UnsetCompanyName
`func (o *CreateOrgBrandRequest) UnsetCompanyName()`

UnsetCompanyName ensures that no value is present for CompanyName, not even an explicit nil
### GetVatNumber

`func (o *CreateOrgBrandRequest) GetVatNumber() string`

GetVatNumber returns the VatNumber field if non-nil, zero value otherwise.

### GetVatNumberOk

`func (o *CreateOrgBrandRequest) GetVatNumberOk() (*string, bool)`

GetVatNumberOk returns a tuple with the VatNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVatNumber

`func (o *CreateOrgBrandRequest) SetVatNumber(v string)`

SetVatNumber sets VatNumber field to given value.

### HasVatNumber

`func (o *CreateOrgBrandRequest) HasVatNumber() bool`

HasVatNumber returns a boolean if a field has been set.

### SetVatNumberNil

`func (o *CreateOrgBrandRequest) SetVatNumberNil(b bool)`

 SetVatNumberNil sets the value for VatNumber to be an explicit nil

### UnsetVatNumber
`func (o *CreateOrgBrandRequest) UnsetVatNumber()`

UnsetVatNumber ensures that no value is present for VatNumber, not even an explicit nil
### GetCustoms

`func (o *CreateOrgBrandRequest) GetCustoms() map[string]string`

GetCustoms returns the Customs field if non-nil, zero value otherwise.

### GetCustomsOk

`func (o *CreateOrgBrandRequest) GetCustomsOk() (*map[string]string, bool)`

GetCustomsOk returns a tuple with the Customs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustoms

`func (o *CreateOrgBrandRequest) SetCustoms(v map[string]string)`

SetCustoms sets Customs field to given value.

### HasCustoms

`func (o *CreateOrgBrandRequest) HasCustoms() bool`

HasCustoms returns a boolean if a field has been set.

### SetCustomsNil

`func (o *CreateOrgBrandRequest) SetCustomsNil(b bool)`

 SetCustomsNil sets the value for Customs to be an explicit nil

### UnsetCustoms
`func (o *CreateOrgBrandRequest) UnsetCustoms()`

UnsetCustoms ensures that no value is present for Customs, not even an explicit nil
### GetAddressLine1

`func (o *CreateOrgBrandRequest) GetAddressLine1() string`

GetAddressLine1 returns the AddressLine1 field if non-nil, zero value otherwise.

### GetAddressLine1Ok

`func (o *CreateOrgBrandRequest) GetAddressLine1Ok() (*string, bool)`

GetAddressLine1Ok returns a tuple with the AddressLine1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressLine1

`func (o *CreateOrgBrandRequest) SetAddressLine1(v string)`

SetAddressLine1 sets AddressLine1 field to given value.

### HasAddressLine1

`func (o *CreateOrgBrandRequest) HasAddressLine1() bool`

HasAddressLine1 returns a boolean if a field has been set.

### SetAddressLine1Nil

`func (o *CreateOrgBrandRequest) SetAddressLine1Nil(b bool)`

 SetAddressLine1Nil sets the value for AddressLine1 to be an explicit nil

### UnsetAddressLine1
`func (o *CreateOrgBrandRequest) UnsetAddressLine1()`

UnsetAddressLine1 ensures that no value is present for AddressLine1, not even an explicit nil
### GetAddressLine2

`func (o *CreateOrgBrandRequest) GetAddressLine2() string`

GetAddressLine2 returns the AddressLine2 field if non-nil, zero value otherwise.

### GetAddressLine2Ok

`func (o *CreateOrgBrandRequest) GetAddressLine2Ok() (*string, bool)`

GetAddressLine2Ok returns a tuple with the AddressLine2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressLine2

`func (o *CreateOrgBrandRequest) SetAddressLine2(v string)`

SetAddressLine2 sets AddressLine2 field to given value.

### HasAddressLine2

`func (o *CreateOrgBrandRequest) HasAddressLine2() bool`

HasAddressLine2 returns a boolean if a field has been set.

### SetAddressLine2Nil

`func (o *CreateOrgBrandRequest) SetAddressLine2Nil(b bool)`

 SetAddressLine2Nil sets the value for AddressLine2 to be an explicit nil

### UnsetAddressLine2
`func (o *CreateOrgBrandRequest) UnsetAddressLine2()`

UnsetAddressLine2 ensures that no value is present for AddressLine2, not even an explicit nil
### GetCity

`func (o *CreateOrgBrandRequest) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *CreateOrgBrandRequest) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *CreateOrgBrandRequest) SetCity(v string)`

SetCity sets City field to given value.

### HasCity

`func (o *CreateOrgBrandRequest) HasCity() bool`

HasCity returns a boolean if a field has been set.

### SetCityNil

`func (o *CreateOrgBrandRequest) SetCityNil(b bool)`

 SetCityNil sets the value for City to be an explicit nil

### UnsetCity
`func (o *CreateOrgBrandRequest) UnsetCity()`

UnsetCity ensures that no value is present for City, not even an explicit nil
### GetPostalCode

`func (o *CreateOrgBrandRequest) GetPostalCode() string`

GetPostalCode returns the PostalCode field if non-nil, zero value otherwise.

### GetPostalCodeOk

`func (o *CreateOrgBrandRequest) GetPostalCodeOk() (*string, bool)`

GetPostalCodeOk returns a tuple with the PostalCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostalCode

`func (o *CreateOrgBrandRequest) SetPostalCode(v string)`

SetPostalCode sets PostalCode field to given value.

### HasPostalCode

`func (o *CreateOrgBrandRequest) HasPostalCode() bool`

HasPostalCode returns a boolean if a field has been set.

### SetPostalCodeNil

`func (o *CreateOrgBrandRequest) SetPostalCodeNil(b bool)`

 SetPostalCodeNil sets the value for PostalCode to be an explicit nil

### UnsetPostalCode
`func (o *CreateOrgBrandRequest) UnsetPostalCode()`

UnsetPostalCode ensures that no value is present for PostalCode, not even an explicit nil
### GetCountry

`func (o *CreateOrgBrandRequest) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *CreateOrgBrandRequest) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *CreateOrgBrandRequest) SetCountry(v string)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *CreateOrgBrandRequest) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### SetCountryNil

`func (o *CreateOrgBrandRequest) SetCountryNil(b bool)`

 SetCountryNil sets the value for Country to be an explicit nil

### UnsetCountry
`func (o *CreateOrgBrandRequest) UnsetCountry()`

UnsetCountry ensures that no value is present for Country, not even an explicit nil
### GetPrimaryColor

`func (o *CreateOrgBrandRequest) GetPrimaryColor() string`

GetPrimaryColor returns the PrimaryColor field if non-nil, zero value otherwise.

### GetPrimaryColorOk

`func (o *CreateOrgBrandRequest) GetPrimaryColorOk() (*string, bool)`

GetPrimaryColorOk returns a tuple with the PrimaryColor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryColor

`func (o *CreateOrgBrandRequest) SetPrimaryColor(v string)`

SetPrimaryColor sets PrimaryColor field to given value.

### HasPrimaryColor

`func (o *CreateOrgBrandRequest) HasPrimaryColor() bool`

HasPrimaryColor returns a boolean if a field has been set.

### SetPrimaryColorNil

`func (o *CreateOrgBrandRequest) SetPrimaryColorNil(b bool)`

 SetPrimaryColorNil sets the value for PrimaryColor to be an explicit nil

### UnsetPrimaryColor
`func (o *CreateOrgBrandRequest) UnsetPrimaryColor()`

UnsetPrimaryColor ensures that no value is present for PrimaryColor, not even an explicit nil
### GetSecondaryColor

`func (o *CreateOrgBrandRequest) GetSecondaryColor() string`

GetSecondaryColor returns the SecondaryColor field if non-nil, zero value otherwise.

### GetSecondaryColorOk

`func (o *CreateOrgBrandRequest) GetSecondaryColorOk() (*string, bool)`

GetSecondaryColorOk returns a tuple with the SecondaryColor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecondaryColor

`func (o *CreateOrgBrandRequest) SetSecondaryColor(v string)`

SetSecondaryColor sets SecondaryColor field to given value.

### HasSecondaryColor

`func (o *CreateOrgBrandRequest) HasSecondaryColor() bool`

HasSecondaryColor returns a boolean if a field has been set.

### SetSecondaryColorNil

`func (o *CreateOrgBrandRequest) SetSecondaryColorNil(b bool)`

 SetSecondaryColorNil sets the value for SecondaryColor to be an explicit nil

### UnsetSecondaryColor
`func (o *CreateOrgBrandRequest) UnsetSecondaryColor()`

UnsetSecondaryColor ensures that no value is present for SecondaryColor, not even an explicit nil
### GetName

`func (o *CreateOrgBrandRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateOrgBrandRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateOrgBrandRequest) SetName(v string)`

SetName sets Name field to given value.


### GetSlug

`func (o *CreateOrgBrandRequest) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *CreateOrgBrandRequest) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *CreateOrgBrandRequest) SetSlug(v string)`

SetSlug sets Slug field to given value.

### HasSlug

`func (o *CreateOrgBrandRequest) HasSlug() bool`

HasSlug returns a boolean if a field has been set.

### GetUseOrgCustoms

`func (o *CreateOrgBrandRequest) GetUseOrgCustoms() bool`

GetUseOrgCustoms returns the UseOrgCustoms field if non-nil, zero value otherwise.

### GetUseOrgCustomsOk

`func (o *CreateOrgBrandRequest) GetUseOrgCustomsOk() (*bool, bool)`

GetUseOrgCustomsOk returns a tuple with the UseOrgCustoms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseOrgCustoms

`func (o *CreateOrgBrandRequest) SetUseOrgCustoms(v bool)`

SetUseOrgCustoms sets UseOrgCustoms field to given value.

### HasUseOrgCustoms

`func (o *CreateOrgBrandRequest) HasUseOrgCustoms() bool`

HasUseOrgCustoms returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


