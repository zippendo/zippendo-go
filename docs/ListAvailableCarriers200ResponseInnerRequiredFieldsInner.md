# ListAvailableCarriers200ResponseInnerRequiredFieldsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | Human-readable label for the configuration field | 
**Key** | **string** | Machine key used to store the field value | 
**Type** | **string** | Data type of the configuration field | 
**Options** | Pointer to [**[]ListCarrierProducts200ResponseInnerAdditionalParametersInnerOptionsInner**](ListCarrierProducts200ResponseInnerAdditionalParametersInnerOptionsInner.md) | Selectable options for enum-type fields | [optional] 
**Description** | **string** | Help text describing the field | 
**Required** | Pointer to **bool** | Whether the field is mandatory | [optional] 

## Methods

### NewListAvailableCarriers200ResponseInnerRequiredFieldsInner

`func NewListAvailableCarriers200ResponseInnerRequiredFieldsInner(name string, key string, type_ string, description string, ) *ListAvailableCarriers200ResponseInnerRequiredFieldsInner`

NewListAvailableCarriers200ResponseInnerRequiredFieldsInner instantiates a new ListAvailableCarriers200ResponseInnerRequiredFieldsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListAvailableCarriers200ResponseInnerRequiredFieldsInnerWithDefaults

`func NewListAvailableCarriers200ResponseInnerRequiredFieldsInnerWithDefaults() *ListAvailableCarriers200ResponseInnerRequiredFieldsInner`

NewListAvailableCarriers200ResponseInnerRequiredFieldsInnerWithDefaults instantiates a new ListAvailableCarriers200ResponseInnerRequiredFieldsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *ListAvailableCarriers200ResponseInnerRequiredFieldsInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ListAvailableCarriers200ResponseInnerRequiredFieldsInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ListAvailableCarriers200ResponseInnerRequiredFieldsInner) SetName(v string)`

SetName sets Name field to given value.


### GetKey

`func (o *ListAvailableCarriers200ResponseInnerRequiredFieldsInner) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *ListAvailableCarriers200ResponseInnerRequiredFieldsInner) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *ListAvailableCarriers200ResponseInnerRequiredFieldsInner) SetKey(v string)`

SetKey sets Key field to given value.


### GetType

`func (o *ListAvailableCarriers200ResponseInnerRequiredFieldsInner) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ListAvailableCarriers200ResponseInnerRequiredFieldsInner) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ListAvailableCarriers200ResponseInnerRequiredFieldsInner) SetType(v string)`

SetType sets Type field to given value.


### GetOptions

`func (o *ListAvailableCarriers200ResponseInnerRequiredFieldsInner) GetOptions() []ListCarrierProducts200ResponseInnerAdditionalParametersInnerOptionsInner`

GetOptions returns the Options field if non-nil, zero value otherwise.

### GetOptionsOk

`func (o *ListAvailableCarriers200ResponseInnerRequiredFieldsInner) GetOptionsOk() (*[]ListCarrierProducts200ResponseInnerAdditionalParametersInnerOptionsInner, bool)`

GetOptionsOk returns a tuple with the Options field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptions

`func (o *ListAvailableCarriers200ResponseInnerRequiredFieldsInner) SetOptions(v []ListCarrierProducts200ResponseInnerAdditionalParametersInnerOptionsInner)`

SetOptions sets Options field to given value.

### HasOptions

`func (o *ListAvailableCarriers200ResponseInnerRequiredFieldsInner) HasOptions() bool`

HasOptions returns a boolean if a field has been set.

### GetDescription

`func (o *ListAvailableCarriers200ResponseInnerRequiredFieldsInner) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ListAvailableCarriers200ResponseInnerRequiredFieldsInner) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ListAvailableCarriers200ResponseInnerRequiredFieldsInner) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetRequired

`func (o *ListAvailableCarriers200ResponseInnerRequiredFieldsInner) GetRequired() bool`

GetRequired returns the Required field if non-nil, zero value otherwise.

### GetRequiredOk

`func (o *ListAvailableCarriers200ResponseInnerRequiredFieldsInner) GetRequiredOk() (*bool, bool)`

GetRequiredOk returns a tuple with the Required field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequired

`func (o *ListAvailableCarriers200ResponseInnerRequiredFieldsInner) SetRequired(v bool)`

SetRequired sets Required field to given value.

### HasRequired

`func (o *ListAvailableCarriers200ResponseInnerRequiredFieldsInner) HasRequired() bool`

HasRequired returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


