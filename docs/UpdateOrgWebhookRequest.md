# UpdateOrgWebhookRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | Human-readable webhook name | [optional] 
**Url** | Pointer to **string** | Webhook endpoint URL | [optional] 
**Events** | Pointer to **[]string** | Events to subscribe to | [optional] 
**IsActive** | Pointer to **bool** | Whether the webhook is active | [optional] 
**BrandId** | Pointer to **NullableString** | Brand this record is assigned to; null (or omitted outside a brand session) keeps it organization-wide | [optional] 

## Methods

### NewUpdateOrgWebhookRequest

`func NewUpdateOrgWebhookRequest() *UpdateOrgWebhookRequest`

NewUpdateOrgWebhookRequest instantiates a new UpdateOrgWebhookRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateOrgWebhookRequestWithDefaults

`func NewUpdateOrgWebhookRequestWithDefaults() *UpdateOrgWebhookRequest`

NewUpdateOrgWebhookRequestWithDefaults instantiates a new UpdateOrgWebhookRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *UpdateOrgWebhookRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateOrgWebhookRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateOrgWebhookRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *UpdateOrgWebhookRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetUrl

`func (o *UpdateOrgWebhookRequest) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *UpdateOrgWebhookRequest) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *UpdateOrgWebhookRequest) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *UpdateOrgWebhookRequest) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### GetEvents

`func (o *UpdateOrgWebhookRequest) GetEvents() []string`

GetEvents returns the Events field if non-nil, zero value otherwise.

### GetEventsOk

`func (o *UpdateOrgWebhookRequest) GetEventsOk() (*[]string, bool)`

GetEventsOk returns a tuple with the Events field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvents

`func (o *UpdateOrgWebhookRequest) SetEvents(v []string)`

SetEvents sets Events field to given value.

### HasEvents

`func (o *UpdateOrgWebhookRequest) HasEvents() bool`

HasEvents returns a boolean if a field has been set.

### GetIsActive

`func (o *UpdateOrgWebhookRequest) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *UpdateOrgWebhookRequest) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *UpdateOrgWebhookRequest) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.

### HasIsActive

`func (o *UpdateOrgWebhookRequest) HasIsActive() bool`

HasIsActive returns a boolean if a field has been set.

### GetBrandId

`func (o *UpdateOrgWebhookRequest) GetBrandId() string`

GetBrandId returns the BrandId field if non-nil, zero value otherwise.

### GetBrandIdOk

`func (o *UpdateOrgWebhookRequest) GetBrandIdOk() (*string, bool)`

GetBrandIdOk returns a tuple with the BrandId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandId

`func (o *UpdateOrgWebhookRequest) SetBrandId(v string)`

SetBrandId sets BrandId field to given value.

### HasBrandId

`func (o *UpdateOrgWebhookRequest) HasBrandId() bool`

HasBrandId returns a boolean if a field has been set.

### SetBrandIdNil

`func (o *UpdateOrgWebhookRequest) SetBrandIdNil(b bool)`

 SetBrandIdNil sets the value for BrandId to be an explicit nil

### UnsetBrandId
`func (o *UpdateOrgWebhookRequest) UnsetBrandId()`

UnsetBrandId ensures that no value is present for BrandId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


