# GetOrder200ResponseShipmentsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Unique shipment identifier. | 
**Reference** | **string** | Customer-facing shipment reference. | 
**Status** | **string** | Lifecycle status of the shipment. | 
**Type** | **string** | Direction of the shipment relative to the organization. | 
**Tracking** | Pointer to [**NullableCreateShipment201ResponseTracking**](CreateShipment201ResponseTracking.md) |  | [optional] 
**CarrierSettings** | [**ListShipments200ResponseDataInnerCarrierSettings**](ListShipments200ResponseDataInnerCarrierSettings.md) |  | 
**ServicePointId** | Pointer to **NullableString** | Selected carrier service point identifier. | [optional] 
**CreatedAt** | **string** | Timestamp when the shipment was created. | 
**UpdatedAt** | **string** | Timestamp when the shipment was last updated. | 
**ShippingRuleId** | Pointer to **NullableString** | ID of the shipping rule used for this shipment. | [optional] 
**Documents** | Pointer to [**[]CreateShipment201ResponseDocumentsInner**](CreateShipment201ResponseDocumentsInner.md) | Documents (labels, customs forms) for this shipment. | [optional] 

## Methods

### NewGetOrder200ResponseShipmentsInner

`func NewGetOrder200ResponseShipmentsInner(id string, reference string, status string, type_ string, carrierSettings ListShipments200ResponseDataInnerCarrierSettings, createdAt string, updatedAt string, ) *GetOrder200ResponseShipmentsInner`

NewGetOrder200ResponseShipmentsInner instantiates a new GetOrder200ResponseShipmentsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetOrder200ResponseShipmentsInnerWithDefaults

`func NewGetOrder200ResponseShipmentsInnerWithDefaults() *GetOrder200ResponseShipmentsInner`

NewGetOrder200ResponseShipmentsInnerWithDefaults instantiates a new GetOrder200ResponseShipmentsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GetOrder200ResponseShipmentsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GetOrder200ResponseShipmentsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GetOrder200ResponseShipmentsInner) SetId(v string)`

SetId sets Id field to given value.


### GetReference

`func (o *GetOrder200ResponseShipmentsInner) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *GetOrder200ResponseShipmentsInner) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *GetOrder200ResponseShipmentsInner) SetReference(v string)`

SetReference sets Reference field to given value.


### GetStatus

`func (o *GetOrder200ResponseShipmentsInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *GetOrder200ResponseShipmentsInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *GetOrder200ResponseShipmentsInner) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetType

`func (o *GetOrder200ResponseShipmentsInner) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *GetOrder200ResponseShipmentsInner) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *GetOrder200ResponseShipmentsInner) SetType(v string)`

SetType sets Type field to given value.


### GetTracking

`func (o *GetOrder200ResponseShipmentsInner) GetTracking() CreateShipment201ResponseTracking`

GetTracking returns the Tracking field if non-nil, zero value otherwise.

### GetTrackingOk

`func (o *GetOrder200ResponseShipmentsInner) GetTrackingOk() (*CreateShipment201ResponseTracking, bool)`

GetTrackingOk returns a tuple with the Tracking field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTracking

`func (o *GetOrder200ResponseShipmentsInner) SetTracking(v CreateShipment201ResponseTracking)`

SetTracking sets Tracking field to given value.

### HasTracking

`func (o *GetOrder200ResponseShipmentsInner) HasTracking() bool`

HasTracking returns a boolean if a field has been set.

### SetTrackingNil

`func (o *GetOrder200ResponseShipmentsInner) SetTrackingNil(b bool)`

 SetTrackingNil sets the value for Tracking to be an explicit nil

### UnsetTracking
`func (o *GetOrder200ResponseShipmentsInner) UnsetTracking()`

UnsetTracking ensures that no value is present for Tracking, not even an explicit nil
### GetCarrierSettings

`func (o *GetOrder200ResponseShipmentsInner) GetCarrierSettings() ListShipments200ResponseDataInnerCarrierSettings`

