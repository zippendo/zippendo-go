# BatchSendShipments200ResponseResultsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ShipmentId** | **string** | The shipment this result refers to. | 
**Status** | **string** | &#x60;sent&#x60; when the carrier booked it, &#x60;failed&#x60; when the carrier or Zippendo rejected it, and &#x60;skipped&#x60; when the batch ran out of time before reaching it. A &#x60;skipped&#x60; shipment was never sent to the carrier and is safe to submit again. | 
**Code** | Pointer to **string** | Canonical machine-readable error code, present when &#x60;status&#x60; is &#x60;failed&#x60; or &#x60;skipped&#x60;. | [optional] 
**Message** | Pointer to **string** | Human-readable detail, present when &#x60;status&#x60; is &#x60;failed&#x60; or &#x60;skipped&#x60;. | [optional] 
**Errors** | Pointer to [**[]SendShipment422ResponseErrorsInner**](SendShipment422ResponseErrorsInner.md) | Carrier-specific errors, present when the carrier rejected the booking. | [optional] 

## Methods

### NewBatchSendShipments200ResponseResultsInner

`func NewBatchSendShipments200ResponseResultsInner(shipmentId string, status string, ) *BatchSendShipments200ResponseResultsInner`

NewBatchSendShipments200ResponseResultsInner instantiates a new BatchSendShipments200ResponseResultsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBatchSendShipments200ResponseResultsInnerWithDefaults

`func NewBatchSendShipments200ResponseResultsInnerWithDefaults() *BatchSendShipments200ResponseResultsInner`

NewBatchSendShipments200ResponseResultsInnerWithDefaults instantiates a new BatchSendShipments200ResponseResultsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetShipmentId

`func (o *BatchSendShipments200ResponseResultsInner) GetShipmentId() string`

GetShipmentId returns the ShipmentId field if non-nil, zero value otherwise.

### GetShipmentIdOk

`func (o *BatchSendShipments200ResponseResultsInner) GetShipmentIdOk() (*string, bool)`

GetShipmentIdOk returns a tuple with the ShipmentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipmentId

`func (o *BatchSendShipments200ResponseResultsInner) SetShipmentId(v string)`

SetShipmentId sets ShipmentId field to given value.


### GetStatus

`func (o *BatchSendShipments200ResponseResultsInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *BatchSendShipments200ResponseResultsInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *BatchSendShipments200ResponseResultsInner) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetCode

`func (o *BatchSendShipments200ResponseResultsInner) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *BatchSendShipments200ResponseResultsInner) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *BatchSendShipments200ResponseResultsInner) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *BatchSendShipments200ResponseResultsInner) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetMessage

`func (o *BatchSendShipments200ResponseResultsInner) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *BatchSendShipments200ResponseResultsInner) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *BatchSendShipments200ResponseResultsInner) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *BatchSendShipments200ResponseResultsInner) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetErrors

`func (o *BatchSendShipments200ResponseResultsInner) GetErrors() []SendShipment422ResponseErrorsInner`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *BatchSendShipments200ResponseResultsInner) GetErrorsOk() (*[]SendShipment422ResponseErrorsInner, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *BatchSendShipments200ResponseResultsInner) SetErrors(v []SendShipment422ResponseErrorsInner)`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *BatchSendShipments200ResponseResultsInner) HasErrors() bool`

HasErrors returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


