# CreateShipment201Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Unique shipment identifier. | 
**Reference** | **string** | Customer-facing shipment reference. | 
**AddressId** | Pointer to **NullableString** | Sender address identifier. | [optional] 
**ServicePointId** | Pointer to **NullableString** | Selected carrier service point identifier. | [optional] 
**Parties** | [**[]CreateShipment201ResponsePartiesInner**](CreateShipment201ResponsePartiesInner.md) | Parties involved in the shipment (sender, receiver, etc.). | 
**Type** | **string** | Direction of the shipment relative to the organization. | 
**CarrierSettings** | [**ListShipments200ResponseDataInnerCarrierSettings**](ListShipments200ResponseDataInnerCarrierSettings.md) |  | 
**Parcels** | [**[]CreateShipment201ResponseParcelsInner**](CreateShipment201ResponseParcelsInner.md) | Parcels included in the shipment. | 
**PickupDetails** | Pointer to [**NullableCreateShipment201ResponsePickupDetails**](CreateShipment201ResponsePickupDetails.md) |  | [optional] 
**TermOfTrade** | **string** | Incoterm governing the shipment. | [default to "DAP"]
**Documents** | Pointer to [**[]CreateShipment201ResponseDocumentsInner**](CreateShipment201ResponseDocumentsInner.md) | Documents generated for the shipment (labels, invoices). | [optional] 
**Errors** | [**[]CreateShipment201ResponseErrorsInner**](CreateShipment201ResponseErrorsInner.md) | Carrier errors recorded for the shipment. | [default to {}]
**Tracking** | Pointer to [**NullableCreateShipment201ResponseTracking**](CreateShipment201ResponseTracking.md) |  | [optional] 
**Status** | **string** | Lifecycle status of the shipment. | 
**OrgId** | **string** | Owning organization identifier. | 
**OrderId** | Pointer to **NullableString** | Associated order identifier. | [optional] 
**ShippingRuleId** | Pointer to **NullableString** | Applied shipping rule identifier. | [optional] 
**ShippingRule** | Pointer to [**NullableCreateShipment201ResponseShippingRule**](CreateShipment201ResponseShippingRule.md) |  | [optional] 
**LabelPrinterId** | Pointer to **NullableString** | Printer assigned for labels on this shipment. | [optional] 
**DocumentPrinterId** | Pointer to **NullableString** | Printer assigned for documents on this shipment. | [optional] 
**Logs** | [**[]CreateShipment201ResponseLogsInner**](CreateShipment201ResponseLogsInner.md) | Request/response logs captured during carrier interactions. | [default to {}]
**Activities** | [**[]CreateShipment201ResponseActivitiesInner**](CreateShipment201ResponseActivitiesInner.md) | Chronological activity history of the shipment. | [default to {}]
**CreatedAt** | **string** | Timestamp when the shipment was created. | 
**UpdatedAt** | **string** | Timestamp when the shipment was last updated. | 

## Methods

### NewCreateShipment201Response

`func NewCreateShipment201Response(id string, reference string, parties []CreateShipment201ResponsePartiesInner, type_ string, carrierSettings ListShipments200ResponseDataInnerCarrierSettings, parcels []CreateShipment201ResponseParcelsInner, termOfTrade string, errors []CreateShipment201ResponseErrorsInner, status string, orgId string, logs []CreateShipment201ResponseLogsInner, activities []CreateShipment201ResponseActivitiesInner, createdAt string, updatedAt string, ) *CreateShipment201Response`

NewCreateShipment201Response instantiates a new CreateShipment201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateShipment201ResponseWithDefaults

`func NewCreateShipment201ResponseWithDefaults() *CreateShipment201Response`

