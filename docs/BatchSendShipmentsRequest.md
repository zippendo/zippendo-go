# BatchSendShipmentsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ShipmentIds** | **[]string** | IDs of the shipments to book. Each must be in &#x60;pending&#x60; or &#x60;error&#x60; status; duplicates are ignored. Max 100 per request. | 

## Methods

### NewBatchSendShipmentsRequest

`func NewBatchSendShipmentsRequest(shipmentIds []string, ) *BatchSendShipmentsRequest`

NewBatchSendShipmentsRequest instantiates a new BatchSendShipmentsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBatchSendShipmentsRequestWithDefaults

`func NewBatchSendShipmentsRequestWithDefaults() *BatchSendShipmentsRequest`

NewBatchSendShipmentsRequestWithDefaults instantiates a new BatchSendShipmentsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetShipmentIds

`func (o *BatchSendShipmentsRequest) GetShipmentIds() []string`

GetShipmentIds returns the ShipmentIds field if non-nil, zero value otherwise.

### GetShipmentIdsOk

`func (o *BatchSendShipmentsRequest) GetShipmentIdsOk() (*[]string, bool)`

GetShipmentIdsOk returns a tuple with the ShipmentIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipmentIds

`func (o *BatchSendShipmentsRequest) SetShipmentIds(v []string)`

SetShipmentIds sets ShipmentIds field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


