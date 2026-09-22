# UpdateAddressRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | Company or person the parcel is sent from, printed on labels | [optional] 
**Description** | Pointer to **NullableString** | Internal label for this address; send null or an empty string to clear it | [optional] 
**AttContact** | Pointer to **NullableString** | Contact person at this address; send null or an empty string to clear it | [optional] 
**Address1** | Pointer to **string** | Address line 1 | [optional] 
**Address2** | Pointer to **NullableString** | Address line 2; send null or an empty string to clear it | [optional] 
**Zipcode** | Pointer to **string** | Postal/ZIP code | [optional] 
**City** | Pointer to **string** | City | [optional] 
**Phone** | Pointer to **string** | Phone number | [optional] 
**CountryCode** | Pointer to **string** | ISO country code | [optional] 
**State** | Pointer to **NullableString** | State/Province; send null or an empty string to clear it | [optional] 
**Email** | Pointer to **string** | Email address | [optional] 
**Customs** | Pointer to **map[string]string** | Customs identifiers | [optional] 
**AddressTypes** | Pointer to **[]string** | Address types (sender, pickup, return) | [optional] 
**BrandId** | Pointer to **NullableString** | Brand this record is assigned to; null (or omitted outside a brand session) keeps it organization-wide | [optional] 

## Methods

### NewUpdateAddressRequest

`func NewUpdateAddressRequest() *UpdateAddressRequest`

NewUpdateAddressRequest instantiates a new UpdateAddressRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateAddressRequestWithDefaults

`func NewUpdateAddressRequestWithDefaults() *UpdateAddressRequest`

NewUpdateAddressRequestWithDefaults instantiates a new UpdateAddressRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *UpdateAddressRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateAddressRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateAddressRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *UpdateAddressRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetDescription

`func (o *UpdateAddressRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *UpdateAddressRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *UpdateAddressRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *UpdateAddressRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *UpdateAddressRequest) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *UpdateAddressRequest) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetAttContact

`func (o *UpdateAddressRequest) GetAttContact() string`

GetAttContact returns the AttContact field if non-nil, zero value otherwise.

### GetAttContactOk

`func (o *UpdateAddressRequest) GetAttContactOk() (*string, bool)`

GetAttContactOk returns a tuple with the AttContact field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttContact

`func (o *UpdateAddressRequest) SetAttContact(v string)`

SetAttContact sets AttContact field to given value.

### HasAttContact

`func (o *UpdateAddressRequest) HasAttContact() bool`

HasAttContact returns a boolean if a field has been set.

### SetAttContactNil

`func (o *UpdateAddressRequest) SetAttContactNil(b bool)`

 SetAttContactNil sets the value for AttContact to be an explicit nil

### UnsetAttContact
`func (o *UpdateAddressRequest) UnsetAttContact()`

UnsetAttContact ensures that no value is present for AttContact, not even an explicit nil
### GetAddress1

`func (o *UpdateAddressRequest) GetAddress1() string`

GetAddress1 returns the Address1 field if non-nil, zero value otherwise.

### GetAddress1Ok

`func (o *UpdateAddressRequest) GetAddress1Ok() (*string, bool)`

GetAddress1Ok returns a tuple with the Address1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress1

`func (o *UpdateAddressRequest) SetAddress1(v string)`

SetAddress1 sets Address1 field to given value.

### HasAddress1

`func (o *UpdateAddressRequest) HasAddress1() bool`

HasAddress1 returns a boolean if a field has been set.

### GetAddress2

`func (o *UpdateAddressRequest) GetAddress2() string`

GetAddress2 returns the Address2 field if non-nil, zero value otherwise.

### GetAddress2Ok

`func (o *UpdateAddressRequest) GetAddress2Ok() (*string, bool)`

GetAddress2Ok returns a tuple with the Address2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress2

`func (o *UpdateAddressRequest) SetAddress2(v string)`

SetAddress2 sets Address2 field to given value.

### HasAddress2

`func (o *UpdateAddressRequest) HasAddress2() bool`

HasAddress2 returns a boolean if a field has been set.

### SetAddress2Nil

`func (o *UpdateAddressRequest) SetAddress2Nil(b bool)`

 SetAddress2Nil sets the value for Address2 to be an explicit nil

### UnsetAddress2
`func (o *UpdateAddressRequest) UnsetAddress2()`

UnsetAddress2 ensures that no value is present for Address2, not even an explicit nil
### GetZipcode

`func (o *UpdateAddressRequest) GetZipcode() string`

GetZipcode returns the Zipcode field if non-nil, zero value otherwise.

### GetZipcodeOk

`func (o *UpdateAddressRequest) GetZipcodeOk() (*string, bool)`

GetZipcodeOk returns a tuple with the Zipcode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZipcode

`func (o *UpdateAddressRequest) SetZipcode(v string)`

SetZipcode sets Zipcode field to given value.

### HasZipcode

`func (o *UpdateAddressRequest) HasZipcode() bool`

HasZipcode returns a boolean if a field has been set.

### GetCity

`func (o *UpdateAddressRequest) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *UpdateAddressRequest) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *UpdateAddressRequest) SetCity(v string)`

SetCity sets City field to given value.

### HasCity

`func (o *UpdateAddressRequest) HasCity() bool`

HasCity returns a boolean if a field has been set.

### GetPhone

`func (o *UpdateAddressRequest) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *UpdateAddressRequest) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *UpdateAddressRequest) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *UpdateAddressRequest) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### GetCountryCode

