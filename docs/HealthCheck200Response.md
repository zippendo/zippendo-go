# HealthCheck200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | **string** | Service status | 
**Timestamp** | **string** | Current server time (ISO 8601) | 
**Version** | **string** | API version | 

## Methods

### NewHealthCheck200Response

`func NewHealthCheck200Response(status string, timestamp string, version string, ) *HealthCheck200Response`

NewHealthCheck200Response instantiates a new HealthCheck200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHealthCheck200ResponseWithDefaults

`func NewHealthCheck200ResponseWithDefaults() *HealthCheck200Response`

NewHealthCheck200ResponseWithDefaults instantiates a new HealthCheck200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *HealthCheck200Response) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *HealthCheck200Response) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *HealthCheck200Response) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetTimestamp

`func (o *HealthCheck200Response) GetTimestamp() string`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *HealthCheck200Response) GetTimestampOk() (*string, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *HealthCheck200Response) SetTimestamp(v string)`

SetTimestamp sets Timestamp field to given value.


### GetVersion

`func (o *HealthCheck200Response) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *HealthCheck200Response) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *HealthCheck200Response) SetVersion(v string)`

SetVersion sets Version field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


