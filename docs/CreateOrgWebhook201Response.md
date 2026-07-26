# CreateOrgWebhook201Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Webhook ID | 
**Name** | **string** | Human-readable webhook name | 
**Url** | **string** | Webhook endpoint URL | 
**Secret** | **string** | Signing secret used to verify webhook payloads | 
**Events** | **[]string** | Events the webhook is subscribed to | 
**IsActive** | **bool** | Whether the webhook is active | 
**CreatedAt** | **string** | Creation timestamp (ISO 8601) | 
**UpdatedAt** | **string** | Last update timestamp (ISO 8601) | 

## Methods

### NewCreateOrgWebhook201Response

`func NewCreateOrgWebhook201Response(id string, name string, url string, secret string, events []string, isActive bool, createdAt string, updatedAt string, ) *CreateOrgWebhook201Response`

NewCreateOrgWebhook201Response instantiates a new CreateOrgWebhook201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateOrgWebhook201ResponseWithDefaults

`func NewCreateOrgWebhook201ResponseWithDefaults() *CreateOrgWebhook201Response`

NewCreateOrgWebhook201ResponseWithDefaults instantiates a new CreateOrgWebhook201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreateOrgWebhook201Response) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateOrgWebhook201Response) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateOrgWebhook201Response) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *CreateOrgWebhook201Response) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateOrgWebhook201Response) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateOrgWebhook201Response) SetName(v string)`

SetName sets Name field to given value.


### GetUrl

`func (o *CreateOrgWebhook201Response) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *CreateOrgWebhook201Response) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *CreateOrgWebhook201Response) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetSecret

`func (o *CreateOrgWebhook201Response) GetSecret() string`

GetSecret returns the Secret field if non-nil, zero value otherwise.

### GetSecretOk

`func (o *CreateOrgWebhook201Response) GetSecretOk() (*string, bool)`

GetSecretOk returns a tuple with the Secret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecret

`func (o *CreateOrgWebhook201Response) SetSecret(v string)`

SetSecret sets Secret field to given value.


### GetEvents

`func (o *CreateOrgWebhook201Response) GetEvents() []string`

GetEvents returns the Events field if non-nil, zero value otherwise.

### GetEventsOk

`func (o *CreateOrgWebhook201Response) GetEventsOk() (*[]string, bool)`

GetEventsOk returns a tuple with the Events field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvents

`func (o *CreateOrgWebhook201Response) SetEvents(v []string)`

SetEvents sets Events field to given value.


### GetIsActive

`func (o *CreateOrgWebhook201Response) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *CreateOrgWebhook201Response) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *CreateOrgWebhook201Response) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.


### GetCreatedAt

`func (o *CreateOrgWebhook201Response) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CreateOrgWebhook201Response) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CreateOrgWebhook201Response) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *CreateOrgWebhook201Response) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *CreateOrgWebhook201Response) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *CreateOrgWebhook201Response) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


