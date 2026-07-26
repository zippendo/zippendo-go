# CreateShipment201ResponseShippingRule

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Unique shipping rule identifier. | 
**Name** | **string** | Display name of the shipping rule. | 
**CarrierId** | **string** | Carrier applied by the rule. | 
**ProductId** | **string** | Carrier product applied by the rule. | 
**Services** | **[]string** | Additional service codes applied by the rule. | 
**AddressId** | **string** | Sender address applied by the rule. | 
**ReturnShippingRuleId** | Pointer to **NullableString** | Shipping rule used for return shipments. | [optional] 
**AutoCreateReturnShipment** | Pointer to **bool** | Whether a return shipment is created automatically. | [optional] 
**AutoPrintLabels** | Pointer to **bool** | Whether labels are printed automatically on send. | [optional] 
**AutoPrintDocuments** | Pointer to **bool** | Whether documents are printed automatically on send. | [optional] 
**LabelPrinterId** | Pointer to **NullableString** | Printer used for labels. | [optional] 
**DocumentPrinterId** | Pointer to **NullableString** | Printer used for documents. | [optional] 

## Methods

### NewCreateShipment201ResponseShippingRule

`func NewCreateShipment201ResponseShippingRule(id string, name string, carrierId string, productId string, services []string, addressId string, ) *CreateShipment201ResponseShippingRule`

NewCreateShipment201ResponseShippingRule instantiates a new CreateShipment201ResponseShippingRule object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateShipment201ResponseShippingRuleWithDefaults

`func NewCreateShipment201ResponseShippingRuleWithDefaults() *CreateShipment201ResponseShippingRule`

