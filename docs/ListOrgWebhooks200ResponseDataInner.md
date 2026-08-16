# ListOrgWebhooks200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Webhook ID | 
**Name** | **string** | Human-readable webhook name | 
**Url** | **string** | Webhook endpoint URL | 
**Events** | **[]string** | Events the webhook is subscribed to | 
**IsActive** | **bool** | Whether the webhook is active | 
**BrandId** | **NullableString** | Brand this record belongs to, or null when it is organization-wide | 
**CreatedAt** | **string** | Creation timestamp (ISO 8601) | 
**UpdatedAt** | **string** | Last update timestamp (ISO 8601) | 

## Methods

### NewListOrgWebhooks200ResponseDataInner

`func NewListOrgWebhooks200ResponseDataInner(id string, name string, url string, events []string, isActive bool, brandId NullableString, createdAt string, updatedAt string, ) *ListOrgWebhooks200ResponseDataInner`

NewListOrgWebhooks200ResponseDataInner instantiates a new ListOrgWebhooks200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListOrgWebhooks200ResponseDataInnerWithDefaults

`func NewListOrgWebhooks200ResponseDataInnerWithDefaults() *ListOrgWebhooks200ResponseDataInner`

NewListOrgWebhooks200ResponseDataInnerWithDefaults instantiates a new ListOrgWebhooks200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ListOrgWebhooks200ResponseDataInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ListOrgWebhooks200ResponseDataInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ListOrgWebhooks200ResponseDataInner) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *ListOrgWebhooks200ResponseDataInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ListOrgWebhooks200ResponseDataInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ListOrgWebhooks200ResponseDataInner) SetName(v string)`

SetName sets Name field to given value.


### GetUrl

`func (o *ListOrgWebhooks200ResponseDataInner) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *ListOrgWebhooks200ResponseDataInner) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *ListOrgWebhooks200ResponseDataInner) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetEvents

`func (o *ListOrgWebhooks200ResponseDataInner) GetEvents() []string`

GetEvents returns the Events field if non-nil, zero value otherwise.

### GetEventsOk

`func (o *ListOrgWebhooks200ResponseDataInner) GetEventsOk() (*[]string, bool)`

GetEventsOk returns a tuple with the Events field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvents

`func (o *ListOrgWebhooks200ResponseDataInner) SetEvents(v []string)`

SetEvents sets Events field to given value.


### GetIsActive

`func (o *ListOrgWebhooks200ResponseDataInner) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *ListOrgWebhooks200ResponseDataInner) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *ListOrgWebhooks200ResponseDataInner) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.


### GetBrandId

`func (o *ListOrgWebhooks200ResponseDataInner) GetBrandId() string`

GetBrandId returns the BrandId field if non-nil, zero value otherwise.

### GetBrandIdOk

`func (o *ListOrgWebhooks200ResponseDataInner) GetBrandIdOk() (*string, bool)`

GetBrandIdOk returns a tuple with the BrandId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandId

`func (o *ListOrgWebhooks200ResponseDataInner) SetBrandId(v string)`

SetBrandId sets BrandId field to given value.


### SetBrandIdNil

`func (o *ListOrgWebhooks200ResponseDataInner) SetBrandIdNil(b bool)`

 SetBrandIdNil sets the value for BrandId to be an explicit nil

### UnsetBrandId
`func (o *ListOrgWebhooks200ResponseDataInner) UnsetBrandId()`

UnsetBrandId ensures that no value is present for BrandId, not even an explicit nil
### GetCreatedAt

`func (o *ListOrgWebhooks200ResponseDataInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ListOrgWebhooks200ResponseDataInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ListOrgWebhooks200ResponseDataInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *ListOrgWebhooks200ResponseDataInner) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ListOrgWebhooks200ResponseDataInner) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ListOrgWebhooks200ResponseDataInner) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