NewCreateShipment201ResponseWithDefaults instantiates a new CreateShipment201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreateShipment201Response) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateShipment201Response) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateShipment201Response) SetId(v string)`

SetId sets Id field to given value.


### GetReference

`func (o *CreateShipment201Response) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *CreateShipment201Response) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *CreateShipment201Response) SetReference(v string)`

SetReference sets Reference field to given value.


### GetAddressId

`func (o *CreateShipment201Response) GetAddressId() string`

GetAddressId returns the AddressId field if non-nil, zero value otherwise.

### GetAddressIdOk

`func (o *CreateShipment201Response) GetAddressIdOk() (*string, bool)`

GetAddressIdOk returns a tuple with the AddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressId

`func (o *CreateShipment201Response) SetAddressId(v string)`

SetAddressId sets AddressId field to given value.

### HasAddressId

`func (o *CreateShipment201Response) HasAddressId() bool`

HasAddressId returns a boolean if a field has been set.

### SetAddressIdNil

`func (o *CreateShipment201Response) SetAddressIdNil(b bool)`

 SetAddressIdNil sets the value for AddressId to be an explicit nil

### UnsetAddressId
`func (o *CreateShipment201Response) UnsetAddressId()`

UnsetAddressId ensures that no value is present for AddressId, not even an explicit nil
### GetServicePointId

`func (o *CreateShipment201Response) GetServicePointId() string`

GetServicePointId returns the ServicePointId field if non-nil, zero value otherwise.

### GetServicePointIdOk

`func (o *CreateShipment201Response) GetServicePointIdOk() (*string, bool)`

GetServicePointIdOk returns a tuple with the ServicePointId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServicePointId

`func (o *CreateShipment201Response) SetServicePointId(v string)`

SetServicePointId sets ServicePointId field to given value.

### HasServicePointId

`func (o *CreateShipment201Response) HasServicePointId() bool`

HasServicePointId returns a boolean if a field has been set.

### SetServicePointIdNil

`func (o *CreateShipment201Response) SetServicePointIdNil(b bool)`

 SetServicePointIdNil sets the value for ServicePointId to be an explicit nil

### UnsetServicePointId
`func (o *CreateShipment201Response) UnsetServicePointId()`

UnsetServicePointId ensures that no value is present for ServicePointId, not even an explicit nil
### GetParties

`func (o *CreateShipment201Response) GetParties() []CreateShipment201ResponsePartiesInner`

GetParties returns the Parties field if non-nil, zero value otherwise.

### GetPartiesOk

`func (o *CreateShipment201Response) GetPartiesOk() (*[]CreateShipment201ResponsePartiesInner, bool)`

GetPartiesOk returns a tuple with the Parties field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParties

`func (o *CreateShipment201Response) SetParties(v []CreateShipment201ResponsePartiesInner)`

SetParties sets Parties field to given value.


### GetType

`func (o *CreateShipment201Response) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CreateShipment201Response) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CreateShipment201Response) SetType(v string)`

SetType sets Type field to given value.


### GetCarrierSettings

`func (o *CreateShipment201Response) GetCarrierSettings() ListShipments200ResponseDataInnerCarrierSettings`

GetCarrierSettings returns the CarrierSettings field if non-nil, zero value otherwise.

### GetCarrierSettingsOk

`func (o *CreateShipment201Response) GetCarrierSettingsOk() (*ListShipments200ResponseDataInnerCarrierSettings, bool)`

GetCarrierSettingsOk returns a tuple with the CarrierSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierSettings

`func (o *CreateShipment201Response) SetCarrierSettings(v ListShipments200ResponseDataInnerCarrierSettings)`

SetCarrierSettings sets CarrierSettings field to given value.


### GetParcels

`func (o *CreateShipment201Response) GetParcels() []CreateShipment201ResponseParcelsInner`

GetParcels returns the Parcels field if non-nil, zero value otherwise.

### GetParcelsOk

`func (o *CreateShipment201Response) GetParcelsOk() (*[]CreateShipment201ResponseParcelsInner, bool)`

GetParcelsOk returns a tuple with the Parcels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParcels

`func (o *CreateShipment201Response) SetParcels(v []CreateShipment201ResponseParcelsInner)`

SetParcels sets Parcels field to given value.


### GetPickupDetails

`func (o *CreateShipment201Response) GetPickupDetails() CreateShipment201ResponsePickupDetails`

GetPickupDetails returns the PickupDetails field if non-nil, zero value otherwise.

### GetPickupDetailsOk

`func (o *CreateShipment201Response) GetPickupDetailsOk() (*CreateShipment201ResponsePickupDetails, bool)`

GetPickupDetailsOk returns a tuple with the PickupDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPickupDetails

`func (o *CreateShipment201Response) SetPickupDetails(v CreateShipment201ResponsePickupDetails)`

SetPickupDetails sets PickupDetails field to given value.

### HasPickupDetails

`func (o *CreateShipment201Response) HasPickupDetails() bool`

HasPickupDetails returns a boolean if a field has been set.

### SetPickupDetailsNil

`func (o *CreateShipment201Response) SetPickupDetailsNil(b bool)`

 SetPickupDetailsNil sets the value for PickupDetails to be an explicit nil

### UnsetPickupDetails
`func (o *CreateShipment201Response) UnsetPickupDetails()`

UnsetPickupDetails ensures that no value is present for PickupDetails, not even an explicit nil
### GetTermOfTrade

`func (o *CreateShipment201Response) GetTermOfTrade() string`

GetTermOfTrade returns the TermOfTrade field if non-nil, zero value otherwise.

### GetTermOfTradeOk

`func (o *CreateShipment201Response) GetTermOfTradeOk() (*string, bool)`

GetTermOfTradeOk returns a tuple with the TermOfTrade field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTermOfTrade

`func (o *CreateShipment201Response) SetTermOfTrade(v string)`

SetTermOfTrade sets TermOfTrade field to given value.


### GetDocuments

`func (o *CreateShipment201Response) GetDocuments() []CreateShipment201ResponseDocumentsInner`

GetDocuments returns the Documents field if non-nil, zero value otherwise.

### GetDocumentsOk

`func (o *CreateShipment201Response) GetDocumentsOk() (*[]CreateShipment201ResponseDocumentsInner, bool)`

GetDocumentsOk returns a tuple with the Documents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocuments

`func (o *CreateShipment201Response) SetDocuments(v []CreateShipment201ResponseDocumentsInner)`

SetDocuments sets Documents field to given value.

### HasDocuments

`func (o *CreateShipment201Response) HasDocuments() bool`

HasDocuments returns a boolean if a field has been set.

### GetErrors

`func (o *CreateShipment201Response) GetErrors() []CreateShipment201ResponseErrorsInner`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *CreateShipment201Response) GetErrorsOk() (*[]CreateShipment201ResponseErrorsInner, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *CreateShipment201Response) SetErrors(v []CreateShipment201ResponseErrorsInner)`

