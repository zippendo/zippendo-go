# CreateOrderChannelWebhookSecret201Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Secret** | **string** | The webhook signing secret. Returned only once — store it in your system; every push to the ingest URL must carry an HMAC-SHA256 hex signature of the raw body computed with it. | 
**WebhookUrl** | **string** | The ingest URL your system pushes signed order events to. | 
**CreatedAt** | **time.Time** | When this secret was issued (ISO 8601). | 

## Methods

### NewCreateOrderChannelWebhookSecret201Response

`func NewCreateOrderChannelWebhookSecret201Response(secret string, webhookUrl string, createdAt time.Time, ) *CreateOrderChannelWebhookSecret201Response`

NewCreateOrderChannelWebhookSecret201Response instantiates a new CreateOrderChannelWebhookSecret201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateOrderChannelWebhookSecret201ResponseWithDefaults

`func NewCreateOrderChannelWebhookSecret201ResponseWithDefaults() *CreateOrderChannelWebhookSecret201Response`

NewCreateOrderChannelWebhookSecret201ResponseWithDefaults instantiates a new CreateOrderChannelWebhookSecret201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSecret

`func (o *CreateOrderChannelWebhookSecret201Response) GetSecret() string`

GetSecret returns the Secret field if non-nil, zero value otherwise.

### GetSecretOk

`func (o *CreateOrderChannelWebhookSecret201Response) GetSecretOk() (*string, bool)`

GetSecretOk returns a tuple with the Secret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecret

`func (o *CreateOrderChannelWebhookSecret201Response) SetSecret(v string)`

SetSecret sets Secret field to given value.


### GetWebhookUrl

`func (o *CreateOrderChannelWebhookSecret201Response) GetWebhookUrl() string`

GetWebhookUrl returns the WebhookUrl field if non-nil, zero value otherwise.

### GetWebhookUrlOk

`func (o *CreateOrderChannelWebhookSecret201Response) GetWebhookUrlOk() (*string, bool)`

GetWebhookUrlOk returns a tuple with the WebhookUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebhookUrl

`func (o *CreateOrderChannelWebhookSecret201Response) SetWebhookUrl(v string)`

SetWebhookUrl sets WebhookUrl field to given value.


### GetCreatedAt

`func (o *CreateOrderChannelWebhookSecret201Response) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CreateOrderChannelWebhookSecret201Response) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CreateOrderChannelWebhookSecret201Response) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