`func (o *UpdateAddressRequest) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *UpdateAddressRequest) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *UpdateAddressRequest) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.

### HasCountryCode

`func (o *UpdateAddressRequest) HasCountryCode() bool`

HasCountryCode returns a boolean if a field has been set.

### GetState

`func (o *UpdateAddressRequest) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *UpdateAddressRequest) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *UpdateAddressRequest) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *UpdateAddressRequest) HasState() bool`

HasState returns a boolean if a field has been set.

### SetStateNil

`func (o *UpdateAddressRequest) SetStateNil(b bool)`

 SetStateNil sets the value for State to be an explicit nil

### UnsetState
`func (o *UpdateAddressRequest) UnsetState()`

UnsetState ensures that no value is present for State, not even an explicit nil
### GetEmail

`func (o *UpdateAddressRequest) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *UpdateAddressRequest) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *UpdateAddressRequest) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *UpdateAddressRequest) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetCustoms

`func (o *UpdateAddressRequest) GetCustoms() map[string]string`

GetCustoms returns the Customs field if non-nil, zero value otherwise.

### GetCustomsOk

`func (o *UpdateAddressRequest) GetCustomsOk() (*map[string]string, bool)`

GetCustomsOk returns a tuple with the Customs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustoms

`func (o *UpdateAddressRequest) SetCustoms(v map[string]string)`

SetCustoms sets Customs field to given value.

### HasCustoms

`func (o *UpdateAddressRequest) HasCustoms() bool`

HasCustoms returns a boolean if a field has been set.

### GetAddressTypes

`func (o *UpdateAddressRequest) GetAddressTypes() []string`

GetAddressTypes returns the AddressTypes field if non-nil, zero value otherwise.

### GetAddressTypesOk

`func (o *UpdateAddressRequest) GetAddressTypesOk() (*[]string, bool)`

GetAddressTypesOk returns a tuple with the AddressTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressTypes

`func (o *UpdateAddressRequest) SetAddressTypes(v []string)`

SetAddressTypes sets AddressTypes field to given value.

### HasAddressTypes

`func (o *UpdateAddressRequest) HasAddressTypes() bool`

HasAddressTypes returns a boolean if a field has been set.

### GetBrandId

`func (o *UpdateAddressRequest) GetBrandId() string`

GetBrandId returns the BrandId field if non-nil, zero value otherwise.

### GetBrandIdOk

`func (o *UpdateAddressRequest) GetBrandIdOk() (*string, bool)`

GetBrandIdOk returns a tuple with the BrandId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandId

`func (o *UpdateAddressRequest) SetBrandId(v string)`

SetBrandId sets BrandId field to given value.

### HasBrandId

`func (o *UpdateAddressRequest) HasBrandId() bool`

HasBrandId returns a boolean if a field has been set.

### SetBrandIdNil

`func (o *UpdateAddressRequest) SetBrandIdNil(b bool)`

 SetBrandIdNil sets the value for BrandId to be an explicit nil

### UnsetBrandId
`func (o *UpdateAddressRequest) UnsetBrandId()`

UnsetBrandId ensures that no value is present for BrandId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


