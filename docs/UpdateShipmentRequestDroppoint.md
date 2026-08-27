# UpdateShipmentRequestDroppoint

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Identifier of the selected service point. | 
**Name** | **string** | Display name of the service point. | 
**Address** | **string** | Formatted address of the service point. | 
**Coordinates** | Pointer to [**[]ListShippingRules200ResponseDataInnerAdditionalParametersValueAnyOfCoordinatesInner**](ListShippingRules200ResponseDataInnerAdditionalParametersValueAnyOfCoordinatesInner.md) | Latitude/longitude of the service point. | [optional] 

## Methods

### NewUpdateShipmentRequestDroppoint

`func NewUpdateShipmentRequestDroppoint(id string, name string, address string, ) *UpdateShipmentRequestDroppoint`

NewUpdateShipmentRequestDroppoint instantiates a new UpdateShipmentRequestDroppoint object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateShipmentRequestDroppointWithDefaults

`func NewUpdateShipmentRequestDroppointWithDefaults() *UpdateShipmentRequestDroppoint`

NewUpdateShipmentRequestDroppointWithDefaults instantiates a new UpdateShipmentRequestDroppoint object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *UpdateShipmentRequestDroppoint) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *UpdateShipmentRequestDroppoint) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *UpdateShipmentRequestDroppoint) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *UpdateShipmentRequestDroppoint) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateShipmentRequestDroppoint) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateShipmentRequestDroppoint) SetName(v string)`

SetName sets Name field to given value.


### GetAddress

`func (o *UpdateShipmentRequestDroppoint) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *UpdateShipmentRequestDroppoint) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *UpdateShipmentRequestDroppoint) SetAddress(v string)`

SetAddress sets Address field to given value.


### GetCoordinates

`func (o *UpdateShipmentRequestDroppoint) GetCoordinates() []ListShippingRules200ResponseDataInnerAdditionalParametersValueAnyOfCoordinatesInner`

GetCoordinates returns the Coordinates field if non-nil, zero value otherwise.

### GetCoordinatesOk

`func (o *UpdateShipmentRequestDroppoint) GetCoordinatesOk() (*[]ListShippingRules200ResponseDataInnerAdditionalParametersValueAnyOfCoordinatesInner, bool)`

GetCoordinatesOk returns a tuple with the Coordinates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoordinates

`func (o *UpdateShipmentRequestDroppoint) SetCoordinates(v []ListShippingRules200ResponseDataInnerAdditionalParametersValueAnyOfCoordinatesInner)`

SetCoordinates sets Coordinates field to given value.

### HasCoordinates

`func (o *UpdateShipmentRequestDroppoint) HasCoordinates() bool`

HasCoordinates returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


