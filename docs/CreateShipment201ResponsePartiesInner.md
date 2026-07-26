# CreateShipment201ResponsePartiesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** | Role of the party in the shipment. | 
**Name** | **string** | Full name or company name of the party. | 
**Attention** | Pointer to **NullableString** | Attention contact at the party. | [optional] 
**Address1** | **string** | Primary street address line. | 
**Address2** | Pointer to **NullableString** | Secondary address line. | [optional] 
**PostalCode** | **string** | Postal code of the party address. | 
**City** | **string** | City of the party address. | 
**CountryCode** | **string** | ISO 3166-1 alpha-2 country code. | 
**Email** | Pointer to **NullableString** | Email address of the party. | [optional] 
**Phone** | Pointer to **NullableString** | Phone number of the party in E.164 format. | [optional] 
**Attributes** | [**[]CreateShipment201ResponsePartiesInnerAttributesInner**](CreateShipment201ResponsePartiesInnerAttributesInner.md) | Additional carrier-specific attributes for the party. | [default to {}]

## Methods

### NewCreateShipment201ResponsePartiesInner

`func NewCreateShipment201ResponsePartiesInner(type_ string, name string, address1 string, postalCode string, city string, countryCode string, attributes []CreateShipment201ResponsePartiesInnerAttributesInner, ) *CreateShipment201ResponsePartiesInner`

NewCreateShipment201ResponsePartiesInner instantiates a new CreateShipment201ResponsePartiesInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateShipment201ResponsePartiesInnerWithDefaults

`func NewCreateShipment201ResponsePartiesInnerWithDefaults() *CreateShipment201ResponsePartiesInner`

NewCreateShipment201ResponsePartiesInnerWithDefaults instantiates a new CreateShipment201ResponsePartiesInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *CreateShipment201ResponsePartiesInner) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CreateShipment201ResponsePartiesInner) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CreateShipment201ResponsePartiesInner) SetType(v string)`

SetType sets Type field to given value.


### GetName

`func (o *CreateShipment201ResponsePartiesInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateShipment201ResponsePartiesInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateShipment201ResponsePartiesInner) SetName(v string)`

SetName sets Name field to given value.


### GetAttention

`func (o *CreateShipment201ResponsePartiesInner) GetAttention() string`

GetAttention returns the Attention field if non-nil, zero value otherwise.

### GetAttentionOk

`func (o *CreateShipment201ResponsePartiesInner) GetAttentionOk() (*string, bool)`

GetAttentionOk returns a tuple with the Attention field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttention

`func (o *CreateShipment201ResponsePartiesInner) SetAttention(v string)`

SetAttention sets Attention field to given value.

### HasAttention

`func (o *CreateShipment201ResponsePartiesInner) HasAttention() bool`

HasAttention returns a boolean if a field has been set.

### SetAttentionNil

`func (o *CreateShipment201ResponsePartiesInner) SetAttentionNil(b bool)`

 SetAttentionNil sets the value for Attention to be an explicit nil

### UnsetAttention
`func (o *CreateShipment201ResponsePartiesInner) UnsetAttention()`

UnsetAttention ensures that no value is present for Attention, not even an explicit nil
### GetAddress1

`func (o *CreateShipment201ResponsePartiesInner) GetAddress1() string`

GetAddress1 returns the Address1 field if non-nil, zero value otherwise.

### GetAddress1Ok

`func (o *CreateShipment201ResponsePartiesInner) GetAddress1Ok() (*string, bool)`

GetAddress1Ok returns a tuple with the Address1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress1

`func (o *CreateShipment201ResponsePartiesInner) SetAddress1(v string)`

SetAddress1 sets Address1 field to given value.


### GetAddress2

`func (o *CreateShipment201ResponsePartiesInner) GetAddress2() string`

GetAddress2 returns the Address2 field if non-nil, zero value otherwise.

### GetAddress2Ok

`func (o *CreateShipment201ResponsePartiesInner) GetAddress2Ok() (*string, bool)`

GetAddress2Ok returns a tuple with the Address2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress2

`func (o *CreateShipment201ResponsePartiesInner) SetAddress2(v string)`

SetAddress2 sets Address2 field to given value.

### HasAddress2

`func (o *CreateShipment201ResponsePartiesInner) HasAddress2() bool`

HasAddress2 returns a boolean if a field has been set.

### SetAddress2Nil

`func (o *CreateShipment201ResponsePartiesInner) SetAddress2Nil(b bool)`

 SetAddress2Nil sets the value for Address2 to be an explicit nil

### UnsetAddress2
`func (o *CreateShipment201ResponsePartiesInner) UnsetAddress2()`

UnsetAddress2 ensures that no value is present for Address2, not even an explicit nil
### GetPostalCode

`func (o *CreateShipment201ResponsePartiesInner) GetPostalCode() string`

GetPostalCode returns the PostalCode field if non-nil, zero value otherwise.

### GetPostalCodeOk

`func (o *CreateShipment201ResponsePartiesInner) GetPostalCodeOk() (*string, bool)`

GetPostalCodeOk returns a tuple with the PostalCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostalCode

`func (o *CreateShipment201ResponsePartiesInner) SetPostalCode(v string)`

SetPostalCode sets PostalCode field to given value.


### GetCity

`func (o *CreateShipment201ResponsePartiesInner) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *CreateShipment201ResponsePartiesInner) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *CreateShipment201ResponsePartiesInner) SetCity(v string)`

SetCity sets City field to given value.


### GetCountryCode

`func (o *CreateShipment201ResponsePartiesInner) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *CreateShipment201ResponsePartiesInner) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *CreateShipment201ResponsePartiesInner) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.


### GetEmail

`func (o *CreateShipment201ResponsePartiesInner) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *CreateShipment201ResponsePartiesInner) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *CreateShipment201ResponsePartiesInner) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *CreateShipment201ResponsePartiesInner) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### SetEmailNil

`func (o *CreateShipment201ResponsePartiesInner) SetEmailNil(b bool)`

 SetEmailNil sets the value for Email to be an explicit nil

### UnsetEmail
`func (o *CreateShipment201ResponsePartiesInner) UnsetEmail()`

UnsetEmail ensures that no value is present for Email, not even an explicit nil
### GetPhone

`func (o *CreateShipment201ResponsePartiesInner) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *CreateShipment201ResponsePartiesInner) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *CreateShipment201ResponsePartiesInner) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *CreateShipment201ResponsePartiesInner) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### SetPhoneNil

`func (o *CreateShipment201ResponsePartiesInner) SetPhoneNil(b bool)`

 SetPhoneNil sets the value for Phone to be an explicit nil

### UnsetPhone
`func (o *CreateShipment201ResponsePartiesInner) UnsetPhone()`

UnsetPhone ensures that no value is present for Phone, not even an explicit nil
### GetAttributes

`func (o *CreateShipment201ResponsePartiesInner) GetAttributes() []CreateShipment201ResponsePartiesInnerAttributesInner`

GetAttributes returns the Attributes field if non-nil, zero value otherwise.

### GetAttributesOk

`func (o *CreateShipment201ResponsePartiesInner) GetAttributesOk() (*[]CreateShipment201ResponsePartiesInnerAttributesInner, bool)`

GetAttributesOk returns a tuple with the Attributes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttributes

`func (o *CreateShipment201ResponsePartiesInner) SetAttributes(v []CreateShipment201ResponsePartiesInnerAttributesInner)`

SetAttributes sets Attributes field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


