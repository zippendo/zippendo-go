# TrackShipment200ResponseEventsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Unique tracking event identifier. | 
**Status** | **string** | Normalized tracking status for the event. | 
**CarrierStatus** | **string** | Raw status string reported by the carrier. | 
**Description** | **NullableString** | Human-readable description of the event. | 
**Location** | **NullableString** | Location where the event was registered. | 
**OccurredAt** | **string** | Timestamp when the event occurred. | 

## Methods

### NewTrackShipment200ResponseEventsInner

`func NewTrackShipment200ResponseEventsInner(id string, status string, carrierStatus string, description NullableString, location NullableString, occurredAt string, ) *TrackShipment200ResponseEventsInner`

NewTrackShipment200ResponseEventsInner instantiates a new TrackShipment200ResponseEventsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrackShipment200ResponseEventsInnerWithDefaults

`func NewTrackShipment200ResponseEventsInnerWithDefaults() *TrackShipment200ResponseEventsInner`

NewTrackShipment200ResponseEventsInnerWithDefaults instantiates a new TrackShipment200ResponseEventsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *TrackShipment200ResponseEventsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *TrackShipment200ResponseEventsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *TrackShipment200ResponseEventsInner) SetId(v string)`

SetId sets Id field to given value.


### GetStatus

`func (o *TrackShipment200ResponseEventsInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *TrackShipment200ResponseEventsInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *TrackShipment200ResponseEventsInner) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetCarrierStatus

`func (o *TrackShipment200ResponseEventsInner) GetCarrierStatus() string`

GetCarrierStatus returns the CarrierStatus field if non-nil, zero value otherwise.

### GetCarrierStatusOk

`func (o *TrackShipment200ResponseEventsInner) GetCarrierStatusOk() (*string, bool)`

GetCarrierStatusOk returns a tuple with the CarrierStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierStatus

`func (o *TrackShipment200ResponseEventsInner) SetCarrierStatus(v string)`

SetCarrierStatus sets CarrierStatus field to given value.


### GetDescription

`func (o *TrackShipment200ResponseEventsInner) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *TrackShipment200ResponseEventsInner) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *TrackShipment200ResponseEventsInner) SetDescription(v string)`

SetDescription sets Description field to given value.


### SetDescriptionNil

`func (o *TrackShipment200ResponseEventsInner) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *TrackShipment200ResponseEventsInner) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetLocation

`func (o *TrackShipment200ResponseEventsInner) GetLocation() string`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *TrackShipment200ResponseEventsInner) GetLocationOk() (*string, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *TrackShipment200ResponseEventsInner) SetLocation(v string)`

SetLocation sets Location field to given value.


### SetLocationNil

`func (o *TrackShipment200ResponseEventsInner) SetLocationNil(b bool)`

 SetLocationNil sets the value for Location to be an explicit nil

### UnsetLocation
`func (o *TrackShipment200ResponseEventsInner) UnsetLocation()`

UnsetLocation ensures that no value is present for Location, not even an explicit nil
### GetOccurredAt

`func (o *TrackShipment200ResponseEventsInner) GetOccurredAt() string`

GetOccurredAt returns the OccurredAt field if non-nil, zero value otherwise.

### GetOccurredAtOk

`func (o *TrackShipment200ResponseEventsInner) GetOccurredAtOk() (*string, bool)`

GetOccurredAtOk returns a tuple with the OccurredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurredAt

`func (o *TrackShipment200ResponseEventsInner) SetOccurredAt(v string)`

SetOccurredAt sets OccurredAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


