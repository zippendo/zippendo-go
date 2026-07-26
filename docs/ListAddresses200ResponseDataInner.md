# ListAddresses200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Unique address identifier | 
**Name** | **string** | Name of the address | 
**AttContact** | **string** | Attention contact person | 
**Address1** | **string** | Address line 1 | 
**Address2** | **NullableString** | Address line 2 | 
**Zipcode** | **string** | Postal/ZIP code | 
**City** | **string** | City | 
**Phone** | **string** | Phone number | 
**CountryCode** | **string** | ISO country code | 
**State** | **NullableString** | State/Province | 
**Email** | **string** | Email address | 
**Customs** | Pointer to **map[string]string** | Customs identifiers keyed by type | [optional] 
**AddressTypes** | **[]string** | Address types (sender, pickup, return) | 
**OrgId** | **string** | Owning organization ID | 
**CreatedAt** | **string** | Creation timestamp (ISO 8601) | 
**UpdatedAt** | **string** | Last update timestamp (ISO 8601) | 

## Methods

### NewListAddresses200ResponseDataInner

`func NewListAddresses200ResponseDataInner(id string, name string, attContact string, address1 string, address2 NullableString, zipcode string, city string, phone string, countryCode string, state NullableString, email string, addressTypes []string, orgId string, createdAt string, updatedAt string, ) *ListAddresses200ResponseDataInner`

NewListAddresses200ResponseDataInner instantiates a new ListAddresses200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListAddresses200ResponseDataInnerWithDefaults

`func NewListAddresses200ResponseDataInnerWithDefaults() *ListAddresses200ResponseDataInner`

NewListAddresses200ResponseDataInnerWithDefaults instantiates a new ListAddresses200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ListAddresses200ResponseDataInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ListAddresses200ResponseDataInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ListAddresses200ResponseDataInner) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *ListAddresses200ResponseDataInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ListAddresses200ResponseDataInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ListAddresses200ResponseDataInner) SetName(v string)`

SetName sets Name field to given value.


### GetAttContact

`func (o *ListAddresses200ResponseDataInner) GetAttContact() string`

GetAttContact returns the AttContact field if non-nil, zero value otherwise.

### GetAttContactOk

`func (o *ListAddresses200ResponseDataInner) GetAttContactOk() (*string, bool)`

GetAttContactOk returns a tuple with the AttContact field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttContact

`func (o *ListAddresses200ResponseDataInner) SetAttContact(v string)`

SetAttContact sets AttContact field to given value.


### GetAddress1

`func (o *ListAddresses200ResponseDataInner) GetAddress1() string`

GetAddress1 returns the Address1 field if non-nil, zero value otherwise.

### GetAddress1Ok

`func (o *ListAddresses200ResponseDataInner) GetAddress1Ok() (*string, bool)`

GetAddress1Ok returns a tuple with the Address1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress1

`func (o *ListAddresses200ResponseDataInner) SetAddress1(v string)`

SetAddress1 sets Address1 field to given value.


### GetAddress2

`func (o *ListAddresses200ResponseDataInner) GetAddress2() string`

GetAddress2 returns the Address2 field if non-nil, zero value otherwise.

### GetAddress2Ok

`func (o *ListAddresses200ResponseDataInner) GetAddress2Ok() (*string, bool)`

GetAddress2Ok returns a tuple with the Address2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress2

`func (o *ListAddresses200ResponseDataInner) SetAddress2(v string)`

SetAddress2 sets Address2 field to given value.


### SetAddress2Nil

`func (o *ListAddresses200ResponseDataInner) SetAddress2Nil(b bool)`

 SetAddress2Nil sets the value for Address2 to be an explicit nil

### UnsetAddress2
`func (o *ListAddresses200ResponseDataInner) UnsetAddress2()`

UnsetAddress2 ensures that no value is present for Address2, not even an explicit nil
### GetZipcode

`func (o *ListAddresses200ResponseDataInner) GetZipcode() string`

GetZipcode returns the Zipcode field if non-nil, zero value otherwise.

### GetZipcodeOk

`func (o *ListAddresses200ResponseDataInner) GetZipcodeOk() (*string, bool)`

GetZipcodeOk returns a tuple with the Zipcode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZipcode

`func (o *ListAddresses200ResponseDataInner) SetZipcode(v string)`

SetZipcode sets Zipcode field to given value.


### GetCity

`func (o *ListAddresses200ResponseDataInner) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *ListAddresses200ResponseDataInner) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *ListAddresses200ResponseDataInner) SetCity(v string)`

SetCity sets City field to given value.


### GetPhone

`func (o *ListAddresses200ResponseDataInner) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *ListAddresses200ResponseDataInner) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *ListAddresses200ResponseDataInner) SetPhone(v string)`

SetPhone sets Phone field to given value.


### GetCountryCode

`func (o *ListAddresses200ResponseDataInner) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *ListAddresses200ResponseDataInner) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *ListAddresses200ResponseDataInner) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.


