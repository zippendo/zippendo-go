# ListOrgBrands200ResponseDataInner

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
**Id** | **string** | Unique brand identifier | 
**OrgId** | **string** | Owning organization | 
**Name** | **string** | Brand display name | 
**Slug** | **string** | URL-safe identifier, unique within the organization | 
**UseOrgCustoms** | **bool** | Whether this brand ships under the organization&#39;s fiscal identity. True (the default) declares the organization&#39;s VAT number and customs identifiers and ignores the brand&#39;s own. False makes the brand&#39;s own values the sole source — nothing falls back to the organization, so an identifier the brand has not set is not declared at all. | 
**LogoUrl** | **NullableString** | Authenticated URL for the brand logo, or null when none is set | 
**ArchivedAt** | **NullableString** | When the brand was archived; null when active | 
**CreatedAt** | **string** | Creation timestamp (ISO 8601) | 
**UpdatedAt** | **string** | Last update timestamp (ISO 8601) | 

## Methods

### NewListOrgBrands200ResponseDataInner

`func NewListOrgBrands200ResponseDataInner(id string, orgId string, name string, slug string, useOrgCustoms bool, logoUrl NullableString, archivedAt NullableString, createdAt string, updatedAt string, ) *ListOrgBrands200ResponseDataInner`

NewListOrgBrands200ResponseDataInner instantiates a new ListOrgBrands200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListOrgBrands200ResponseDataInnerWithDefaults

`func NewListOrgBrands200ResponseDataInnerWithDefaults() *ListOrgBrands200ResponseDataInner`

NewListOrgBrands200ResponseDataInnerWithDefaults instantiates a new ListOrgBrands200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCompanyName

`func (o *ListOrgBrands200ResponseDataInner) GetCompanyName() string`

GetCompanyName returns the CompanyName field if non-nil, zero value otherwise.

### GetCompanyNameOk

`func (o *ListOrgBrands200ResponseDataInner) GetCompanyNameOk() (*string, bool)`

GetCompanyNameOk returns a tuple with the CompanyName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompanyName

`func (o *ListOrgBrands200ResponseDataInner) SetCompanyName(v string)`

SetCompanyName sets CompanyName field to given value.

### HasCompanyName

`func (o *ListOrgBrands200ResponseDataInner) HasCompanyName() bool`

HasCompanyName returns a boolean if a field has been set.

### SetCompanyNameNil

`func (o *ListOrgBrands200ResponseDataInner) SetCompanyNameNil(b bool)`

 SetCompanyNameNil sets the value for CompanyName to be an explicit nil

### UnsetCompanyName
`func (o *ListOrgBrands200ResponseDataInner) UnsetCompanyName()`

UnsetCompanyName ensures that no value is present for CompanyName, not even an explicit nil
### GetVatNumber

`func (o *ListOrgBrands200ResponseDataInner) GetVatNumber() string`

GetVatNumber returns the VatNumber field if non-nil, zero value otherwise.

### GetVatNumberOk

`func (o *ListOrgBrands200ResponseDataInner) GetVatNumberOk() (*string, bool)`

GetVatNumberOk returns a tuple with the VatNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVatNumber

`func (o *ListOrgBrands200ResponseDataInner) SetVatNumber(v string)`

SetVatNumber sets VatNumber field to given value.

### HasVatNumber

`func (o *ListOrgBrands200ResponseDataInner) HasVatNumber() bool`

HasVatNumber returns a boolean if a field has been set.

### SetVatNumberNil

`func (o *ListOrgBrands200ResponseDataInner) SetVatNumberNil(b bool)`

 SetVatNumberNil sets the value for VatNumber to be an explicit nil

### UnsetVatNumber
`func (o *ListOrgBrands200ResponseDataInner) UnsetVatNumber()`

UnsetVatNumber ensures that no value is present for VatNumber, not even an explicit nil
### GetCustoms

`func (o *ListOrgBrands200ResponseDataInner) GetCustoms() map[string]string`

GetCustoms returns the Customs field if non-nil, zero value otherwise.

### GetCustomsOk

