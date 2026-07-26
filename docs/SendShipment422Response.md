# SendShipment422Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | Pointer to **string** | Machine-readable error code. | [optional] 
**Error** | **string** | Error category. | 
**Message** | **string** | Human-readable summary of the carrier failure. | 
**Errors** | [**[]SendShipment422ResponseErrorsInner**](SendShipment422ResponseErrorsInner.md) | Detailed carrier errors that caused the booking to fail. | 

## Methods

### NewSendShipment422Response

`func NewSendShipment422Response(error_ string, message string, errors []SendShipment422ResponseErrorsInner, ) *SendShipment422Response`

NewSendShipment422Response instantiates a new SendShipment422Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSendShipment422ResponseWithDefaults

`func NewSendShipment422ResponseWithDefaults() *SendShipment422Response`

NewSendShipment422ResponseWithDefaults instantiates a new SendShipment422Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *SendShipment422Response) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *SendShipment422Response) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *SendShipment422Response) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *SendShipment422Response) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetError

`func (o *SendShipment422Response) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *SendShipment422Response) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *SendShipment422Response) SetError(v string)`

SetError sets Error field to given value.


### GetMessage

`func (o *SendShipment422Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *SendShipment422Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *SendShipment422Response) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetErrors

`func (o *SendShipment422Response) GetErrors() []SendShipment422ResponseErrorsInner`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *SendShipment422Response) GetErrorsOk() (*[]SendShipment422ResponseErrorsInner, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *SendShipment422Response) SetErrors(v []SendShipment422ResponseErrorsInner)`

SetErrors sets Errors field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


