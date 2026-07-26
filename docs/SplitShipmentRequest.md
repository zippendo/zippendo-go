# SplitShipmentRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ParcelId** | **string** | Parcel whose order lines are split into a new shipment. | 
**OrderLineIds** | Pointer to **[]string** | Order line IDs to move. If omitted, all order lines in the parcel are moved. | [optional] 
**CarrierId** | Pointer to **string** | Carrier for the new shipment. Copied from the original if omitted. | [optional] 
**ProductId** | Pointer to **string** | Carrier product for the new shipment. Copied from the original if omitted. | [optional] 
**Services** | Pointer to **[]string** | Service codes for the new shipment. Copied from the original if omitted. | [optional] 
**AdditionalParameters** | Pointer to **map[string]interface{}** | Carrier-specific parameters for the new shipment. | [optional] 
**Reference** | Pointer to **string** | Reference for the new shipment. Defaults to the original reference with a suffix. | [optional] 

## Methods

### NewSplitShipmentRequest

`func NewSplitShipmentRequest(parcelId string, ) *SplitShipmentRequest`

NewSplitShipmentRequest instantiates a new SplitShipmentRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSplitShipmentRequestWithDefaults

`func NewSplitShipmentRequestWithDefaults() *SplitShipmentRequest`

NewSplitShipmentRequestWithDefaults instantiates a new SplitShipmentRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetParcelId

`func (o *SplitShipmentRequest) GetParcelId() string`

GetParcelId returns the ParcelId field if non-nil, zero value otherwise.

### GetParcelIdOk

`func (o *SplitShipmentRequest) GetParcelIdOk() (*string, bool)`

GetParcelIdOk returns a tuple with the ParcelId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParcelId

`func (o *SplitShipmentRequest) SetParcelId(v string)`

SetParcelId sets ParcelId field to given value.


### GetOrderLineIds

`func (o *SplitShipmentRequest) GetOrderLineIds() []string`

GetOrderLineIds returns the OrderLineIds field if non-nil, zero value otherwise.

### GetOrderLineIdsOk

`func (o *SplitShipmentRequest) GetOrderLineIdsOk() (*[]string, bool)`

GetOrderLineIdsOk returns a tuple with the OrderLineIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderLineIds

`func (o *SplitShipmentRequest) SetOrderLineIds(v []string)`

SetOrderLineIds sets OrderLineIds field to given value.

### HasOrderLineIds

`func (o *SplitShipmentRequest) HasOrderLineIds() bool`

HasOrderLineIds returns a boolean if a field has been set.

### GetCarrierId

`func (o *SplitShipmentRequest) GetCarrierId() string`

GetCarrierId returns the CarrierId field if non-nil, zero value otherwise.

### GetCarrierIdOk

`func (o *SplitShipmentRequest) GetCarrierIdOk() (*string, bool)`

GetCarrierIdOk returns a tuple with the CarrierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierId

`func (o *SplitShipmentRequest) SetCarrierId(v string)`

SetCarrierId sets CarrierId field to given value.

### HasCarrierId

`func (o *SplitShipmentRequest) HasCarrierId() bool`

HasCarrierId returns a boolean if a field has been set.

### GetProductId

`func (o *SplitShipmentRequest) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *SplitShipmentRequest) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *SplitShipmentRequest) SetProductId(v string)`

SetProductId sets ProductId field to given value.

### HasProductId

`func (o *SplitShipmentRequest) HasProductId() bool`

HasProductId returns a boolean if a field has been set.

### GetServices

`func (o *SplitShipmentRequest) GetServices() []string`

GetServices returns the Services field if non-nil, zero value otherwise.

### GetServicesOk

`func (o *SplitShipmentRequest) GetServicesOk() (*[]string, bool)`

GetServicesOk returns a tuple with the Services field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServices

`func (o *SplitShipmentRequest) SetServices(v []string)`

SetServices sets Services field to given value.

### HasServices

`func (o *SplitShipmentRequest) HasServices() bool`

HasServices returns a boolean if a field has been set.

### GetAdditionalParameters

`func (o *SplitShipmentRequest) GetAdditionalParameters() map[string]interface{}`

GetAdditionalParameters returns the AdditionalParameters field if non-nil, zero value otherwise.

### GetAdditionalParametersOk

`func (o *SplitShipmentRequest) GetAdditionalParametersOk() (*map[string]interface{}, bool)`

GetAdditionalParametersOk returns a tuple with the AdditionalParameters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditionalParameters

`func (o *SplitShipmentRequest) SetAdditionalParameters(v map[string]interface{})`

SetAdditionalParameters sets AdditionalParameters field to given value.

### HasAdditionalParameters

`func (o *SplitShipmentRequest) HasAdditionalParameters() bool`

HasAdditionalParameters returns a boolean if a field has been set.

### GetReference

`func (o *SplitShipmentRequest) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *SplitShipmentRequest) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *SplitShipmentRequest) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *SplitShipmentRequest) HasReference() bool`

HasReference returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


