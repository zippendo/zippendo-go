# UpdateOrgRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | Organization name | [optional] 
**Slug** | Pointer to **string** | Organization slug | [optional] 
**Description** | Pointer to **string** | Organization description | [optional] 
**Currency** | Pointer to **string** | Billing currency (ISO 4217 code) | [optional] 
**VatNumber** | Pointer to **NullableString** | Company VAT/tax ID for invoices | [optional] 
**OverageEnabled** | Pointer to **bool** | Allow shipments beyond plan limit (overage charges apply) | [optional] 
**Phone** | Pointer to **NullableString** | Billing/contact phone number | [optional] 
**BillingEmail** | Pointer to **NullableString** | Billing email for invoices | [optional] 
**CompanyName** | Pointer to **NullableString** | Legal company name | [optional] 
**AddressLine1** | Pointer to **NullableString** | Address line 1 | [optional] 
**AddressLine2** | Pointer to **NullableString** | Address line 2 | [optional] 
**City** | Pointer to **NullableString** | City | [optional] 
**PostalCode** | Pointer to **NullableString** | Postal code | [optional] 
**Country** | Pointer to **NullableString** | Country (ISO 3166-1 alpha-2 code) | [optional] 
**Customs** | Pointer to **map[string]string** | Organization-wide customs identifiers (EORI, IOSS, VOEC, etc.); null clears all | [optional] 

## Methods

### NewUpdateOrgRequest

`func NewUpdateOrgRequest() *UpdateOrgRequest`

NewUpdateOrgRequest instantiates a new UpdateOrgRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateOrgRequestWithDefaults

`func NewUpdateOrgRequestWithDefaults() *UpdateOrgRequest`

NewUpdateOrgRequestWithDefaults instantiates a new UpdateOrgRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *UpdateOrgRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateOrgRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateOrgRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *UpdateOrgRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetSlug

`func (o *UpdateOrgRequest) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *UpdateOrgRequest) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *UpdateOrgRequest) SetSlug(v string)`

SetSlug sets Slug field to given value.

### HasSlug

`func (o *UpdateOrgRequest) HasSlug() bool`

HasSlug returns a boolean if a field has been set.

### GetDescription

`func (o *UpdateOrgRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *UpdateOrgRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *UpdateOrgRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *UpdateOrgRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetCurrency

`func (o *UpdateOrgRequest) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *UpdateOrgRequest) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *UpdateOrgRequest) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *UpdateOrgRequest) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetVatNumber

`func (o *UpdateOrgRequest) GetVatNumber() string`

GetVatNumber returns the VatNumber field if non-nil, zero value otherwise.

### GetVatNumberOk

`func (o *UpdateOrgRequest) GetVatNumberOk() (*string, bool)`

GetVatNumberOk returns a tuple with the VatNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVatNumber

`func (o *UpdateOrgRequest) SetVatNumber(v string)`

SetVatNumber sets VatNumber field to given value.

### HasVatNumber

`func (o *UpdateOrgRequest) HasVatNumber() bool`

HasVatNumber returns a boolean if a field has been set.

### SetVatNumberNil

`func (o *UpdateOrgRequest) SetVatNumberNil(b bool)`

 SetVatNumberNil sets the value for VatNumber to be an explicit nil

### UnsetVatNumber
`func (o *UpdateOrgRequest) UnsetVatNumber()`

UnsetVatNumber ensures that no value is present for VatNumber, not even an explicit nil
### GetOverageEnabled

`func (o *UpdateOrgRequest) GetOverageEnabled() bool`

GetOverageEnabled returns the OverageEnabled field if non-nil, zero value otherwise.

### GetOverageEnabledOk

`func (o *UpdateOrgRequest) GetOverageEnabledOk() (*bool, bool)`

GetOverageEnabledOk returns a tuple with the OverageEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverageEnabled

`func (o *UpdateOrgRequest) SetOverageEnabled(v bool)`

SetOverageEnabled sets OverageEnabled field to given value.

