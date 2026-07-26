# ListShipments200ResponseDataInnerAddress

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

### NewListShipments200ResponseDataInnerAddress

`func NewListShipments200ResponseDataInnerAddress(id string, name string, attContact string, address1 string, address2 NullableString, zipcode string, city string, phone string, countryCode string, state NullableString, email string, addressTypes []string, orgId string, createdAt string, updatedAt string, ) *ListShipments200ResponseDataInnerAddress`

NewListShipments200ResponseDataInnerAddress instantiates a new ListShipments200ResponseDataInnerAddress object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListShipments200ResponseDataInnerAddressWithDefaults

`func NewListShipments200ResponseDataInnerAddressWithDefaults() *ListShipments200ResponseDataInnerAddress`

NewListShipments200ResponseDataInnerAddressWithDefaults instantiates a new ListShipments200ResponseDataInnerAddress object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ListShipments200ResponseDataInnerAddress) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ListShipments200ResponseDataInnerAddress) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ListShipments200ResponseDataInnerAddress) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *ListShipments200ResponseDataInnerAddress) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ListShipments200ResponseDataInnerAddress) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ListShipments200ResponseDataInnerAddress) SetName(v string)`

SetName sets Name field to given value.


### GetAttContact

`func (o *ListShipments200ResponseDataInnerAddress) GetAttContact() string`

GetAttContact returns the AttContact field if non-nil, zero value otherwise.

### GetAttContactOk

`func (o *ListShipments200ResponseDataInnerAddress) GetAttContactOk() (*string, bool)`

GetAttContactOk returns a tuple with the AttContact field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttContact

`func (o *ListShipments200ResponseDataInnerAddress) SetAttContact(v string)`

SetAttContact sets AttContact field to given value.


### GetAddress1

`func (o *ListShipments200ResponseDataInnerAddress) GetAddress1() string`

GetAddress1 returns the Address1 field if non-nil, zero value otherwise.

### GetAddress1Ok

`func (o *ListShipments200ResponseDataInnerAddress) GetAddress1Ok() (*string, bool)`

GetAddress1Ok returns a tuple with the Address1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress1

`func (o *ListShipments200ResponseDataInnerAddress) SetAddress1(v string)`

SetAddress1 sets Address1 field to given value.


### GetAddress2

`func (o *ListShipments200ResponseDataInnerAddress) GetAddress2() string`

GetAddress2 returns the Address2 field if non-nil, zero value otherwise.

### GetAddress2Ok

`func (o *ListShipments200ResponseDataInnerAddress) GetAddress2Ok() (*string, bool)`

GetAddress2Ok returns a tuple with the Address2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress2

`func (o *ListShipments200ResponseDataInnerAddress) SetAddress2(v string)`

SetAddress2 sets Address2 field to given value.


### SetAddress2Nil

`func (o *ListShipments200ResponseDataInnerAddress) SetAddress2Nil(b bool)`

 SetAddress2Nil sets the value for Address2 to be an explicit nil

### UnsetAddress2
`func (o *ListShipments200ResponseDataInnerAddress) UnsetAddress2()`

UnsetAddress2 ensures that no value is present for Address2, not even an explicit nil
### GetZipcode

`func (o *ListShipments200ResponseDataInnerAddress) GetZipcode() string`

GetZipcode returns the Zipcode field if non-nil, zero value otherwise.

### GetZipcodeOk

`func (o *ListShipments200ResponseDataInnerAddress) GetZipcodeOk() (*string, bool)`

GetZipcodeOk returns a tuple with the Zipcode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZipcode

`func (o *ListShipments200ResponseDataInnerAddress) SetZipcode(v string)`

SetZipcode sets Zipcode field to given value.


### GetCity

`func (o *ListShipments200ResponseDataInnerAddress) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *ListShipments200ResponseDataInnerAddress) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *ListShipments200ResponseDataInnerAddress) SetCity(v string)`

SetCity sets City field to given value.


### GetPhone

`func (o *ListShipments200ResponseDataInnerAddress) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *ListShipments200ResponseDataInnerAddress) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *ListShipments200ResponseDataInnerAddress) SetPhone(v string)`

SetPhone sets Phone field to given value.


### GetCountryCode

`func (o *ListShipments200ResponseDataInnerAddress) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *ListShipments200ResponseDataInnerAddress) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *ListShipments200ResponseDataInnerAddress) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.


### GetState

`func (o *ListShipments200ResponseDataInnerAddress) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *ListShipments200ResponseDataInnerAddress) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *ListShipments200ResponseDataInnerAddress) SetState(v string)`

SetState sets State field to given value.


### SetStateNil

`func (o *ListShipments200ResponseDataInnerAddress) SetStateNil(b bool)`

 SetStateNil sets the value for State to be an explicit nil

### UnsetState
`func (o *ListShipments200ResponseDataInnerAddress) UnsetState()`

UnsetState ensures that no value is present for State, not even an explicit nil
### GetEmail

`func (o *ListShipments200ResponseDataInnerAddress) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *ListShipments200ResponseDataInnerAddress) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *ListShipments200ResponseDataInnerAddress) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetCustoms

`func (o *ListShipments200ResponseDataInnerAddress) GetCustoms() map[string]string`

GetCustoms returns the Customs field if non-nil, zero value otherwise.

### GetCustomsOk

`func (o *ListShipments200ResponseDataInnerAddress) GetCustomsOk() (*map[string]string, bool)`

GetCustomsOk returns a tuple with the Customs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustoms

`func (o *ListShipments200ResponseDataInnerAddress) SetCustoms(v map[string]string)`

SetCustoms sets Customs field to given value.

### HasCustoms

`func (o *ListShipments200ResponseDataInnerAddress) HasCustoms() bool`

HasCustoms returns a boolean if a field has been set.

### SetCustomsNil

`func (o *ListShipments200ResponseDataInnerAddress) SetCustomsNil(b bool)`

 SetCustomsNil sets the value for Customs to be an explicit nil

### UnsetCustoms
`func (o *ListShipments200ResponseDataInnerAddress) UnsetCustoms()`

UnsetCustoms ensures that no value is present for Customs, not even an explicit nil
### GetAddressTypes

`func (o *ListShipments200ResponseDataInnerAddress) GetAddressTypes() []string`

GetAddressTypes returns the AddressTypes field if non-nil, zero value otherwise.

### GetAddressTypesOk

`func (o *ListShipments200ResponseDataInnerAddress) GetAddressTypesOk() (*[]string, bool)`

GetAddressTypesOk returns a tuple with the AddressTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressTypes

`func (o *ListShipments200ResponseDataInnerAddress) SetAddressTypes(v []string)`

SetAddressTypes sets AddressTypes field to given value.


### GetOrgId

`func (o *ListShipments200ResponseDataInnerAddress) GetOrgId() string`

GetOrgId returns the OrgId field if non-nil, zero value otherwise.

### GetOrgIdOk

`func (o *ListShipments200ResponseDataInnerAddress) GetOrgIdOk() (*string, bool)`

GetOrgIdOk returns a tuple with the OrgId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrgId

`func (o *ListShipments200ResponseDataInnerAddress) SetOrgId(v string)`

SetOrgId sets OrgId field to given value.


### GetCreatedAt

`func (o *ListShipments200ResponseDataInnerAddress) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ListShipments200ResponseDataInnerAddress) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ListShipments200ResponseDataInnerAddress) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *ListShipments200ResponseDataInnerAddress) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ListShipments200ResponseDataInnerAddress) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ListShipments200ResponseDataInnerAddress) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


