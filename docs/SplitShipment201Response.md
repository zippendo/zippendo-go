# SplitShipment201Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OriginalShipment** | [**CreateShipment201Response**](CreateShipment201Response.md) |  | 
**NewShipment** | [**CreateShipment201Response**](CreateShipment201Response.md) |  | 

## Methods

### NewSplitShipment201Response

`func NewSplitShipment201Response(originalShipment CreateShipment201Response, newShipment CreateShipment201Response, ) *SplitShipment201Response`

NewSplitShipment201Response instantiates a new SplitShipment201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSplitShipment201ResponseWithDefaults

`func NewSplitShipment201ResponseWithDefaults() *SplitShipment201Response`

NewSplitShipment201ResponseWithDefaults instantiates a new SplitShipment201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOriginalShipment

`func (o *SplitShipment201Response) GetOriginalShipment() CreateShipment201Response`

GetOriginalShipment returns the OriginalShipment field if non-nil, zero value otherwise.

### GetOriginalShipmentOk

`func (o *SplitShipment201Response) GetOriginalShipmentOk() (*CreateShipment201Response, bool)`

GetOriginalShipmentOk returns a tuple with the OriginalShipment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalShipment

`func (o *SplitShipment201Response) SetOriginalShipment(v CreateShipment201Response)`

SetOriginalShipment sets OriginalShipment field to given value.


### GetNewShipment

`func (o *SplitShipment201Response) GetNewShipment() CreateShipment201Response`

GetNewShipment returns the NewShipment field if non-nil, zero value otherwise.

### GetNewShipmentOk

`func (o *SplitShipment201Response) GetNewShipmentOk() (*CreateShipment201Response, bool)`

GetNewShipmentOk returns a tuple with the NewShipment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewShipment

`func (o *SplitShipment201Response) SetNewShipment(v CreateShipment201Response)`

SetNewShipment sets NewShipment field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


