# BatchSplitShipmentRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ParcelId** | **string** | Parcel whose order lines are split across new shipments. | 
**Shipments** | [**[]BatchSplitShipmentRequestShipmentsInner**](BatchSplitShipmentRequestShipmentsInner.md) | New shipments to create from the split parcel. | 
**CarrierId** | Pointer to **string** | Carrier for all new shipments. Copied from the original if omitted. | [optional] 
**ProductId** | Pointer to **string** | Carrier product for all new shipments. Copied from the original if omitted. | [optional] 
**Services** | Pointer to **[]string** | Service codes for all new shipments. Copied from the original if omitted. | [optional] 
**AdditionalParameters** | Pointer to [**map[string]CreateShippingRuleRequestAdditionalParametersValue**](CreateShippingRuleRequestAdditionalParametersValue.md) | Carrier-specific parameters for all new shipments. Copied from the original if omitted. | [optional] 

## Methods

### NewBatchSplitShipmentRequest

`func NewBatchSplitShipmentRequest(parcelId string, shipments []BatchSplitShipmentRequestShipmentsInner, ) *BatchSplitShipmentRequest`

NewBatchSplitShipmentRequest instantiates a new BatchSplitShipmentRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBatchSplitShipmentRequestWithDefaults

`func NewBatchSplitShipmentRequestWithDefaults() *BatchSplitShipmentRequest`

NewBatchSplitShipmentRequestWithDefaults instantiates a new BatchSplitShipmentRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetParcelId

`func (o *BatchSplitShipmentRequest) GetParcelId() string`

GetParcelId returns the ParcelId field if non-nil, zero value otherwise.

### GetParcelIdOk

`func (o *BatchSplitShipmentRequest) GetParcelIdOk() (*string, bool)`

GetParcelIdOk returns a tuple with the ParcelId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParcelId

`func (o *BatchSplitShipmentRequest) SetParcelId(v string)`

SetParcelId sets ParcelId field to given value.


### GetShipments

`func (o *BatchSplitShipmentRequest) GetShipments() []BatchSplitShipmentRequestShipmentsInner`

GetShipments returns the Shipments field if non-nil, zero value otherwise.

### GetShipmentsOk

`func (o *BatchSplitShipmentRequest) GetShipmentsOk() (*[]BatchSplitShipmentRequestShipmentsInner, bool)`

GetShipmentsOk returns a tuple with the Shipments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipments

`func (o *BatchSplitShipmentRequest) SetShipments(v []BatchSplitShipmentRequestShipmentsInner)`

SetShipments sets Shipments field to given value.


### GetCarrierId

`func (o *BatchSplitShipmentRequest) GetCarrierId() string`

GetCarrierId returns the CarrierId field if non-nil, zero value otherwise.

### GetCarrierIdOk

`func (o *BatchSplitShipmentRequest) GetCarrierIdOk() (*string, bool)`

GetCarrierIdOk returns a tuple with the CarrierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierId

`func (o *BatchSplitShipmentRequest) SetCarrierId(v string)`

SetCarrierId sets CarrierId field to given value.

### HasCarrierId

`func (o *BatchSplitShipmentRequest) HasCarrierId() bool`

HasCarrierId returns a boolean if a field has been set.

### GetProductId

`func (o *BatchSplitShipmentRequest) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *BatchSplitShipmentRequest) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *BatchSplitShipmentRequest) SetProductId(v string)`

SetProductId sets ProductId field to given value.

### HasProductId

`func (o *BatchSplitShipmentRequest) HasProductId() bool`

HasProductId returns a boolean if a field has been set.

### GetServices

`func (o *BatchSplitShipmentRequest) GetServices() []string`

GetServices returns the Services field if non-nil, zero value otherwise.

### GetServicesOk

`func (o *BatchSplitShipmentRequest) GetServicesOk() (*[]string, bool)`

GetServicesOk returns a tuple with the Services field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServices

`func (o *BatchSplitShipmentRequest) SetServices(v []string)`

SetServices sets Services field to given value.

### HasServices

`func (o *BatchSplitShipmentRequest) HasServices() bool`

HasServices returns a boolean if a field has been set.

### GetAdditionalParameters

`func (o *BatchSplitShipmentRequest) GetAdditionalParameters() map[string]CreateShippingRuleRequestAdditionalParametersValue`

GetAdditionalParameters returns the AdditionalParameters field if non-nil, zero value otherwise.

### GetAdditionalParametersOk

`func (o *BatchSplitShipmentRequest) GetAdditionalParametersOk() (*map[string]CreateShippingRuleRequestAdditionalParametersValue, bool)`

GetAdditionalParametersOk returns a tuple with the AdditionalParameters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditionalParameters

`func (o *BatchSplitShipmentRequest) SetAdditionalParameters(v map[string]CreateShippingRuleRequestAdditionalParametersValue)`

SetAdditionalParameters sets AdditionalParameters field to given value.

### HasAdditionalParameters

`func (o *BatchSplitShipmentRequest) HasAdditionalParameters() bool`

HasAdditionalParameters returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


