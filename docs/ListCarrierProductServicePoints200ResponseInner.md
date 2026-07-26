# ListCarrierProductServicePoints200ResponseInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Lat** | **float32** | Latitude of the service point | 
**Lng** | **float32** | Longitude of the service point | 
**Name** | **string** | Name of the service point | 
**ServicePointId** | **string** | Unique service point identifier | 
**OpeningHours** | Pointer to **[]string** | Opening hours of the service point | [optional] 
**Description** | Pointer to **string** | Additional description of the service point | [optional] 
**Distance** | Pointer to **float32** | Distance from the searched location in meters | [optional] 
**Address** | Pointer to [**ListCarrierProductServicePoints200ResponseInnerAddress**](ListCarrierProductServicePoints200ResponseInnerAddress.md) |  | [optional] 

## Methods

### NewListCarrierProductServicePoints200ResponseInner

`func NewListCarrierProductServicePoints200ResponseInner(lat float32, lng float32, name string, servicePointId string, ) *ListCarrierProductServicePoints200ResponseInner`

NewListCarrierProductServicePoints200ResponseInner instantiates a new ListCarrierProductServicePoints200ResponseInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListCarrierProductServicePoints200ResponseInnerWithDefaults

`func NewListCarrierProductServicePoints200ResponseInnerWithDefaults() *ListCarrierProductServicePoints200ResponseInner`

NewListCarrierProductServicePoints200ResponseInnerWithDefaults instantiates a new ListCarrierProductServicePoints200ResponseInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLat

`func (o *ListCarrierProductServicePoints200ResponseInner) GetLat() float32`

GetLat returns the Lat field if non-nil, zero value otherwise.

### GetLatOk

`func (o *ListCarrierProductServicePoints200ResponseInner) GetLatOk() (*float32, bool)`

GetLatOk returns a tuple with the Lat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLat

`func (o *ListCarrierProductServicePoints200ResponseInner) SetLat(v float32)`

SetLat sets Lat field to given value.


### GetLng

`func (o *ListCarrierProductServicePoints200ResponseInner) GetLng() float32`

GetLng returns the Lng field if non-nil, zero value otherwise.

### GetLngOk

`func (o *ListCarrierProductServicePoints200ResponseInner) GetLngOk() (*float32, bool)`

GetLngOk returns a tuple with the Lng field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLng

`func (o *ListCarrierProductServicePoints200ResponseInner) SetLng(v float32)`

SetLng sets Lng field to given value.


### GetName

`func (o *ListCarrierProductServicePoints200ResponseInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ListCarrierProductServicePoints200ResponseInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ListCarrierProductServicePoints200ResponseInner) SetName(v string)`

SetName sets Name field to given value.


### GetServicePointId

`func (o *ListCarrierProductServicePoints200ResponseInner) GetServicePointId() string`

GetServicePointId returns the ServicePointId field if non-nil, zero value otherwise.

### GetServicePointIdOk

`func (o *ListCarrierProductServicePoints200ResponseInner) GetServicePointIdOk() (*string, bool)`

GetServicePointIdOk returns a tuple with the ServicePointId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServicePointId

`func (o *ListCarrierProductServicePoints200ResponseInner) SetServicePointId(v string)`

SetServicePointId sets ServicePointId field to given value.


### GetOpeningHours

`func (o *ListCarrierProductServicePoints200ResponseInner) GetOpeningHours() []string`

GetOpeningHours returns the OpeningHours field if non-nil, zero value otherwise.

### GetOpeningHoursOk

`func (o *ListCarrierProductServicePoints200ResponseInner) GetOpeningHoursOk() (*[]string, bool)`

GetOpeningHoursOk returns a tuple with the OpeningHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpeningHours

`func (o *ListCarrierProductServicePoints200ResponseInner) SetOpeningHours(v []string)`

SetOpeningHours sets OpeningHours field to given value.

### HasOpeningHours

`func (o *ListCarrierProductServicePoints200ResponseInner) HasOpeningHours() bool`

HasOpeningHours returns a boolean if a field has been set.

### GetDescription

`func (o *ListCarrierProductServicePoints200ResponseInner) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ListCarrierProductServicePoints200ResponseInner) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ListCarrierProductServicePoints200ResponseInner) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ListCarrierProductServicePoints200ResponseInner) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetDistance

`func (o *ListCarrierProductServicePoints200ResponseInner) GetDistance() float32`

GetDistance returns the Distance field if non-nil, zero value otherwise.

### GetDistanceOk

`func (o *ListCarrierProductServicePoints200ResponseInner) GetDistanceOk() (*float32, bool)`

GetDistanceOk returns a tuple with the Distance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDistance

`func (o *ListCarrierProductServicePoints200ResponseInner) SetDistance(v float32)`

SetDistance sets Distance field to given value.

### HasDistance

`func (o *ListCarrierProductServicePoints200ResponseInner) HasDistance() bool`

HasDistance returns a boolean if a field has been set.

### GetAddress

`func (o *ListCarrierProductServicePoints200ResponseInner) GetAddress() ListCarrierProductServicePoints200ResponseInnerAddress`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *ListCarrierProductServicePoints200ResponseInner) GetAddressOk() (*ListCarrierProductServicePoints200ResponseInnerAddress, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *ListCarrierProductServicePoints200ResponseInner) SetAddress(v ListCarrierProductServicePoints200ResponseInnerAddress)`

SetAddress sets Address field to given value.

### HasAddress

`func (o *ListCarrierProductServicePoints200ResponseInner) HasAddress() bool`

HasAddress returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


