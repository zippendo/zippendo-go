# GetOrgBranding200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PrimaryColor** | **NullableString** | Primary brand color (hex) | 
**SecondaryColor** | **NullableString** | Secondary brand color (hex) | 
**LogoUrl** | **NullableString** | Authenticated URL to download the org logo image, or null if no logo is set | 

## Methods

### NewGetOrgBranding200Response

`func NewGetOrgBranding200Response(primaryColor NullableString, secondaryColor NullableString, logoUrl NullableString, ) *GetOrgBranding200Response`

NewGetOrgBranding200Response instantiates a new GetOrgBranding200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetOrgBranding200ResponseWithDefaults

`func NewGetOrgBranding200ResponseWithDefaults() *GetOrgBranding200Response`

NewGetOrgBranding200ResponseWithDefaults instantiates a new GetOrgBranding200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPrimaryColor

`func (o *GetOrgBranding200Response) GetPrimaryColor() string`

GetPrimaryColor returns the PrimaryColor field if non-nil, zero value otherwise.

### GetPrimaryColorOk

`func (o *GetOrgBranding200Response) GetPrimaryColorOk() (*string, bool)`

GetPrimaryColorOk returns a tuple with the PrimaryColor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryColor

`func (o *GetOrgBranding200Response) SetPrimaryColor(v string)`

SetPrimaryColor sets PrimaryColor field to given value.


### SetPrimaryColorNil

`func (o *GetOrgBranding200Response) SetPrimaryColorNil(b bool)`

 SetPrimaryColorNil sets the value for PrimaryColor to be an explicit nil

### UnsetPrimaryColor
`func (o *GetOrgBranding200Response) UnsetPrimaryColor()`

UnsetPrimaryColor ensures that no value is present for PrimaryColor, not even an explicit nil
### GetSecondaryColor

`func (o *GetOrgBranding200Response) GetSecondaryColor() string`

GetSecondaryColor returns the SecondaryColor field if non-nil, zero value otherwise.

### GetSecondaryColorOk

`func (o *GetOrgBranding200Response) GetSecondaryColorOk() (*string, bool)`

GetSecondaryColorOk returns a tuple with the SecondaryColor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecondaryColor

`func (o *GetOrgBranding200Response) SetSecondaryColor(v string)`

SetSecondaryColor sets SecondaryColor field to given value.


### SetSecondaryColorNil

`func (o *GetOrgBranding200Response) SetSecondaryColorNil(b bool)`

 SetSecondaryColorNil sets the value for SecondaryColor to be an explicit nil

### UnsetSecondaryColor
`func (o *GetOrgBranding200Response) UnsetSecondaryColor()`

UnsetSecondaryColor ensures that no value is present for SecondaryColor, not even an explicit nil
### GetLogoUrl

`func (o *GetOrgBranding200Response) GetLogoUrl() string`

GetLogoUrl returns the LogoUrl field if non-nil, zero value otherwise.

### GetLogoUrlOk

`func (o *GetOrgBranding200Response) GetLogoUrlOk() (*string, bool)`

GetLogoUrlOk returns a tuple with the LogoUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogoUrl

`func (o *GetOrgBranding200Response) SetLogoUrl(v string)`

SetLogoUrl sets LogoUrl field to given value.


### SetLogoUrlNil

`func (o *GetOrgBranding200Response) SetLogoUrlNil(b bool)`

 SetLogoUrlNil sets the value for LogoUrl to be an explicit nil

### UnsetLogoUrl
`func (o *GetOrgBranding200Response) UnsetLogoUrl()`

UnsetLogoUrl ensures that no value is present for LogoUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


