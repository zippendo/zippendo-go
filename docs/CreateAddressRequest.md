# CreateAddressRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | Name of the address | 
**AttContact** | **string** | Attention contact person | 
**Address1** | **string** | Address line 1 | 
**Address2** | Pointer to **string** | Address line 2 | [optional] 
**Zipcode** | **string** | Postal/ZIP code | 
**City** | **string** | City | 
**Phone** | **string** | Phone number | 
**CountryCode** | **string** | Country code (ISO 2 or 3 letter) | 
**State** | Pointer to **string** | State/Province | [optional] 
**Email** | **string** | Email address | 
**Customs** | Pointer to **map[string]string** | Customs identifiers (voec, eori, sprn, ioss, fda, duns) | [optional] 
**AddressTypes** | Pointer to **[]string** | Address types (sender, pickup, return) | [optional] [default to {"sender"}]
**BrandId** | Pointer to **NullableString** | Brand this record is assigned to; null (or omitted outside a brand session) keeps it organization-wide | [optional] 

## Methods

### NewCreateAddressRequest

`func NewCreateAddressRequest(name string, attContact string, address1 string, zipcode string, city string, phone string, countryCode string, email string, ) *CreateAddressRequest`

NewCreateAddressRequest instantiates a new CreateAddressRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateAddressRequestWithDefaults

`func NewCreateAddressRequestWithDefaults() *CreateAddressRequest`

NewCreateAddressRequestWithDefaults instantiates a new CreateAddressRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateAddressRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateAddressRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateAddressRequest) SetName(v string)`

SetName sets Name field to given value.


### GetAttContact

`func (o *CreateAddressRequest) GetAttContact() string`

GetAttContact returns the AttContact field if non-nil, zero value otherwise.

### GetAttContactOk

`func (o *CreateAddressRequest) GetAttContactOk() (*string, bool)`

GetAttContactOk returns a tuple with the AttContact field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttContact

`func (o *CreateAddressRequest) SetAttContact(v string)`

SetAttContact sets AttContact field to given value.


### GetAddress1

`func (o *CreateAddressRequest) GetAddress1() string`

GetAddress1 returns the Address1 field if non-nil, zero value otherwise.

### GetAddress1Ok

`func (o *CreateAddressRequest) GetAddress1Ok() (*string, bool)`

GetAddress1Ok returns a tuple with the Address1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress1

`func (o *CreateAddressRequest) SetAddress1(v string)`

SetAddress1 sets Address1 field to given value.


### GetAddress2

`func (o *CreateAddressRequest) GetAddress2() string`

GetAddress2 returns the Address2 field if non-nil, zero value otherwise.

### GetAddress2Ok

`func (o *CreateAddressRequest) GetAddress2Ok() (*string, bool)`

GetAddress2Ok returns a tuple with the Address2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress2

`func (o *CreateAddressRequest) SetAddress2(v string)`

SetAddress2 sets Address2 field to given value.

### HasAddress2

`func (o *CreateAddressRequest) HasAddress2() bool`

HasAddress2 returns a boolean if a field has been set.

### GetZipcode

`func (o *CreateAddressRequest) GetZipcode() string`

GetZipcode returns the Zipcode field if non-nil, zero value otherwise.

### GetZipcodeOk

`func (o *CreateAddressRequest) GetZipcodeOk() (*string, bool)`

GetZipcodeOk returns a tuple with the Zipcode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZipcode

`func (o *CreateAddressRequest) SetZipcode(v string)`

SetZipcode sets Zipcode field to given value.


### GetCity

`func (o *CreateAddressRequest) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *CreateAddressRequest) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *CreateAddressRequest) SetCity(v string)`

SetCity sets City field to given value.


### GetPhone

`func (o *CreateAddressRequest) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *CreateAddressRequest) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *CreateAddressRequest) SetPhone(v string)`

SetPhone sets Phone field to given value.


### GetCountryCode

`func (o *CreateAddressRequest) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *CreateAddressRequest) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *CreateAddressRequest) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.


### GetState

`func (o *CreateAddressRequest) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *CreateAddressRequest) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *CreateAddressRequest) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *CreateAddressRequest) HasState() bool`

HasState returns a boolean if a field has been set.

### GetEmail

`func (o *CreateAddressRequest) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *CreateAddressRequest) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *CreateAddressRequest) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetCustoms

`func (o *CreateAddressRequest) GetCustoms() map[string]string`

GetCustoms returns the Customs field if non-nil, zero value otherwise.

### GetCustomsOk

`func (o *CreateAddressRequest) GetCustomsOk() (*map[string]string, bool)`

GetCustomsOk returns a tuple with the Customs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustoms

`func (o *CreateAddressRequest) SetCustoms(v map[string]string)`

SetCustoms sets Customs field to given value.

### HasCustoms

`func (o *CreateAddressRequest) HasCustoms() bool`

HasCustoms returns a boolean if a field has been set.

### GetAddressTypes

`func (o *CreateAddressRequest) GetAddressTypes() []string`

GetAddressTypes returns the AddressTypes field if non-nil, zero value otherwise.

### GetAddressTypesOk

`func (o *CreateAddressRequest) GetAddressTypesOk() (*[]string, bool)`

GetAddressTypesOk returns a tuple with the AddressTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressTypes

`func (o *CreateAddressRequest) SetAddressTypes(v []string)`

SetAddressTypes sets AddressTypes field to given value.

### HasAddressTypes

`func (o *CreateAddressRequest) HasAddressTypes() bool`

HasAddressTypes returns a boolean if a field has been set.

### GetBrandId

`func (o *CreateAddressRequest) GetBrandId() string`

GetBrandId returns the BrandId field if non-nil, zero value otherwise.

### GetBrandIdOk

`func (o *CreateAddressRequest) GetBrandIdOk() (*string, bool)`

GetBrandIdOk returns a tuple with the BrandId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandId

`func (o *CreateAddressRequest) SetBrandId(v string)`

SetBrandId sets BrandId field to given value.

### HasBrandId

`func (o *CreateAddressRequest) HasBrandId() bool`

HasBrandId returns a boolean if a field has been set.

### SetBrandIdNil

`func (o *CreateAddressRequest) SetBrandIdNil(b bool)`

 SetBrandIdNil sets the value for BrandId to be an explicit nil

### UnsetBrandId
`func (o *CreateAddressRequest) UnsetBrandId()`

UnsetBrandId ensures that no value is present for BrandId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


