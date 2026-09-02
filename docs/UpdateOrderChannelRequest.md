# UpdateOrderChannelRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BrandId** | Pointer to **NullableString** | Brand this channel belongs to; null for organization-wide | [optional] 
**Name** | Pointer to **string** | Display name for the channel. | [optional] 
**Enabled** | Pointer to **bool** | Whether the channel is active. | [optional] 
**Credentials** | Pointer to **map[string]interface{}** | Type-specific platform credentials. | [optional] 
**Settings** | Pointer to [**UpdateOrderChannelRequestSettings**](UpdateOrderChannelRequestSettings.md) |  | [optional] 
**ShippingRuleIds** | Pointer to **[]string** | IDs of shipping rules linked to this channel. | [optional] 

## Methods

### NewUpdateOrderChannelRequest

`func NewUpdateOrderChannelRequest() *UpdateOrderChannelRequest`

NewUpdateOrderChannelRequest instantiates a new UpdateOrderChannelRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateOrderChannelRequestWithDefaults

`func NewUpdateOrderChannelRequestWithDefaults() *UpdateOrderChannelRequest`

NewUpdateOrderChannelRequestWithDefaults instantiates a new UpdateOrderChannelRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBrandId

`func (o *UpdateOrderChannelRequest) GetBrandId() string`

GetBrandId returns the BrandId field if non-nil, zero value otherwise.

### GetBrandIdOk

`func (o *UpdateOrderChannelRequest) GetBrandIdOk() (*string, bool)`

GetBrandIdOk returns a tuple with the BrandId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandId

`func (o *UpdateOrderChannelRequest) SetBrandId(v string)`

SetBrandId sets BrandId field to given value.

### HasBrandId

`func (o *UpdateOrderChannelRequest) HasBrandId() bool`

HasBrandId returns a boolean if a field has been set.

### SetBrandIdNil

`func (o *UpdateOrderChannelRequest) SetBrandIdNil(b bool)`

 SetBrandIdNil sets the value for BrandId to be an explicit nil

### UnsetBrandId
`func (o *UpdateOrderChannelRequest) UnsetBrandId()`

UnsetBrandId ensures that no value is present for BrandId, not even an explicit nil
### GetName

`func (o *UpdateOrderChannelRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateOrderChannelRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateOrderChannelRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *UpdateOrderChannelRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetEnabled

`func (o *UpdateOrderChannelRequest) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *UpdateOrderChannelRequest) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *UpdateOrderChannelRequest) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *UpdateOrderChannelRequest) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetCredentials

`func (o *UpdateOrderChannelRequest) GetCredentials() map[string]interface{}`

GetCredentials returns the Credentials field if non-nil, zero value otherwise.

### GetCredentialsOk

`func (o *UpdateOrderChannelRequest) GetCredentialsOk() (*map[string]interface{}, bool)`

GetCredentialsOk returns a tuple with the Credentials field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCredentials

`func (o *UpdateOrderChannelRequest) SetCredentials(v map[string]interface{})`

SetCredentials sets Credentials field to given value.

### HasCredentials

`func (o *UpdateOrderChannelRequest) HasCredentials() bool`

HasCredentials returns a boolean if a field has been set.

### SetCredentialsNil

`func (o *UpdateOrderChannelRequest) SetCredentialsNil(b bool)`

 SetCredentialsNil sets the value for Credentials to be an explicit nil

### UnsetCredentials
`func (o *UpdateOrderChannelRequest) UnsetCredentials()`

UnsetCredentials ensures that no value is present for Credentials, not even an explicit nil
### GetSettings

`func (o *UpdateOrderChannelRequest) GetSettings() UpdateOrderChannelRequestSettings`

GetSettings returns the Settings field if non-nil, zero value otherwise.

### GetSettingsOk

`func (o *UpdateOrderChannelRequest) GetSettingsOk() (*UpdateOrderChannelRequestSettings, bool)`

GetSettingsOk returns a tuple with the Settings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettings

`func (o *UpdateOrderChannelRequest) SetSettings(v UpdateOrderChannelRequestSettings)`

SetSettings sets Settings field to given value.

### HasSettings

`func (o *UpdateOrderChannelRequest) HasSettings() bool`

HasSettings returns a boolean if a field has been set.

### GetShippingRuleIds

`func (o *UpdateOrderChannelRequest) GetShippingRuleIds() []string`

GetShippingRuleIds returns the ShippingRuleIds field if non-nil, zero value otherwise.

### GetShippingRuleIdsOk

`func (o *UpdateOrderChannelRequest) GetShippingRuleIdsOk() (*[]string, bool)`

GetShippingRuleIdsOk returns a tuple with the ShippingRuleIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingRuleIds

`func (o *UpdateOrderChannelRequest) SetShippingRuleIds(v []string)`

SetShippingRuleIds sets ShippingRuleIds field to given value.

### HasShippingRuleIds

`func (o *UpdateOrderChannelRequest) HasShippingRuleIds() bool`

HasShippingRuleIds returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


