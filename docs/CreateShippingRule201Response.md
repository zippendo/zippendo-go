# CreateShippingRule201Response

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
**AdditionalParameters** | [**map[string]ListShippingRules200ResponseDataInnerAdditionalParametersValue**](ListShippingRules200ResponseDataInnerAdditionalParametersValue.md) | Carrier-specific extra parameters, keyed by the carrier parameter &#x60;key&#x60; from the product&#39;s &#x60;additionalParameters[].key&#x60;. | 
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
**BrandId** | **NullableString** | Brand this record belongs to, or null when it is organization-wide | 
**CreatedAt** | **string** | Creation timestamp (ISO 8601) | 
**UpdatedAt** | **string** | Last update timestamp (ISO 8601) | 

## Methods

### NewCreateShippingRule201Response

`func NewCreateShippingRule201Response(id string, name string, description NullableString, direction string, carrierId string, productId string, services []string, additionalParameters map[string]ListShippingRules200ResponseDataInnerAdditionalParametersValue, addressId string, receivingCountries []string, emailNotification bool, phoneNotification bool, minWeight NullableFloat32, maxWeight NullableFloat32, minOrderValue NullableFloat32, maxOrderValue NullableFloat32, conditions []ListShippingRules200ResponseDataInnerConditionsInner, generateProformaInvoice bool, generateCommercialInvoice bool, generatePackingList bool, autoPrintLabels bool, autoPrintDocuments bool, labelPrinterId NullableString, documentPrinterId NullableString, returnShippingRuleId NullableString, autoCreateReturnShipment bool, orgId string, brandId NullableString, createdAt string, updatedAt string, ) *CreateShippingRule201Response`

NewCreateShippingRule201Response instantiates a new CreateShippingRule201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateShippingRule201ResponseWithDefaults

`func NewCreateShippingRule201ResponseWithDefaults() *CreateShippingRule201Response`

NewCreateShippingRule201ResponseWithDefaults instantiates a new CreateShippingRule201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreateShippingRule201Response) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateShippingRule201Response) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateShippingRule201Response) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *CreateShippingRule201Response) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateShippingRule201Response) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateShippingRule201Response) SetName(v string)`

SetName sets Name field to given value.


### GetDescription

`func (o *CreateShippingRule201Response) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateShippingRule201Response) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateShippingRule201Response) SetDescription(v string)`

SetDescription sets Description field to given value.


### SetDescriptionNil

`func (o *CreateShippingRule201Response) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *CreateShippingRule201Response) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetDirection

`func (o *CreateShippingRule201Response) GetDirection() string`

GetDirection returns the Direction field if non-nil, zero value otherwise.

### GetDirectionOk

`func (o *CreateShippingRule201Response) GetDirectionOk() (*string, bool)`

GetDirectionOk returns a tuple with the Direction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDirection

`func (o *CreateShippingRule201Response) SetDirection(v string)`

SetDirection sets Direction field to given value.


### GetCarrierId

`func (o *CreateShippingRule201Response) GetCarrierId() string`

GetCarrierId returns the CarrierId field if non-nil, zero value otherwise.

### GetCarrierIdOk

`func (o *CreateShippingRule201Response) GetCarrierIdOk() (*string, bool)`

GetCarrierIdOk returns a tuple with the CarrierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierId

`func (o *CreateShippingRule201Response) SetCarrierId(v string)`

SetCarrierId sets CarrierId field to given value.


### GetProductId

`func (o *CreateShippingRule201Response) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *CreateShippingRule201Response) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *CreateShippingRule201Response) SetProductId(v string)`

SetProductId sets ProductId field to given value.


### GetServices

`func (o *CreateShippingRule201Response) GetServices() []string`

GetServices returns the Services field if non-nil, zero value otherwise.

### GetServicesOk

`func (o *CreateShippingRule201Response) GetServicesOk() (*[]string, bool)`

GetServicesOk returns a tuple with the Services field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServices

`func (o *CreateShippingRule201Response) SetServices(v []string)`

