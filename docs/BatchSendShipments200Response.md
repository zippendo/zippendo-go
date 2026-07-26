# BatchSendShipments200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Results** | [**[]BatchSendShipments200ResponseResultsInner**](BatchSendShipments200ResponseResultsInner.md) | Per-shipment outcome (one entry per unique requested shipment id). | 
**Summary** | [**BatchSendShipments200ResponseSummary**](BatchSendShipments200ResponseSummary.md) |  | 

## Methods

### NewBatchSendShipments200Response

`func NewBatchSendShipments200Response(results []BatchSendShipments200ResponseResultsInner, summary BatchSendShipments200ResponseSummary, ) *BatchSendShipments200Response`

NewBatchSendShipments200Response instantiates a new BatchSendShipments200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBatchSendShipments200ResponseWithDefaults

`func NewBatchSendShipments200ResponseWithDefaults() *BatchSendShipments200Response`

NewBatchSendShipments200ResponseWithDefaults instantiates a new BatchSendShipments200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetResults

`func (o *BatchSendShipments200Response) GetResults() []BatchSendShipments200ResponseResultsInner`

GetResults returns the Results field if non-nil, zero value otherwise.

### GetResultsOk

`func (o *BatchSendShipments200Response) GetResultsOk() (*[]BatchSendShipments200ResponseResultsInner, bool)`

GetResultsOk returns a tuple with the Results field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResults

`func (o *BatchSendShipments200Response) SetResults(v []BatchSendShipments200ResponseResultsInner)`

SetResults sets Results field to given value.


### GetSummary

`func (o *BatchSendShipments200Response) GetSummary() BatchSendShipments200ResponseSummary`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *BatchSendShipments200Response) GetSummaryOk() (*BatchSendShipments200ResponseSummary, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *BatchSendShipments200Response) SetSummary(v BatchSendShipments200ResponseSummary)`

SetSummary sets Summary field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


