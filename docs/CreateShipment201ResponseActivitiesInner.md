# CreateShipment201ResponseActivitiesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Unique activity identifier. | 
**Action** | **string** | Type of activity performed on the shipment. | 
**Description** | **string** | Human-readable description of the activity. | 
**Metadata** | Pointer to **interface{}** | Additional structured data about the activity. | [optional] 
**CreatedAt** | **string** | Timestamp when the activity occurred. | 

## Methods

### NewCreateShipment201ResponseActivitiesInner

`func NewCreateShipment201ResponseActivitiesInner(id string, action string, description string, createdAt string, ) *CreateShipment201ResponseActivitiesInner`

NewCreateShipment201ResponseActivitiesInner instantiates a new CreateShipment201ResponseActivitiesInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateShipment201ResponseActivitiesInnerWithDefaults

`func NewCreateShipment201ResponseActivitiesInnerWithDefaults() *CreateShipment201ResponseActivitiesInner`

NewCreateShipment201ResponseActivitiesInnerWithDefaults instantiates a new CreateShipment201ResponseActivitiesInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreateShipment201ResponseActivitiesInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateShipment201ResponseActivitiesInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateShipment201ResponseActivitiesInner) SetId(v string)`

SetId sets Id field to given value.


### GetAction

`func (o *CreateShipment201ResponseActivitiesInner) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *CreateShipment201ResponseActivitiesInner) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *CreateShipment201ResponseActivitiesInner) SetAction(v string)`

SetAction sets Action field to given value.


### GetDescription

`func (o *CreateShipment201ResponseActivitiesInner) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateShipment201ResponseActivitiesInner) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateShipment201ResponseActivitiesInner) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetMetadata

`func (o *CreateShipment201ResponseActivitiesInner) GetMetadata() interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *CreateShipment201ResponseActivitiesInner) GetMetadataOk() (*interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *CreateShipment201ResponseActivitiesInner) SetMetadata(v interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *CreateShipment201ResponseActivitiesInner) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *CreateShipment201ResponseActivitiesInner) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *CreateShipment201ResponseActivitiesInner) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetCreatedAt

`func (o *CreateShipment201ResponseActivitiesInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CreateShipment201ResponseActivitiesInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CreateShipment201ResponseActivitiesInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


