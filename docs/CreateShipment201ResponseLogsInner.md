# CreateShipment201ResponseLogsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Unique log entry identifier. | 
**Direction** | **string** | Direction of the logged request. | 
**Request** | **interface{}** | Captured request payload. | 
**Response** | Pointer to **interface{}** | Captured response payload. | [optional] 
**StatusCode** | Pointer to **NullableFloat32** | HTTP status code of the response. | [optional] 
**Error** | Pointer to **NullableString** | Error message if the request failed. | [optional] 
**Duration** | Pointer to **NullableFloat32** | Request duration in milliseconds. | [optional] 
**CreatedAt** | **string** | Timestamp when the log entry was created. | 

## Methods

### NewCreateShipment201ResponseLogsInner

`func NewCreateShipment201ResponseLogsInner(id string, direction string, request interface{}, createdAt string, ) *CreateShipment201ResponseLogsInner`

NewCreateShipment201ResponseLogsInner instantiates a new CreateShipment201ResponseLogsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateShipment201ResponseLogsInnerWithDefaults

`func NewCreateShipment201ResponseLogsInnerWithDefaults() *CreateShipment201ResponseLogsInner`

NewCreateShipment201ResponseLogsInnerWithDefaults instantiates a new CreateShipment201ResponseLogsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreateShipment201ResponseLogsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateShipment201ResponseLogsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateShipment201ResponseLogsInner) SetId(v string)`

SetId sets Id field to given value.


### GetDirection

`func (o *CreateShipment201ResponseLogsInner) GetDirection() string`

GetDirection returns the Direction field if non-nil, zero value otherwise.

### GetDirectionOk

`func (o *CreateShipment201ResponseLogsInner) GetDirectionOk() (*string, bool)`

GetDirectionOk returns a tuple with the Direction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDirection

`func (o *CreateShipment201ResponseLogsInner) SetDirection(v string)`

SetDirection sets Direction field to given value.


### GetRequest

`func (o *CreateShipment201ResponseLogsInner) GetRequest() interface{}`

GetRequest returns the Request field if non-nil, zero value otherwise.

### GetRequestOk

`func (o *CreateShipment201ResponseLogsInner) GetRequestOk() (*interface{}, bool)`

GetRequestOk returns a tuple with the Request field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequest

`func (o *CreateShipment201ResponseLogsInner) SetRequest(v interface{})`

SetRequest sets Request field to given value.


### SetRequestNil

`func (o *CreateShipment201ResponseLogsInner) SetRequestNil(b bool)`

 SetRequestNil sets the value for Request to be an explicit nil

### UnsetRequest
`func (o *CreateShipment201ResponseLogsInner) UnsetRequest()`

UnsetRequest ensures that no value is present for Request, not even an explicit nil
### GetResponse

`func (o *CreateShipment201ResponseLogsInner) GetResponse() interface{}`

GetResponse returns the Response field if non-nil, zero value otherwise.

### GetResponseOk

`func (o *CreateShipment201ResponseLogsInner) GetResponseOk() (*interface{}, bool)`

GetResponseOk returns a tuple with the Response field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponse

`func (o *CreateShipment201ResponseLogsInner) SetResponse(v interface{})`

SetResponse sets Response field to given value.

### HasResponse

`func (o *CreateShipment201ResponseLogsInner) HasResponse() bool`

HasResponse returns a boolean if a field has been set.

### SetResponseNil

`func (o *CreateShipment201ResponseLogsInner) SetResponseNil(b bool)`

 SetResponseNil sets the value for Response to be an explicit nil

### UnsetResponse
`func (o *CreateShipment201ResponseLogsInner) UnsetResponse()`

UnsetResponse ensures that no value is present for Response, not even an explicit nil
### GetStatusCode

`func (o *CreateShipment201ResponseLogsInner) GetStatusCode() float32`

GetStatusCode returns the StatusCode field if non-nil, zero value otherwise.

### GetStatusCodeOk

`func (o *CreateShipment201ResponseLogsInner) GetStatusCodeOk() (*float32, bool)`

GetStatusCodeOk returns a tuple with the StatusCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatusCode

`func (o *CreateShipment201ResponseLogsInner) SetStatusCode(v float32)`

SetStatusCode sets StatusCode field to given value.

### HasStatusCode

`func (o *CreateShipment201ResponseLogsInner) HasStatusCode() bool`

HasStatusCode returns a boolean if a field has been set.

### SetStatusCodeNil

`func (o *CreateShipment201ResponseLogsInner) SetStatusCodeNil(b bool)`

 SetStatusCodeNil sets the value for StatusCode to be an explicit nil

### UnsetStatusCode
`func (o *CreateShipment201ResponseLogsInner) UnsetStatusCode()`

UnsetStatusCode ensures that no value is present for StatusCode, not even an explicit nil
### GetError

`func (o *CreateShipment201ResponseLogsInner) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *CreateShipment201ResponseLogsInner) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *CreateShipment201ResponseLogsInner) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *CreateShipment201ResponseLogsInner) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *CreateShipment201ResponseLogsInner) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *CreateShipment201ResponseLogsInner) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetDuration

`func (o *CreateShipment201ResponseLogsInner) GetDuration() float32`

GetDuration returns the Duration field if non-nil, zero value otherwise.

### GetDurationOk

`func (o *CreateShipment201ResponseLogsInner) GetDurationOk() (*float32, bool)`

GetDurationOk returns a tuple with the Duration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuration

`func (o *CreateShipment201ResponseLogsInner) SetDuration(v float32)`

SetDuration sets Duration field to given value.

### HasDuration

`func (o *CreateShipment201ResponseLogsInner) HasDuration() bool`

HasDuration returns a boolean if a field has been set.

### SetDurationNil

`func (o *CreateShipment201ResponseLogsInner) SetDurationNil(b bool)`

 SetDurationNil sets the value for Duration to be an explicit nil

### UnsetDuration
`func (o *CreateShipment201ResponseLogsInner) UnsetDuration()`

UnsetDuration ensures that no value is present for Duration, not even an explicit nil
### GetCreatedAt

`func (o *CreateShipment201ResponseLogsInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CreateShipment201ResponseLogsInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CreateShipment201ResponseLogsInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


