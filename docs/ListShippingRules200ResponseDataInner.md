# ListShippingRules200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Unique shipping rule identifier | 
**Name** | **string** | Shipping rule name | 
**Description** | **NullableString** | Optional description | 
**Direction** | **string** | Whether this rule is for outbound or inbound (return) shipments | [default to "outbound"]
**CarrierId** | **string** | Carrier ID | 
**ProductId** | **string** | Product ID from carrier | 
**Services** | **[]string** | List of selected services | 
**AdditionalParameters** | [**[]ListShippingRules200ResponseDataInnerAdditionalParametersInner**](ListShippingRules200ResponseDataInnerAdditionalParametersInner.md) | Carrier-specific extra parameters. DEPRECATED array form &#x60;[{ name, val }]&#x60; where &#x60;name&#x60; is the carrier parameter &#x60;key&#x60; (from the product&#39;s &#x60;additionalParameters[].key&#x60;, e.g. &#x60;returnFunctionality&#x60;) and &#x60;val&#x60; is the stringified value. This will change to a &#x60;{ key: value }&#x60; object in a future version — writes already accept either shape. | 
**AddressId** | **string** | Sender address ID | 
**ReceivingCountries** | **[]string** | List of supported country codes | 
**EmailNotification** | **bool** | Send email notification to recipient | [default to false]
**PhoneNotification** | **bool** | Send SMS notification to recipient | [default to false]
**MinWeight** | **NullableFloat32** | Minimum required weight in kg. Orders below this are excluded from the rule. | 
**MaxWeight** | **NullableFloat32** | Maximum allowed weight in kg. Orders exceeding this are excluded from the rule. | 
**MinOrderValue** | **NullableFloat32** | Minimum required order value in currency units. Orders below this are excluded from the rule. | 
**MaxOrderValue** | **NullableFloat32** | Maximum allowed order value in currency units. Orders exceeding this are excluded from the rule. | 
**Conditions** | [**[]ListShippingRules200ResponseDataInnerConditionsInner**](ListShippingRules200ResponseDataInnerConditionsInner.md) | Rule conditions (weight/price/quantity) | 
**GenerateProformaInvoice** | **bool** | Generate proforma invoice for shipments | [default to false]
**GenerateCommercialInvoice** | **bool** | Generate commercial invoice for international shipments | [default to false]
**GeneratePackingList** | **bool** | Generate packing slip with package and item details | [default to false]
**AutoPrintLabels** | **bool** | Automatically print labels when shipment is sent | [default to false]
**AutoPrintDocuments** | **bool** | Automatically print documents when shipment is sent | [default to false]
**LabelPrinterId** | **NullableString** | ID of the label printer | 
**DocumentPrinterId** | **NullableString** | ID of the document printer | 
**ReturnShippingRuleId** | **NullableString** | ID of the return shipping rule | 
**AutoCreateReturnShipment** | **bool** | Automatically create and send a return shipment on dispatch | [default to false]
**OrgId** | **string** | Owning organization ID | 
**CreatedAt** | **string** | Creation timestamp (ISO 8601) | 
**UpdatedAt** | **string** | Last update timestamp (ISO 8601) | 
**Carrier** | [**ListShippingRules200ResponseDataInnerCarrier**](ListShippingRules200ResponseDataInnerCarrier.md) |  | 
**Address** | [**ListAddresses200ResponseDataInner**](ListAddresses200ResponseDataInner.md) |  | 
**LabelPrinter** | Pointer to [**NullableListShippingRules200ResponseDataInnerLabelPrinter**](ListShippingRules200ResponseDataInnerLabelPrinter.md) |  | [optional] 
**DocumentPrinter** | Pointer to [**NullableListShippingRules200ResponseDataInnerLabelPrinter**](ListShippingRules200ResponseDataInnerLabelPrinter.md) |  | [optional] 
**ReturnShippingRule** | Pointer to [**NullableListShippingRules200ResponseDataInnerReturnShippingRule**](ListShippingRules200ResponseDataInnerReturnShippingRule.md) |  | [optional] 

## Methods

### NewListShippingRules200ResponseDataInner

