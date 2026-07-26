# BatchSendShipments200ResponseSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Total** | **int32** | Number of unique shipments processed. | 
**Sent** | **int32** | How many were successfully booked. | 
**Failed** | **int32** | How many failed. | 

## Methods

### NewBatchSendShipments200ResponseSummary

`func NewBatchSendShipments200ResponseSummary(total int32, sent int32, failed int32, ) *BatchSendShipments200ResponseSummary`

NewBatchSendShipments200ResponseSummary instantiates a new BatchSendShipments200ResponseSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBatchSendShipments200ResponseSummaryWithDefaults

`func NewBatchSendShipments200ResponseSummaryWithDefaults() *BatchSendShipments200ResponseSummary`

NewBatchSendShipments200ResponseSummaryWithDefaults instantiates a new BatchSendShipments200ResponseSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTotal

`func (o *BatchSendShipments200ResponseSummary) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *BatchSendShipments200ResponseSummary) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *BatchSendShipments200ResponseSummary) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetSent

`func (o *BatchSendShipments200ResponseSummary) GetSent() int32`

GetSent returns the Sent field if non-nil, zero value otherwise.

### GetSentOk

`func (o *BatchSendShipments200ResponseSummary) GetSentOk() (*int32, bool)`

GetSentOk returns a tuple with the Sent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSent

`func (o *BatchSendShipments200ResponseSummary) SetSent(v int32)`

SetSent sets Sent field to given value.


### GetFailed

`func (o *BatchSendShipments200ResponseSummary) GetFailed() int32`

GetFailed returns the Failed field if non-nil, zero value otherwise.

### GetFailedOk

`func (o *BatchSendShipments200ResponseSummary) GetFailedOk() (*int32, bool)`

GetFailedOk returns a tuple with the Failed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailed

`func (o *BatchSendShipments200ResponseSummary) SetFailed(v int32)`

SetFailed sets Failed field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


