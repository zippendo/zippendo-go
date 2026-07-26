# BatchSplitShipmentRequestShipmentsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Reference** | Pointer to **string** | Reference for this new shipment. Defaults to original reference with a suffix. | [optional] 
**OrderLines** | [**[]BatchSplitShipmentRequestShipmentsInnerOrderLinesInner**](BatchSplitShipmentRequestShipmentsInnerOrderLinesInner.md) | Order lines and quantities to move into this new shipment. | 

## Methods

### NewBatchSplitShipmentRequestShipmentsInner

`func NewBatchSplitShipmentRequestShipmentsInner(orderLines []BatchSplitShipmentRequestShipmentsInnerOrderLinesInner, ) *BatchSplitShipmentRequestShipmentsInner`

NewBatchSplitShipmentRequestShipmentsInner instantiates a new BatchSplitShipmentRequestShipmentsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBatchSplitShipmentRequestShipmentsInnerWithDefaults

`func NewBatchSplitShipmentRequestShipmentsInnerWithDefaults() *BatchSplitShipmentRequestShipmentsInner`

NewBatchSplitShipmentRequestShipmentsInnerWithDefaults instantiates a new BatchSplitShipmentRequestShipmentsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetReference

`func (o *BatchSplitShipmentRequestShipmentsInner) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *BatchSplitShipmentRequestShipmentsInner) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *BatchSplitShipmentRequestShipmentsInner) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *BatchSplitShipmentRequestShipmentsInner) HasReference() bool`

HasReference returns a boolean if a field has been set.

### GetOrderLines

`func (o *BatchSplitShipmentRequestShipmentsInner) GetOrderLines() []BatchSplitShipmentRequestShipmentsInnerOrderLinesInner`

GetOrderLines returns the OrderLines field if non-nil, zero value otherwise.

### GetOrderLinesOk

`func (o *BatchSplitShipmentRequestShipmentsInner) GetOrderLinesOk() (*[]BatchSplitShipmentRequestShipmentsInnerOrderLinesInner, bool)`

GetOrderLinesOk returns a tuple with the OrderLines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderLines

`func (o *BatchSplitShipmentRequestShipmentsInner) SetOrderLines(v []BatchSplitShipmentRequestShipmentsInnerOrderLinesInner)`

SetOrderLines sets OrderLines field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


