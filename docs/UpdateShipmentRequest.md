# UpdateShipmentRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Reference** | Pointer to **string** | Customer-facing shipment reference. | [optional] 
**AddressId** | Pointer to **NullableString** | Sender address identifier. | [optional] 
**ServicePointId** | Pointer to **NullableString** | Selected carrier service point identifier. | [optional] 
**Parties** | Pointer to [**[]CreateShipmentRequestPartiesInner**](CreateShipmentRequestPartiesInner.md) | Parties involved in the shipment. Optional when orderId is provided. | [optional] 
**Type** | Pointer to **string** | Direction of the shipment relative to the organization. | [optional] 
**CarrierSettings** | Pointer to [**UpdateShipmentRequestCarrierSettings**](UpdateShipmentRequestCarrierSettings.md) |  | [optional] 
**Parcels** | Pointer to [**[]CreateShipmentRequestParcelsInner**](CreateShipmentRequestParcelsInner.md) | Parcels to include. Optional when orderId is provided. | [optional] 
**PickupDetails** | Pointer to [**NullableCreateShipmentRequestPickupDetails**](CreateShipmentRequestPickupDetails.md) |  | [optional] 
**TermOfTrade** | Pointer to **string** | Incoterm governing the shipment. | [optional] [default to "DAP"]
**Status** | Pointer to **string** | Lifecycle status of the shipment. | [optional] [default to "pending"]
**OrderId** | Pointer to **NullableString** | Order to derive parties and parcels from. | [optional] 
**LabelPrinterId** | Pointer to **NullableString** | Printer to assign for labels. | [optional] 
**DocumentPrinterId** | Pointer to **NullableString** | Printer to assign for documents. | [optional] 
**ShippingRuleId** | Pointer to **NullableString** | Shipping rule to apply to the shipment. Pass null to clear. | [optional] 
**Droppoint** | Pointer to [**UpdateShipmentRequestDroppoint**](UpdateShipmentRequestDroppoint.md) |  | [optional] 

## Methods

### NewUpdateShipmentRequest

`func NewUpdateShipmentRequest() *UpdateShipmentRequest`

NewUpdateShipmentRequest instantiates a new UpdateShipmentRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateShipmentRequestWithDefaults

`func NewUpdateShipmentRequestWithDefaults() *UpdateShipmentRequest`

NewUpdateShipmentRequestWithDefaults instantiates a new UpdateShipmentRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetReference

`func (o *UpdateShipmentRequest) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *UpdateShipmentRequest) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *UpdateShipmentRequest) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *UpdateShipmentRequest) HasReference() bool`

HasReference returns a boolean if a field has been set.

### GetAddressId

`func (o *UpdateShipmentRequest) GetAddressId() string`

GetAddressId returns the AddressId field if non-nil, zero value otherwise.

### GetAddressIdOk

`func (o *UpdateShipmentRequest) GetAddressIdOk() (*string, bool)`

GetAddressIdOk returns a tuple with the AddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressId

`func (o *UpdateShipmentRequest) SetAddressId(v string)`

SetAddressId sets AddressId field to given value.

### HasAddressId

`func (o *UpdateShipmentRequest) HasAddressId() bool`

HasAddressId returns a boolean if a field has been set.

### SetAddressIdNil

`func (o *UpdateShipmentRequest) SetAddressIdNil(b bool)`

 SetAddressIdNil sets the value for AddressId to be an explicit nil

### UnsetAddressId
`func (o *UpdateShipmentRequest) UnsetAddressId()`

UnsetAddressId ensures that no value is present for AddressId, not even an explicit nil
### GetServicePointId

`func (o *UpdateShipmentRequest) GetServicePointId() string`

GetServicePointId returns the ServicePointId field if non-nil, zero value otherwise.

### GetServicePointIdOk

`func (o *UpdateShipmentRequest) GetServicePointIdOk() (*string, bool)`

GetServicePointIdOk returns a tuple with the ServicePointId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServicePointId

`func (o *UpdateShipmentRequest) SetServicePointId(v string)`

SetServicePointId sets ServicePointId field to given value.

### HasServicePointId

`func (o *UpdateShipmentRequest) HasServicePointId() bool`

HasServicePointId returns a boolean if a field has been set.

### SetServicePointIdNil

`func (o *UpdateShipmentRequest) SetServicePointIdNil(b bool)`

 SetServicePointIdNil sets the value for ServicePointId to be an explicit nil

### UnsetServicePointId
`func (o *UpdateShipmentRequest) UnsetServicePointId()`

UnsetServicePointId ensures that no value is present for ServicePointId, not even an explicit nil
### GetParties

`func (o *UpdateShipmentRequest) GetParties() []CreateShipmentRequestPartiesInner`

GetParties returns the Parties field if non-nil, zero value otherwise.

