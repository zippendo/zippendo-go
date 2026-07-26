# ListApiTokens401Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | Pointer to **string** | Machine-readable error code (translate by this on the client) | [optional] 
**Error** | **string** | Short human title | 
**Message** | **string** | Human-readable English detail (i18n fallback) | 

## Methods

### NewListApiTokens401Response

`func NewListApiTokens401Response(error_ string, message string, ) *ListApiTokens401Response`

NewListApiTokens401Response instantiates a new ListApiTokens401Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListApiTokens401ResponseWithDefaults

`func NewListApiTokens401ResponseWithDefaults() *ListApiTokens401Response`

NewListApiTokens401ResponseWithDefaults instantiates a new ListApiTokens401Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *ListApiTokens401Response) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *ListApiTokens401Response) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *ListApiTokens401Response) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *ListApiTokens401Response) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetError

`func (o *ListApiTokens401Response) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ListApiTokens401Response) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ListApiTokens401Response) SetError(v string)`

SetError sets Error field to given value.


### GetMessage

`func (o *ListApiTokens401Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *ListApiTokens401Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *ListApiTokens401Response) SetMessage(v string)`

SetMessage sets Message field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


