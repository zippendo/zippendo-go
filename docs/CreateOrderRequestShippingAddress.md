# CreateOrderRequestShippingAddress

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | Recipient full name. | 
**Attention** | Pointer to **NullableString** | Attention / care-of line. | [optional] 
**Company** | Pointer to **NullableString** | Company name. | [optional] 
**Address1** | **string** | Street address line 1. | 
**Address2** | Pointer to **NullableString** | Street address line 2. | [optional] 
**City** | **string** | City name. | 
**Province** | Pointer to **NullableString** | Province or region name. | [optional] 
**ProvinceCode** | Pointer to **NullableString** | Province or region code. | [optional] 
**PostalCode** | **string** | Postal code. | 
**Country** | Pointer to **NullableString** | Country name. | [optional] 
**CountryCode** | **string** | ISO 3166-1 alpha-2 country code. | 
**Phone** | Pointer to **NullableString** | Recipient phone number. | [optional] 
**Email** | Pointer to **NullableString** | Recipient email address. | [optional] 

## Methods

### NewCreateOrderRequestShippingAddress

`func NewCreateOrderRequestShippingAddress(name string, address1 string, city string, postalCode string, countryCode string, ) *CreateOrderRequestShippingAddress`

NewCreateOrderRequestShippingAddress instantiates a new CreateOrderRequestShippingAddress object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateOrderRequestShippingAddressWithDefaults

`func NewCreateOrderRequestShippingAddressWithDefaults() *CreateOrderRequestShippingAddress`

NewCreateOrderRequestShippingAddressWithDefaults instantiates a new CreateOrderRequestShippingAddress object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateOrderRequestShippingAddress) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateOrderRequestShippingAddress) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateOrderRequestShippingAddress) SetName(v string)`

SetName sets Name field to given value.


### GetAttention

`func (o *CreateOrderRequestShippingAddress) GetAttention() string`

GetAttention returns the Attention field if non-nil, zero value otherwise.

### GetAttentionOk

`func (o *CreateOrderRequestShippingAddress) GetAttentionOk() (*string, bool)`

GetAttentionOk returns a tuple with the Attention field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttention

`func (o *CreateOrderRequestShippingAddress) SetAttention(v string)`

SetAttention sets Attention field to given value.

### HasAttention

`func (o *CreateOrderRequestShippingAddress) HasAttention() bool`

HasAttention returns a boolean if a field has been set.

### SetAttentionNil

`func (o *CreateOrderRequestShippingAddress) SetAttentionNil(b bool)`

 SetAttentionNil sets the value for Attention to be an explicit nil

### UnsetAttention
`func (o *CreateOrderRequestShippingAddress) UnsetAttention()`

UnsetAttention ensures that no value is present for Attention, not even an explicit nil
### GetCompany

`func (o *CreateOrderRequestShippingAddress) GetCompany() string`

GetCompany returns the Company field if non-nil, zero value otherwise.

### GetCompanyOk

`func (o *CreateOrderRequestShippingAddress) GetCompanyOk() (*string, bool)`

GetCompanyOk returns a tuple with the Company field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompany

`func (o *CreateOrderRequestShippingAddress) SetCompany(v string)`

SetCompany sets Company field to given value.

### HasCompany

`func (o *CreateOrderRequestShippingAddress) HasCompany() bool`

HasCompany returns a boolean if a field has been set.

### SetCompanyNil

`func (o *CreateOrderRequestShippingAddress) SetCompanyNil(b bool)`

 SetCompanyNil sets the value for Company to be an explicit nil

### UnsetCompany
`func (o *CreateOrderRequestShippingAddress) UnsetCompany()`

UnsetCompany ensures that no value is present for Company, not even an explicit nil
### GetAddress1

`func (o *CreateOrderRequestShippingAddress) GetAddress1() string`

GetAddress1 returns the Address1 field if non-nil, zero value otherwise.

### GetAddress1Ok

`func (o *CreateOrderRequestShippingAddress) GetAddress1Ok() (*string, bool)`

GetAddress1Ok returns a tuple with the Address1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress1

`func (o *CreateOrderRequestShippingAddress) SetAddress1(v string)`

SetAddress1 sets Address1 field to given value.


### GetAddress2

`func (o *CreateOrderRequestShippingAddress) GetAddress2() string`

GetAddress2 returns the Address2 field if non-nil, zero value otherwise.

### GetAddress2Ok

`func (o *CreateOrderRequestShippingAddress) GetAddress2Ok() (*string, bool)`

GetAddress2Ok returns a tuple with the Address2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress2

`func (o *CreateOrderRequestShippingAddress) SetAddress2(v string)`

SetAddress2 sets Address2 field to given value.

### HasAddress2

`func (o *CreateOrderRequestShippingAddress) HasAddress2() bool`

HasAddress2 returns a boolean if a field has been set.

### SetAddress2Nil

`func (o *CreateOrderRequestShippingAddress) SetAddress2Nil(b bool)`

 SetAddress2Nil sets the value for Address2 to be an explicit nil

### UnsetAddress2
`func (o *CreateOrderRequestShippingAddress) UnsetAddress2()`

UnsetAddress2 ensures that no value is present for Address2, not even an explicit nil
### GetCity

`func (o *CreateOrderRequestShippingAddress) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *CreateOrderRequestShippingAddress) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *CreateOrderRequestShippingAddress) SetCity(v string)`

SetCity sets City field to given value.


### GetProvince

`func (o *CreateOrderRequestShippingAddress) GetProvince() string`

GetProvince returns the Province field if non-nil, zero value otherwise.

### GetProvinceOk

`func (o *CreateOrderRequestShippingAddress) GetProvinceOk() (*string, bool)`

GetProvinceOk returns a tuple with the Province field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvince

`func (o *CreateOrderRequestShippingAddress) SetProvince(v string)`

SetProvince sets Province field to given value.

### HasProvince

`func (o *CreateOrderRequestShippingAddress) HasProvince() bool`

HasProvince returns a boolean if a field has been set.

### SetProvinceNil

`func (o *CreateOrderRequestShippingAddress) SetProvinceNil(b bool)`

 SetProvinceNil sets the value for Province to be an explicit nil

### UnsetProvince
`func (o *CreateOrderRequestShippingAddress) UnsetProvince()`

UnsetProvince ensures that no value is present for Province, not even an explicit nil
### GetProvinceCode

`func (o *CreateOrderRequestShippingAddress) GetProvinceCode() string`

GetProvinceCode returns the ProvinceCode field if non-nil, zero value otherwise.

### GetProvinceCodeOk

`func (o *CreateOrderRequestShippingAddress) GetProvinceCodeOk() (*string, bool)`

GetProvinceCodeOk returns a tuple with the ProvinceCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvinceCode

`func (o *CreateOrderRequestShippingAddress) SetProvinceCode(v string)`

SetProvinceCode sets ProvinceCode field to given value.

### HasProvinceCode

`func (o *CreateOrderRequestShippingAddress) HasProvinceCode() bool`

HasProvinceCode returns a boolean if a field has been set.

### SetProvinceCodeNil

`func (o *CreateOrderRequestShippingAddress) SetProvinceCodeNil(b bool)`

 SetProvinceCodeNil sets the value for ProvinceCode to be an explicit nil

### UnsetProvinceCode
`func (o *CreateOrderRequestShippingAddress) UnsetProvinceCode()`

UnsetProvinceCode ensures that no value is present for ProvinceCode, not even an explicit nil
### GetPostalCode

`func (o *CreateOrderRequestShippingAddress) GetPostalCode() string`

GetPostalCode returns the PostalCode field if non-nil, zero value otherwise.

### GetPostalCodeOk

`func (o *CreateOrderRequestShippingAddress) GetPostalCodeOk() (*string, bool)`

GetPostalCodeOk returns a tuple with the PostalCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostalCode

`func (o *CreateOrderRequestShippingAddress) SetPostalCode(v string)`

SetPostalCode sets PostalCode field to given value.


### GetCountry

`func (o *CreateOrderRequestShippingAddress) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *CreateOrderRequestShippingAddress) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *CreateOrderRequestShippingAddress) SetCountry(v string)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *CreateOrderRequestShippingAddress) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### SetCountryNil

