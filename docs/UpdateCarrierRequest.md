# UpdateCarrierRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | Carrier display name | [optional] 
**CarrierSlug** | Pointer to **string** | Carrier slug identifier | [optional] 
**Config** | Pointer to [**map[string]ListCarriers200ResponseDataInnerConfigValue**](ListCarriers200ResponseDataInnerConfigValue.md) | Carrier configuration (required and optional fields) | [optional] 

## Methods

### NewUpdateCarrierRequest

`func NewUpdateCarrierRequest() *UpdateCarrierRequest`

NewUpdateCarrierRequest instantiates a new UpdateCarrierRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateCarrierRequestWithDefaults

`func NewUpdateCarrierRequestWithDefaults() *UpdateCarrierRequest`

NewUpdateCarrierRequestWithDefaults instantiates a new UpdateCarrierRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *UpdateCarrierRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateCarrierRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateCarrierRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *UpdateCarrierRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetCarrierSlug

`func (o *UpdateCarrierRequest) GetCarrierSlug() string`

GetCarrierSlug returns the CarrierSlug field if non-nil, zero value otherwise.

### GetCarrierSlugOk

`func (o *UpdateCarrierRequest) GetCarrierSlugOk() (*string, bool)`

GetCarrierSlugOk returns a tuple with the CarrierSlug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierSlug

`func (o *UpdateCarrierRequest) SetCarrierSlug(v string)`

SetCarrierSlug sets CarrierSlug field to given value.

### HasCarrierSlug

`func (o *UpdateCarrierRequest) HasCarrierSlug() bool`

HasCarrierSlug returns a boolean if a field has been set.

### GetConfig

`func (o *UpdateCarrierRequest) GetConfig() map[string]ListCarriers200ResponseDataInnerConfigValue`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *UpdateCarrierRequest) GetConfigOk() (*map[string]ListCarriers200ResponseDataInnerConfigValue, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *UpdateCarrierRequest) SetConfig(v map[string]ListCarriers200ResponseDataInnerConfigValue)`

SetConfig sets Config field to given value.

### HasConfig

`func (o *UpdateCarrierRequest) HasConfig() bool`

HasConfig returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


