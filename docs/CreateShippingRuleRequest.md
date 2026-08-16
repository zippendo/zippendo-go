# CreateShippingRuleRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | Shipping rule name | 
**Description** | Pointer to **string** | Optional description | [optional] 
**Direction** | Pointer to **string** | Whether this rule is for outbound or inbound (return) shipments | [optional] [default to "outbound"]
**CarrierId** | **string** | Carrier ID | 
**ProductId** | **string** | Product ID from carrier | 
**Services** | **[]string** | List of selected services | 
**AdditionalParameters** | Pointer to [**map[string]CreateShippingRuleRequestAdditionalParametersValue**](CreateShippingRuleRequestAdditionalParametersValue.md) | Carrier-specific extra parameters, keyed by the carrier parameter &#x60;key&#x60; from the product&#39;s &#x60;additionalParameters[].key&#x60; (e.g. &#x60;returnFunctionality&#x60;). | [optional] [default to {}]
**AddressId** | **string** | Sender address ID | 
**ReceivingCountries** | **[]string** | List of supported country codes | 
**EmailNotification** | Pointer to **bool** | Send email notification to recipient | [optional] [default to false]
**PhoneNotification** | Pointer to **bool** | Send SMS notification to recipient | [optional] [default to false]
**MinWeight** | Pointer to **NullableFloat32** | Minimum required weight in kg | [optional] 
**MaxWeight** | Pointer to **NullableFloat32** | Maximum allowed weight in kg | [optional] 
**MinOrderValue** | Pointer to **NullableFloat32** | Minimum required order value in currency units | [optional] 
**MaxOrderValue** | Pointer to **NullableFloat32** | Maximum allowed order value in currency units | [optional] 
**Conditions** | [**[]CreateShippingRuleRequestConditionsInner**](CreateShippingRuleRequestConditionsInner.md) | Rule conditions (weight/price/quantity) | 
**GenerateProformaInvoice** | Pointer to **bool** | Generate proforma invoice for shipments | [optional] [default to false]
**GenerateCommercialInvoice** | Pointer to **bool** | Generate commercial invoice for international shipments | [optional] [default to false]
**GeneratePackingList** | Pointer to **bool** | Generate packing slip with package and item details | [optional] [default to false]
**AutoPrintLabels** | Pointer to **bool** | Automatically print labels when shipment is sent | [optional] [default to false]
**AutoPrintDocuments** | Pointer to **bool** | Automatically print documents when shipment is sent | [optional] [default to false]
**LabelPrinterId** | Pointer to **NullableString** | ID of the label printer | [optional] 
**DocumentPrinterId** | Pointer to **NullableString** | ID of the document printer | [optional] 
**ReturnShippingRuleId** | Pointer to **NullableString** | ID of the return shipping rule | [optional] 
**AutoCreateReturnShipment** | Pointer to **bool** | Automatically create and send a return shipment on dispatch | [optional] [default to false]
**BrandId** | Pointer to **NullableString** | Brand this record is assigned to; null (or omitted outside a brand session) keeps it organization-wide | [optional] 

## Methods

### NewCreateShippingRuleRequest

`func NewCreateShippingRuleRequest(name string, carrierId string, productId string, services []string, addressId string, receivingCountries []string, conditions []CreateShippingRuleRequestConditionsInner, ) *CreateShippingRuleRequest`

NewCreateShippingRuleRequest instantiates a new CreateShippingRuleRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateShippingRuleRequestWithDefaults

`func NewCreateShippingRuleRequestWithDefaults() *CreateShippingRuleRequest`