SetServices sets Services field to given value.


### GetAdditionalParameters

`func (o *CreateShippingRule201Response) GetAdditionalParameters() map[string]ListShippingRules200ResponseDataInnerAdditionalParametersValue`

GetAdditionalParameters returns the AdditionalParameters field if non-nil, zero value otherwise.

### GetAdditionalParametersOk

`func (o *CreateShippingRule201Response) GetAdditionalParametersOk() (*map[string]ListShippingRules200ResponseDataInnerAdditionalParametersValue, bool)`

GetAdditionalParametersOk returns a tuple with the AdditionalParameters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditionalParameters

`func (o *CreateShippingRule201Response) SetAdditionalParameters(v map[string]ListShippingRules200ResponseDataInnerAdditionalParametersValue)`

SetAdditionalParameters sets AdditionalParameters field to given value.


### GetAddressId

`func (o *CreateShippingRule201Response) GetAddressId() string`

GetAddressId returns the AddressId field if non-nil, zero value otherwise.

### GetAddressIdOk

`func (o *CreateShippingRule201Response) GetAddressIdOk() (*string, bool)`

GetAddressIdOk returns a tuple with the AddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressId

`func (o *CreateShippingRule201Response) SetAddressId(v string)`

SetAddressId sets AddressId field to given value.


### GetReceivingCountries

`func (o *CreateShippingRule201Response) GetReceivingCountries() []string`

GetReceivingCountries returns the ReceivingCountries field if non-nil, zero value otherwise.

### GetReceivingCountriesOk

`func (o *CreateShippingRule201Response) GetReceivingCountriesOk() (*[]string, bool)`

GetReceivingCountriesOk returns a tuple with the ReceivingCountries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceivingCountries

`func (o *CreateShippingRule201Response) SetReceivingCountries(v []string)`

SetReceivingCountries sets ReceivingCountries field to given value.


### GetEmailNotification

`func (o *CreateShippingRule201Response) GetEmailNotification() bool`

GetEmailNotification returns the EmailNotification field if non-nil, zero value otherwise.

### GetEmailNotificationOk

`func (o *CreateShippingRule201Response) GetEmailNotificationOk() (*bool, bool)`

GetEmailNotificationOk returns a tuple with the EmailNotification field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmailNotification

`func (o *CreateShippingRule201Response) SetEmailNotification(v bool)`

SetEmailNotification sets EmailNotification field to given value.


### GetPhoneNotification

`func (o *CreateShippingRule201Response) GetPhoneNotification() bool`

GetPhoneNotification returns the PhoneNotification field if non-nil, zero value otherwise.

### GetPhoneNotificationOk

`func (o *CreateShippingRule201Response) GetPhoneNotificationOk() (*bool, bool)`

GetPhoneNotificationOk returns a tuple with the PhoneNotification field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhoneNotification

`func (o *CreateShippingRule201Response) SetPhoneNotification(v bool)`

SetPhoneNotification sets PhoneNotification field to given value.


### GetMinWeight

`func (o *CreateShippingRule201Response) GetMinWeight() float32`

GetMinWeight returns the MinWeight field if non-nil, zero value otherwise.

### GetMinWeightOk

`func (o *CreateShippingRule201Response) GetMinWeightOk() (*float32, bool)`

GetMinWeightOk returns a tuple with the MinWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinWeight

`func (o *CreateShippingRule201Response) SetMinWeight(v float32)`

SetMinWeight sets MinWeight field to given value.


### SetMinWeightNil

`func (o *CreateShippingRule201Response) SetMinWeightNil(b bool)`

 SetMinWeightNil sets the value for MinWeight to be an explicit nil

### UnsetMinWeight
`func (o *CreateShippingRule201Response) UnsetMinWeight()`

UnsetMinWeight ensures that no value is present for MinWeight, not even an explicit nil
### GetMaxWeight

`func (o *CreateShippingRule201Response) GetMaxWeight() float32`

GetMaxWeight returns the MaxWeight field if non-nil, zero value otherwise.