`func (o *CreateOrderRequestShippingAddress) SetCountryNil(b bool)`

 SetCountryNil sets the value for Country to be an explicit nil

### UnsetCountry
`func (o *CreateOrderRequestShippingAddress) UnsetCountry()`

UnsetCountry ensures that no value is present for Country, not even an explicit nil
### GetCountryCode

`func (o *CreateOrderRequestShippingAddress) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *CreateOrderRequestShippingAddress) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *CreateOrderRequestShippingAddress) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.


### GetPhone

`func (o *CreateOrderRequestShippingAddress) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *CreateOrderRequestShippingAddress) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *CreateOrderRequestShippingAddress) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *CreateOrderRequestShippingAddress) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### SetPhoneNil

`func (o *CreateOrderRequestShippingAddress) SetPhoneNil(b bool)`

 SetPhoneNil sets the value for Phone to be an explicit nil

### UnsetPhone
`func (o *CreateOrderRequestShippingAddress) UnsetPhone()`

UnsetPhone ensures that no value is present for Phone, not even an explicit nil
### GetEmail

`func (o *CreateOrderRequestShippingAddress) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *CreateOrderRequestShippingAddress) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *CreateOrderRequestShippingAddress) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *CreateOrderRequestShippingAddress) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### SetEmailNil

`func (o *CreateOrderRequestShippingAddress) SetEmailNil(b bool)`

 SetEmailNil sets the value for Email to be an explicit nil

### UnsetEmail
`func (o *CreateOrderRequestShippingAddress) UnsetEmail()`

UnsetEmail ensures that no value is present for Email, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