`func NewListShippingRules200ResponseDataInner(id string, name string, description NullableString, direction string, carrierId string, productId string, services []string, additionalParameters []ListShippingRules200ResponseDataInnerAdditionalParametersInner, addressId string, receivingCountries []string, emailNotification bool, phoneNotification bool, minWeight NullableFloat32, maxWeight NullableFloat32, minOrderValue NullableFloat32, maxOrderValue NullableFloat32, conditions []ListShippingRules200ResponseDataInnerConditionsInner, generateProformaInvoice bool, generateCommercialInvoice bool, generatePackingList bool, autoPrintLabels bool, autoPrintDocuments bool, labelPrinterId NullableString, documentPrinterId NullableString, returnShippingRuleId NullableString, autoCreateReturnShipment bool, orgId string, createdAt string, updatedAt string, carrier ListShippingRules200ResponseDataInnerCarrier, address ListAddresses200ResponseDataInner, ) *ListShippingRules200ResponseDataInner`

NewListShippingRules200ResponseDataInner instantiates a new ListShippingRules200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListShippingRules200ResponseDataInnerWithDefaults

`func NewListShippingRules200ResponseDataInnerWithDefaults() *ListShippingRules200ResponseDataInner`

NewListShippingRules200ResponseDataInnerWithDefaults instantiates a new ListShippingRules200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ListShippingRules200ResponseDataInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ListShippingRules200ResponseDataInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ListShippingRules200ResponseDataInner) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *ListShippingRules200ResponseDataInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ListShippingRules200ResponseDataInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ListShippingRules200ResponseDataInner) SetName(v string)`

SetName sets Name field to given value.


### GetDescription

`func (o *ListShippingRules200ResponseDataInner) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ListShippingRules200ResponseDataInner) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ListShippingRules200ResponseDataInner) SetDescription(v string)`

SetDescription sets Description field to given value.


### SetDescriptionNil

`func (o *ListShippingRules200ResponseDataInner) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *ListShippingRules200ResponseDataInner) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetDirection

`func (o *ListShippingRules200ResponseDataInner) GetDirection() string`

GetDirection returns the Direction field if non-nil, zero value otherwise.

### GetDirectionOk

`func (o *ListShippingRules200ResponseDataInner) GetDirectionOk() (*string, bool)`

GetDirectionOk returns a tuple with the Direction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDirection

`func (o *ListShippingRules200ResponseDataInner) SetDirection(v string)`

SetDirection sets Direction field to given value.


### GetCarrierId

`func (o *ListShippingRules200ResponseDataInner) GetCarrierId() string`

GetCarrierId returns the CarrierId field if non-nil, zero value otherwise.

### GetCarrierIdOk

`func (o *ListShippingRules200ResponseDataInner) GetCarrierIdOk() (*string, bool)`

GetCarrierIdOk returns a tuple with the CarrierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierId

`func (o *ListShippingRules200ResponseDataInner) SetCarrierId(v string)`

SetCarrierId sets CarrierId field to given value.


### GetProductId

`func (o *ListShippingRules200ResponseDataInner) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *ListShippingRules200ResponseDataInner) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *ListShippingRules200ResponseDataInner) SetProductId(v string)`

SetProductId sets ProductId field to given value.


### GetServices

`func (o *ListShippingRules200ResponseDataInner) GetServices() []string`

GetServices returns the Services field if non-nil, zero value otherwise.

### GetServicesOk

`func (o *ListShippingRules200ResponseDataInner) GetServicesOk() (*[]string, bool)`

GetServicesOk returns a tuple with the Services field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServices

`func (o *ListShippingRules200ResponseDataInner) SetServices(v []string)`

SetServices sets Services field to given value.


### GetAdditionalParameters

`func (o *ListShippingRules200ResponseDataInner) GetAdditionalParameters() []ListShippingRules200ResponseDataInnerAdditionalParametersInner`

GetAdditionalParameters returns the AdditionalParameters field if non-nil, zero value otherwise.

### GetAdditionalParametersOk

`func (o *ListShippingRules200ResponseDataInner) GetAdditionalParametersOk() (*[]ListShippingRules200ResponseDataInnerAdditionalParametersInner, bool)`