### GetPartiesOk

`func (o *UpdateShipmentRequest) GetPartiesOk() (*[]CreateShipmentRequestPartiesInner, bool)`

GetPartiesOk returns a tuple with the Parties field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParties

`func (o *UpdateShipmentRequest) SetParties(v []CreateShipmentRequestPartiesInner)`

SetParties sets Parties field to given value.

### HasParties

`func (o *UpdateShipmentRequest) HasParties() bool`

HasParties returns a boolean if a field has been set.

### GetType

`func (o *UpdateShipmentRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *UpdateShipmentRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *UpdateShipmentRequest) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *UpdateShipmentRequest) HasType() bool`

HasType returns a boolean if a field has been set.

### GetCarrierSettings

`func (o *UpdateShipmentRequest) GetCarrierSettings() UpdateShipmentRequestCarrierSettings`

GetCarrierSettings returns the CarrierSettings field if non-nil, zero value otherwise.

### GetCarrierSettingsOk

`func (o *UpdateShipmentRequest) GetCarrierSettingsOk() (*UpdateShipmentRequestCarrierSettings, bool)`

GetCarrierSettingsOk returns a tuple with the CarrierSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierSettings

`func (o *UpdateShipmentRequest) SetCarrierSettings(v UpdateShipmentRequestCarrierSettings)`

SetCarrierSettings sets CarrierSettings field to given value.

### HasCarrierSettings

`func (o *UpdateShipmentRequest) HasCarrierSettings() bool`

HasCarrierSettings returns a boolean if a field has been set.

### GetParcels

`func (o *UpdateShipmentRequest) GetParcels() []CreateShipmentRequestParcelsInner`

GetParcels returns the Parcels field if non-nil, zero value otherwise.

### GetParcelsOk

`func (o *UpdateShipmentRequest) GetParcelsOk() (*[]CreateShipmentRequestParcelsInner, bool)`

GetParcelsOk returns a tuple with the Parcels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParcels

`func (o *UpdateShipmentRequest) SetParcels(v []CreateShipmentRequestParcelsInner)`

SetParcels sets Parcels field to given value.

### HasParcels

`func (o *UpdateShipmentRequest) HasParcels() bool`

HasParcels returns a boolean if a field has been set.

### GetPickupDetails

`func (o *UpdateShipmentRequest) GetPickupDetails() CreateShipmentRequestPickupDetails`

GetPickupDetails returns the PickupDetails field if non-nil, zero value otherwise.

### GetPickupDetailsOk

`func (o *UpdateShipmentRequest) GetPickupDetailsOk() (*CreateShipmentRequestPickupDetails, bool)`

GetPickupDetailsOk returns a tuple with the PickupDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPickupDetails

`func (o *UpdateShipmentRequest) SetPickupDetails(v CreateShipmentRequestPickupDetails)`

SetPickupDetails sets PickupDetails field to given value.

### HasPickupDetails

`func (o *UpdateShipmentRequest) HasPickupDetails() bool`

HasPickupDetails returns a boolean if a field has been set.

### SetPickupDetailsNil

`func (o *UpdateShipmentRequest) SetPickupDetailsNil(b bool)`

 SetPickupDetailsNil sets the value for PickupDetails to be an explicit nil

### UnsetPickupDetails
`func (o *UpdateShipmentRequest) UnsetPickupDetails()`

UnsetPickupDetails ensures that no value is present for PickupDetails, not even an explicit nil
### GetTermOfTrade

`func (o *UpdateShipmentRequest) GetTermOfTrade() string`

GetTermOfTrade returns the TermOfTrade field if non-nil, zero value otherwise.

### GetTermOfTradeOk

`func (o *UpdateShipmentRequest) GetTermOfTradeOk() (*string, bool)`

GetTermOfTradeOk returns a tuple with the TermOfTrade field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTermOfTrade

`func (o *UpdateShipmentRequest) SetTermOfTrade(v string)`

SetTermOfTrade sets TermOfTrade field to given value.

### HasTermOfTrade

`func (o *UpdateShipmentRequest) HasTermOfTrade() bool`

HasTermOfTrade returns a boolean if a field has been set.

### GetStatus

