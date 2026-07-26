# ConnectCarrierRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | Carrier display name | 
**CarrierSlug** | **string** | Carrier slug identifier | 
**Config** | [**map[string]ListCarriers200ResponseDataInnerConfigValue**](ListCarriers200ResponseDataInnerConfigValue.md) | Carrier configuration (required and optional fields) | 

## Methods

### NewConnectCarrierRequest

`func NewConnectCarrierRequest(name string, carrierSlug string, config map[string]ListCarriers200ResponseDataInnerConfigValue, ) *ConnectCarrierRequest`

NewConnectCarrierRequest instantiates a new ConnectCarrierRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConnectCarrierRequestWithDefaults

`func NewConnectCarrierRequestWithDefaults() *ConnectCarrierRequest`

NewConnectCarrierRequestWithDefaults instantiates a new ConnectCarrierRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *ConnectCarrierRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ConnectCarrierRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ConnectCarrierRequest) SetName(v string)`

SetName sets Name field to given value.


### GetCarrierSlug

`func (o *ConnectCarrierRequest) GetCarrierSlug() string`

GetCarrierSlug returns the CarrierSlug field if non-nil, zero value otherwise.

### GetCarrierSlugOk

`func (o *ConnectCarrierRequest) GetCarrierSlugOk() (*string, bool)`

GetCarrierSlugOk returns a tuple with the CarrierSlug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierSlug

`func (o *ConnectCarrierRequest) SetCarrierSlug(v string)`

SetCarrierSlug sets CarrierSlug field to given value.


### GetConfig

`func (o *ConnectCarrierRequest) GetConfig() map[string]ListCarriers200ResponseDataInnerConfigValue`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *ConnectCarrierRequest) GetConfigOk() (*map[string]ListCarriers200ResponseDataInnerConfigValue, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *ConnectCarrierRequest) SetConfig(v map[string]ListCarriers200ResponseDataInnerConfigValue)`

SetConfig sets Config field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