SetErrors sets Errors field to given value.


### GetTracking

`func (o *CreateShipment201Response) GetTracking() CreateShipment201ResponseTracking`

GetTracking returns the Tracking field if non-nil, zero value otherwise.

### GetTrackingOk

`func (o *CreateShipment201Response) GetTrackingOk() (*CreateShipment201ResponseTracking, bool)`

GetTrackingOk returns a tuple with the Tracking field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTracking

`func (o *CreateShipment201Response) SetTracking(v CreateShipment201ResponseTracking)`

SetTracking sets Tracking field to given value.

### HasTracking

`func (o *CreateShipment201Response) HasTracking() bool`

HasTracking returns a boolean if a field has been set.

### SetTrackingNil

`func (o *CreateShipment201Response) SetTrackingNil(b bool)`

 SetTrackingNil sets the value for Tracking to be an explicit nil

### UnsetTracking
`func (o *CreateShipment201Response) UnsetTracking()`

UnsetTracking ensures that no value is present for Tracking, not even an explicit nil
### GetStatus

`func (o *CreateShipment201Response) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CreateShipment201Response) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CreateShipment201Response) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetOrgId

`func (o *CreateShipment201Response) GetOrgId() string`

GetOrgId returns the OrgId field if non-nil, zero value otherwise.

### GetOrgIdOk

`func (o *CreateShipment201Response) GetOrgIdOk() (*string, bool)`

GetOrgIdOk returns a tuple with the OrgId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrgId

`func (o *CreateShipment201Response) SetOrgId(v string)`

SetOrgId sets OrgId field to given value.


### GetOrderId

`func (o *CreateShipment201Response) GetOrderId() string`

GetOrderId returns the OrderId field if non-nil, zero value otherwise.

### GetOrderIdOk

`func (o *CreateShipment201Response) GetOrderIdOk() (*string, bool)`

GetOrderIdOk returns a tuple with the OrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderId

`func (o *CreateShipment201Response) SetOrderId(v string)`

SetOrderId sets OrderId field to given value.

### HasOrderId

`func (o *CreateShipment201Response) HasOrderId() bool`

HasOrderId returns a boolean if a field has been set.

### SetOrderIdNil

`func (o *CreateShipment201Response) SetOrderIdNil(b bool)`

 SetOrderIdNil sets the value for OrderId to be an explicit nil

### UnsetOrderId
`func (o *CreateShipment201Response) UnsetOrderId()`

UnsetOrderId ensures that no value is present for OrderId, not even an explicit nil
### GetShippingRuleId

`func (o *CreateShipment201Response) GetShippingRuleId() string`

GetShippingRuleId returns the ShippingRuleId field if non-nil, zero value otherwise.

### GetShippingRuleIdOk

`func (o *CreateShipment201Response) GetShippingRuleIdOk() (*string, bool)`

GetShippingRuleIdOk returns a tuple with the ShippingRuleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingRuleId

`func (o *CreateShipment201Response) SetShippingRuleId(v string)`

SetShippingRuleId sets ShippingRuleId field to given value.

### HasShippingRuleId

`func (o *CreateShipment201Response) HasShippingRuleId() bool`

HasShippingRuleId returns a boolean if a field has been set.

### SetShippingRuleIdNil

`func (o *CreateShipment201Response) SetShippingRuleIdNil(b bool)`

 SetShippingRuleIdNil sets the value for ShippingRuleId to be an explicit nil

### UnsetShippingRuleId
`func (o *CreateShipment201Response) UnsetShippingRuleId()`

UnsetShippingRuleId ensures that no value is present for ShippingRuleId, not even an explicit nil
### GetShippingRule

`func (o *CreateShipment201Response) GetShippingRule() CreateShipment201ResponseShippingRule`

GetShippingRule returns the ShippingRule field if non-nil, zero value otherwise.

### GetShippingRuleOk

`func (o *CreateShipment201Response) GetShippingRuleOk() (*CreateShipment201ResponseShippingRule, bool)`

GetShippingRuleOk returns a tuple with the ShippingRule field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingRule

`func (o *CreateShipment201Response) SetShippingRule(v CreateShipment201ResponseShippingRule)`

SetShippingRule sets ShippingRule field to given value.

### HasShippingRule

`func (o *CreateShipment201Response) HasShippingRule() bool`

HasShippingRule returns a boolean if a field has been set.

### SetShippingRuleNil

`func (o *CreateShipment201Response) SetShippingRuleNil(b bool)`

 SetShippingRuleNil sets the value for ShippingRule to be an explicit nil

### UnsetShippingRule
`func (o *CreateShipment201Response) UnsetShippingRule()`

UnsetShippingRule ensures that no value is present for ShippingRule, not even an explicit nil
### GetLabelPrinterId

`func (o *CreateShipment201Response) GetLabelPrinterId() string`

GetLabelPrinterId returns the LabelPrinterId field if non-nil, zero value otherwise.

### GetLabelPrinterIdOk

`func (o *CreateShipment201Response) GetLabelPrinterIdOk() (*string, bool)`

GetLabelPrinterIdOk returns a tuple with the LabelPrinterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabelPrinterId

`func (o *CreateShipment201Response) SetLabelPrinterId(v string)`

SetLabelPrinterId sets LabelPrinterId field to given value.

### HasLabelPrinterId

`func (o *CreateShipment201Response) HasLabelPrinterId() bool`

HasLabelPrinterId returns a boolean if a field has been set.

### SetLabelPrinterIdNil

`func (o *CreateShipment201Response) SetLabelPrinterIdNil(b bool)`

 SetLabelPrinterIdNil sets the value for LabelPrinterId to be an explicit nil

### UnsetLabelPrinterId
`func (o *CreateShipment201Response) UnsetLabelPrinterId()`

UnsetLabelPrinterId ensures that no value is present for LabelPrinterId, not even an explicit nil
### GetDocumentPrinterId

`func (o *CreateShipment201Response) GetDocumentPrinterId() string`

GetDocumentPrinterId returns the DocumentPrinterId field if non-nil, zero value otherwise.

### GetDocumentPrinterIdOk

`func (o *CreateShipment201Response) GetDocumentPrinterIdOk() (*string, bool)`

GetDocumentPrinterIdOk returns a tuple with the DocumentPrinterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocumentPrinterId

`func (o *CreateShipment201Response) SetDocumentPrinterId(v string)`

SetDocumentPrinterId sets DocumentPrinterId field to given value.

### HasDocumentPrinterId

`func (o *CreateShipment201Response) HasDocumentPrinterId() bool`

HasDocumentPrinterId returns a boolean if a field has been set.

### SetDocumentPrinterIdNil

`func (o *CreateShipment201Response) SetDocumentPrinterIdNil(b bool)`

 SetDocumentPrinterIdNil sets the value for DocumentPrinterId to be an explicit nil

### UnsetDocumentPrinterId
`func (o *CreateShipment201Response) UnsetDocumentPrinterId()`

UnsetDocumentPrinterId ensures that no value is present for DocumentPrinterId, not even an explicit nil
### GetLogs

`func (o *CreateShipment201Response) GetLogs() []CreateShipment201ResponseLogsInner`

GetLogs returns the Logs field if non-nil, zero value otherwise.

### GetLogsOk

`func (o *CreateShipment201Response) GetLogsOk() (*[]CreateShipment201ResponseLogsInner, bool)`

GetLogsOk returns a tuple with the Logs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogs

`func (o *CreateShipment201Response) SetLogs(v []CreateShipment201ResponseLogsInner)`

SetLogs sets Logs field to given value.


### GetActivities

`func (o *CreateShipment201Response) GetActivities() []CreateShipment201ResponseActivitiesInner`

GetActivities returns the Activities field if non-nil, zero value otherwise.

### GetActivitiesOk

`func (o *CreateShipment201Response) GetActivitiesOk() (*[]CreateShipment201ResponseActivitiesInner, bool)`

GetActivitiesOk returns a tuple with the Activities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivities

`func (o *CreateShipment201Response) SetActivities(v []CreateShipment201ResponseActivitiesInner)`

SetActivities sets Activities field to given value.


### GetCreatedAt

`func (o *CreateShipment201Response) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CreateShipment201Response) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CreateShipment201Response) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *CreateShipment201Response) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *CreateShipment201Response) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *CreateShipment201Response) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


