# TrackShipment200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TrackingNumber** | **NullableString** | Carrier tracking number. | 
**TrackingUrl** | **NullableString** | Public carrier tracking URL. | 
**CurrentStatus** | **NullableString** | Latest normalized tracking status. | 
**EstimatedDelivery** | Pointer to **NullableString** | Estimated delivery timestamp. | [optional] 
**Events** | [**[]TrackShipment200ResponseEventsInner**](TrackShipment200ResponseEventsInner.md) | Tracking events ordered from newest to oldest. | 

## Methods

### NewTrackShipment200Response

`func NewTrackShipment200Response(trackingNumber NullableString, trackingUrl NullableString, currentStatus NullableString, events []TrackShipment200ResponseEventsInner, ) *TrackShipment200Response`

NewTrackShipment200Response instantiates a new TrackShipment200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrackShipment200ResponseWithDefaults

`func NewTrackShipment200ResponseWithDefaults() *TrackShipment200Response`

NewTrackShipment200ResponseWithDefaults instantiates a new TrackShipment200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTrackingNumber

`func (o *TrackShipment200Response) GetTrackingNumber() string`

GetTrackingNumber returns the TrackingNumber field if non-nil, zero value otherwise.

### GetTrackingNumberOk

`func (o *TrackShipment200Response) GetTrackingNumberOk() (*string, bool)`

GetTrackingNumberOk returns a tuple with the TrackingNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingNumber

`func (o *TrackShipment200Response) SetTrackingNumber(v string)`

SetTrackingNumber sets TrackingNumber field to given value.


### SetTrackingNumberNil

`func (o *TrackShipment200Response) SetTrackingNumberNil(b bool)`

 SetTrackingNumberNil sets the value for TrackingNumber to be an explicit nil

### UnsetTrackingNumber
`func (o *TrackShipment200Response) UnsetTrackingNumber()`

UnsetTrackingNumber ensures that no value is present for TrackingNumber, not even an explicit nil
### GetTrackingUrl

`func (o *TrackShipment200Response) GetTrackingUrl() string`

GetTrackingUrl returns the TrackingUrl field if non-nil, zero value otherwise.

### GetTrackingUrlOk

`func (o *TrackShipment200Response) GetTrackingUrlOk() (*string, bool)`

GetTrackingUrlOk returns a tuple with the TrackingUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingUrl

`func (o *TrackShipment200Response) SetTrackingUrl(v string)`

SetTrackingUrl sets TrackingUrl field to given value.


### SetTrackingUrlNil

`func (o *TrackShipment200Response) SetTrackingUrlNil(b bool)`

 SetTrackingUrlNil sets the value for TrackingUrl to be an explicit nil

### UnsetTrackingUrl
`func (o *TrackShipment200Response) UnsetTrackingUrl()`

UnsetTrackingUrl ensures that no value is present for TrackingUrl, not even an explicit nil
### GetCurrentStatus

`func (o *TrackShipment200Response) GetCurrentStatus() string`

GetCurrentStatus returns the CurrentStatus field if non-nil, zero value otherwise.

### GetCurrentStatusOk

`func (o *TrackShipment200Response) GetCurrentStatusOk() (*string, bool)`

GetCurrentStatusOk returns a tuple with the CurrentStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentStatus

`func (o *TrackShipment200Response) SetCurrentStatus(v string)`

SetCurrentStatus sets CurrentStatus field to given value.


### SetCurrentStatusNil

`func (o *TrackShipment200Response) SetCurrentStatusNil(b bool)`

 SetCurrentStatusNil sets the value for CurrentStatus to be an explicit nil

### UnsetCurrentStatus
`func (o *TrackShipment200Response) UnsetCurrentStatus()`

UnsetCurrentStatus ensures that no value is present for CurrentStatus, not even an explicit nil
### GetEstimatedDelivery

`func (o *TrackShipment200Response) GetEstimatedDelivery() string`

GetEstimatedDelivery returns the EstimatedDelivery field if non-nil, zero value otherwise.

### GetEstimatedDeliveryOk

`func (o *TrackShipment200Response) GetEstimatedDeliveryOk() (*string, bool)`

GetEstimatedDeliveryOk returns a tuple with the EstimatedDelivery field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstimatedDelivery

`func (o *TrackShipment200Response) SetEstimatedDelivery(v string)`

SetEstimatedDelivery sets EstimatedDelivery field to given value.

### HasEstimatedDelivery

`func (o *TrackShipment200Response) HasEstimatedDelivery() bool`

HasEstimatedDelivery returns a boolean if a field has been set.

### SetEstimatedDeliveryNil

`func (o *TrackShipment200Response) SetEstimatedDeliveryNil(b bool)`

 SetEstimatedDeliveryNil sets the value for EstimatedDelivery to be an explicit nil

### UnsetEstimatedDelivery
`func (o *TrackShipment200Response) UnsetEstimatedDelivery()`

UnsetEstimatedDelivery ensures that no value is present for EstimatedDelivery, not even an explicit nil
### GetEvents

`func (o *TrackShipment200Response) GetEvents() []TrackShipment200ResponseEventsInner`

GetEvents returns the Events field if non-nil, zero value otherwise.

### GetEventsOk

`func (o *TrackShipment200Response) GetEventsOk() (*[]TrackShipment200ResponseEventsInner, bool)`

GetEventsOk returns a tuple with the Events field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvents

`func (o *TrackShipment200Response) SetEvents(v []TrackShipment200ResponseEventsInner)`

SetEvents sets Events field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


