# ListCarrierProducts200ResponseInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | Display name of the shipping product | 
**ProductId** | **string** | Unique carrier product identifier | 
**Type** | **string** | Direction of the shipment for this product | 
**Description** | Pointer to **string** | Description of the shipping product | [optional] 
**AvailableCountries** | **[]string** | Recipient countries supported by this product | 
**AvailableSenderCountries** | **[]string** | Sender countries supported by this product | 
**IsServicePoint** | **bool** | Whether delivery is to a service point/pickup location | [default to false]
**IsPickupAvailable** | **bool** | Whether carrier pickup is available for this product | [default to false]
**Services** | Pointer to [**[]ListCarrierProducts200ResponseInnerServicesInner**](ListCarrierProducts200ResponseInnerServicesInner.md) | Additional services available for this product | [optional] 
**AdditionalParameters** | Pointer to [**[]ListCarrierProducts200ResponseInnerAdditionalParametersInner**](ListCarrierProducts200ResponseInnerAdditionalParametersInner.md) | Extra parameters that can or must be supplied for this product | [optional] 
**WeightLimits** | Pointer to [**ListCarrierProducts200ResponseInnerWeightLimits**](ListCarrierProducts200ResponseInnerWeightLimits.md) |  | [optional] 

## Methods

### NewListCarrierProducts200ResponseInner

`func NewListCarrierProducts200ResponseInner(name string, productId string, type_ string, availableCountries []string, availableSenderCountries []string, isServicePoint bool, isPickupAvailable bool, ) *ListCarrierProducts200ResponseInner`

NewListCarrierProducts200ResponseInner instantiates a new ListCarrierProducts200ResponseInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListCarrierProducts200ResponseInnerWithDefaults

`func NewListCarrierProducts200ResponseInnerWithDefaults() *ListCarrierProducts200ResponseInner`

NewListCarrierProducts200ResponseInnerWithDefaults instantiates a new ListCarrierProducts200ResponseInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *ListCarrierProducts200ResponseInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ListCarrierProducts200ResponseInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ListCarrierProducts200ResponseInner) SetName(v string)`

SetName sets Name field to given value.


### GetProductId

`func (o *ListCarrierProducts200ResponseInner) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *ListCarrierProducts200ResponseInner) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *ListCarrierProducts200ResponseInner) SetProductId(v string)`

SetProductId sets ProductId field to given value.


### GetType

`func (o *ListCarrierProducts200ResponseInner) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ListCarrierProducts200ResponseInner) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ListCarrierProducts200ResponseInner) SetType(v string)`

SetType sets Type field to given value.


### GetDescription

`func (o *ListCarrierProducts200ResponseInner) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ListCarrierProducts200ResponseInner) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ListCarrierProducts200ResponseInner) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ListCarrierProducts200ResponseInner) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetAvailableCountries

`func (o *ListCarrierProducts200ResponseInner) GetAvailableCountries() []string`

GetAvailableCountries returns the AvailableCountries field if non-nil, zero value otherwise.

### GetAvailableCountriesOk

`func (o *ListCarrierProducts200ResponseInner) GetAvailableCountriesOk() (*[]string, bool)`

GetAvailableCountriesOk returns a tuple with the AvailableCountries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailableCountries

`func (o *ListCarrierProducts200ResponseInner) SetAvailableCountries(v []string)`

SetAvailableCountries sets AvailableCountries field to given value.


### GetAvailableSenderCountries

`func (o *ListCarrierProducts200ResponseInner) GetAvailableSenderCountries() []string`

GetAvailableSenderCountries returns the AvailableSenderCountries field if non-nil, zero value otherwise.

### GetAvailableSenderCountriesOk

`func (o *ListCarrierProducts200ResponseInner) GetAvailableSenderCountriesOk() (*[]string, bool)`

GetAvailableSenderCountriesOk returns a tuple with the AvailableSenderCountries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailableSenderCountries

`func (o *ListCarrierProducts200ResponseInner) SetAvailableSenderCountries(v []string)`

