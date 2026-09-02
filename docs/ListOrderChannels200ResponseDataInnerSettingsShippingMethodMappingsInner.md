# ListOrderChannels200ResponseDataInnerSettingsShippingMethodMappingsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Match** | **string** | Shipping-method title to match against imported orders (trimmed, case-insensitive, exact). | 
**ShippingRuleId** | **string** | Shipping rule applied to orders whose shipping-method title matches. | 
**ServicePointSelection** | Pointer to **string** | For rules whose product delivers to a service point: &#39;nearest&#39; auto-selects the closest point to the recipient address; &#39;manual&#39; keeps the shipment in draft for manual selection. | [optional] 

## Methods

### NewListOrderChannels200ResponseDataInnerSettingsShippingMethodMappingsInner

`func NewListOrderChannels200ResponseDataInnerSettingsShippingMethodMappingsInner(match string, shippingRuleId string, ) *ListOrderChannels200ResponseDataInnerSettingsShippingMethodMappingsInner`

NewListOrderChannels200ResponseDataInnerSettingsShippingMethodMappingsInner instantiates a new ListOrderChannels200ResponseDataInnerSettingsShippingMethodMappingsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListOrderChannels200ResponseDataInnerSettingsShippingMethodMappingsInnerWithDefaults

`func NewListOrderChannels200ResponseDataInnerSettingsShippingMethodMappingsInnerWithDefaults() *ListOrderChannels200ResponseDataInnerSettingsShippingMethodMappingsInner`

NewListOrderChannels200ResponseDataInnerSettingsShippingMethodMappingsInnerWithDefaults instantiates a new ListOrderChannels200ResponseDataInnerSettingsShippingMethodMappingsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMatch

`func (o *ListOrderChannels200ResponseDataInnerSettingsShippingMethodMappingsInner) GetMatch() string`

GetMatch returns the Match field if non-nil, zero value otherwise.

### GetMatchOk

`func (o *ListOrderChannels200ResponseDataInnerSettingsShippingMethodMappingsInner) GetMatchOk() (*string, bool)`

GetMatchOk returns a tuple with the Match field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatch

`func (o *ListOrderChannels200ResponseDataInnerSettingsShippingMethodMappingsInner) SetMatch(v string)`

SetMatch sets Match field to given value.


### GetShippingRuleId

`func (o *ListOrderChannels200ResponseDataInnerSettingsShippingMethodMappingsInner) GetShippingRuleId() string`

GetShippingRuleId returns the ShippingRuleId field if non-nil, zero value otherwise.

### GetShippingRuleIdOk

`func (o *ListOrderChannels200ResponseDataInnerSettingsShippingMethodMappingsInner) GetShippingRuleIdOk() (*string, bool)`

GetShippingRuleIdOk returns a tuple with the ShippingRuleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingRuleId

`func (o *ListOrderChannels200ResponseDataInnerSettingsShippingMethodMappingsInner) SetShippingRuleId(v string)`

SetShippingRuleId sets ShippingRuleId field to given value.


### GetServicePointSelection

`func (o *ListOrderChannels200ResponseDataInnerSettingsShippingMethodMappingsInner) GetServicePointSelection() string`

GetServicePointSelection returns the ServicePointSelection field if non-nil, zero value otherwise.

### GetServicePointSelectionOk

`func (o *ListOrderChannels200ResponseDataInnerSettingsShippingMethodMappingsInner) GetServicePointSelectionOk() (*string, bool)`

GetServicePointSelectionOk returns a tuple with the ServicePointSelection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServicePointSelection

`func (o *ListOrderChannels200ResponseDataInnerSettingsShippingMethodMappingsInner) SetServicePointSelection(v string)`

SetServicePointSelection sets ServicePointSelection field to given value.

### HasServicePointSelection

`func (o *ListOrderChannels200ResponseDataInnerSettingsShippingMethodMappingsInner) HasServicePointSelection() bool`

HasServicePointSelection returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


