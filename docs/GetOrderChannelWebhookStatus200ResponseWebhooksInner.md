# GetOrderChannelWebhookStatus200ResponseWebhooksInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **float32** | Platform webhook ID. | 
**Topic** | **string** | Webhook event topic. | 
**Address** | **string** | Registered callback address. | 
**CreatedAt** | **string** | Webhook creation timestamp. | 
**DeliveryUrl** | Pointer to **string** | WooCommerce delivery URL (same as &#x60;address&#x60;; present for WooCommerce channels). | [optional] 
**Status** | Pointer to **string** | WooCommerce webhook status. A value other than &#x60;active&#x60; means WooCommerce disabled the webhook (e.g. after repeated delivery failures). | [optional] 

## Methods

### NewGetOrderChannelWebhookStatus200ResponseWebhooksInner

`func NewGetOrderChannelWebhookStatus200ResponseWebhooksInner(id float32, topic string, address string, createdAt string, ) *GetOrderChannelWebhookStatus200ResponseWebhooksInner`

NewGetOrderChannelWebhookStatus200ResponseWebhooksInner instantiates a new GetOrderChannelWebhookStatus200ResponseWebhooksInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetOrderChannelWebhookStatus200ResponseWebhooksInnerWithDefaults

`func NewGetOrderChannelWebhookStatus200ResponseWebhooksInnerWithDefaults() *GetOrderChannelWebhookStatus200ResponseWebhooksInner`

NewGetOrderChannelWebhookStatus200ResponseWebhooksInnerWithDefaults instantiates a new GetOrderChannelWebhookStatus200ResponseWebhooksInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GetOrderChannelWebhookStatus200ResponseWebhooksInner) GetId() float32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GetOrderChannelWebhookStatus200ResponseWebhooksInner) GetIdOk() (*float32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GetOrderChannelWebhookStatus200ResponseWebhooksInner) SetId(v float32)`

SetId sets Id field to given value.


### GetTopic

`func (o *GetOrderChannelWebhookStatus200ResponseWebhooksInner) GetTopic() string`

GetTopic returns the Topic field if non-nil, zero value otherwise.

### GetTopicOk

`func (o *GetOrderChannelWebhookStatus200ResponseWebhooksInner) GetTopicOk() (*string, bool)`

GetTopicOk returns a tuple with the Topic field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopic

`func (o *GetOrderChannelWebhookStatus200ResponseWebhooksInner) SetTopic(v string)`

SetTopic sets Topic field to given value.


### GetAddress

`func (o *GetOrderChannelWebhookStatus200ResponseWebhooksInner) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *GetOrderChannelWebhookStatus200ResponseWebhooksInner) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *GetOrderChannelWebhookStatus200ResponseWebhooksInner) SetAddress(v string)`

SetAddress sets Address field to given value.


### GetCreatedAt

`func (o *GetOrderChannelWebhookStatus200ResponseWebhooksInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GetOrderChannelWebhookStatus200ResponseWebhooksInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GetOrderChannelWebhookStatus200ResponseWebhooksInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetDeliveryUrl

`func (o *GetOrderChannelWebhookStatus200ResponseWebhooksInner) GetDeliveryUrl() string`

GetDeliveryUrl returns the DeliveryUrl field if non-nil, zero value otherwise.

### GetDeliveryUrlOk

`func (o *GetOrderChannelWebhookStatus200ResponseWebhooksInner) GetDeliveryUrlOk() (*string, bool)`

GetDeliveryUrlOk returns a tuple with the DeliveryUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveryUrl

`func (o *GetOrderChannelWebhookStatus200ResponseWebhooksInner) SetDeliveryUrl(v string)`

SetDeliveryUrl sets DeliveryUrl field to given value.

### HasDeliveryUrl

`func (o *GetOrderChannelWebhookStatus200ResponseWebhooksInner) HasDeliveryUrl() bool`

HasDeliveryUrl returns a boolean if a field has been set.

### GetStatus

`func (o *GetOrderChannelWebhookStatus200ResponseWebhooksInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *GetOrderChannelWebhookStatus200ResponseWebhooksInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *GetOrderChannelWebhookStatus200ResponseWebhooksInner) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *GetOrderChannelWebhookStatus200ResponseWebhooksInner) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


