# CreateShipmentRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Reference** | Pointer to **string** | Customer-facing shipment reference. | [optional] 
**AddressId** | Pointer to **NullableString** | Sender address identifier. | [optional] 
**ServicePointId** | Pointer to **NullableString** | Selected carrier service point identifier. | [optional] 
**Parties** | Pointer to [**[]CreateShipmentRequestPartiesInner**](CreateShipmentRequestPartiesInner.md) | Parties involved in the shipment. Optional when orderId is provided. | [optional] 
**Type** | **string** | Direction of the shipment relative to the organization. | 
**CarrierSettings** | Pointer to [**CreateShipmentRequestCarrierSettings**](CreateShipmentRequestCarrierSettings.md) |  | [optional] 
**Parcels** | Pointer to [**[]CreateShipmentRequestParcelsInner**](CreateShipmentRequestParcelsInner.md) | Parcels to include. Optional when orderId is provided. | [optional] 
**PickupDetails** | Pointer to [**NullableCreateShipmentRequestPickupDetails**](CreateShipmentRequestPickupDetails.md) |  | [optional] 
**TermOfTrade** | Pointer to **string** | Incoterm governing the shipment. | [optional] [default to "DAP"]
**Status** | Pointer to **string** | Lifecycle status of the shipment. | [optional] [default to "pending"]
**OrderId** | Pointer to **NullableString** | Order to derive parties and parcels from. | [optional] 
**LabelPrinterId** | Pointer to **NullableString** | Printer to assign for labels. | [optional] 
**DocumentPrinterId** | Pointer to **NullableString** | Printer to assign for documents. | [optional] 
**ShippingRuleId** | Pointer to **string** | Create the shipment from this shipping rule: carrier settings and the sender address derive from the rule (explicit carrierSettings and addressId are then ignored). | [optional] 
**Droppoint** | Pointer to [**CreateShipmentRequestDroppoint**](CreateShipmentRequestDroppoint.md) |  | [optional] 

## Methods

### NewCreateShipmentRequest

`func NewCreateShipmentRequest(type_ string, ) *CreateShipmentRequest`

NewCreateShipmentRequest instantiates a new CreateShipmentRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateShipmentRequestWithDefaults

`func NewCreateShipmentRequestWithDefaults() *CreateShipmentRequest`

NewCreateShipmentRequestWithDefaults instantiates a new CreateShipmentRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetReference

`func (o *CreateShipmentRequest) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *CreateShipmentRequest) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *CreateShipmentRequest) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *CreateShipmentRequest) HasReference() bool`

HasReference returns a boolean if a field has been set.

### GetAddressId

`func (o *CreateShipmentRequest) GetAddressId() string`

GetAddressId returns the AddressId field if non-nil, zero value otherwise.

### GetAddressIdOk

`func (o *CreateShipmentRequest) GetAddressIdOk() (*string, bool)`

GetAddressIdOk returns a tuple with the AddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressId

`func (o *CreateShipmentRequest) SetAddressId(v string)`

SetAddressId sets AddressId field to given value.

### HasAddressId

`func (o *CreateShipmentRequest) HasAddressId() bool`

HasAddressId returns a boolean if a field has been set.

### SetAddressIdNil

`func (o *CreateShipmentRequest) SetAddressIdNil(b bool)`

 SetAddressIdNil sets the value for AddressId to be an explicit nil

### UnsetAddressId
`func (o *CreateShipmentRequest) UnsetAddressId()`

UnsetAddressId ensures that no value is present for AddressId, not even an explicit nil
### GetServicePointId

`func (o *CreateShipmentRequest) GetServicePointId() string`

GetServicePointId returns the ServicePointId field if non-nil, zero value otherwise.

### GetServicePointIdOk

`func (o *CreateShipmentRequest) GetServicePointIdOk() (*string, bool)`

GetServicePointIdOk returns a tuple with the ServicePointId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServicePointId

`func (o *CreateShipmentRequest) SetServicePointId(v string)`

SetServicePointId sets ServicePointId field to given value.

### HasServicePointId

`func (o *CreateShipmentRequest) HasServicePointId() bool`

HasServicePointId returns a boolean if a field has been set.

### SetServicePointIdNil

`func (o *CreateShipmentRequest) SetServicePointIdNil(b bool)`

 SetServicePointIdNil sets the value for ServicePointId to be an explicit nil

### UnsetServicePointId
`func (o *CreateShipmentRequest) UnsetServicePointId()`

UnsetServicePointId ensures that no value is present for ServicePointId, not even an explicit nil
### GetParties