### GetMaxWeightOk

`func (o *CreateShippingRule201Response) GetMaxWeightOk() (*float32, bool)`

GetMaxWeightOk returns a tuple with the MaxWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxWeight

`func (o *CreateShippingRule201Response) SetMaxWeight(v float32)`

SetMaxWeight sets MaxWeight field to given value.


### SetMaxWeightNil

`func (o *CreateShippingRule201Response) SetMaxWeightNil(b bool)`

 SetMaxWeightNil sets the value for MaxWeight to be an explicit nil

### UnsetMaxWeight
`func (o *CreateShippingRule201Response) UnsetMaxWeight()`

UnsetMaxWeight ensures that no value is present for MaxWeight, not even an explicit nil
### GetMinOrderValue

`func (o *CreateShippingRule201Response) GetMinOrderValue() float32`

GetMinOrderValue returns the MinOrderValue field if non-nil, zero value otherwise.

### GetMinOrderValueOk

`func (o *CreateShippingRule201Response) GetMinOrderValueOk() (*float32, bool)`

GetMinOrderValueOk returns a tuple with the MinOrderValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinOrderValue

`func (o *CreateShippingRule201Response) SetMinOrderValue(v float32)`

SetMinOrderValue sets MinOrderValue field to given value.


### SetMinOrderValueNil

`func (o *CreateShippingRule201Response) SetMinOrderValueNil(b bool)`

 SetMinOrderValueNil sets the value for MinOrderValue to be an explicit nil

### UnsetMinOrderValue
`func (o *CreateShippingRule201Response) UnsetMinOrderValue()`

UnsetMinOrderValue ensures that no value is present for MinOrderValue, not even an explicit nil
### GetMaxOrderValue

`func (o *CreateShippingRule201Response) GetMaxOrderValue() float32`

GetMaxOrderValue returns the MaxOrderValue field if non-nil, zero value otherwise.

### GetMaxOrderValueOk

`func (o *CreateShippingRule201Response) GetMaxOrderValueOk() (*float32, bool)`

GetMaxOrderValueOk returns a tuple with the MaxOrderValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxOrderValue

`func (o *CreateShippingRule201Response) SetMaxOrderValue(v float32)`

SetMaxOrderValue sets MaxOrderValue field to given value.


### SetMaxOrderValueNil

`func (o *CreateShippingRule201Response) SetMaxOrderValueNil(b bool)`

 SetMaxOrderValueNil sets the value for MaxOrderValue to be an explicit nil

### UnsetMaxOrderValue
`func (o *CreateShippingRule201Response) UnsetMaxOrderValue()`

UnsetMaxOrderValue ensures that no value is present for MaxOrderValue, not even an explicit nil
### GetConditions

`func (o *CreateShippingRule201Response) GetConditions() []ListShippingRules200ResponseDataInnerConditionsInner`

GetConditions returns the Conditions field if non-nil, zero value otherwise.

### GetConditionsOk

`func (o *CreateShippingRule201Response) GetConditionsOk() (*[]ListShippingRules200ResponseDataInnerConditionsInner, bool)`

GetConditionsOk returns a tuple with the Conditions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConditions

`func (o *CreateShippingRule201Response) SetConditions(v []ListShippingRules200ResponseDataInnerConditionsInner)`

SetConditions sets Conditions field to given value.


### GetGenerateProformaInvoice

`func (o *CreateShippingRule201Response) GetGenerateProformaInvoice() bool`

GetGenerateProformaInvoice returns the GenerateProformaInvoice field if non-nil, zero value otherwise.

### GetGenerateProformaInvoiceOk

`func (o *CreateShippingRule201Response) GetGenerateProformaInvoiceOk() (*bool, bool)`

GetGenerateProformaInvoiceOk returns a tuple with the GenerateProformaInvoice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGenerateProformaInvoice

`func (o *CreateShippingRule201Response) SetGenerateProformaInvoice(v bool)`

SetGenerateProformaInvoice sets GenerateProformaInvoice field to given value.


