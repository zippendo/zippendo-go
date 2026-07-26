# CreateShipmentRequestPartiesInner

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
**Attributes** | Pointer to [**[]CreateShipmentRequestPartiesInnerAttributesInner**](CreateShipmentRequestPartiesInnerAttributesInner.md) | Additional carrier-specific attributes for the party. | [optional] [default to {}]

## Methods

### NewCreateShipmentRequestPartiesInner

`func NewCreateShipmentRequestPartiesInner(type_ string, name string, address1 string, postalCode string, city string, countryCode string, ) *CreateShipmentRequestPartiesInner`

NewCreateShipmentRequestPartiesInner instantiates a new CreateShipmentRequestPartiesInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateShipmentRequestPartiesInnerWithDefaults

`func NewCreateShipmentRequestPartiesInnerWithDefaults() *CreateShipmentRequestPartiesInner`

NewCreateShipmentRequestPartiesInnerWithDefaults instantiates a new CreateShipmentRequestPartiesInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *CreateShipmentRequestPartiesInner) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CreateShipmentRequestPartiesInner) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CreateShipmentRequestPartiesInner) SetType(v string)`

SetType sets Type field to given value.


### GetName

`func (o *CreateShipmentRequestPartiesInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateShipmentRequestPartiesInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateShipmentRequestPartiesInner) SetName(v string)`

SetName sets Name field to given value.


### GetAttention

`func (o *CreateShipmentRequestPartiesInner) GetAttention() string`

GetAttention returns the Attention field if non-nil, zero value otherwise.

### GetAttentionOk

`func (o *CreateShipmentRequestPartiesInner) GetAttentionOk() (*string, bool)`

GetAttentionOk returns a tuple with the Attention field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttention

`func (o *CreateShipmentRequestPartiesInner) SetAttention(v string)`

SetAttention sets Attention field to given value.

### HasAttention

`func (o *CreateShipmentRequestPartiesInner) HasAttention() bool`

HasAttention returns a boolean if a field has been set.

### SetAttentionNil

`func (o *CreateShipmentRequestPartiesInner) SetAttentionNil(b bool)`

 SetAttentionNil sets the value for Attention to be an explicit nil

### UnsetAttention
`func (o *CreateShipmentRequestPartiesInner) UnsetAttention()`

UnsetAttention ensures that no value is present for Attention, not even an explicit nil
### GetAddress1

`func (o *CreateShipmentRequestPartiesInner) GetAddress1() string`

GetAddress1 returns the Address1 field if non-nil, zero value otherwise.

### GetAddress1Ok

`func (o *CreateShipmentRequestPartiesInner) GetAddress1Ok() (*string, bool)`

GetAddress1Ok returns a tuple with the Address1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress1

`func (o *CreateShipmentRequestPartiesInner) SetAddress1(v string)`

SetAddress1 sets Address1 field to given value.


### GetAddress2

`func (o *CreateShipmentRequestPartiesInner) GetAddress2() string`

GetAddress2 returns the Address2 field if non-nil, zero value otherwise.

### GetAddress2Ok

`func (o *CreateShipmentRequestPartiesInner) GetAddress2Ok() (*string, bool)`

GetAddress2Ok returns a tuple with the Address2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress2

`func (o *CreateShipmentRequestPartiesInner) SetAddress2(v string)`

SetAddress2 sets Address2 field to given value.

### HasAddress2

`func (o *CreateShipmentRequestPartiesInner) HasAddress2() bool`

HasAddress2 returns a boolean if a field has been set.

### SetAddress2Nil

`func (o *CreateShipmentRequestPartiesInner) SetAddress2Nil(b bool)`

 SetAddress2Nil sets the value for Address2 to be an explicit nil

### UnsetAddress2
`func (o *CreateShipmentRequestPartiesInner) UnsetAddress2()`

UnsetAddress2 ensures that no value is present for Address2, not even an explicit nil
### GetPostalCode

`func (o *CreateShipmentRequestPartiesInner) GetPostalCode() string`

GetPostalCode returns the PostalCode field if non-nil, zero value otherwise.

### GetPostalCodeOk

`func (o *CreateShipmentRequestPartiesInner) GetPostalCodeOk() (*string, bool)`

GetPostalCodeOk returns a tuple with the PostalCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostalCode

`func (o *CreateShipmentRequestPartiesInner) SetPostalCode(v string)`

SetPostalCode sets PostalCode field to given value.


### GetCity

`func (o *CreateShipmentRequestPartiesInner) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *CreateShipmentRequestPartiesInner) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *CreateShipmentRequestPartiesInner) SetCity(v string)`

SetCity sets City field to given value.


### GetCountryCode

`func (o *CreateShipmentRequestPartiesInner) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *CreateShipmentRequestPartiesInner) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *CreateShipmentRequestPartiesInner) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.


### GetEmail

`func (o *CreateShipmentRequestPartiesInner) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *CreateShipmentRequestPartiesInner) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *CreateShipmentRequestPartiesInner) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *CreateShipmentRequestPartiesInner) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### SetEmailNil

`func (o *CreateShipmentRequestPartiesInner) SetEmailNil(b bool)`

 SetEmailNil sets the value for Email to be an explicit nil

### UnsetEmail
`func (o *CreateShipmentRequestPartiesInner) UnsetEmail()`

UnsetEmail ensures that no value is present for Email, not even an explicit nil
### GetPhone

`func (o *CreateShipmentRequestPartiesInner) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *CreateShipmentRequestPartiesInner) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *CreateShipmentRequestPartiesInner) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *CreateShipmentRequestPartiesInner) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### SetPhoneNil

`func (o *CreateShipmentRequestPartiesInner) SetPhoneNil(b bool)`

 SetPhoneNil sets the value for Phone to be an explicit nil

### UnsetPhone
`func (o *CreateShipmentRequestPartiesInner) UnsetPhone()`

UnsetPhone ensures that no value is present for Phone, not even an explicit nil
### GetAttributes

`func (o *CreateShipmentRequestPartiesInner) GetAttributes() []CreateShipmentRequestPartiesInnerAttributesInner`

GetAttributes returns the Attributes field if non-nil, zero value otherwise.

### GetAttributesOk

`func (o *CreateShipmentRequestPartiesInner) GetAttributesOk() (*[]CreateShipmentRequestPartiesInnerAttributesInner, bool)`

GetAttributesOk returns a tuple with the Attributes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttributes

`func (o *CreateShipmentRequestPartiesInner) SetAttributes(v []CreateShipmentRequestPartiesInnerAttributesInner)`

SetAttributes sets Attributes field to given value.

### HasAttributes

`func (o *CreateShipmentRequestPartiesInner) HasAttributes() bool`

HasAttributes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


