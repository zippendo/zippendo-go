# CreateShipmentRequestCarrierSettings

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CarrierId** | **string** | Identifier of the carrier to use. | 
**ProductId** | **string** | Identifier of the carrier product/service. | 
**Services** | **[]string** | Additional service codes requested from the carrier. | 
**AdditionalParameters** | [**map[string]CreateShippingRuleRequestAdditionalParametersValue**](CreateShippingRuleRequestAdditionalParametersValue.md) | Carrier-specific extra parameters as key/value pairs. | 

## Methods

### NewCreateShipmentRequestCarrierSettings

`func NewCreateShipmentRequestCarrierSettings(carrierId string, productId string, services []string, additionalParameters map[string]CreateShippingRuleRequestAdditionalParametersValue, ) *CreateShipmentRequestCarrierSettings`

NewCreateShipmentRequestCarrierSettings instantiates a new CreateShipmentRequestCarrierSettings object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateShipmentRequestCarrierSettingsWithDefaults

`func NewCreateShipmentRequestCarrierSettingsWithDefaults() *CreateShipmentRequestCarrierSettings`

NewCreateShipmentRequestCarrierSettingsWithDefaults instantiates a new CreateShipmentRequestCarrierSettings object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCarrierId

`func (o *CreateShipmentRequestCarrierSettings) GetCarrierId() string`

GetCarrierId returns the CarrierId field if non-nil, zero value otherwise.

### GetCarrierIdOk

`func (o *CreateShipmentRequestCarrierSettings) GetCarrierIdOk() (*string, bool)`

GetCarrierIdOk returns a tuple with the CarrierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierId

`func (o *CreateShipmentRequestCarrierSettings) SetCarrierId(v string)`

SetCarrierId sets CarrierId field to given value.


### GetProductId

`func (o *CreateShipmentRequestCarrierSettings) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *CreateShipmentRequestCarrierSettings) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *CreateShipmentRequestCarrierSettings) SetProductId(v string)`

SetProductId sets ProductId field to given value.


### GetServices

`func (o *CreateShipmentRequestCarrierSettings) GetServices() []string`

GetServices returns the Services field if non-nil, zero value otherwise.

### GetServicesOk

`func (o *CreateShipmentRequestCarrierSettings) GetServicesOk() (*[]string, bool)`

GetServicesOk returns a tuple with the Services field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServices

`func (o *CreateShipmentRequestCarrierSettings) SetServices(v []string)`

SetServices sets Services field to given value.


### GetAdditionalParameters

`func (o *CreateShipmentRequestCarrierSettings) GetAdditionalParameters() map[string]CreateShippingRuleRequestAdditionalParametersValue`

GetAdditionalParameters returns the AdditionalParameters field if non-nil, zero value otherwise.

### GetAdditionalParametersOk

`func (o *CreateShipmentRequestCarrierSettings) GetAdditionalParametersOk() (*map[string]CreateShippingRuleRequestAdditionalParametersValue, bool)`

GetAdditionalParametersOk returns a tuple with the AdditionalParameters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditionalParameters

`func (o *CreateShipmentRequestCarrierSettings) SetAdditionalParameters(v map[string]CreateShippingRuleRequestAdditionalParametersValue)`

SetAdditionalParameters sets AdditionalParameters field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


