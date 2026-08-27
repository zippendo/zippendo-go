# CreateShipmentRequestDroppoint

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Identifier of the selected service point. | 
**Name** | **string** | Display name of the service point. | 
**Address** | **string** | Formatted address of the service point. | 
**Coordinates** | Pointer to [**[]ListShippingRules200ResponseDataInnerAdditionalParametersValueAnyOfCoordinatesInner**](ListShippingRules200ResponseDataInnerAdditionalParametersValueAnyOfCoordinatesInner.md) | Latitude/longitude of the service point. | [optional] 

## Methods

### NewCreateShipmentRequestDroppoint

`func NewCreateShipmentRequestDroppoint(id string, name string, address string, ) *CreateShipmentRequestDroppoint`

NewCreateShipmentRequestDroppoint instantiates a new CreateShipmentRequestDroppoint object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateShipmentRequestDroppointWithDefaults

`func NewCreateShipmentRequestDroppointWithDefaults() *CreateShipmentRequestDroppoint`

NewCreateShipmentRequestDroppointWithDefaults instantiates a new CreateShipmentRequestDroppoint object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreateShipmentRequestDroppoint) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateShipmentRequestDroppoint) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateShipmentRequestDroppoint) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *CreateShipmentRequestDroppoint) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateShipmentRequestDroppoint) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateShipmentRequestDroppoint) SetName(v string)`

SetName sets Name field to given value.


### GetAddress

`func (o *CreateShipmentRequestDroppoint) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *CreateShipmentRequestDroppoint) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *CreateShipmentRequestDroppoint) SetAddress(v string)`

SetAddress sets Address field to given value.


### GetCoordinates

`func (o *CreateShipmentRequestDroppoint) GetCoordinates() []ListShippingRules200ResponseDataInnerAdditionalParametersValueAnyOfCoordinatesInner`

GetCoordinates returns the Coordinates field if non-nil, zero value otherwise.

### GetCoordinatesOk

`func (o *CreateShipmentRequestDroppoint) GetCoordinatesOk() (*[]ListShippingRules200ResponseDataInnerAdditionalParametersValueAnyOfCoordinatesInner, bool)`

GetCoordinatesOk returns a tuple with the Coordinates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoordinates

`func (o *CreateShipmentRequestDroppoint) SetCoordinates(v []ListShippingRules200ResponseDataInnerAdditionalParametersValueAnyOfCoordinatesInner)`

SetCoordinates sets Coordinates field to given value.

### HasCoordinates

`func (o *CreateShipmentRequestDroppoint) HasCoordinates() bool`

HasCoordinates returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