GetAdditionalParametersOk returns a tuple with the AdditionalParameters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditionalParameters

`func (o *ListShippingRules200ResponseDataInner) SetAdditionalParameters(v []ListShippingRules200ResponseDataInnerAdditionalParametersInner)`

SetAdditionalParameters sets AdditionalParameters field to given value.


### GetAddressId

`func (o *ListShippingRules200ResponseDataInner) GetAddressId() string`

GetAddressId returns the AddressId field if non-nil, zero value otherwise.

### GetAddressIdOk

`func (o *ListShippingRules200ResponseDataInner) GetAddressIdOk() (*string, bool)`

GetAddressIdOk returns a tuple with the AddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressId

`func (o *ListShippingRules200ResponseDataInner) SetAddressId(v string)`

SetAddressId sets AddressId field to given value.


### GetReceivingCountries

`func (o *ListShippingRules200ResponseDataInner) GetReceivingCountries() []string`

GetReceivingCountries returns the ReceivingCountries field if non-nil, zero value otherwise.

### GetReceivingCountriesOk

`func (o *ListShippingRules200ResponseDataInner) GetReceivingCountriesOk() (*[]string, bool)`

GetReceivingCountriesOk returns a tuple with the ReceivingCountries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceivingCountries

`func (o *ListShippingRules200ResponseDataInner) SetReceivingCountries(v []string)`

SetReceivingCountries sets ReceivingCountries field to given value.


### GetEmailNotification

`func (o *ListShippingRules200ResponseDataInner) GetEmailNotification() bool`

GetEmailNotification returns the EmailNotification field if non-nil, zero value otherwise.

### GetEmailNotificationOk

`func (o *ListShippingRules200ResponseDataInner) GetEmailNotificationOk() (*bool, bool)`

GetEmailNotificationOk returns a tuple with the EmailNotification field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmailNotification

`func (o *ListShippingRules200ResponseDataInner) SetEmailNotification(v bool)`

SetEmailNotification sets EmailNotification field to given value.


### GetPhoneNotification

`func (o *ListShippingRules200ResponseDataInner) GetPhoneNotification() bool`

GetPhoneNotification returns the PhoneNotification field if non-nil, zero value otherwise.

### GetPhoneNotificationOk

`func (o *ListShippingRules200ResponseDataInner) GetPhoneNotificationOk() (*bool, bool)`

GetPhoneNotificationOk returns a tuple with the PhoneNotification field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhoneNotification

`func (o *ListShippingRules200ResponseDataInner) SetPhoneNotification(v bool)`

SetPhoneNotification sets PhoneNotification field to given value.


### GetMinWeight

`func (o *ListShippingRules200ResponseDataInner) GetMinWeight() float32`

GetMinWeight returns the MinWeight field if non-nil, zero value otherwise.

### GetMinWeightOk

`func (o *ListShippingRules200ResponseDataInner) GetMinWeightOk() (*float32, bool)`

GetMinWeightOk returns a tuple with the MinWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinWeight

`func (o *ListShippingRules200ResponseDataInner) SetMinWeight(v float32)`

SetMinWeight sets MinWeight field to given value.


### SetMinWeightNil

`func (o *ListShippingRules200ResponseDataInner) SetMinWeightNil(b bool)`

 SetMinWeightNil sets the value for MinWeight to be an explicit nil

### UnsetMinWeight
`func (o *ListShippingRules200ResponseDataInner) UnsetMinWeight()`

UnsetMinWeight ensures that no value is present for MinWeight, not even an explicit nil
### GetMaxWeight

`func (o *ListShippingRules200ResponseDataInner) GetMaxWeight() float32`

GetMaxWeight returns the MaxWeight field if non-nil, zero value otherwise.

### GetMaxWeightOk

`func (o *ListShippingRules200ResponseDataInner) GetMaxWeightOk() (*float32, bool)`

GetMaxWeightOk returns a tuple with the MaxWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxWeight

`func (o *ListShippingRules200ResponseDataInner) SetMaxWeight(v float32)`

SetMaxWeight sets MaxWeight field to given value.


### SetMaxWeightNil

`func (o *ListShippingRules200ResponseDataInner) SetMaxWeightNil(b bool)`

 SetMaxWeightNil sets the value for MaxWeight to be an explicit nil

