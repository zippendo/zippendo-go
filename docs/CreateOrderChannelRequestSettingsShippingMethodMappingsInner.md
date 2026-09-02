# CreateOrderChannelRequestSettingsShippingMethodMappingsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Match** | **string** | Shipping-method title to match against imported orders (trimmed, case-insensitive, exact). | 
**ShippingRuleId** | **string** | Shipping rule applied to orders whose shipping-method title matches. | 
**ServicePointSelection** | Pointer to **string** | For rules whose product delivers to a service point: &#39;nearest&#39; auto-selects the closest point to the recipient address; &#39;manual&#39; keeps the shipment in draft for manual selection. | [optional] 

## Methods

### NewCreateOrderChannelRequestSettingsShippingMethodMappingsInner

`func NewCreateOrderChannelRequestSettingsShippingMethodMappingsInner(match string, shippingRuleId string, ) *CreateOrderChannelRequestSettingsShippingMethodMappingsInner`

NewCreateOrderChannelRequestSettingsShippingMethodMappingsInner instantiates a new CreateOrderChannelRequestSettingsShippingMethodMappingsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateOrderChannelRequestSettingsShippingMethodMappingsInnerWithDefaults

`func NewCreateOrderChannelRequestSettingsShippingMethodMappingsInnerWithDefaults() *CreateOrderChannelRequestSettingsShippingMethodMappingsInner`

NewCreateOrderChannelRequestSettingsShippingMethodMappingsInnerWithDefaults instantiates a new CreateOrderChannelRequestSettingsShippingMethodMappingsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMatch

`func (o *CreateOrderChannelRequestSettingsShippingMethodMappingsInner) GetMatch() string`

GetMatch returns the Match field if non-nil, zero value otherwise.

### GetMatchOk

`func (o *CreateOrderChannelRequestSettingsShippingMethodMappingsInner) GetMatchOk() (*string, bool)`

GetMatchOk returns a tuple with the Match field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatch

`func (o *CreateOrderChannelRequestSettingsShippingMethodMappingsInner) SetMatch(v string)`

SetMatch sets Match field to given value.


### GetShippingRuleId

`func (o *CreateOrderChannelRequestSettingsShippingMethodMappingsInner) GetShippingRuleId() string`

GetShippingRuleId returns the ShippingRuleId field if non-nil, zero value otherwise.

### GetShippingRuleIdOk

`func (o *CreateOrderChannelRequestSettingsShippingMethodMappingsInner) GetShippingRuleIdOk() (*string, bool)`

GetShippingRuleIdOk returns a tuple with the ShippingRuleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingRuleId

`func (o *CreateOrderChannelRequestSettingsShippingMethodMappingsInner) SetShippingRuleId(v string)`

SetShippingRuleId sets ShippingRuleId field to given value.


### GetServicePointSelection

`func (o *CreateOrderChannelRequestSettingsShippingMethodMappingsInner) GetServicePointSelection() string`

GetServicePointSelection returns the ServicePointSelection field if non-nil, zero value otherwise.

### GetServicePointSelectionOk

`func (o *CreateOrderChannelRequestSettingsShippingMethodMappingsInner) GetServicePointSelectionOk() (*string, bool)`

GetServicePointSelectionOk returns a tuple with the ServicePointSelection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServicePointSelection

`func (o *CreateOrderChannelRequestSettingsShippingMethodMappingsInner) SetServicePointSelection(v string)`

SetServicePointSelection sets ServicePointSelection field to given value.

### HasServicePointSelection

`func (o *CreateOrderChannelRequestSettingsShippingMethodMappingsInner) HasServicePointSelection() bool`

HasServicePointSelection returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


