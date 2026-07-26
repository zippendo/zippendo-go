# ListCarrierProducts200ResponseInnerAdditionalParametersInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | Display label for the parameter | 
**Key** | **string** | Machine key the value is stored under | 
**Type** | **string** | Data type of the parameter | 
**Options** | Pointer to [**[]ListCarrierProducts200ResponseInnerAdditionalParametersInnerOptionsInner**](ListCarrierProducts200ResponseInnerAdditionalParametersInnerOptionsInner.md) | Selectable options for enum-type parameters | [optional] 
**Description** | **string** | Description of the parameter | 
**IsRequired** | **bool** | Whether the parameter is mandatory | [default to false]
**RequiredService** | Pointer to **[]string** | Service IDs for which this parameter is required | [optional] 

## Methods

### NewListCarrierProducts200ResponseInnerAdditionalParametersInner

`func NewListCarrierProducts200ResponseInnerAdditionalParametersInner(name string, key string, type_ string, description string, isRequired bool, ) *ListCarrierProducts200ResponseInnerAdditionalParametersInner`

NewListCarrierProducts200ResponseInnerAdditionalParametersInner instantiates a new ListCarrierProducts200ResponseInnerAdditionalParametersInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListCarrierProducts200ResponseInnerAdditionalParametersInnerWithDefaults

`func NewListCarrierProducts200ResponseInnerAdditionalParametersInnerWithDefaults() *ListCarrierProducts200ResponseInnerAdditionalParametersInner`

NewListCarrierProducts200ResponseInnerAdditionalParametersInnerWithDefaults instantiates a new ListCarrierProducts200ResponseInnerAdditionalParametersInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *ListCarrierProducts200ResponseInnerAdditionalParametersInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ListCarrierProducts200ResponseInnerAdditionalParametersInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ListCarrierProducts200ResponseInnerAdditionalParametersInner) SetName(v string)`

SetName sets Name field to given value.


### GetKey

`func (o *ListCarrierProducts200ResponseInnerAdditionalParametersInner) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *ListCarrierProducts200ResponseInnerAdditionalParametersInner) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *ListCarrierProducts200ResponseInnerAdditionalParametersInner) SetKey(v string)`

SetKey sets Key field to given value.


### GetType

`func (o *ListCarrierProducts200ResponseInnerAdditionalParametersInner) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ListCarrierProducts200ResponseInnerAdditionalParametersInner) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ListCarrierProducts200ResponseInnerAdditionalParametersInner) SetType(v string)`

SetType sets Type field to given value.


### GetOptions

`func (o *ListCarrierProducts200ResponseInnerAdditionalParametersInner) GetOptions() []ListCarrierProducts200ResponseInnerAdditionalParametersInnerOptionsInner`

GetOptions returns the Options field if non-nil, zero value otherwise.

### GetOptionsOk

`func (o *ListCarrierProducts200ResponseInnerAdditionalParametersInner) GetOptionsOk() (*[]ListCarrierProducts200ResponseInnerAdditionalParametersInnerOptionsInner, bool)`

GetOptionsOk returns a tuple with the Options field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptions

`func (o *ListCarrierProducts200ResponseInnerAdditionalParametersInner) SetOptions(v []ListCarrierProducts200ResponseInnerAdditionalParametersInnerOptionsInner)`

SetOptions sets Options field to given value.

### HasOptions

`func (o *ListCarrierProducts200ResponseInnerAdditionalParametersInner) HasOptions() bool`

HasOptions returns a boolean if a field has been set.

### GetDescription

`func (o *ListCarrierProducts200ResponseInnerAdditionalParametersInner) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ListCarrierProducts200ResponseInnerAdditionalParametersInner) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ListCarrierProducts200ResponseInnerAdditionalParametersInner) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetIsRequired

`func (o *ListCarrierProducts200ResponseInnerAdditionalParametersInner) GetIsRequired() bool`

GetIsRequired returns the IsRequired field if non-nil, zero value otherwise.

### GetIsRequiredOk

`func (o *ListCarrierProducts200ResponseInnerAdditionalParametersInner) GetIsRequiredOk() (*bool, bool)`

GetIsRequiredOk returns a tuple with the IsRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsRequired

`func (o *ListCarrierProducts200ResponseInnerAdditionalParametersInner) SetIsRequired(v bool)`

SetIsRequired sets IsRequired field to given value.


### GetRequiredService

`func (o *ListCarrierProducts200ResponseInnerAdditionalParametersInner) GetRequiredService() []string`

GetRequiredService returns the RequiredService field if non-nil, zero value otherwise.

### GetRequiredServiceOk

`func (o *ListCarrierProducts200ResponseInnerAdditionalParametersInner) GetRequiredServiceOk() (*[]string, bool)`

GetRequiredServiceOk returns a tuple with the RequiredService field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequiredService

`func (o *ListCarrierProducts200ResponseInnerAdditionalParametersInner) SetRequiredService(v []string)`

SetRequiredService sets RequiredService field to given value.

### HasRequiredService

`func (o *ListCarrierProducts200ResponseInnerAdditionalParametersInner) HasRequiredService() bool`

HasRequiredService returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