### UnsetMaxWeight
`func (o *ListShippingRules200ResponseDataInner) UnsetMaxWeight()`

UnsetMaxWeight ensures that no value is present for MaxWeight, not even an explicit nil
### GetMinOrderValue

`func (o *ListShippingRules200ResponseDataInner) GetMinOrderValue() float32`

GetMinOrderValue returns the MinOrderValue field if non-nil, zero value otherwise.

### GetMinOrderValueOk

`func (o *ListShippingRules200ResponseDataInner) GetMinOrderValueOk() (*float32, bool)`

GetMinOrderValueOk returns a tuple with the MinOrderValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinOrderValue

`func (o *ListShippingRules200ResponseDataInner) SetMinOrderValue(v float32)`

SetMinOrderValue sets MinOrderValue field to given value.


### SetMinOrderValueNil

`func (o *ListShippingRules200ResponseDataInner) SetMinOrderValueNil(b bool)`

 SetMinOrderValueNil sets the value for MinOrderValue to be an explicit nil

### UnsetMinOrderValue
`func (o *ListShippingRules200ResponseDataInner) UnsetMinOrderValue()`

UnsetMinOrderValue ensures that no value is present for MinOrderValue, not even an explicit nil
### GetMaxOrderValue

`func (o *ListShippingRules200ResponseDataInner) GetMaxOrderValue() float32`

GetMaxOrderValue returns the MaxOrderValue field if non-nil, zero value otherwise.

### GetMaxOrderValueOk

`func (o *ListShippingRules200ResponseDataInner) GetMaxOrderValueOk() (*float32, bool)`

GetMaxOrderValueOk returns a tuple with the MaxOrderValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxOrderValue

`func (o *ListShippingRules200ResponseDataInner) SetMaxOrderValue(v float32)`

SetMaxOrderValue sets MaxOrderValue field to given value.


### SetMaxOrderValueNil

`func (o *ListShippingRules200ResponseDataInner) SetMaxOrderValueNil(b bool)`

 SetMaxOrderValueNil sets the value for MaxOrderValue to be an explicit nil

### UnsetMaxOrderValue
`func (o *ListShippingRules200ResponseDataInner) UnsetMaxOrderValue()`

UnsetMaxOrderValue ensures that no value is present for MaxOrderValue, not even an explicit nil
### GetConditions

`func (o *ListShippingRules200ResponseDataInner) GetConditions() []ListShippingRules200ResponseDataInnerConditionsInner`

GetConditions returns the Conditions field if non-nil, zero value otherwise.

### GetConditionsOk

`func (o *ListShippingRules200ResponseDataInner) GetConditionsOk() (*[]ListShippingRules200ResponseDataInnerConditionsInner, bool)`

GetConditionsOk returns a tuple with the Conditions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConditions

`func (o *ListShippingRules200ResponseDataInner) SetConditions(v []ListShippingRules200ResponseDataInnerConditionsInner)`

SetConditions sets Conditions field to given value.


### GetGenerateProformaInvoice

`func (o *ListShippingRules200ResponseDataInner) GetGenerateProformaInvoice() bool`

GetGenerateProformaInvoice returns the GenerateProformaInvoice field if non-nil, zero value otherwise.

### GetGenerateProformaInvoiceOk

`func (o *ListShippingRules200ResponseDataInner) GetGenerateProformaInvoiceOk() (*bool, bool)`

GetGenerateProformaInvoiceOk returns a tuple with the GenerateProformaInvoice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGenerateProformaInvoice

`func (o *ListShippingRules200ResponseDataInner) SetGenerateProformaInvoice(v bool)`

SetGenerateProformaInvoice sets GenerateProformaInvoice field to given value.


### GetGenerateCommercialInvoice

`func (o *ListShippingRules200ResponseDataInner) GetGenerateCommercialInvoice() bool`

GetGenerateCommercialInvoice returns the GenerateCommercialInvoice field if non-nil, zero value otherwise.

### GetGenerateCommercialInvoiceOk

`func (o *ListShippingRules200ResponseDataInner) GetGenerateCommercialInvoiceOk() (*bool, bool)`

