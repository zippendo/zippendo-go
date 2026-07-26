# ListCarrierProductServicePointsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Address1** | **string** | Street address line 1 | 
**Address2** | Pointer to **NullableString** | Street address line 2 | [optional] 
**PostalCode** | **string** | Postal code | 
**State** | Pointer to **NullableString** | State or region | [optional] 
**City** | **string** | City name | 
**CountryCode** | **string** | ISO 3166-1 alpha-2 country code | 

## Methods

### NewListCarrierProductServicePointsRequest

`func NewListCarrierProductServicePointsRequest(address1 string, postalCode string, city string, countryCode string, ) *ListCarrierProductServicePointsRequest`

NewListCarrierProductServicePointsRequest instantiates a new ListCarrierProductServicePointsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListCarrierProductServicePointsRequestWithDefaults

`func NewListCarrierProductServicePointsRequestWithDefaults() *ListCarrierProductServicePointsRequest`

NewListCarrierProductServicePointsRequestWithDefaults instantiates a new ListCarrierProductServicePointsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddress1

`func (o *ListCarrierProductServicePointsRequest) GetAddress1() string`

GetAddress1 returns the Address1 field if non-nil, zero value otherwise.

### GetAddress1Ok

`func (o *ListCarrierProductServicePointsRequest) GetAddress1Ok() (*string, bool)`

GetAddress1Ok returns a tuple with the Address1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress1

`func (o *ListCarrierProductServicePointsRequest) SetAddress1(v string)`

SetAddress1 sets Address1 field to given value.


### GetAddress2

`func (o *ListCarrierProductServicePointsRequest) GetAddress2() string`

GetAddress2 returns the Address2 field if non-nil, zero value otherwise.

### GetAddress2Ok

`func (o *ListCarrierProductServicePointsRequest) GetAddress2Ok() (*string, bool)`

GetAddress2Ok returns a tuple with the Address2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress2

`func (o *ListCarrierProductServicePointsRequest) SetAddress2(v string)`

SetAddress2 sets Address2 field to given value.

### HasAddress2

`func (o *ListCarrierProductServicePointsRequest) HasAddress2() bool`

HasAddress2 returns a boolean if a field has been set.

### SetAddress2Nil

`func (o *ListCarrierProductServicePointsRequest) SetAddress2Nil(b bool)`

 SetAddress2Nil sets the value for Address2 to be an explicit nil

### UnsetAddress2
`func (o *ListCarrierProductServicePointsRequest) UnsetAddress2()`

UnsetAddress2 ensures that no value is present for Address2, not even an explicit nil
### GetPostalCode

`func (o *ListCarrierProductServicePointsRequest) GetPostalCode() string`

GetPostalCode returns the PostalCode field if non-nil, zero value otherwise.

### GetPostalCodeOk

`func (o *ListCarrierProductServicePointsRequest) GetPostalCodeOk() (*string, bool)`

GetPostalCodeOk returns a tuple with the PostalCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostalCode

`func (o *ListCarrierProductServicePointsRequest) SetPostalCode(v string)`

SetPostalCode sets PostalCode field to given value.


### GetState

`func (o *ListCarrierProductServicePointsRequest) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *ListCarrierProductServicePointsRequest) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *ListCarrierProductServicePointsRequest) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *ListCarrierProductServicePointsRequest) HasState() bool`

HasState returns a boolean if a field has been set.

### SetStateNil

`func (o *ListCarrierProductServicePointsRequest) SetStateNil(b bool)`

 SetStateNil sets the value for State to be an explicit nil

### UnsetState
`func (o *ListCarrierProductServicePointsRequest) UnsetState()`

UnsetState ensures that no value is present for State, not even an explicit nil
### GetCity

`func (o *ListCarrierProductServicePointsRequest) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *ListCarrierProductServicePointsRequest) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *ListCarrierProductServicePointsRequest) SetCity(v string)`

SetCity sets City field to given value.


### GetCountryCode

`func (o *ListCarrierProductServicePointsRequest) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *ListCarrierProductServicePointsRequest) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *ListCarrierProductServicePointsRequest) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


