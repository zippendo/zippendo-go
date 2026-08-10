# ListShipments200ResponseDataInnerCarrierSettings

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CarrierId** | **string** | Identifier of the carrier to use. | 
**ProductId** | **string** | Identifier of the carrier product/service. | 
**Services** | **[]string** | Additional service codes requested from the carrier. | 
**AdditionalParameters** | [**map[string]ListShippingRules200ResponseDataInnerAdditionalParametersValue**](ListShippingRules200ResponseDataInnerAdditionalParametersValue.md) | Carrier-specific extra parameters as key/value pairs. | 

## Methods

### NewListShipments200ResponseDataInnerCarrierSettings

`func NewListShipments200ResponseDataInnerCarrierSettings(carrierId string, productId string, services []string, additionalParameters map[string]ListShippingRules200ResponseDataInnerAdditionalParametersValue, ) *ListShipments200ResponseDataInnerCarrierSettings`

NewListShipments200ResponseDataInnerCarrierSettings instantiates a new ListShipments200ResponseDataInnerCarrierSettings object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListShipments200ResponseDataInnerCarrierSettingsWithDefaults

`func NewListShipments200ResponseDataInnerCarrierSettingsWithDefaults() *ListShipments200ResponseDataInnerCarrierSettings`

NewListShipments200ResponseDataInnerCarrierSettingsWithDefaults instantiates a new ListShipments200ResponseDataInnerCarrierSettings object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCarrierId

`func (o *ListShipments200ResponseDataInnerCarrierSettings) GetCarrierId() string`

GetCarrierId returns the CarrierId field if non-nil, zero value otherwise.

### GetCarrierIdOk

`func (o *ListShipments200ResponseDataInnerCarrierSettings) GetCarrierIdOk() (*string, bool)`

GetCarrierIdOk returns a tuple with the CarrierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierId

`func (o *ListShipments200ResponseDataInnerCarrierSettings) SetCarrierId(v string)`

SetCarrierId sets CarrierId field to given value.


### GetProductId

`func (o *ListShipments200ResponseDataInnerCarrierSettings) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *ListShipments200ResponseDataInnerCarrierSettings) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *ListShipments200ResponseDataInnerCarrierSettings) SetProductId(v string)`

SetProductId sets ProductId field to given value.


### GetServices

`func (o *ListShipments200ResponseDataInnerCarrierSettings) GetServices() []string`

GetServices returns the Services field if non-nil, zero value otherwise.

### GetServicesOk

`func (o *ListShipments200ResponseDataInnerCarrierSettings) GetServicesOk() (*[]string, bool)`

GetServicesOk returns a tuple with the Services field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServices

`func (o *ListShipments200ResponseDataInnerCarrierSettings) SetServices(v []string)`

SetServices sets Services field to given value.


### GetAdditionalParameters

`func (o *ListShipments200ResponseDataInnerCarrierSettings) GetAdditionalParameters() map[string]ListShippingRules200ResponseDataInnerAdditionalParametersValue`

GetAdditionalParameters returns the AdditionalParameters field if non-nil, zero value otherwise.

### GetAdditionalParametersOk

`func (o *ListShipments200ResponseDataInnerCarrierSettings) GetAdditionalParametersOk() (*map[string]ListShippingRules200ResponseDataInnerAdditionalParametersValue, bool)`

GetAdditionalParametersOk returns a tuple with the AdditionalParameters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditionalParameters

`func (o *ListShipments200ResponseDataInnerCarrierSettings) SetAdditionalParameters(v map[string]ListShippingRules200ResponseDataInnerAdditionalParametersValue)`

SetAdditionalParameters sets AdditionalParameters field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