GetGenerateCommercialInvoiceOk returns a tuple with the GenerateCommercialInvoice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGenerateCommercialInvoice

`func (o *ListShippingRules200ResponseDataInner) SetGenerateCommercialInvoice(v bool)`

SetGenerateCommercialInvoice sets GenerateCommercialInvoice field to given value.


### GetGeneratePackingList

`func (o *ListShippingRules200ResponseDataInner) GetGeneratePackingList() bool`

GetGeneratePackingList returns the GeneratePackingList field if non-nil, zero value otherwise.

### GetGeneratePackingListOk

`func (o *ListShippingRules200ResponseDataInner) GetGeneratePackingListOk() (*bool, bool)`

GetGeneratePackingListOk returns a tuple with the GeneratePackingList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneratePackingList

`func (o *ListShippingRules200ResponseDataInner) SetGeneratePackingList(v bool)`

SetGeneratePackingList sets GeneratePackingList field to given value.


### GetAutoPrintLabels

`func (o *ListShippingRules200ResponseDataInner) GetAutoPrintLabels() bool`

GetAutoPrintLabels returns the AutoPrintLabels field if non-nil, zero value otherwise.

### GetAutoPrintLabelsOk

`func (o *ListShippingRules200ResponseDataInner) GetAutoPrintLabelsOk() (*bool, bool)`

GetAutoPrintLabelsOk returns a tuple with the AutoPrintLabels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoPrintLabels

`func (o *ListShippingRules200ResponseDataInner) SetAutoPrintLabels(v bool)`

SetAutoPrintLabels sets AutoPrintLabels field to given value.


### GetAutoPrintDocuments

`func (o *ListShippingRules200ResponseDataInner) GetAutoPrintDocuments() bool`

GetAutoPrintDocuments returns the AutoPrintDocuments field if non-nil, zero value otherwise.

### GetAutoPrintDocumentsOk

`func (o *ListShippingRules200ResponseDataInner) GetAutoPrintDocumentsOk() (*bool, bool)`

GetAutoPrintDocumentsOk returns a tuple with the AutoPrintDocuments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoPrintDocuments

`func (o *ListShippingRules200ResponseDataInner) SetAutoPrintDocuments(v bool)`

SetAutoPrintDocuments sets AutoPrintDocuments field to given value.


### GetLabelPrinterId

`func (o *ListShippingRules200ResponseDataInner) GetLabelPrinterId() string`

GetLabelPrinterId returns the LabelPrinterId field if non-nil, zero value otherwise.

### GetLabelPrinterIdOk

`func (o *ListShippingRules200ResponseDataInner) GetLabelPrinterIdOk() (*string, bool)`

GetLabelPrinterIdOk returns a tuple with the LabelPrinterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabelPrinterId

`func (o *ListShippingRules200ResponseDataInner) SetLabelPrinterId(v string)`

SetLabelPrinterId sets LabelPrinterId field to given value.


### SetLabelPrinterIdNil

`func (o *ListShippingRules200ResponseDataInner) SetLabelPrinterIdNil(b bool)`

 SetLabelPrinterIdNil sets the value for LabelPrinterId to be an explicit nil

### UnsetLabelPrinterId
`func (o *ListShippingRules200ResponseDataInner) UnsetLabelPrinterId()`

UnsetLabelPrinterId ensures that no value is present for LabelPrinterId, not even an explicit nil
### GetDocumentPrinterId

`func (o *ListShippingRules200ResponseDataInner) GetDocumentPrinterId() string`

GetDocumentPrinterId returns the DocumentPrinterId field if non-nil, zero value otherwise.

### GetDocumentPrinterIdOk

`func (o *ListShippingRules200ResponseDataInner) GetDocumentPrinterIdOk() (*string, bool)`

GetDocumentPrinterIdOk returns a tuple with the DocumentPrinterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocumentPrinterId

`func (o *ListShippingRules200ResponseDataInner) SetDocumentPrinterId(v string)`

SetDocumentPrinterId sets DocumentPrinterId field to given value.


### SetDocumentPrinterIdNil