`func (o *UpdateShipmentRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *UpdateShipmentRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *UpdateShipmentRequest) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *UpdateShipmentRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetOrderId

`func (o *UpdateShipmentRequest) GetOrderId() string`

GetOrderId returns the OrderId field if non-nil, zero value otherwise.

### GetOrderIdOk

`func (o *UpdateShipmentRequest) GetOrderIdOk() (*string, bool)`

GetOrderIdOk returns a tuple with the OrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderId

`func (o *UpdateShipmentRequest) SetOrderId(v string)`

SetOrderId sets OrderId field to given value.

### HasOrderId

`func (o *UpdateShipmentRequest) HasOrderId() bool`

HasOrderId returns a boolean if a field has been set.

### SetOrderIdNil

`func (o *UpdateShipmentRequest) SetOrderIdNil(b bool)`

 SetOrderIdNil sets the value for OrderId to be an explicit nil

### UnsetOrderId
`func (o *UpdateShipmentRequest) UnsetOrderId()`

UnsetOrderId ensures that no value is present for OrderId, not even an explicit nil
### GetLabelPrinterId

`func (o *UpdateShipmentRequest) GetLabelPrinterId() string`

GetLabelPrinterId returns the LabelPrinterId field if non-nil, zero value otherwise.

### GetLabelPrinterIdOk

`func (o *UpdateShipmentRequest) GetLabelPrinterIdOk() (*string, bool)`

GetLabelPrinterIdOk returns a tuple with the LabelPrinterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabelPrinterId

`func (o *UpdateShipmentRequest) SetLabelPrinterId(v string)`

SetLabelPrinterId sets LabelPrinterId field to given value.

### HasLabelPrinterId

`func (o *UpdateShipmentRequest) HasLabelPrinterId() bool`

HasLabelPrinterId returns a boolean if a field has been set.

### SetLabelPrinterIdNil

`func (o *UpdateShipmentRequest) SetLabelPrinterIdNil(b bool)`

 SetLabelPrinterIdNil sets the value for LabelPrinterId to be an explicit nil

### UnsetLabelPrinterId
`func (o *UpdateShipmentRequest) UnsetLabelPrinterId()`

UnsetLabelPrinterId ensures that no value is present for LabelPrinterId, not even an explicit nil
### GetDocumentPrinterId

`func (o *UpdateShipmentRequest) GetDocumentPrinterId() string`

GetDocumentPrinterId returns the DocumentPrinterId field if non-nil, zero value otherwise.

### GetDocumentPrinterIdOk

`func (o *UpdateShipmentRequest) GetDocumentPrinterIdOk() (*string, bool)`

GetDocumentPrinterIdOk returns a tuple with the DocumentPrinterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocumentPrinterId

`func (o *UpdateShipmentRequest) SetDocumentPrinterId(v string)`

SetDocumentPrinterId sets DocumentPrinterId field to given value.

### HasDocumentPrinterId

`func (o *UpdateShipmentRequest) HasDocumentPrinterId() bool`

HasDocumentPrinterId returns a boolean if a field has been set.

### SetDocumentPrinterIdNil

`func (o *UpdateShipmentRequest) SetDocumentPrinterIdNil(b bool)`

 SetDocumentPrinterIdNil sets the value for DocumentPrinterId to be an explicit nil

### UnsetDocumentPrinterId
`func (o *UpdateShipmentRequest) UnsetDocumentPrinterId()`

UnsetDocumentPrinterId ensures that no value is present for DocumentPrinterId, not even an explicit nil
### GetShippingRuleId

`func (o *UpdateShipmentRequest) GetShippingRuleId() string`

GetShippingRuleId returns the ShippingRuleId field if non-nil, zero value otherwise.

### GetShippingRuleIdOk

`func (o *UpdateShipmentRequest) GetShippingRuleIdOk() (*string, bool)`

GetShippingRuleIdOk returns a tuple with the ShippingRuleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingRuleId

`func (o *UpdateShipmentRequest) SetShippingRuleId(v string)`

SetShippingRuleId sets ShippingRuleId field to given value.

### HasShippingRuleId

`func (o *UpdateShipmentRequest) HasShippingRuleId() bool`

HasShippingRuleId returns a boolean if a field has been set.

### SetShippingRuleIdNil

`func (o *UpdateShipmentRequest) SetShippingRuleIdNil(b bool)`

 SetShippingRuleIdNil sets the value for ShippingRuleId to be an explicit nil

### UnsetShippingRuleId
`func (o *UpdateShipmentRequest) UnsetShippingRuleId()`

UnsetShippingRuleId ensures that no value is present for ShippingRuleId, not even an explicit nil
### GetDroppoint

`func (o *UpdateShipmentRequest) GetDroppoint() UpdateShipmentRequestDroppoint`

GetDroppoint returns the Droppoint field if non-nil, zero value otherwise.

### GetDroppointOk

`func (o *UpdateShipmentRequest) GetDroppointOk() (*UpdateShipmentRequestDroppoint, bool)`

GetDroppointOk returns a tuple with the Droppoint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDroppoint

`func (o *UpdateShipmentRequest) SetDroppoint(v UpdateShipmentRequestDroppoint)`

SetDroppoint sets Droppoint field to given value.

### HasDroppoint

`func (o *UpdateShipmentRequest) HasDroppoint() bool`

HasDroppoint returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