### GetGenerateCommercialInvoice

`func (o *CreateShippingRule201Response) GetGenerateCommercialInvoice() bool`

GetGenerateCommercialInvoice returns the GenerateCommercialInvoice field if non-nil, zero value otherwise.

### GetGenerateCommercialInvoiceOk

`func (o *CreateShippingRule201Response) GetGenerateCommercialInvoiceOk() (*bool, bool)`

GetGenerateCommercialInvoiceOk returns a tuple with the GenerateCommercialInvoice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGenerateCommercialInvoice

`func (o *CreateShippingRule201Response) SetGenerateCommercialInvoice(v bool)`

SetGenerateCommercialInvoice sets GenerateCommercialInvoice field to given value.


### GetGeneratePackingList

`func (o *CreateShippingRule201Response) GetGeneratePackingList() bool`

GetGeneratePackingList returns the GeneratePackingList field if non-nil, zero value otherwise.

### GetGeneratePackingListOk

`func (o *CreateShippingRule201Response) GetGeneratePackingListOk() (*bool, bool)`

GetGeneratePackingListOk returns a tuple with the GeneratePackingList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneratePackingList

`func (o *CreateShippingRule201Response) SetGeneratePackingList(v bool)`

SetGeneratePackingList sets GeneratePackingList field to given value.


### GetAutoPrintLabels

`func (o *CreateShippingRule201Response) GetAutoPrintLabels() bool`

GetAutoPrintLabels returns the AutoPrintLabels field if non-nil, zero value otherwise.

### GetAutoPrintLabelsOk

`func (o *CreateShippingRule201Response) GetAutoPrintLabelsOk() (*bool, bool)`

GetAutoPrintLabelsOk returns a tuple with the AutoPrintLabels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoPrintLabels

`func (o *CreateShippingRule201Response) SetAutoPrintLabels(v bool)`

SetAutoPrintLabels sets AutoPrintLabels field to given value.


### GetAutoPrintDocuments

`func (o *CreateShippingRule201Response) GetAutoPrintDocuments() bool`

GetAutoPrintDocuments returns the AutoPrintDocuments field if non-nil, zero value otherwise.

### GetAutoPrintDocumentsOk

`func (o *CreateShippingRule201Response) GetAutoPrintDocumentsOk() (*bool, bool)`

GetAutoPrintDocumentsOk returns a tuple with the AutoPrintDocuments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoPrintDocuments

`func (o *CreateShippingRule201Response) SetAutoPrintDocuments(v bool)`

SetAutoPrintDocuments sets AutoPrintDocuments field to given value.


### GetLabelPrinterId

`func (o *CreateShippingRule201Response) GetLabelPrinterId() string`

GetLabelPrinterId returns the LabelPrinterId field if non-nil, zero value otherwise.

### GetLabelPrinterIdOk

`func (o *CreateShippingRule201Response) GetLabelPrinterIdOk() (*string, bool)`

GetLabelPrinterIdOk returns a tuple with the LabelPrinterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabelPrinterId

`func (o *CreateShippingRule201Response) SetLabelPrinterId(v string)`

SetLabelPrinterId sets LabelPrinterId field to given value.


### SetLabelPrinterIdNil

`func (o *CreateShippingRule201Response) SetLabelPrinterIdNil(b bool)`

 SetLabelPrinterIdNil sets the value for LabelPrinterId to be an explicit nil

### UnsetLabelPrinterId
`func (o *CreateShippingRule201Response) UnsetLabelPrinterId()`

UnsetLabelPrinterId ensures that no value is present for LabelPrinterId, not even an explicit nil
### GetDocumentPrinterId

`func (o *CreateShippingRule201Response) GetDocumentPrinterId() string`

GetDocumentPrinterId returns the DocumentPrinterId field if non-nil, zero value otherwise.

### GetDocumentPrinterIdOk

`func (o *CreateShippingRule201Response) GetDocumentPrinterIdOk() (*string, bool)`

GetDocumentPrinterIdOk returns a tuple with the DocumentPrinterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocumentPrinterId

