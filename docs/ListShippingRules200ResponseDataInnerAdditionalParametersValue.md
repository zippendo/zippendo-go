# ListShippingRules200ResponseDataInnerAdditionalParametersValue

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Identifier of the selected service point. | 
**Name** | **string** | Display name of the service point. | 
**Address** | **string** | Formatted address of the service point. | 
**Coordinates** | Pointer to [**[]ListShippingRules200ResponseDataInnerAdditionalParametersValueAnyOfCoordinatesInner**](ListShippingRules200ResponseDataInnerAdditionalParametersValueAnyOfCoordinatesInner.md) | Latitude/longitude of the service point. | [optional] 

## Methods

### NewListShippingRules200ResponseDataInnerAdditionalParametersValue

`func NewListShippingRules200ResponseDataInnerAdditionalParametersValue(id string, name string, address string, ) *ListShippingRules200ResponseDataInnerAdditionalParametersValue`

NewListShippingRules200ResponseDataInnerAdditionalParametersValue instantiates a new ListShippingRules200ResponseDataInnerAdditionalParametersValue object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListShippingRules200ResponseDataInnerAdditionalParametersValueWithDefaults

`func NewListShippingRules200ResponseDataInnerAdditionalParametersValueWithDefaults() *ListShippingRules200ResponseDataInnerAdditionalParametersValue`

NewListShippingRules200ResponseDataInnerAdditionalParametersValueWithDefaults instantiates a new ListShippingRules200ResponseDataInnerAdditionalParametersValue object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ListShippingRules200ResponseDataInnerAdditionalParametersValue) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ListShippingRules200ResponseDataInnerAdditionalParametersValue) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ListShippingRules200ResponseDataInnerAdditionalParametersValue) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *ListShippingRules200ResponseDataInnerAdditionalParametersValue) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ListShippingRules200ResponseDataInnerAdditionalParametersValue) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ListShippingRules200ResponseDataInnerAdditionalParametersValue) SetName(v string)`

SetName sets Name field to given value.


### GetAddress

`func (o *ListShippingRules200ResponseDataInnerAdditionalParametersValue) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *ListShippingRules200ResponseDataInnerAdditionalParametersValue) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *ListShippingRules200ResponseDataInnerAdditionalParametersValue) SetAddress(v string)`

SetAddress sets Address field to given value.


### GetCoordinates

`func (o *ListShippingRules200ResponseDataInnerAdditionalParametersValue) GetCoordinates() []ListShippingRules200ResponseDataInnerAdditionalParametersValueAnyOfCoordinatesInner`

GetCoordinates returns the Coordinates field if non-nil, zero value otherwise.

### GetCoordinatesOk

`func (o *ListShippingRules200ResponseDataInnerAdditionalParametersValue) GetCoordinatesOk() (*[]ListShippingRules200ResponseDataInnerAdditionalParametersValueAnyOfCoordinatesInner, bool)`

GetCoordinatesOk returns a tuple with the Coordinates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoordinates

`func (o *ListShippingRules200ResponseDataInnerAdditionalParametersValue) SetCoordinates(v []ListShippingRules200ResponseDataInnerAdditionalParametersValueAnyOfCoordinatesInner)`

SetCoordinates sets Coordinates field to given value.

### HasCoordinates

`func (o *ListShippingRules200ResponseDataInnerAdditionalParametersValue) HasCoordinates() bool`

HasCoordinates returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