NewCreateShipment201ResponseShippingRuleWithDefaults instantiates a new CreateShipment201ResponseShippingRule object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreateShipment201ResponseShippingRule) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateShipment201ResponseShippingRule) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateShipment201ResponseShippingRule) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *CreateShipment201ResponseShippingRule) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateShipment201ResponseShippingRule) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateShipment201ResponseShippingRule) SetName(v string)`

SetName sets Name field to given value.


### GetCarrierId

`func (o *CreateShipment201ResponseShippingRule) GetCarrierId() string`

GetCarrierId returns the CarrierId field if non-nil, zero value otherwise.

### GetCarrierIdOk

`func (o *CreateShipment201ResponseShippingRule) GetCarrierIdOk() (*string, bool)`

GetCarrierIdOk returns a tuple with the CarrierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierId

`func (o *CreateShipment201ResponseShippingRule) SetCarrierId(v string)`

SetCarrierId sets CarrierId field to given value.


### GetProductId

`func (o *CreateShipment201ResponseShippingRule) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *CreateShipment201ResponseShippingRule) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *CreateShipment201ResponseShippingRule) SetProductId(v string)`

SetProductId sets ProductId field to given value.


### GetServices

`func (o *CreateShipment201ResponseShippingRule) GetServices() []string`

GetServices returns the Services field if non-nil, zero value otherwise.

### GetServicesOk

`func (o *CreateShipment201ResponseShippingRule) GetServicesOk() (*[]string, bool)`

GetServicesOk returns a tuple with the Services field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServices

`func (o *CreateShipment201ResponseShippingRule) SetServices(v []string)`

SetServices sets Services field to given value.


### GetAddressId

`func (o *CreateShipment201ResponseShippingRule) GetAddressId() string`

GetAddressId returns the AddressId field if non-nil, zero value otherwise.

### GetAddressIdOk

`func (o *CreateShipment201ResponseShippingRule) GetAddressIdOk() (*string, bool)`

GetAddressIdOk returns a tuple with the AddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressId

`func (o *CreateShipment201ResponseShippingRule) SetAddressId(v string)`

SetAddressId sets AddressId field to given value.


### GetReturnShippingRuleId

`func (o *CreateShipment201ResponseShippingRule) GetReturnShippingRuleId() string`

GetReturnShippingRuleId returns the ReturnShippingRuleId field if non-nil, zero value otherwise.

### GetReturnShippingRuleIdOk

`func (o *CreateShipment201ResponseShippingRule) GetReturnShippingRuleIdOk() (*string, bool)`

GetReturnShippingRuleIdOk returns a tuple with the ReturnShippingRuleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnShippingRuleId

`func (o *CreateShipment201ResponseShippingRule) SetReturnShippingRuleId(v string)`

SetReturnShippingRuleId sets ReturnShippingRuleId field to given value.

### HasReturnShippingRuleId

`func (o *CreateShipment201ResponseShippingRule) HasReturnShippingRuleId() bool`

HasReturnShippingRuleId returns a boolean if a field has been set.

### SetReturnShippingRuleIdNil

`func (o *CreateShipment201ResponseShippingRule) SetReturnShippingRuleIdNil(b bool)`

 SetReturnShippingRuleIdNil sets the value for ReturnShippingRuleId to be an explicit nil

### UnsetReturnShippingRuleId
`func (o *CreateShipment201ResponseShippingRule) UnsetReturnShippingRuleId()`

UnsetReturnShippingRuleId ensures that no value is present for ReturnShippingRuleId, not even an explicit nil
### GetAutoCreateReturnShipment

`func (o *CreateShipment201ResponseShippingRule) GetAutoCreateReturnShipment() bool`

GetAutoCreateReturnShipment returns the AutoCreateReturnShipment field if non-nil, zero value otherwise.

### GetAutoCreateReturnShipmentOk

`func (o *CreateShipment201ResponseShippingRule) GetAutoCreateReturnShipmentOk() (*bool, bool)`

GetAutoCreateReturnShipmentOk returns a tuple with the AutoCreateReturnShipment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoCreateReturnShipment

`func (o *CreateShipment201ResponseShippingRule) SetAutoCreateReturnShipment(v bool)`

SetAutoCreateReturnShipment sets AutoCreateReturnShipment field to given value.

### HasAutoCreateReturnShipment

`func (o *CreateShipment201ResponseShippingRule) HasAutoCreateReturnShipment() bool`

HasAutoCreateReturnShipment returns a boolean if a field has been set.

### GetAutoPrintLabels

`func (o *CreateShipment201ResponseShippingRule) GetAutoPrintLabels() bool`

GetAutoPrintLabels returns the AutoPrintLabels field if non-nil, zero value otherwise.

### GetAutoPrintLabelsOk

`func (o *CreateShipment201ResponseShippingRule) GetAutoPrintLabelsOk() (*bool, bool)`

GetAutoPrintLabelsOk returns a tuple with the AutoPrintLabels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoPrintLabels

`func (o *CreateShipment201ResponseShippingRule) SetAutoPrintLabels(v bool)`

SetAutoPrintLabels sets AutoPrintLabels field to given value.

### HasAutoPrintLabels

`func (o *CreateShipment201ResponseShippingRule) HasAutoPrintLabels() bool`

HasAutoPrintLabels returns a boolean if a field has been set.

### GetAutoPrintDocuments

`func (o *CreateShipment201ResponseShippingRule) GetAutoPrintDocuments() bool`

GetAutoPrintDocuments returns the AutoPrintDocuments field if non-nil, zero value otherwise.

### GetAutoPrintDocumentsOk

`func (o *CreateShipment201ResponseShippingRule) GetAutoPrintDocumentsOk() (*bool, bool)`

GetAutoPrintDocumentsOk returns a tuple with the AutoPrintDocuments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoPrintDocuments

`func (o *CreateShipment201ResponseShippingRule) SetAutoPrintDocuments(v bool)`

SetAutoPrintDocuments sets AutoPrintDocuments field to given value.

### HasAutoPrintDocuments

`func (o *CreateShipment201ResponseShippingRule) HasAutoPrintDocuments() bool`

HasAutoPrintDocuments returns a boolean if a field has been set.

### GetLabelPrinterId

`func (o *CreateShipment201ResponseShippingRule) GetLabelPrinterId() string`

GetLabelPrinterId returns the LabelPrinterId field if non-nil, zero value otherwise.

### GetLabelPrinterIdOk

`func (o *CreateShipment201ResponseShippingRule) GetLabelPrinterIdOk() (*string, bool)`

GetLabelPrinterIdOk returns a tuple with the LabelPrinterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabelPrinterId

`func (o *CreateShipment201ResponseShippingRule) SetLabelPrinterId(v string)`

SetLabelPrinterId sets LabelPrinterId field to given value.

### HasLabelPrinterId

`func (o *CreateShipment201ResponseShippingRule) HasLabelPrinterId() bool`

HasLabelPrinterId returns a boolean if a field has been set.

### SetLabelPrinterIdNil

`func (o *CreateShipment201ResponseShippingRule) SetLabelPrinterIdNil(b bool)`

 SetLabelPrinterIdNil sets the value for LabelPrinterId to be an explicit nil

### UnsetLabelPrinterId
`func (o *CreateShipment201ResponseShippingRule) UnsetLabelPrinterId()`

UnsetLabelPrinterId ensures that no value is present for LabelPrinterId, not even an explicit nil
### GetDocumentPrinterId

`func (o *CreateShipment201ResponseShippingRule) GetDocumentPrinterId() string`

GetDocumentPrinterId returns the DocumentPrinterId field if non-nil, zero value otherwise.

### GetDocumentPrinterIdOk

`func (o *CreateShipment201ResponseShippingRule) GetDocumentPrinterIdOk() (*string, bool)`

GetDocumentPrinterIdOk returns a tuple with the DocumentPrinterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocumentPrinterId

`func (o *CreateShipment201ResponseShippingRule) SetDocumentPrinterId(v string)`

SetDocumentPrinterId sets DocumentPrinterId field to given value.

### HasDocumentPrinterId

`func (o *CreateShipment201ResponseShippingRule) HasDocumentPrinterId() bool`

HasDocumentPrinterId returns a boolean if a field has been set.

### SetDocumentPrinterIdNil

`func (o *CreateShipment201ResponseShippingRule) SetDocumentPrinterIdNil(b bool)`

 SetDocumentPrinterIdNil sets the value for DocumentPrinterId to be an explicit nil

### UnsetDocumentPrinterId
`func (o *CreateShipment201ResponseShippingRule) UnsetDocumentPrinterId()`

UnsetDocumentPrinterId ensures that no value is present for DocumentPrinterId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


