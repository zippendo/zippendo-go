# CreateShippingRuleRequestAdditionalParametersValueAnyOf

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Identifier of the selected service point. | 
**Name** | **string** | Display name of the service point. | 
**Address** | **string** | Formatted address of the service point. | 
**Coordinates** | Pointer to [**[]ListShippingRules200ResponseDataInnerAdditionalParametersValueAnyOfCoordinatesInner**](ListShippingRules200ResponseDataInnerAdditionalParametersValueAnyOfCoordinatesInner.md) | Latitude/longitude of the service point. | [optional] 

## Methods

### NewCreateShippingRuleRequestAdditionalParametersValueAnyOf

`func NewCreateShippingRuleRequestAdditionalParametersValueAnyOf(id string, name string, address string, ) *CreateShippingRuleRequestAdditionalParametersValueAnyOf`

NewCreateShippingRuleRequestAdditionalParametersValueAnyOf instantiates a new CreateShippingRuleRequestAdditionalParametersValueAnyOf object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateShippingRuleRequestAdditionalParametersValueAnyOfWithDefaults

`func NewCreateShippingRuleRequestAdditionalParametersValueAnyOfWithDefaults() *CreateShippingRuleRequestAdditionalParametersValueAnyOf`

NewCreateShippingRuleRequestAdditionalParametersValueAnyOfWithDefaults instantiates a new CreateShippingRuleRequestAdditionalParametersValueAnyOf object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreateShippingRuleRequestAdditionalParametersValueAnyOf) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateShippingRuleRequestAdditionalParametersValueAnyOf) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateShippingRuleRequestAdditionalParametersValueAnyOf) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *CreateShippingRuleRequestAdditionalParametersValueAnyOf) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateShippingRuleRequestAdditionalParametersValueAnyOf) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateShippingRuleRequestAdditionalParametersValueAnyOf) SetName(v string)`

SetName sets Name field to given value.


### GetAddress

`func (o *CreateShippingRuleRequestAdditionalParametersValueAnyOf) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *CreateShippingRuleRequestAdditionalParametersValueAnyOf) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *CreateShippingRuleRequestAdditionalParametersValueAnyOf) SetAddress(v string)`

SetAddress sets Address field to given value.


### GetCoordinates

`func (o *CreateShippingRuleRequestAdditionalParametersValueAnyOf) GetCoordinates() []ListShippingRules200ResponseDataInnerAdditionalParametersValueAnyOfCoordinatesInner`

GetCoordinates returns the Coordinates field if non-nil, zero value otherwise.

### GetCoordinatesOk

`func (o *CreateShippingRuleRequestAdditionalParametersValueAnyOf) GetCoordinatesOk() (*[]ListShippingRules200ResponseDataInnerAdditionalParametersValueAnyOfCoordinatesInner, bool)`

GetCoordinatesOk returns a tuple with the Coordinates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoordinates

`func (o *CreateShippingRuleRequestAdditionalParametersValueAnyOf) SetCoordinates(v []ListShippingRules200ResponseDataInnerAdditionalParametersValueAnyOfCoordinatesInner)`

SetCoordinates sets Coordinates field to given value.

### HasCoordinates

`func (o *CreateShippingRuleRequestAdditionalParametersValueAnyOf) HasCoordinates() bool`

HasCoordinates returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