`func (o *ListOrgBrands200ResponseDataInner) GetCustomsOk() (*map[string]string, bool)`

GetCustomsOk returns a tuple with the Customs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustoms

`func (o *ListOrgBrands200ResponseDataInner) SetCustoms(v map[string]string)`

SetCustoms sets Customs field to given value.

### HasCustoms

`func (o *ListOrgBrands200ResponseDataInner) HasCustoms() bool`

HasCustoms returns a boolean if a field has been set.

### SetCustomsNil

`func (o *ListOrgBrands200ResponseDataInner) SetCustomsNil(b bool)`

 SetCustomsNil sets the value for Customs to be an explicit nil

### UnsetCustoms
`func (o *ListOrgBrands200ResponseDataInner) UnsetCustoms()`

UnsetCustoms ensures that no value is present for Customs, not even an explicit nil
### GetAddressLine1

`func (o *ListOrgBrands200ResponseDataInner) GetAddressLine1() string`

GetAddressLine1 returns the AddressLine1 field if non-nil, zero value otherwise.

### GetAddressLine1Ok

`func (o *ListOrgBrands200ResponseDataInner) GetAddressLine1Ok() (*string, bool)`

GetAddressLine1Ok returns a tuple with the AddressLine1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressLine1

`func (o *ListOrgBrands200ResponseDataInner) SetAddressLine1(v string)`

SetAddressLine1 sets AddressLine1 field to given value.

### HasAddressLine1

`func (o *ListOrgBrands200ResponseDataInner) HasAddressLine1() bool`

HasAddressLine1 returns a boolean if a field has been set.

### SetAddressLine1Nil

`func (o *ListOrgBrands200ResponseDataInner) SetAddressLine1Nil(b bool)`

 SetAddressLine1Nil sets the value for AddressLine1 to be an explicit nil

### UnsetAddressLine1
`func (o *ListOrgBrands200ResponseDataInner) UnsetAddressLine1()`

UnsetAddressLine1 ensures that no value is present for AddressLine1, not even an explicit nil
### GetAddressLine2

`func (o *ListOrgBrands200ResponseDataInner) GetAddressLine2() string`

GetAddressLine2 returns the AddressLine2 field if non-nil, zero value otherwise.

### GetAddressLine2Ok

`func (o *ListOrgBrands200ResponseDataInner) GetAddressLine2Ok() (*string, bool)`

GetAddressLine2Ok returns a tuple with the AddressLine2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressLine2

`func (o *ListOrgBrands200ResponseDataInner) SetAddressLine2(v string)`

SetAddressLine2 sets AddressLine2 field to given value.

### HasAddressLine2

`func (o *ListOrgBrands200ResponseDataInner) HasAddressLine2() bool`

HasAddressLine2 returns a boolean if a field has been set.

### SetAddressLine2Nil

`func (o *ListOrgBrands200ResponseDataInner) SetAddressLine2Nil(b bool)`

 SetAddressLine2Nil sets the value for AddressLine2 to be an explicit nil

### UnsetAddressLine2
`func (o *ListOrgBrands200ResponseDataInner) UnsetAddressLine2()`

UnsetAddressLine2 ensures that no value is present for AddressLine2, not even an explicit nil
### GetCity

`func (o *ListOrgBrands200ResponseDataInner) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *ListOrgBrands200ResponseDataInner) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *ListOrgBrands200ResponseDataInner) SetCity(v string)`

SetCity sets City field to given value.

### HasCity

`func (o *ListOrgBrands200ResponseDataInner) HasCity() bool`

HasCity returns a boolean if a field has been set.

### SetCityNil

`func (o *ListOrgBrands200ResponseDataInner) SetCityNil(b bool)`

 SetCityNil sets the value for City to be an explicit nil

### UnsetCity
`func (o *ListOrgBrands200ResponseDataInner) UnsetCity()`

UnsetCity ensures that no value is present for City, not even an explicit nil
### GetPostalCode

`func (o *ListOrgBrands200ResponseDataInner) GetPostalCode() string`