`func (o *CreateShipmentRequest) GetParties() []CreateShipmentRequestPartiesInner`

GetParties returns the Parties field if non-nil, zero value otherwise.

### GetPartiesOk

`func (o *CreateShipmentRequest) GetPartiesOk() (*[]CreateShipmentRequestPartiesInner, bool)`

GetPartiesOk returns a tuple with the Parties field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParties

`func (o *CreateShipmentRequest) SetParties(v []CreateShipmentRequestPartiesInner)`

SetParties sets Parties field to given value.

### HasParties

`func (o *CreateShipmentRequest) HasParties() bool`

HasParties returns a boolean if a field has been set.

### GetType

`func (o *CreateShipmentRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CreateShipmentRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CreateShipmentRequest) SetType(v string)`

SetType sets Type field to given value.


### GetCarrierSettings

`func (o *CreateShipmentRequest) GetCarrierSettings() CreateShipmentRequestCarrierSettings`

GetCarrierSettings returns the CarrierSettings field if non-nil, zero value otherwise.

### GetCarrierSettingsOk

`func (o *CreateShipmentRequest) GetCarrierSettingsOk() (*CreateShipmentRequestCarrierSettings, bool)`

GetCarrierSettingsOk returns a tuple with the CarrierSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierSettings

`func (o *CreateShipmentRequest) SetCarrierSettings(v CreateShipmentRequestCarrierSettings)`

SetCarrierSettings sets CarrierSettings field to given value.

### HasCarrierSettings

`func (o *CreateShipmentRequest) HasCarrierSettings() bool`

HasCarrierSettings returns a boolean if a field has been set.

### GetParcels

`func (o *CreateShipmentRequest) GetParcels() []CreateShipmentRequestParcelsInner`

GetParcels returns the Parcels field if non-nil, zero value otherwise.

### GetParcelsOk

`func (o *CreateShipmentRequest) GetParcelsOk() (*[]CreateShipmentRequestParcelsInner, bool)`

GetParcelsOk returns a tuple with the Parcels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParcels

`func (o *CreateShipmentRequest) SetParcels(v []CreateShipmentRequestParcelsInner)`

SetParcels sets Parcels field to given value.

### HasParcels

`func (o *CreateShipmentRequest) HasParcels() bool`

HasParcels returns a boolean if a field has been set.

### GetPickupDetails

`func (o *CreateShipmentRequest) GetPickupDetails() CreateShipmentRequestPickupDetails`

GetPickupDetails returns the PickupDetails field if non-nil, zero value otherwise.

### GetPickupDetailsOk

`func (o *CreateShipmentRequest) GetPickupDetailsOk() (*CreateShipmentRequestPickupDetails, bool)`

GetPickupDetailsOk returns a tuple with the PickupDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPickupDetails

`func (o *CreateShipmentRequest) SetPickupDetails(v CreateShipmentRequestPickupDetails)`

SetPickupDetails sets PickupDetails field to given value.

### HasPickupDetails

`func (o *CreateShipmentRequest) HasPickupDetails() bool`

HasPickupDetails returns a boolean if a field has been set.

### SetPickupDetailsNil

`func (o *CreateShipmentRequest) SetPickupDetailsNil(b bool)`

 SetPickupDetailsNil sets the value for PickupDetails to be an explicit nil

### UnsetPickupDetails
`func (o *CreateShipmentRequest) UnsetPickupDetails()`

UnsetPickupDetails ensures that no value is present for PickupDetails, not even an explicit nil
### GetTermOfTrade

`func (o *CreateShipmentRequest) GetTermOfTrade() string`

GetTermOfTrade returns the TermOfTrade field if non-nil, zero value otherwise.

### GetTermOfTradeOk

`func (o *CreateShipmentRequest) GetTermOfTradeOk() (*string, bool)`

GetTermOfTradeOk returns a tuple with the TermOfTrade field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTermOfTrade

`func (o *CreateShipmentRequest) SetTermOfTrade(v string)`

SetTermOfTrade sets TermOfTrade field to given value.

### HasTermOfTrade

`func (o *CreateShipmentRequest) HasTermOfTrade() bool`

HasTermOfTrade returns a boolean if a field has been set.

### GetStatus