`func (o *ListShippingRules200ResponseDataInner) SetDocumentPrinterIdNil(b bool)`

 SetDocumentPrinterIdNil sets the value for DocumentPrinterId to be an explicit nil

### UnsetDocumentPrinterId
`func (o *ListShippingRules200ResponseDataInner) UnsetDocumentPrinterId()`

UnsetDocumentPrinterId ensures that no value is present for DocumentPrinterId, not even an explicit nil
### GetReturnShippingRuleId

`func (o *ListShippingRules200ResponseDataInner) GetReturnShippingRuleId() string`

GetReturnShippingRuleId returns the ReturnShippingRuleId field if non-nil, zero value otherwise.

### GetReturnShippingRuleIdOk

`func (o *ListShippingRules200ResponseDataInner) GetReturnShippingRuleIdOk() (*string, bool)`

GetReturnShippingRuleIdOk returns a tuple with the ReturnShippingRuleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnShippingRuleId

`func (o *ListShippingRules200ResponseDataInner) SetReturnShippingRuleId(v string)`

SetReturnShippingRuleId sets ReturnShippingRuleId field to given value.


### SetReturnShippingRuleIdNil

`func (o *ListShippingRules200ResponseDataInner) SetReturnShippingRuleIdNil(b bool)`

 SetReturnShippingRuleIdNil sets the value for ReturnShippingRuleId to be an explicit nil

### UnsetReturnShippingRuleId
`func (o *ListShippingRules200ResponseDataInner) UnsetReturnShippingRuleId()`

UnsetReturnShippingRuleId ensures that no value is present for ReturnShippingRuleId, not even an explicit nil
### GetAutoCreateReturnShipment

`func (o *ListShippingRules200ResponseDataInner) GetAutoCreateReturnShipment() bool`

GetAutoCreateReturnShipment returns the AutoCreateReturnShipment field if non-nil, zero value otherwise.

### GetAutoCreateReturnShipmentOk

`func (o *ListShippingRules200ResponseDataInner) GetAutoCreateReturnShipmentOk() (*bool, bool)`

GetAutoCreateReturnShipmentOk returns a tuple with the AutoCreateReturnShipment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoCreateReturnShipment

`func (o *ListShippingRules200ResponseDataInner) SetAutoCreateReturnShipment(v bool)`

SetAutoCreateReturnShipment sets AutoCreateReturnShipment field to given value.


### GetOrgId

`func (o *ListShippingRules200ResponseDataInner) GetOrgId() string`

GetOrgId returns the OrgId field if non-nil, zero value otherwise.

### GetOrgIdOk

`func (o *ListShippingRules200ResponseDataInner) GetOrgIdOk() (*string, bool)`

GetOrgIdOk returns a tuple with the OrgId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrgId

`func (o *ListShippingRules200ResponseDataInner) SetOrgId(v string)`

SetOrgId sets OrgId field to given value.


### GetCreatedAt

`func (o *ListShippingRules200ResponseDataInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ListShippingRules200ResponseDataInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ListShippingRules200ResponseDataInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *ListShippingRules200ResponseDataInner) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ListShippingRules200ResponseDataInner) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ListShippingRules200ResponseDataInner) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetCarrier

`func (o *ListShippingRules200ResponseDataInner) GetCarrier() ListShippingRules200ResponseDataInnerCarrier`

GetCarrier returns the Carrier field if non-nil, zero value otherwise.

### GetCarrierOk

`func (o *ListShippingRules200ResponseDataInner) GetCarrierOk() (*ListShippingRules200ResponseDataInnerCarrier, bool)`

GetCarrierOk returns a tuple with the Carrier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrier

`func (o *ListShippingRules200ResponseDataInner) SetCarrier(v ListShippingRules200ResponseDataInnerCarrier)`

SetCarrier sets Carrier field to given value.


### GetAddress

`func (o *ListShippingRules200ResponseDataInner) GetAddress() ListAddresses200ResponseDataInner`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *ListShippingRules200ResponseDataInner) GetAddressOk() (*ListAddresses200ResponseDataInner, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *ListShippingRules200ResponseDataInner) SetAddress(v ListAddresses200ResponseDataInner)`

SetAddress sets Address field to given value.


### GetLabelPrinter