SetAvailableSenderCountries sets AvailableSenderCountries field to given value.


### GetIsServicePoint

`func (o *ListCarrierProducts200ResponseInner) GetIsServicePoint() bool`

GetIsServicePoint returns the IsServicePoint field if non-nil, zero value otherwise.

### GetIsServicePointOk

`func (o *ListCarrierProducts200ResponseInner) GetIsServicePointOk() (*bool, bool)`

GetIsServicePointOk returns a tuple with the IsServicePoint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsServicePoint

`func (o *ListCarrierProducts200ResponseInner) SetIsServicePoint(v bool)`

SetIsServicePoint sets IsServicePoint field to given value.


### GetIsPickupAvailable

`func (o *ListCarrierProducts200ResponseInner) GetIsPickupAvailable() bool`

GetIsPickupAvailable returns the IsPickupAvailable field if non-nil, zero value otherwise.

### GetIsPickupAvailableOk

`func (o *ListCarrierProducts200ResponseInner) GetIsPickupAvailableOk() (*bool, bool)`

GetIsPickupAvailableOk returns a tuple with the IsPickupAvailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsPickupAvailable

`func (o *ListCarrierProducts200ResponseInner) SetIsPickupAvailable(v bool)`

SetIsPickupAvailable sets IsPickupAvailable field to given value.


### GetServices

`func (o *ListCarrierProducts200ResponseInner) GetServices() []ListCarrierProducts200ResponseInnerServicesInner`

GetServices returns the Services field if non-nil, zero value otherwise.

### GetServicesOk

`func (o *ListCarrierProducts200ResponseInner) GetServicesOk() (*[]ListCarrierProducts200ResponseInnerServicesInner, bool)`

GetServicesOk returns a tuple with the Services field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServices

`func (o *ListCarrierProducts200ResponseInner) SetServices(v []ListCarrierProducts200ResponseInnerServicesInner)`

SetServices sets Services field to given value.

### HasServices

`func (o *ListCarrierProducts200ResponseInner) HasServices() bool`

HasServices returns a boolean if a field has been set.

### GetAdditionalParameters

`func (o *ListCarrierProducts200ResponseInner) GetAdditionalParameters() []ListCarrierProducts200ResponseInnerAdditionalParametersInner`

GetAdditionalParameters returns the AdditionalParameters field if non-nil, zero value otherwise.

### GetAdditionalParametersOk

`func (o *ListCarrierProducts200ResponseInner) GetAdditionalParametersOk() (*[]ListCarrierProducts200ResponseInnerAdditionalParametersInner, bool)`

GetAdditionalParametersOk returns a tuple with the AdditionalParameters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditionalParameters

`func (o *ListCarrierProducts200ResponseInner) SetAdditionalParameters(v []ListCarrierProducts200ResponseInnerAdditionalParametersInner)`

SetAdditionalParameters sets AdditionalParameters field to given value.

### HasAdditionalParameters

`func (o *ListCarrierProducts200ResponseInner) HasAdditionalParameters() bool`

HasAdditionalParameters returns a boolean if a field has been set.

### GetWeightLimits

`func (o *ListCarrierProducts200ResponseInner) GetWeightLimits() ListCarrierProducts200ResponseInnerWeightLimits`

GetWeightLimits returns the WeightLimits field if non-nil, zero value otherwise.

### GetWeightLimitsOk

`func (o *ListCarrierProducts200ResponseInner) GetWeightLimitsOk() (*ListCarrierProducts200ResponseInnerWeightLimits, bool)`

GetWeightLimitsOk returns a tuple with the WeightLimits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeightLimits

`func (o *ListCarrierProducts200ResponseInner) SetWeightLimits(v ListCarrierProducts200ResponseInnerWeightLimits)`

SetWeightLimits sets WeightLimits field to given value.

### HasWeightLimits

`func (o *ListCarrierProducts200ResponseInner) HasWeightLimits() bool`

HasWeightLimits returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