GetPostalCode returns the PostalCode field if non-nil, zero value otherwise.

### GetPostalCodeOk

`func (o *ListOrgBrands200ResponseDataInner) GetPostalCodeOk() (*string, bool)`

GetPostalCodeOk returns a tuple with the PostalCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostalCode

`func (o *ListOrgBrands200ResponseDataInner) SetPostalCode(v string)`

SetPostalCode sets PostalCode field to given value.

### HasPostalCode

`func (o *ListOrgBrands200ResponseDataInner) HasPostalCode() bool`

HasPostalCode returns a boolean if a field has been set.

### SetPostalCodeNil

`func (o *ListOrgBrands200ResponseDataInner) SetPostalCodeNil(b bool)`

 SetPostalCodeNil sets the value for PostalCode to be an explicit nil

### UnsetPostalCode
`func (o *ListOrgBrands200ResponseDataInner) UnsetPostalCode()`

UnsetPostalCode ensures that no value is present for PostalCode, not even an explicit nil
### GetCountry

`func (o *ListOrgBrands200ResponseDataInner) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *ListOrgBrands200ResponseDataInner) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *ListOrgBrands200ResponseDataInner) SetCountry(v string)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *ListOrgBrands200ResponseDataInner) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### SetCountryNil

`func (o *ListOrgBrands200ResponseDataInner) SetCountryNil(b bool)`

 SetCountryNil sets the value for Country to be an explicit nil

### UnsetCountry
`func (o *ListOrgBrands200ResponseDataInner) UnsetCountry()`

UnsetCountry ensures that no value is present for Country, not even an explicit nil
### GetPrimaryColor

`func (o *ListOrgBrands200ResponseDataInner) GetPrimaryColor() string`

GetPrimaryColor returns the PrimaryColor field if non-nil, zero value otherwise.

### GetPrimaryColorOk

`func (o *ListOrgBrands200ResponseDataInner) GetPrimaryColorOk() (*string, bool)`

GetPrimaryColorOk returns a tuple with the PrimaryColor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryColor

`func (o *ListOrgBrands200ResponseDataInner) SetPrimaryColor(v string)`

SetPrimaryColor sets PrimaryColor field to given value.

### HasPrimaryColor

`func (o *ListOrgBrands200ResponseDataInner) HasPrimaryColor() bool`

HasPrimaryColor returns a boolean if a field has been set.

### SetPrimaryColorNil

`func (o *ListOrgBrands200ResponseDataInner) SetPrimaryColorNil(b bool)`

 SetPrimaryColorNil sets the value for PrimaryColor to be an explicit nil

### UnsetPrimaryColor
`func (o *ListOrgBrands200ResponseDataInner) UnsetPrimaryColor()`

UnsetPrimaryColor ensures that no value is present for PrimaryColor, not even an explicit nil
### GetSecondaryColor

`func (o *ListOrgBrands200ResponseDataInner) GetSecondaryColor() string`

GetSecondaryColor returns the SecondaryColor field if non-nil, zero value otherwise.

### GetSecondaryColorOk

`func (o *ListOrgBrands200ResponseDataInner) GetSecondaryColorOk() (*string, bool)`

GetSecondaryColorOk returns a tuple with the SecondaryColor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecondaryColor

`func (o *ListOrgBrands200ResponseDataInner) SetSecondaryColor(v string)`

SetSecondaryColor sets SecondaryColor field to given value.

### HasSecondaryColor

`func (o *ListOrgBrands200ResponseDataInner) HasSecondaryColor() bool`

HasSecondaryColor returns a boolean if a field has been set.

### SetSecondaryColorNil

`func (o *ListOrgBrands200ResponseDataInner) SetSecondaryColorNil(b bool)`

 SetSecondaryColorNil sets the value for SecondaryColor to be an explicit nil

### UnsetSecondaryColor
`func (o *ListOrgBrands200ResponseDataInner) UnsetSecondaryColor()`

UnsetSecondaryColor ensures that no value is present for SecondaryColor, not even an explicit nil
### GetId

`func (o *ListOrgBrands200ResponseDataInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ListOrgBrands200ResponseDataInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ListOrgBrands200ResponseDataInner) SetId(v string)`

SetId sets Id field to given value.


### GetOrgId

`func (o *ListOrgBrands200ResponseDataInner) GetOrgId() string`

GetOrgId returns the OrgId field if non-nil, zero value otherwise.

### GetOrgIdOk

`func (o *ListOrgBrands200ResponseDataInner) GetOrgIdOk() (*string, bool)`

GetOrgIdOk returns a tuple with the OrgId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrgId

`func (o *ListOrgBrands200ResponseDataInner) SetOrgId(v string)`

SetOrgId sets OrgId field to given value.


### GetName

`func (o *ListOrgBrands200ResponseDataInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ListOrgBrands200ResponseDataInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ListOrgBrands200ResponseDataInner) SetName(v string)`

SetName sets Name field to given value.


### GetSlug

`func (o *ListOrgBrands200ResponseDataInner) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *ListOrgBrands200ResponseDataInner) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *ListOrgBrands200ResponseDataInner) SetSlug(v string)`

SetSlug sets Slug field to given value.


### GetUseOrgCustoms

`func (o *ListOrgBrands200ResponseDataInner) GetUseOrgCustoms() bool`

GetUseOrgCustoms returns the UseOrgCustoms field if non-nil, zero value otherwise.

### GetUseOrgCustomsOk

`func (o *ListOrgBrands200ResponseDataInner) GetUseOrgCustomsOk() (*bool, bool)`

GetUseOrgCustomsOk returns a tuple with the UseOrgCustoms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseOrgCustoms

`func (o *ListOrgBrands200ResponseDataInner) SetUseOrgCustoms(v bool)`

SetUseOrgCustoms sets UseOrgCustoms field to given value.


### GetLogoUrl

`func (o *ListOrgBrands200ResponseDataInner) GetLogoUrl() string`

GetLogoUrl returns the LogoUrl field if non-nil, zero value otherwise.

### GetLogoUrlOk

`func (o *ListOrgBrands200ResponseDataInner) GetLogoUrlOk() (*string, bool)`

GetLogoUrlOk returns a tuple with the LogoUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogoUrl

`func (o *ListOrgBrands200ResponseDataInner) SetLogoUrl(v string)`

SetLogoUrl sets LogoUrl field to given value.


### SetLogoUrlNil

`func (o *ListOrgBrands200ResponseDataInner) SetLogoUrlNil(b bool)`

 SetLogoUrlNil sets the value for LogoUrl to be an explicit nil

### UnsetLogoUrl
`func (o *ListOrgBrands200ResponseDataInner) UnsetLogoUrl()`

UnsetLogoUrl ensures that no value is present for LogoUrl, not even an explicit nil
### GetArchivedAt

`func (o *ListOrgBrands200ResponseDataInner) GetArchivedAt() string`

GetArchivedAt returns the ArchivedAt field if non-nil, zero value otherwise.

### GetArchivedAtOk

`func (o *ListOrgBrands200ResponseDataInner) GetArchivedAtOk() (*string, bool)`

GetArchivedAtOk returns a tuple with the ArchivedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchivedAt

`func (o *ListOrgBrands200ResponseDataInner) SetArchivedAt(v string)`

SetArchivedAt sets ArchivedAt field to given value.


### SetArchivedAtNil

`func (o *ListOrgBrands200ResponseDataInner) SetArchivedAtNil(b bool)`

 SetArchivedAtNil sets the value for ArchivedAt to be an explicit nil

### UnsetArchivedAt
`func (o *ListOrgBrands200ResponseDataInner) UnsetArchivedAt()`

UnsetArchivedAt ensures that no value is present for ArchivedAt, not even an explicit nil
### GetCreatedAt

`func (o *ListOrgBrands200ResponseDataInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ListOrgBrands200ResponseDataInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ListOrgBrands200ResponseDataInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *ListOrgBrands200ResponseDataInner) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ListOrgBrands200ResponseDataInner) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ListOrgBrands200ResponseDataInner) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