`func (o *ListShippingRules200ResponseDataInner) GetLabelPrinter() ListShippingRules200ResponseDataInnerLabelPrinter`

GetLabelPrinter returns the LabelPrinter field if non-nil, zero value otherwise.

### GetLabelPrinterOk

`func (o *ListShippingRules200ResponseDataInner) GetLabelPrinterOk() (*ListShippingRules200ResponseDataInnerLabelPrinter, bool)`

GetLabelPrinterOk returns a tuple with the LabelPrinter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabelPrinter

`func (o *ListShippingRules200ResponseDataInner) SetLabelPrinter(v ListShippingRules200ResponseDataInnerLabelPrinter)`

SetLabelPrinter sets LabelPrinter field to given value.

### HasLabelPrinter

`func (o *ListShippingRules200ResponseDataInner) HasLabelPrinter() bool`

HasLabelPrinter returns a boolean if a field has been set.

### SetLabelPrinterNil

`func (o *ListShippingRules200ResponseDataInner) SetLabelPrinterNil(b bool)`

 SetLabelPrinterNil sets the value for LabelPrinter to be an explicit nil

### UnsetLabelPrinter
`func (o *ListShippingRules200ResponseDataInner) UnsetLabelPrinter()`

UnsetLabelPrinter ensures that no value is present for LabelPrinter, not even an explicit nil
### GetDocumentPrinter

`func (o *ListShippingRules200ResponseDataInner) GetDocumentPrinter() ListShippingRules200ResponseDataInnerLabelPrinter`

GetDocumentPrinter returns the DocumentPrinter field if non-nil, zero value otherwise.

### GetDocumentPrinterOk

`func (o *ListShippingRules200ResponseDataInner) GetDocumentPrinterOk() (*ListShippingRules200ResponseDataInnerLabelPrinter, bool)`

GetDocumentPrinterOk returns a tuple with the DocumentPrinter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocumentPrinter

`func (o *ListShippingRules200ResponseDataInner) SetDocumentPrinter(v ListShippingRules200ResponseDataInnerLabelPrinter)`

SetDocumentPrinter sets DocumentPrinter field to given value.

### HasDocumentPrinter

`func (o *ListShippingRules200ResponseDataInner) HasDocumentPrinter() bool`

HasDocumentPrinter returns a boolean if a field has been set.

### SetDocumentPrinterNil

`func (o *ListShippingRules200ResponseDataInner) SetDocumentPrinterNil(b bool)`

 SetDocumentPrinterNil sets the value for DocumentPrinter to be an explicit nil

### UnsetDocumentPrinter
`func (o *ListShippingRules200ResponseDataInner) UnsetDocumentPrinter()`

UnsetDocumentPrinter ensures that no value is present for DocumentPrinter, not even an explicit nil
### GetReturnShippingRule

`func (o *ListShippingRules200ResponseDataInner) GetReturnShippingRule() ListShippingRules200ResponseDataInnerReturnShippingRule`

GetReturnShippingRule returns the ReturnShippingRule field if non-nil, zero value otherwise.

### GetReturnShippingRuleOk

`func (o *ListShippingRules200ResponseDataInner) GetReturnShippingRuleOk() (*ListShippingRules200ResponseDataInnerReturnShippingRule, bool)`

GetReturnShippingRuleOk returns a tuple with the ReturnShippingRule field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnShippingRule

`func (o *ListShippingRules200ResponseDataInner) SetReturnShippingRule(v ListShippingRules200ResponseDataInnerReturnShippingRule)`

SetReturnShippingRule sets ReturnShippingRule field to given value.

### HasReturnShippingRule

`func (o *ListShippingRules200ResponseDataInner) HasReturnShippingRule() bool`

HasReturnShippingRule returns a boolean if a field has been set.

### SetReturnShippingRuleNil

`func (o *ListShippingRules200ResponseDataInner) SetReturnShippingRuleNil(b bool)`

 SetReturnShippingRuleNil sets the value for ReturnShippingRule to be an explicit nil

### UnsetReturnShippingRule
`func (o *ListShippingRules200ResponseDataInner) UnsetReturnShippingRule()`

UnsetReturnShippingRule ensures that no value is present for ReturnShippingRule, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


