# BatchSplitShipment201Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OriginalShipment** | [**CreateShipment201Response**](CreateShipment201Response.md) |  | 
**NewShipments** | [**[]CreateShipment201Response**](CreateShipment201Response.md) | Newly created shipments resulting from the split. | 

## Methods

### NewBatchSplitShipment201Response

`func NewBatchSplitShipment201Response(originalShipment CreateShipment201Response, newShipments []CreateShipment201Response, ) *BatchSplitShipment201Response`

NewBatchSplitShipment201Response instantiates a new BatchSplitShipment201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBatchSplitShipment201ResponseWithDefaults

`func NewBatchSplitShipment201ResponseWithDefaults() *BatchSplitShipment201Response`

NewBatchSplitShipment201ResponseWithDefaults instantiates a new BatchSplitShipment201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOriginalShipment

`func (o *BatchSplitShipment201Response) GetOriginalShipment() CreateShipment201Response`

GetOriginalShipment returns the OriginalShipment field if non-nil, zero value otherwise.

### GetOriginalShipmentOk

`func (o *BatchSplitShipment201Response) GetOriginalShipmentOk() (*CreateShipment201Response, bool)`

GetOriginalShipmentOk returns a tuple with the OriginalShipment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalShipment

`func (o *BatchSplitShipment201Response) SetOriginalShipment(v CreateShipment201Response)`

SetOriginalShipment sets OriginalShipment field to given value.


### GetNewShipments

`func (o *BatchSplitShipment201Response) GetNewShipments() []CreateShipment201Response`

GetNewShipments returns the NewShipments field if non-nil, zero value otherwise.

### GetNewShipmentsOk

`func (o *BatchSplitShipment201Response) GetNewShipmentsOk() (*[]CreateShipment201Response, bool)`

GetNewShipmentsOk returns a tuple with the NewShipments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewShipments

`func (o *BatchSplitShipment201Response) SetNewShipments(v []CreateShipment201Response)`

SetNewShipments sets NewShipments field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


