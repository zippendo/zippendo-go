# SplitShipmentParcelRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Parcels** | [**[]SplitShipmentParcelRequestParcelsInner**](SplitShipmentParcelRequestParcelsInner.md) | Target parcel layout to redistribute order lines into. | 

## Methods

### NewSplitShipmentParcelRequest

`func NewSplitShipmentParcelRequest(parcels []SplitShipmentParcelRequestParcelsInner, ) *SplitShipmentParcelRequest`

NewSplitShipmentParcelRequest instantiates a new SplitShipmentParcelRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSplitShipmentParcelRequestWithDefaults

`func NewSplitShipmentParcelRequestWithDefaults() *SplitShipmentParcelRequest`

NewSplitShipmentParcelRequestWithDefaults instantiates a new SplitShipmentParcelRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetParcels

`func (o *SplitShipmentParcelRequest) GetParcels() []SplitShipmentParcelRequestParcelsInner`

GetParcels returns the Parcels field if non-nil, zero value otherwise.

### GetParcelsOk

`func (o *SplitShipmentParcelRequest) GetParcelsOk() (*[]SplitShipmentParcelRequestParcelsInner, bool)`

GetParcelsOk returns a tuple with the Parcels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParcels

`func (o *SplitShipmentParcelRequest) SetParcels(v []SplitShipmentParcelRequestParcelsInner)`

SetParcels sets Parcels field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