NewCreateShippingRuleRequestWithDefaults instantiates a new CreateShippingRuleRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateShippingRuleRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateShippingRuleRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateShippingRuleRequest) SetName(v string)`

SetName sets Name field to given value.


### GetDescription

`func (o *CreateShippingRuleRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateShippingRuleRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateShippingRuleRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CreateShippingRuleRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetDirection

`func (o *CreateShippingRuleRequest) GetDirection() string`

GetDirection returns the Direction field if non-nil, zero value otherwise.

### GetDirectionOk

`func (o *CreateShippingRuleRequest) GetDirectionOk() (*string, bool)`

GetDirectionOk returns a tuple with the Direction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDirection

`func (o *CreateShippingRuleRequest) SetDirection(v string)`

SetDirection sets Direction field to given value.

### HasDirection

`func (o *CreateShippingRuleRequest) HasDirection() bool`

HasDirection returns a boolean if a field has been set.

### GetCarrierId

`func (o *CreateShippingRuleRequest) GetCarrierId() string`

GetCarrierId returns the CarrierId field if non-nil, zero value otherwise.

### GetCarrierIdOk

`func (o *CreateShippingRuleRequest) GetCarrierIdOk() (*string, bool)`

GetCarrierIdOk returns a tuple with the CarrierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierId

`func (o *CreateShippingRuleRequest) SetCarrierId(v string)`

SetCarrierId sets CarrierId field to given value.


### GetProductId

`func (o *CreateShippingRuleRequest) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *CreateShippingRuleRequest) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *CreateShippingRuleRequest) SetProductId(v string)`

SetProductId sets ProductId field to given value.


### GetServices

`func (o *CreateShippingRuleRequest) GetServices() []string`

GetServices returns the Services field if non-nil, zero value otherwise.

### GetServicesOk

`func (o *CreateShippingRuleRequest) GetServicesOk() (*[]string, bool)`

GetServicesOk returns a tuple with the Services field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServices

`func (o *CreateShippingRuleRequest) SetServices(v []string)`

SetServices sets Services field to given value.


### GetAdditionalParameters

`func (o *CreateShippingRuleRequest) GetAdditionalParameters() map[string]CreateShippingRuleRequestAdditionalParametersValue`

GetAdditionalParameters returns the AdditionalParameters field if non-nil, zero value otherwise.

### GetAdditionalParametersOk

`func (o *CreateShippingRuleRequest) GetAdditionalParametersOk() (*map[string]CreateShippingRuleRequestAdditionalParametersValue, bool)`

GetAdditionalParametersOk returns a tuple with the AdditionalParameters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditionalParameters

`func (o *CreateShippingRuleRequest) SetAdditionalParameters(v map[string]CreateShippingRuleRequestAdditionalParametersValue)`

SetAdditionalParameters sets AdditionalParameters field to given value.

### HasAdditionalParameters

`func (o *CreateShippingRuleRequest) HasAdditionalParameters() bool`

HasAdditionalParameters returns a boolean if a field has been set.

### GetAddressId

`func (o *CreateShippingRuleRequest) GetAddressId() string`

GetAddressId returns the AddressId field if non-nil, zero value otherwise.

### GetAddressIdOk

`func (o *CreateShippingRuleRequest) GetAddressIdOk() (*string, bool)`

GetAddressIdOk returns a tuple with the AddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressId

`func (o *CreateShippingRuleRequest) SetAddressId(v string)`

SetAddressId sets AddressId field to given value.


### GetReceivingCountries

`func (o *CreateShippingRuleRequest) GetReceivingCountries() []string`

GetReceivingCountries returns the ReceivingCountries field if non-nil, zero value otherwise.

### GetReceivingCountriesOk

`func (o *CreateShippingRuleRequest) GetReceivingCountriesOk() (*[]string, bool)`

GetReceivingCountriesOk returns a tuple with the ReceivingCountries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceivingCountries

`func (o *CreateShippingRuleRequest) SetReceivingCountries(v []string)`

SetReceivingCountries sets ReceivingCountries field to given value.


### GetEmailNotification

`func (o *CreateShippingRuleRequest) GetEmailNotification() bool`

GetEmailNotification returns the EmailNotification field if non-nil, zero value otherwise.

### GetEmailNotificationOk

`func (o *CreateShippingRuleRequest) GetEmailNotificationOk() (*bool, bool)`

GetEmailNotificationOk returns a tuple with the EmailNotification field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmailNotification

`func (o *CreateShippingRuleRequest) SetEmailNotification(v bool)`

SetEmailNotification sets EmailNotification field to given value.

### HasEmailNotification

`func (o *CreateShippingRuleRequest) HasEmailNotification() bool`

HasEmailNotification returns a boolean if a field has been set.

### GetPhoneNotification

`func (o *CreateShippingRuleRequest) GetPhoneNotification() bool`

GetPhoneNotification returns the PhoneNotification field if non-nil, zero value otherwise.

### GetPhoneNotificationOk

`func (o *CreateShippingRuleRequest) GetPhoneNotificationOk() (*bool, bool)`

GetPhoneNotificationOk returns a tuple with the PhoneNotification field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhoneNotification

`func (o *CreateShippingRuleRequest) SetPhoneNotification(v bool)`

SetPhoneNotification sets PhoneNotification field to given value.

### HasPhoneNotification

`func (o *CreateShippingRuleRequest) HasPhoneNotification() bool`

HasPhoneNotification returns a boolean if a field has been set.

### GetMinWeight

`func (o *CreateShippingRuleRequest) GetMinWeight() float32`

GetMinWeight returns the MinWeight field if non-nil, zero value otherwise.

### GetMinWeightOk

`func (o *CreateShippingRuleRequest) GetMinWeightOk() (*float32, bool)`

GetMinWeightOk returns a tuple with the MinWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinWeight

`func (o *CreateShippingRuleRequest) SetMinWeight(v float32)`

SetMinWeight sets MinWeight field to given value.

### HasMinWeight

`func (o *CreateShippingRuleRequest) HasMinWeight() bool`

HasMinWeight returns a boolean if a field has been set.

### SetMinWeightNil

`func (o *CreateShippingRuleRequest) SetMinWeightNil(b bool)`

 SetMinWeightNil sets the value for MinWeight to be an explicit nil

### UnsetMinWeight
`func (o *CreateShippingRuleRequest) UnsetMinWeight()`

UnsetMinWeight ensures that no value is present for MinWeight, not even an explicit nil
### GetMaxWeight

`func (o *CreateShippingRuleRequest) GetMaxWeight() float32`

GetMaxWeight returns the MaxWeight field if non-nil, zero value otherwise.

### GetMaxWeightOk

`func (o *CreateShippingRuleRequest) GetMaxWeightOk() (*float32, bool)`

GetMaxWeightOk returns a tuple with the MaxWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxWeight

`func (o *CreateShippingRuleRequest) SetMaxWeight(v float32)`

SetMaxWeight sets MaxWeight field to given value.

### HasMaxWeight

`func (o *CreateShippingRuleRequest) HasMaxWeight() bool`

HasMaxWeight returns a boolean if a field has been set.

### SetMaxWeightNil

`func (o *CreateShippingRuleRequest) SetMaxWeightNil(b bool)`

 SetMaxWeightNil sets the value for MaxWeight to be an explicit nil

### UnsetMaxWeight
`func (o *CreateShippingRuleRequest) UnsetMaxWeight()`

UnsetMaxWeight ensures that no value is present for MaxWeight, not even an explicit nil
### GetMinOrderValue

`func (o *CreateShippingRuleRequest) GetMinOrderValue() float32`

GetMinOrderValue returns the MinOrderValue field if non-nil, zero value otherwise.

### GetMinOrderValueOk

`func (o *CreateShippingRuleRequest) GetMinOrderValueOk() (*float32, bool)`

GetMinOrderValueOk returns a tuple with the MinOrderValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinOrderValue

`func (o *CreateShippingRuleRequest) SetMinOrderValue(v float32)`

SetMinOrderValue sets MinOrderValue field to given value.

### HasMinOrderValue

`func (o *CreateShippingRuleRequest) HasMinOrderValue() bool`

HasMinOrderValue returns a boolean if a field has been set.

### SetMinOrderValueNil

`func (o *CreateShippingRuleRequest) SetMinOrderValueNil(b bool)`

 SetMinOrderValueNil sets the value for MinOrderValue to be an explicit nil

### UnsetMinOrderValue
`func (o *CreateShippingRuleRequest) UnsetMinOrderValue()`

UnsetMinOrderValue ensures that no value is present for MinOrderValue, not even an explicit nil
### GetMaxOrderValue

`func (o *CreateShippingRuleRequest) GetMaxOrderValue() float32`

GetMaxOrderValue returns the MaxOrderValue field if non-nil, zero value otherwise.

### GetMaxOrderValueOk

`func (o *CreateShippingRuleRequest) GetMaxOrderValueOk() (*float32, bool)`

GetMaxOrderValueOk returns a tuple with the MaxOrderValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxOrderValue

`func (o *CreateShippingRuleRequest) SetMaxOrderValue(v float32)`

SetMaxOrderValue sets MaxOrderValue field to given value.

### HasMaxOrderValue

`func (o *CreateShippingRuleRequest) HasMaxOrderValue() bool`

HasMaxOrderValue returns a boolean if a field has been set.

### SetMaxOrderValueNil

`func (o *CreateShippingRuleRequest) SetMaxOrderValueNil(b bool)`

 SetMaxOrderValueNil sets the value for MaxOrderValue to be an explicit nil

### UnsetMaxOrderValue
`func (o *CreateShippingRuleRequest) UnsetMaxOrderValue()`

UnsetMaxOrderValue ensures that no value is present for MaxOrderValue, not even an explicit nil
### GetConditions

`func (o *CreateShippingRuleRequest) GetConditions() []CreateShippingRuleRequestConditionsInner`

GetConditions returns the Conditions field if non-nil, zero value otherwise.

### GetConditionsOk

`func (o *CreateShippingRuleRequest) GetConditionsOk() (*[]CreateShippingRuleRequestConditionsInner, bool)`

GetConditionsOk returns a tuple with the Conditions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConditions

`func (o *CreateShippingRuleRequest) SetConditions(v []CreateShippingRuleRequestConditionsInner)`

SetConditions sets Conditions field to given value.


### GetGenerateProformaInvoice

`func (o *CreateShippingRuleRequest) GetGenerateProformaInvoice() bool`

GetGenerateProformaInvoice returns the GenerateProformaInvoice field if non-nil, zero value otherwise.

### GetGenerateProformaInvoiceOk

`func (o *CreateShippingRuleRequest) GetGenerateProformaInvoiceOk() (*bool, bool)`

GetGenerateProformaInvoiceOk returns a tuple with the GenerateProformaInvoice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGenerateProformaInvoice

`func (o *CreateShippingRuleRequest) SetGenerateProformaInvoice(v bool)`

SetGenerateProformaInvoice sets GenerateProformaInvoice field to given value.

### HasGenerateProformaInvoice

`func (o *CreateShippingRuleRequest) HasGenerateProformaInvoice() bool`

HasGenerateProformaInvoice returns a boolean if a field has been set.

### GetGenerateCommercialInvoice

`func (o *CreateShippingRuleRequest) GetGenerateCommercialInvoice() bool`

GetGenerateCommercialInvoice returns the GenerateCommercialInvoice field if non-nil, zero value otherwise.

### GetGenerateCommercialInvoiceOk

`func (o *CreateShippingRuleRequest) GetGenerateCommercialInvoiceOk() (*bool, bool)`

GetGenerateCommercialInvoiceOk returns a tuple with the GenerateCommercialInvoice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGenerateCommercialInvoice

`func (o *CreateShippingRuleRequest) SetGenerateCommercialInvoice(v bool)`

SetGenerateCommercialInvoice sets GenerateCommercialInvoice field to given value.

### HasGenerateCommercialInvoice

`func (o *CreateShippingRuleRequest) HasGenerateCommercialInvoice() bool`

HasGenerateCommercialInvoice returns a boolean if a field has been set.

### GetGeneratePackingList

`func (o *CreateShippingRuleRequest) GetGeneratePackingList() bool`

GetGeneratePackingList returns the GeneratePackingList field if non-nil, zero value otherwise.

### GetGeneratePackingListOk

`func (o *CreateShippingRuleRequest) GetGeneratePackingListOk() (*bool, bool)`

GetGeneratePackingListOk returns a tuple with the GeneratePackingList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneratePackingList

`func (o *CreateShippingRuleRequest) SetGeneratePackingList(v bool)`

SetGeneratePackingList sets GeneratePackingList field to given value.

### HasGeneratePackingList

`func (o *CreateShippingRuleRequest) HasGeneratePackingList() bool`

HasGeneratePackingList returns a boolean if a field has been set.

### GetAutoPrintLabels

`func (o *CreateShippingRuleRequest) GetAutoPrintLabels() bool`

GetAutoPrintLabels returns the AutoPrintLabels field if non-nil, zero value otherwise.

### GetAutoPrintLabelsOk

`func (o *CreateShippingRuleRequest) GetAutoPrintLabelsOk() (*bool, bool)`

GetAutoPrintLabelsOk returns a tuple with the AutoPrintLabels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoPrintLabels

`func (o *CreateShippingRuleRequest) SetAutoPrintLabels(v bool)`

SetAutoPrintLabels sets AutoPrintLabels field to given value.

### HasAutoPrintLabels

`func (o *CreateShippingRuleRequest) HasAutoPrintLabels() bool`

HasAutoPrintLabels returns a boolean if a field has been set.

### GetAutoPrintDocuments

`func (o *CreateShippingRuleRequest) GetAutoPrintDocuments() bool`

GetAutoPrintDocuments returns the AutoPrintDocuments field if non-nil, zero value otherwise.

### GetAutoPrintDocumentsOk

`func (o *CreateShippingRuleRequest) GetAutoPrintDocumentsOk() (*bool, bool)`

GetAutoPrintDocumentsOk returns a tuple with the AutoPrintDocuments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoPrintDocuments

`func (o *CreateShippingRuleRequest) SetAutoPrintDocuments(v bool)`

SetAutoPrintDocuments sets AutoPrintDocuments field to given value.

### HasAutoPrintDocuments

`func (o *CreateShippingRuleRequest) HasAutoPrintDocuments() bool`

HasAutoPrintDocuments returns a boolean if a field has been set.

### GetLabelPrinterId

`func (o *CreateShippingRuleRequest) GetLabelPrinterId() string`

GetLabelPrinterId returns the LabelPrinterId field if non-nil, zero value otherwise.

### GetLabelPrinterIdOk

`func (o *CreateShippingRuleRequest) GetLabelPrinterIdOk() (*string, bool)`

GetLabelPrinterIdOk returns a tuple with the LabelPrinterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabelPrinterId

`func (o *CreateShippingRuleRequest) SetLabelPrinterId(v string)`

SetLabelPrinterId sets LabelPrinterId field to given value.

### HasLabelPrinterId

`func (o *CreateShippingRuleRequest) HasLabelPrinterId() bool`

HasLabelPrinterId returns a boolean if a field has been set.

### SetLabelPrinterIdNil

`func (o *CreateShippingRuleRequest) SetLabelPrinterIdNil(b bool)`

 SetLabelPrinterIdNil sets the value for LabelPrinterId to be an explicit nil

### UnsetLabelPrinterId
`func (o *CreateShippingRuleRequest) UnsetLabelPrinterId()`

UnsetLabelPrinterId ensures that no value is present for LabelPrinterId, not even an explicit nil
### GetDocumentPrinterId

`func (o *CreateShippingRuleRequest) GetDocumentPrinterId() string`

GetDocumentPrinterId returns the DocumentPrinterId field if non-nil, zero value otherwise.

### GetDocumentPrinterIdOk

`func (o *CreateShippingRuleRequest) GetDocumentPrinterIdOk() (*string, bool)`

GetDocumentPrinterIdOk returns a tuple with the DocumentPrinterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocumentPrinterId

`func (o *CreateShippingRuleRequest) SetDocumentPrinterId(v string)`

SetDocumentPrinterId sets DocumentPrinterId field to given value.

### HasDocumentPrinterId

`func (o *CreateShippingRuleRequest) HasDocumentPrinterId() bool`

HasDocumentPrinterId returns a boolean if a field has been set.

### SetDocumentPrinterIdNil

`func (o *CreateShippingRuleRequest) SetDocumentPrinterIdNil(b bool)`

 SetDocumentPrinterIdNil sets the value for DocumentPrinterId to be an explicit nil

### UnsetDocumentPrinterId
`func (o *CreateShippingRuleRequest) UnsetDocumentPrinterId()`

UnsetDocumentPrinterId ensures that no value is present for DocumentPrinterId, not even an explicit nil
### GetReturnShippingRuleId

`func (o *CreateShippingRuleRequest) GetReturnShippingRuleId() string`

GetReturnShippingRuleId returns the ReturnShippingRuleId field if non-nil, zero value otherwise.

### GetReturnShippingRuleIdOk

`func (o *CreateShippingRuleRequest) GetReturnShippingRuleIdOk() (*string, bool)`

GetReturnShippingRuleIdOk returns a tuple with the ReturnShippingRuleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnShippingRuleId

`func (o *CreateShippingRuleRequest) SetReturnShippingRuleId(v string)`

SetReturnShippingRuleId sets ReturnShippingRuleId field to given value.

### HasReturnShippingRuleId

`func (o *CreateShippingRuleRequest) HasReturnShippingRuleId() bool`

HasReturnShippingRuleId returns a boolean if a field has been set.

### SetReturnShippingRuleIdNil

`func (o *CreateShippingRuleRequest) SetReturnShippingRuleIdNil(b bool)`

 SetReturnShippingRuleIdNil sets the value for ReturnShippingRuleId to be an explicit nil

### UnsetReturnShippingRuleId
`func (o *CreateShippingRuleRequest) UnsetReturnShippingRuleId()`

UnsetReturnShippingRuleId ensures that no value is present for ReturnShippingRuleId, not even an explicit nil
### GetAutoCreateReturnShipment

`func (o *CreateShippingRuleRequest) GetAutoCreateReturnShipment() bool`

GetAutoCreateReturnShipment returns the AutoCreateReturnShipment field if non-nil, zero value otherwise.

### GetAutoCreateReturnShipmentOk

`func (o *CreateShippingRuleRequest) GetAutoCreateReturnShipmentOk() (*bool, bool)`

GetAutoCreateReturnShipmentOk returns a tuple with the AutoCreateReturnShipment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoCreateReturnShipment

`func (o *CreateShippingRuleRequest) SetAutoCreateReturnShipment(v bool)`

SetAutoCreateReturnShipment sets AutoCreateReturnShipment field to given value.

### HasAutoCreateReturnShipment

`func (o *CreateShippingRuleRequest) HasAutoCreateReturnShipment() bool`

HasAutoCreateReturnShipment returns a boolean if a field has been set.

### GetBrandId

`func (o *CreateShippingRuleRequest) GetBrandId() string`

GetBrandId returns the BrandId field if non-nil, zero value otherwise.

### GetBrandIdOk

`func (o *CreateShippingRuleRequest) GetBrandIdOk() (*string, bool)`

GetBrandIdOk returns a tuple with the BrandId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandId

`func (o *CreateShippingRuleRequest) SetBrandId(v string)`

SetBrandId sets BrandId field to given value.

### HasBrandId

`func (o *CreateShippingRuleRequest) HasBrandId() bool`

HasBrandId returns a boolean if a field has been set.

### SetBrandIdNil

`func (o *CreateShippingRuleRequest) SetBrandIdNil(b bool)`

 SetBrandIdNil sets the value for BrandId to be an explicit nil

### UnsetBrandId
`func (o *CreateShippingRuleRequest) UnsetBrandId()`

UnsetBrandId ensures that no value is present for BrandId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