### HasOverageEnabled

`func (o *UpdateOrgRequest) HasOverageEnabled() bool`

HasOverageEnabled returns a boolean if a field has been set.

### GetPhone

`func (o *UpdateOrgRequest) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *UpdateOrgRequest) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *UpdateOrgRequest) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *UpdateOrgRequest) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### SetPhoneNil

`func (o *UpdateOrgRequest) SetPhoneNil(b bool)`

 SetPhoneNil sets the value for Phone to be an explicit nil

### UnsetPhone
`func (o *UpdateOrgRequest) UnsetPhone()`

UnsetPhone ensures that no value is present for Phone, not even an explicit nil
### GetBillingEmail

`func (o *UpdateOrgRequest) GetBillingEmail() string`

GetBillingEmail returns the BillingEmail field if non-nil, zero value otherwise.

### GetBillingEmailOk

`func (o *UpdateOrgRequest) GetBillingEmailOk() (*string, bool)`

GetBillingEmailOk returns a tuple with the BillingEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingEmail

`func (o *UpdateOrgRequest) SetBillingEmail(v string)`

SetBillingEmail sets BillingEmail field to given value.

### HasBillingEmail

`func (o *UpdateOrgRequest) HasBillingEmail() bool`

HasBillingEmail returns a boolean if a field has been set.

### SetBillingEmailNil

`func (o *UpdateOrgRequest) SetBillingEmailNil(b bool)`

 SetBillingEmailNil sets the value for BillingEmail to be an explicit nil

### UnsetBillingEmail
`func (o *UpdateOrgRequest) UnsetBillingEmail()`

UnsetBillingEmail ensures that no value is present for BillingEmail, not even an explicit nil
### GetCompanyName

`func (o *UpdateOrgRequest) GetCompanyName() string`

GetCompanyName returns the CompanyName field if non-nil, zero value otherwise.

### GetCompanyNameOk

`func (o *UpdateOrgRequest) GetCompanyNameOk() (*string, bool)`

GetCompanyNameOk returns a tuple with the CompanyName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompanyName

`func (o *UpdateOrgRequest) SetCompanyName(v string)`

SetCompanyName sets CompanyName field to given value.

### HasCompanyName

`func (o *UpdateOrgRequest) HasCompanyName() bool`

HasCompanyName returns a boolean if a field has been set.

### SetCompanyNameNil

`func (o *UpdateOrgRequest) SetCompanyNameNil(b bool)`

 SetCompanyNameNil sets the value for CompanyName to be an explicit nil

### UnsetCompanyName
`func (o *UpdateOrgRequest) UnsetCompanyName()`

UnsetCompanyName ensures that no value is present for CompanyName, not even an explicit nil
### GetAddressLine1

`func (o *UpdateOrgRequest) GetAddressLine1() string`

GetAddressLine1 returns the AddressLine1 field if non-nil, zero value otherwise.

### GetAddressLine1Ok

`func (o *UpdateOrgRequest) GetAddressLine1Ok() (*string, bool)`

GetAddressLine1Ok returns a tuple with the AddressLine1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressLine1

`func (o *UpdateOrgRequest) SetAddressLine1(v string)`

SetAddressLine1 sets AddressLine1 field to given value.

### HasAddressLine1

`func (o *UpdateOrgRequest) HasAddressLine1() bool`

HasAddressLine1 returns a boolean if a field has been set.

### SetAddressLine1Nil

`func (o *UpdateOrgRequest) SetAddressLine1Nil(b bool)`

 SetAddressLine1Nil sets the value for AddressLine1 to be an explicit nil

### UnsetAddressLine1
`func (o *UpdateOrgRequest) UnsetAddressLine1()`

UnsetAddressLine1 ensures that no value is present for AddressLine1, not even an explicit nil
### GetAddressLine2

`func (o *UpdateOrgRequest) GetAddressLine2() string`

GetAddressLine2 returns the AddressLine2 field if non-nil, zero value otherwise.

### GetAddressLine2Ok

`func (o *UpdateOrgRequest) GetAddressLine2Ok() (*string, bool)`

GetAddressLine2Ok returns a tuple with the AddressLine2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressLine2

`func (o *UpdateOrgRequest) SetAddressLine2(v string)`

SetAddressLine2 sets AddressLine2 field to given value.

### HasAddressLine2

`func (o *UpdateOrgRequest) HasAddressLine2() bool`

HasAddressLine2 returns a boolean if a field has been set.

### SetAddressLine2Nil

`func (o *UpdateOrgRequest) SetAddressLine2Nil(b bool)`

 SetAddressLine2Nil sets the value for AddressLine2 to be an explicit nil

### UnsetAddressLine2
`func (o *UpdateOrgRequest) UnsetAddressLine2()`

UnsetAddressLine2 ensures that no value is present for AddressLine2, not even an explicit nil
### GetCity

`func (o *UpdateOrgRequest) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *UpdateOrgRequest) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *UpdateOrgRequest) SetCity(v string)`

SetCity sets City field to given value.

### HasCity

`func (o *UpdateOrgRequest) HasCity() bool`

HasCity returns a boolean if a field has been set.

### SetCityNil

`func (o *UpdateOrgRequest) SetCityNil(b bool)`

 SetCityNil sets the value for City to be an explicit nil

### UnsetCity
`func (o *UpdateOrgRequest) UnsetCity()`

UnsetCity ensures that no value is present for City, not even an explicit nil
### GetPostalCode

`func (o *UpdateOrgRequest) GetPostalCode() string`

GetPostalCode returns the PostalCode field if non-nil, zero value otherwise.

### GetPostalCodeOk

`func (o *UpdateOrgRequest) GetPostalCodeOk() (*string, bool)`

GetPostalCodeOk returns a tuple with the PostalCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostalCode

`func (o *UpdateOrgRequest) SetPostalCode(v string)`

SetPostalCode sets PostalCode field to given value.

### HasPostalCode

`func (o *UpdateOrgRequest) HasPostalCode() bool`

HasPostalCode returns a boolean if a field has been set.

### SetPostalCodeNil

`func (o *UpdateOrgRequest) SetPostalCodeNil(b bool)`

 SetPostalCodeNil sets the value for PostalCode to be an explicit nil

### UnsetPostalCode
`func (o *UpdateOrgRequest) UnsetPostalCode()`

UnsetPostalCode ensures that no value is present for PostalCode, not even an explicit nil
### GetCountry

`func (o *UpdateOrgRequest) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *UpdateOrgRequest) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *UpdateOrgRequest) SetCountry(v string)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *UpdateOrgRequest) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### SetCountryNil

`func (o *UpdateOrgRequest) SetCountryNil(b bool)`

 SetCountryNil sets the value for Country to be an explicit nil

### UnsetCountry
`func (o *UpdateOrgRequest) UnsetCountry()`

UnsetCountry ensures that no value is present for Country, not even an explicit nil
### GetCustoms

`func (o *UpdateOrgRequest) GetCustoms() map[string]string`

GetCustoms returns the Customs field if non-nil, zero value otherwise.

### GetCustomsOk

`func (o *UpdateOrgRequest) GetCustomsOk() (*map[string]string, bool)`

GetCustomsOk returns a tuple with the Customs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustoms

`func (o *UpdateOrgRequest) SetCustoms(v map[string]string)`

SetCustoms sets Customs field to given value.

### HasCustoms

`func (o *UpdateOrgRequest) HasCustoms() bool`

HasCustoms returns a boolean if a field has been set.

### SetCustomsNil

`func (o *UpdateOrgRequest) SetCustomsNil(b bool)`

 SetCustomsNil sets the value for Customs to be an explicit nil

### UnsetCustoms
`func (o *UpdateOrgRequest) UnsetCustoms()`

UnsetCustoms ensures that no value is present for Customs, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


