# CreateShipment201ResponseErrorsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Unique error identifier. | 
**Carrier** | **string** | Carrier that produced the error. | 
**Code** | Pointer to **NullableString** | Carrier-specific error code. | [optional] 
**Message** | **string** | Human-readable error message. | 
**CreatedAt** | **string** | Timestamp when the error occurred. | 

## Methods

### NewCreateShipment201ResponseErrorsInner

`func NewCreateShipment201ResponseErrorsInner(id string, carrier string, message string, createdAt string, ) *CreateShipment201ResponseErrorsInner`

NewCreateShipment201ResponseErrorsInner instantiates a new CreateShipment201ResponseErrorsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateShipment201ResponseErrorsInnerWithDefaults

`func NewCreateShipment201ResponseErrorsInnerWithDefaults() *CreateShipment201ResponseErrorsInner`

NewCreateShipment201ResponseErrorsInnerWithDefaults instantiates a new CreateShipment201ResponseErrorsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreateShipment201ResponseErrorsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateShipment201ResponseErrorsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateShipment201ResponseErrorsInner) SetId(v string)`

SetId sets Id field to given value.


### GetCarrier

`func (o *CreateShipment201ResponseErrorsInner) GetCarrier() string`

GetCarrier returns the Carrier field if non-nil, zero value otherwise.

### GetCarrierOk

`func (o *CreateShipment201ResponseErrorsInner) GetCarrierOk() (*string, bool)`

GetCarrierOk returns a tuple with the Carrier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrier

`func (o *CreateShipment201ResponseErrorsInner) SetCarrier(v string)`

SetCarrier sets Carrier field to given value.


### GetCode

`func (o *CreateShipment201ResponseErrorsInner) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *CreateShipment201ResponseErrorsInner) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *CreateShipment201ResponseErrorsInner) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *CreateShipment201ResponseErrorsInner) HasCode() bool`

HasCode returns a boolean if a field has been set.

### SetCodeNil

`func (o *CreateShipment201ResponseErrorsInner) SetCodeNil(b bool)`

 SetCodeNil sets the value for Code to be an explicit nil

### UnsetCode
`func (o *CreateShipment201ResponseErrorsInner) UnsetCode()`

UnsetCode ensures that no value is present for Code, not even an explicit nil
### GetMessage

`func (o *CreateShipment201ResponseErrorsInner) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *CreateShipment201ResponseErrorsInner) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *CreateShipment201ResponseErrorsInner) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetCreatedAt

`func (o *CreateShipment201ResponseErrorsInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CreateShipment201ResponseErrorsInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CreateShipment201ResponseErrorsInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