`func (o *CreateShipmentRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CreateShipmentRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CreateShipmentRequest) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *CreateShipmentRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetOrderId

`func (o *CreateShipmentRequest) GetOrderId() string`

GetOrderId returns the OrderId field if non-nil, zero value otherwise.

### GetOrderIdOk

`func (o *CreateShipmentRequest) GetOrderIdOk() (*string, bool)`

GetOrderIdOk returns a tuple with the OrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderId

`func (o *CreateShipmentRequest) SetOrderId(v string)`

SetOrderId sets OrderId field to given value.

### HasOrderId

`func (o *CreateShipmentRequest) HasOrderId() bool`

HasOrderId returns a boolean if a field has been set.

### SetOrderIdNil

`func (o *CreateShipmentRequest) SetOrderIdNil(b bool)`

 SetOrderIdNil sets the value for OrderId to be an explicit nil

### UnsetOrderId
`func (o *CreateShipmentRequest) UnsetOrderId()`

UnsetOrderId ensures that no value is present for OrderId, not even an explicit nil
### GetLabelPrinterId

`func (o *CreateShipmentRequest) GetLabelPrinterId() string`

GetLabelPrinterId returns the LabelPrinterId field if non-nil, zero value otherwise.

### GetLabelPrinterIdOk

`func (o *CreateShipmentRequest) GetLabelPrinterIdOk() (*string, bool)`

GetLabelPrinterIdOk returns a tuple with the LabelPrinterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabelPrinterId

`func (o *CreateShipmentRequest) SetLabelPrinterId(v string)`

SetLabelPrinterId sets LabelPrinterId field to given value.

### HasLabelPrinterId

`func (o *CreateShipmentRequest) HasLabelPrinterId() bool`

HasLabelPrinterId returns a boolean if a field has been set.

### SetLabelPrinterIdNil

`func (o *CreateShipmentRequest) SetLabelPrinterIdNil(b bool)`

 SetLabelPrinterIdNil sets the value for LabelPrinterId to be an explicit nil

### UnsetLabelPrinterId
`func (o *CreateShipmentRequest) UnsetLabelPrinterId()`

UnsetLabelPrinterId ensures that no value is present for LabelPrinterId, not even an explicit nil
### GetDocumentPrinterId

`func (o *CreateShipmentRequest) GetDocumentPrinterId() string`

GetDocumentPrinterId returns the DocumentPrinterId field if non-nil, zero value otherwise.

### GetDocumentPrinterIdOk

`func (o *CreateShipmentRequest) GetDocumentPrinterIdOk() (*string, bool)`

GetDocumentPrinterIdOk returns a tuple with the DocumentPrinterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocumentPrinterId

`func (o *CreateShipmentRequest) SetDocumentPrinterId(v string)`

SetDocumentPrinterId sets DocumentPrinterId field to given value.

### HasDocumentPrinterId

`func (o *CreateShipmentRequest) HasDocumentPrinterId() bool`

HasDocumentPrinterId returns a boolean if a field has been set.

### SetDocumentPrinterIdNil

`func (o *CreateShipmentRequest) SetDocumentPrinterIdNil(b bool)`

 SetDocumentPrinterIdNil sets the value for DocumentPrinterId to be an explicit nil

### UnsetDocumentPrinterId
`func (o *CreateShipmentRequest) UnsetDocumentPrinterId()`

UnsetDocumentPrinterId ensures that no value is present for DocumentPrinterId, not even an explicit nil
### GetShippingRuleId

`func (o *CreateShipmentRequest) GetShippingRuleId() string`

GetShippingRuleId returns the ShippingRuleId field if non-nil, zero value otherwise.

### GetShippingRuleIdOk

`func (o *CreateShipmentRequest) GetShippingRuleIdOk() (*string, bool)`

GetShippingRuleIdOk returns a tuple with the ShippingRuleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingRuleId

`func (o *CreateShipmentRequest) SetShippingRuleId(v string)`

SetShippingRuleId sets ShippingRuleId field to given value.

### HasShippingRuleId

`func (o *CreateShipmentRequest) HasShippingRuleId() bool`

HasShippingRuleId returns a boolean if a field has been set.

### GetDroppoint

`func (o *CreateShipmentRequest) GetDroppoint() CreateShipmentRequestDroppoint`

GetDroppoint returns the Droppoint field if non-nil, zero value otherwise.

### GetDroppointOk

`func (o *CreateShipmentRequest) GetDroppointOk() (*CreateShipmentRequestDroppoint, bool)`

GetDroppointOk returns a tuple with the Droppoint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDroppoint

`func (o *CreateShipmentRequest) SetDroppoint(v CreateShipmentRequestDroppoint)`

SetDroppoint sets Droppoint field to given value.

### HasDroppoint

`func (o *CreateShipmentRequest) HasDroppoint() bool`

HasDroppoint returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


