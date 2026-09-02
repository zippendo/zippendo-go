# GetOrderChannelWebhookStatus200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enabled** | **bool** | Whether webhooks are enabled for the channel. | 
**WebhookUrl** | **string** | Expected callback URL for this channel. | 
**Webhooks** | [**[]GetOrderChannelWebhookStatus200ResponseWebhooksInner**](GetOrderChannelWebhookStatus200ResponseWebhooksInner.md) | Webhooks registered for this channel&#39;s callback URL. | 

## Methods

### NewGetOrderChannelWebhookStatus200Response

`func NewGetOrderChannelWebhookStatus200Response(enabled bool, webhookUrl string, webhooks []GetOrderChannelWebhookStatus200ResponseWebhooksInner, ) *GetOrderChannelWebhookStatus200Response`

NewGetOrderChannelWebhookStatus200Response instantiates a new GetOrderChannelWebhookStatus200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetOrderChannelWebhookStatus200ResponseWithDefaults

`func NewGetOrderChannelWebhookStatus200ResponseWithDefaults() *GetOrderChannelWebhookStatus200Response`

NewGetOrderChannelWebhookStatus200ResponseWithDefaults instantiates a new GetOrderChannelWebhookStatus200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnabled

`func (o *GetOrderChannelWebhookStatus200Response) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *GetOrderChannelWebhookStatus200Response) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *GetOrderChannelWebhookStatus200Response) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetWebhookUrl

`func (o *GetOrderChannelWebhookStatus200Response) GetWebhookUrl() string`

GetWebhookUrl returns the WebhookUrl field if non-nil, zero value otherwise.

### GetWebhookUrlOk

`func (o *GetOrderChannelWebhookStatus200Response) GetWebhookUrlOk() (*string, bool)`

GetWebhookUrlOk returns a tuple with the WebhookUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebhookUrl

`func (o *GetOrderChannelWebhookStatus200Response) SetWebhookUrl(v string)`

SetWebhookUrl sets WebhookUrl field to given value.


### GetWebhooks

`func (o *GetOrderChannelWebhookStatus200Response) GetWebhooks() []GetOrderChannelWebhookStatus200ResponseWebhooksInner`

GetWebhooks returns the Webhooks field if non-nil, zero value otherwise.

### GetWebhooksOk

`func (o *GetOrderChannelWebhookStatus200Response) GetWebhooksOk() (*[]GetOrderChannelWebhookStatus200ResponseWebhooksInner, bool)`

GetWebhooksOk returns a tuple with the Webhooks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebhooks

`func (o *GetOrderChannelWebhookStatus200Response) SetWebhooks(v []GetOrderChannelWebhookStatus200ResponseWebhooksInner)`

SetWebhooks sets Webhooks field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