`func (o *CreateShippingRule201Response) SetDocumentPrinterId(v string)`

SetDocumentPrinterId sets DocumentPrinterId field to given value.


### SetDocumentPrinterIdNil

`func (o *CreateShippingRule201Response) SetDocumentPrinterIdNil(b bool)`

 SetDocumentPrinterIdNil sets the value for DocumentPrinterId to be an explicit nil

### UnsetDocumentPrinterId
`func (o *CreateShippingRule201Response) UnsetDocumentPrinterId()`

UnsetDocumentPrinterId ensures that no value is present for DocumentPrinterId, not even an explicit nil
### GetReturnShippingRuleId

`func (o *CreateShippingRule201Response) GetReturnShippingRuleId() string`

GetReturnShippingRuleId returns the ReturnShippingRuleId field if non-nil, zero value otherwise.

### GetReturnShippingRuleIdOk

`func (o *CreateShippingRule201Response) GetReturnShippingRuleIdOk() (*string, bool)`

GetReturnShippingRuleIdOk returns a tuple with the ReturnShippingRuleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnShippingRuleId

`func (o *CreateShippingRule201Response) SetReturnShippingRuleId(v string)`

SetReturnShippingRuleId sets ReturnShippingRuleId field to given value.


### SetReturnShippingRuleIdNil

`func (o *CreateShippingRule201Response) SetReturnShippingRuleIdNil(b bool)`

 SetReturnShippingRuleIdNil sets the value for ReturnShippingRuleId to be an explicit nil

### UnsetReturnShippingRuleId
`func (o *CreateShippingRule201Response) UnsetReturnShippingRuleId()`

UnsetReturnShippingRuleId ensures that no value is present for ReturnShippingRuleId, not even an explicit nil
### GetAutoCreateReturnShipment

`func (o *CreateShippingRule201Response) GetAutoCreateReturnShipment() bool`

GetAutoCreateReturnShipment returns the AutoCreateReturnShipment field if non-nil, zero value otherwise.

### GetAutoCreateReturnShipmentOk

`func (o *CreateShippingRule201Response) GetAutoCreateReturnShipmentOk() (*bool, bool)`

GetAutoCreateReturnShipmentOk returns a tuple with the AutoCreateReturnShipment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoCreateReturnShipment

`func (o *CreateShippingRule201Response) SetAutoCreateReturnShipment(v bool)`

SetAutoCreateReturnShipment sets AutoCreateReturnShipment field to given value.


### GetOrgId

`func (o *CreateShippingRule201Response) GetOrgId() string`

GetOrgId returns the OrgId field if non-nil, zero value otherwise.

### GetOrgIdOk

`func (o *CreateShippingRule201Response) GetOrgIdOk() (*string, bool)`

GetOrgIdOk returns a tuple with the OrgId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrgId

`func (o *CreateShippingRule201Response) SetOrgId(v string)`

SetOrgId sets OrgId field to given value.


### GetBrandId

`func (o *CreateShippingRule201Response) GetBrandId() string`

GetBrandId returns the BrandId field if non-nil, zero value otherwise.

### GetBrandIdOk

`func (o *CreateShippingRule201Response) GetBrandIdOk() (*string, bool)`

GetBrandIdOk returns a tuple with the BrandId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandId

`func (o *CreateShippingRule201Response) SetBrandId(v string)`

SetBrandId sets BrandId field to given value.


### SetBrandIdNil

`func (o *CreateShippingRule201Response) SetBrandIdNil(b bool)`

 SetBrandIdNil sets the value for BrandId to be an explicit nil

### UnsetBrandId
`func (o *CreateShippingRule201Response) UnsetBrandId()`

UnsetBrandId ensures that no value is present for BrandId, not even an explicit nil
### GetCreatedAt

`func (o *CreateShippingRule201Response) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CreateShippingRule201Response) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CreateShippingRule201Response) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *CreateShippingRule201Response) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *CreateShippingRule201Response) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *CreateShippingRule201Response) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


