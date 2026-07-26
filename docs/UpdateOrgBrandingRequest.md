# UpdateOrgBrandingRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PrimaryColor** | Pointer to **NullableString** | Primary brand color (hex) — tints the document title and table headers | [optional] 
**SecondaryColor** | Pointer to **NullableString** | Secondary brand color (hex) — tints the subtitle, section headings, and totals accent | [optional] 

## Methods

### NewUpdateOrgBrandingRequest

`func NewUpdateOrgBrandingRequest() *UpdateOrgBrandingRequest`

NewUpdateOrgBrandingRequest instantiates a new UpdateOrgBrandingRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateOrgBrandingRequestWithDefaults

`func NewUpdateOrgBrandingRequestWithDefaults() *UpdateOrgBrandingRequest`

NewUpdateOrgBrandingRequestWithDefaults instantiates a new UpdateOrgBrandingRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPrimaryColor

`func (o *UpdateOrgBrandingRequest) GetPrimaryColor() string`

GetPrimaryColor returns the PrimaryColor field if non-nil, zero value otherwise.

### GetPrimaryColorOk

`func (o *UpdateOrgBrandingRequest) GetPrimaryColorOk() (*string, bool)`

GetPrimaryColorOk returns a tuple with the PrimaryColor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryColor

`func (o *UpdateOrgBrandingRequest) SetPrimaryColor(v string)`

SetPrimaryColor sets PrimaryColor field to given value.

### HasPrimaryColor

`func (o *UpdateOrgBrandingRequest) HasPrimaryColor() bool`

HasPrimaryColor returns a boolean if a field has been set.

### SetPrimaryColorNil

`func (o *UpdateOrgBrandingRequest) SetPrimaryColorNil(b bool)`

 SetPrimaryColorNil sets the value for PrimaryColor to be an explicit nil

### UnsetPrimaryColor
`func (o *UpdateOrgBrandingRequest) UnsetPrimaryColor()`

UnsetPrimaryColor ensures that no value is present for PrimaryColor, not even an explicit nil
### GetSecondaryColor

`func (o *UpdateOrgBrandingRequest) GetSecondaryColor() string`

GetSecondaryColor returns the SecondaryColor field if non-nil, zero value otherwise.

### GetSecondaryColorOk

`func (o *UpdateOrgBrandingRequest) GetSecondaryColorOk() (*string, bool)`

GetSecondaryColorOk returns a tuple with the SecondaryColor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecondaryColor

`func (o *UpdateOrgBrandingRequest) SetSecondaryColor(v string)`

SetSecondaryColor sets SecondaryColor field to given value.

### HasSecondaryColor

`func (o *UpdateOrgBrandingRequest) HasSecondaryColor() bool`

HasSecondaryColor returns a boolean if a field has been set.

### SetSecondaryColorNil

`func (o *UpdateOrgBrandingRequest) SetSecondaryColorNil(b bool)`

 SetSecondaryColorNil sets the value for SecondaryColor to be an explicit nil

### UnsetSecondaryColor
`func (o *UpdateOrgBrandingRequest) UnsetSecondaryColor()`

UnsetSecondaryColor ensures that no value is present for SecondaryColor, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