### GetState

`func (o *ListAddresses200ResponseDataInner) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *ListAddresses200ResponseDataInner) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *ListAddresses200ResponseDataInner) SetState(v string)`

SetState sets State field to given value.


### SetStateNil

`func (o *ListAddresses200ResponseDataInner) SetStateNil(b bool)`

 SetStateNil sets the value for State to be an explicit nil

### UnsetState
`func (o *ListAddresses200ResponseDataInner) UnsetState()`

UnsetState ensures that no value is present for State, not even an explicit nil
### GetEmail

`func (o *ListAddresses200ResponseDataInner) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *ListAddresses200ResponseDataInner) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *ListAddresses200ResponseDataInner) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetCustoms

`func (o *ListAddresses200ResponseDataInner) GetCustoms() map[string]string`

GetCustoms returns the Customs field if non-nil, zero value otherwise.

### GetCustomsOk

`func (o *ListAddresses200ResponseDataInner) GetCustomsOk() (*map[string]string, bool)`

GetCustomsOk returns a tuple with the Customs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustoms

`func (o *ListAddresses200ResponseDataInner) SetCustoms(v map[string]string)`

SetCustoms sets Customs field to given value.

### HasCustoms

`func (o *ListAddresses200ResponseDataInner) HasCustoms() bool`

HasCustoms returns a boolean if a field has been set.

### SetCustomsNil

`func (o *ListAddresses200ResponseDataInner) SetCustomsNil(b bool)`

 SetCustomsNil sets the value for Customs to be an explicit nil

### UnsetCustoms
`func (o *ListAddresses200ResponseDataInner) UnsetCustoms()`

UnsetCustoms ensures that no value is present for Customs, not even an explicit nil
### GetAddressTypes

`func (o *ListAddresses200ResponseDataInner) GetAddressTypes() []string`

GetAddressTypes returns the AddressTypes field if non-nil, zero value otherwise.

### GetAddressTypesOk

`func (o *ListAddresses200ResponseDataInner) GetAddressTypesOk() (*[]string, bool)`

GetAddressTypesOk returns a tuple with the AddressTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressTypes

`func (o *ListAddresses200ResponseDataInner) SetAddressTypes(v []string)`

SetAddressTypes sets AddressTypes field to given value.


### GetOrgId

`func (o *ListAddresses200ResponseDataInner) GetOrgId() string`

GetOrgId returns the OrgId field if non-nil, zero value otherwise.

### GetOrgIdOk

`func (o *ListAddresses200ResponseDataInner) GetOrgIdOk() (*string, bool)`

GetOrgIdOk returns a tuple with the OrgId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrgId

`func (o *ListAddresses200ResponseDataInner) SetOrgId(v string)`

SetOrgId sets OrgId field to given value.


### GetCreatedAt

`func (o *ListAddresses200ResponseDataInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ListAddresses200ResponseDataInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ListAddresses200ResponseDataInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *ListAddresses200ResponseDataInner) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ListAddresses200ResponseDataInner) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ListAddresses200ResponseDataInner) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