GetCarrierSettings returns the CarrierSettings field if non-nil, zero value otherwise.

### GetCarrierSettingsOk

`func (o *GetOrder200ResponseShipmentsInner) GetCarrierSettingsOk() (*ListShipments200ResponseDataInnerCarrierSettings, bool)`

GetCarrierSettingsOk returns a tuple with the CarrierSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierSettings

`func (o *GetOrder200ResponseShipmentsInner) SetCarrierSettings(v ListShipments200ResponseDataInnerCarrierSettings)`

SetCarrierSettings sets CarrierSettings field to given value.


### GetServicePointId

`func (o *GetOrder200ResponseShipmentsInner) GetServicePointId() string`

GetServicePointId returns the ServicePointId field if non-nil, zero value otherwise.

### GetServicePointIdOk

`func (o *GetOrder200ResponseShipmentsInner) GetServicePointIdOk() (*string, bool)`

GetServicePointIdOk returns a tuple with the ServicePointId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServicePointId

`func (o *GetOrder200ResponseShipmentsInner) SetServicePointId(v string)`

SetServicePointId sets ServicePointId field to given value.

### HasServicePointId

`func (o *GetOrder200ResponseShipmentsInner) HasServicePointId() bool`

HasServicePointId returns a boolean if a field has been set.

### SetServicePointIdNil

`func (o *GetOrder200ResponseShipmentsInner) SetServicePointIdNil(b bool)`

 SetServicePointIdNil sets the value for ServicePointId to be an explicit nil

### UnsetServicePointId
`func (o *GetOrder200ResponseShipmentsInner) UnsetServicePointId()`

UnsetServicePointId ensures that no value is present for ServicePointId, not even an explicit nil
### GetCreatedAt

`func (o *GetOrder200ResponseShipmentsInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GetOrder200ResponseShipmentsInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GetOrder200ResponseShipmentsInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *GetOrder200ResponseShipmentsInner) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *GetOrder200ResponseShipmentsInner) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *GetOrder200ResponseShipmentsInner) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetShippingRuleId

`func (o *GetOrder200ResponseShipmentsInner) GetShippingRuleId() string`

GetShippingRuleId returns the ShippingRuleId field if non-nil, zero value otherwise.

### GetShippingRuleIdOk

`func (o *GetOrder200ResponseShipmentsInner) GetShippingRuleIdOk() (*string, bool)`

GetShippingRuleIdOk returns a tuple with the ShippingRuleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingRuleId

`func (o *GetOrder200ResponseShipmentsInner) SetShippingRuleId(v string)`

SetShippingRuleId sets ShippingRuleId field to given value.

### HasShippingRuleId

`func (o *GetOrder200ResponseShipmentsInner) HasShippingRuleId() bool`

HasShippingRuleId returns a boolean if a field has been set.

### SetShippingRuleIdNil

`func (o *GetOrder200ResponseShipmentsInner) SetShippingRuleIdNil(b bool)`

 SetShippingRuleIdNil sets the value for ShippingRuleId to be an explicit nil

### UnsetShippingRuleId
`func (o *GetOrder200ResponseShipmentsInner) UnsetShippingRuleId()`

UnsetShippingRuleId ensures that no value is present for ShippingRuleId, not even an explicit nil
### GetDocuments

`func (o *GetOrder200ResponseShipmentsInner) GetDocuments() []CreateShipment201ResponseDocumentsInner`

GetDocuments returns the Documents field if non-nil, zero value otherwise.

### GetDocumentsOk

`func (o *GetOrder200ResponseShipmentsInner) GetDocumentsOk() (*[]CreateShipment201ResponseDocumentsInner, bool)`

GetDocumentsOk returns a tuple with the Documents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocuments

`func (o *GetOrder200ResponseShipmentsInner) SetDocuments(v []CreateShipment201ResponseDocumentsInner)`

SetDocuments sets Documents field to given value.

### HasDocuments

`func (o *GetOrder200ResponseShipmentsInner) HasDocuments() bool`

HasDocuments returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


