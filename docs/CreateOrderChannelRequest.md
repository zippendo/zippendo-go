# CreateOrderChannelRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | Display name for the channel. | 
**Type** | **string** | Type of the order channel. Platform channels (Shopify, WooCommerce) are created via their connect flows. | 
**BrandId** | Pointer to **NullableString** | Brand this channel belongs to; null for organization-wide | [optional] 
**Enabled** | Pointer to **bool** | Whether the channel is active. | [optional] [default to true]
**Settings** | Pointer to [**CreateOrderChannelRequestSettings**](CreateOrderChannelRequestSettings.md) |  | [optional] [default to {"useWebhooks":true,"autoSync":false,"syncIntervalMinutes":15,"autoShipOnCreate":false,"syncOnlyUnfulfilled":true,"servicePointCount":6}]

## Methods

### NewCreateOrderChannelRequest

`func NewCreateOrderChannelRequest(name string, type_ string, ) *CreateOrderChannelRequest`

NewCreateOrderChannelRequest instantiates a new CreateOrderChannelRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateOrderChannelRequestWithDefaults

`func NewCreateOrderChannelRequestWithDefaults() *CreateOrderChannelRequest`

NewCreateOrderChannelRequestWithDefaults instantiates a new CreateOrderChannelRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateOrderChannelRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateOrderChannelRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateOrderChannelRequest) SetName(v string)`

SetName sets Name field to given value.


### GetType

`func (o *CreateOrderChannelRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CreateOrderChannelRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CreateOrderChannelRequest) SetType(v string)`

SetType sets Type field to given value.


### GetBrandId

`func (o *CreateOrderChannelRequest) GetBrandId() string`

GetBrandId returns the BrandId field if non-nil, zero value otherwise.

### GetBrandIdOk

`func (o *CreateOrderChannelRequest) GetBrandIdOk() (*string, bool)`

GetBrandIdOk returns a tuple with the BrandId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandId

`func (o *CreateOrderChannelRequest) SetBrandId(v string)`

SetBrandId sets BrandId field to given value.

### HasBrandId

`func (o *CreateOrderChannelRequest) HasBrandId() bool`

HasBrandId returns a boolean if a field has been set.

### SetBrandIdNil

`func (o *CreateOrderChannelRequest) SetBrandIdNil(b bool)`

 SetBrandIdNil sets the value for BrandId to be an explicit nil

### UnsetBrandId
`func (o *CreateOrderChannelRequest) UnsetBrandId()`

UnsetBrandId ensures that no value is present for BrandId, not even an explicit nil
### GetEnabled

`func (o *CreateOrderChannelRequest) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *CreateOrderChannelRequest) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *CreateOrderChannelRequest) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *CreateOrderChannelRequest) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetSettings

`func (o *CreateOrderChannelRequest) GetSettings() CreateOrderChannelRequestSettings`

GetSettings returns the Settings field if non-nil, zero value otherwise.

### GetSettingsOk

`func (o *CreateOrderChannelRequest) GetSettingsOk() (*CreateOrderChannelRequestSettings, bool)`

GetSettingsOk returns a tuple with the Settings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettings

`func (o *CreateOrderChannelRequest) SetSettings(v CreateOrderChannelRequestSettings)`

SetSettings sets Settings field to given value.

### HasSettings

`func (o *CreateOrderChannelRequest) HasSettings() bool`

HasSettings returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


