# ListOrgWebhookDeliveries200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Delivery log ID | 
**WebhookId** | **string** | ID of the webhook this delivery belongs to | 
**Event** | **string** | Event type that was delivered | 
**Payload** | **interface{}** | JSON payload that was sent | 
**StatusCode** | **NullableFloat32** | HTTP status code returned by the endpoint | 
**Response** | **NullableString** | Response body returned by the endpoint | 
**Duration** | **NullableFloat32** | Request duration in milliseconds | 
**Success** | **bool** | Whether the delivery succeeded | 
**Attempt** | **float32** | Delivery attempt number | 
**Error** | **NullableString** | Error message if the delivery failed | 
**CreatedAt** | **string** | Delivery timestamp (ISO 8601) | 

## Methods

### NewListOrgWebhookDeliveries200ResponseDataInner

`func NewListOrgWebhookDeliveries200ResponseDataInner(id string, webhookId string, event string, payload interface{}, statusCode NullableFloat32, response NullableString, duration NullableFloat32, success bool, attempt float32, error_ NullableString, createdAt string, ) *ListOrgWebhookDeliveries200ResponseDataInner`

NewListOrgWebhookDeliveries200ResponseDataInner instantiates a new ListOrgWebhookDeliveries200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListOrgWebhookDeliveries200ResponseDataInnerWithDefaults

`func NewListOrgWebhookDeliveries200ResponseDataInnerWithDefaults() *ListOrgWebhookDeliveries200ResponseDataInner`

NewListOrgWebhookDeliveries200ResponseDataInnerWithDefaults instantiates a new ListOrgWebhookDeliveries200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) SetId(v string)`

SetId sets Id field to given value.


### GetWebhookId

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) GetWebhookId() string`

GetWebhookId returns the WebhookId field if non-nil, zero value otherwise.

### GetWebhookIdOk

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) GetWebhookIdOk() (*string, bool)`

GetWebhookIdOk returns a tuple with the WebhookId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebhookId

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) SetWebhookId(v string)`

SetWebhookId sets WebhookId field to given value.


### GetEvent

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) GetEvent() string`

GetEvent returns the Event field if non-nil, zero value otherwise.

### GetEventOk

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) GetEventOk() (*string, bool)`

GetEventOk returns a tuple with the Event field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvent

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) SetEvent(v string)`

SetEvent sets Event field to given value.


### GetPayload

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) GetPayload() interface{}`

GetPayload returns the Payload field if non-nil, zero value otherwise.

### GetPayloadOk

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) GetPayloadOk() (*interface{}, bool)`

GetPayloadOk returns a tuple with the Payload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayload

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) SetPayload(v interface{})`

SetPayload sets Payload field to given value.


### SetPayloadNil

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) SetPayloadNil(b bool)`

 SetPayloadNil sets the value for Payload to be an explicit nil

### UnsetPayload
`func (o *ListOrgWebhookDeliveries200ResponseDataInner) UnsetPayload()`

UnsetPayload ensures that no value is present for Payload, not even an explicit nil
### GetStatusCode

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) GetStatusCode() float32`

GetStatusCode returns the StatusCode field if non-nil, zero value otherwise.

### GetStatusCodeOk

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) GetStatusCodeOk() (*float32, bool)`

GetStatusCodeOk returns a tuple with the StatusCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatusCode

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) SetStatusCode(v float32)`

SetStatusCode sets StatusCode field to given value.


### SetStatusCodeNil

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) SetStatusCodeNil(b bool)`

 SetStatusCodeNil sets the value for StatusCode to be an explicit nil

### UnsetStatusCode
`func (o *ListOrgWebhookDeliveries200ResponseDataInner) UnsetStatusCode()`

UnsetStatusCode ensures that no value is present for StatusCode, not even an explicit nil
### GetResponse

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) GetResponse() string`

GetResponse returns the Response field if non-nil, zero value otherwise.

### GetResponseOk

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) GetResponseOk() (*string, bool)`

GetResponseOk returns a tuple with the Response field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponse

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) SetResponse(v string)`

SetResponse sets Response field to given value.


### SetResponseNil

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) SetResponseNil(b bool)`

 SetResponseNil sets the value for Response to be an explicit nil

### UnsetResponse
`func (o *ListOrgWebhookDeliveries200ResponseDataInner) UnsetResponse()`

UnsetResponse ensures that no value is present for Response, not even an explicit nil
### GetDuration

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) GetDuration() float32`

GetDuration returns the Duration field if non-nil, zero value otherwise.

### GetDurationOk

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) GetDurationOk() (*float32, bool)`

GetDurationOk returns a tuple with the Duration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuration

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) SetDuration(v float32)`

SetDuration sets Duration field to given value.


### SetDurationNil

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) SetDurationNil(b bool)`

 SetDurationNil sets the value for Duration to be an explicit nil

### UnsetDuration
`func (o *ListOrgWebhookDeliveries200ResponseDataInner) UnsetDuration()`

UnsetDuration ensures that no value is present for Duration, not even an explicit nil
### GetSuccess

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetAttempt

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) GetAttempt() float32`

GetAttempt returns the Attempt field if non-nil, zero value otherwise.

### GetAttemptOk

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) GetAttemptOk() (*float32, bool)`

GetAttemptOk returns a tuple with the Attempt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttempt

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) SetAttempt(v float32)`

SetAttempt sets Attempt field to given value.


### GetError

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) SetError(v string)`

SetError sets Error field to given value.


### SetErrorNil

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *ListOrgWebhookDeliveries200ResponseDataInner) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetCreatedAt

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ListOrgWebhookDeliveries200ResponseDataInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


