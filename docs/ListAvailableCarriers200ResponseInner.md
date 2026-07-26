# ListAvailableCarriers200ResponseInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | Display name of the carrier | 
**Slug** | **string** | Unique carrier slug identifier | 
**Group** | Pointer to **string** | Carrier group or family name | [optional] 
**Description** | Pointer to **string** | Short description of the carrier | [optional] 
**Logo** | Pointer to **string** | URL to the carrier logo image | [optional] 
**BrandColor** | Pointer to **string** | Carrier brand color (hex) | [optional] 
**LearnMoreUrl** | Pointer to **string** | URL with more information about the carrier | [optional] 
**RequiredFields** | Pointer to [**[]ListAvailableCarriers200ResponseInnerRequiredFieldsInner**](ListAvailableCarriers200ResponseInnerRequiredFieldsInner.md) | Configuration fields that must be provided to connect the carrier | [optional] 
**OptionalFields** | Pointer to [**[]ListAvailableCarriers200ResponseInnerRequiredFieldsInner**](ListAvailableCarriers200ResponseInnerRequiredFieldsInner.md) | Optional configuration fields for the carrier | [optional] 
**Deprecated** | Pointer to **bool** | Whether this integration is deprecated (still works, but discouraged) | [optional] 
**DeprecationMessage** | Pointer to **string** | Guidance shown alongside the deprecated tag (e.g. what to migrate to) | [optional] 

## Methods

### NewListAvailableCarriers200ResponseInner

`func NewListAvailableCarriers200ResponseInner(name string, slug string, ) *ListAvailableCarriers200ResponseInner`

NewListAvailableCarriers200ResponseInner instantiates a new ListAvailableCarriers200ResponseInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListAvailableCarriers200ResponseInnerWithDefaults

`func NewListAvailableCarriers200ResponseInnerWithDefaults() *ListAvailableCarriers200ResponseInner`

NewListAvailableCarriers200ResponseInnerWithDefaults instantiates a new ListAvailableCarriers200ResponseInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *ListAvailableCarriers200ResponseInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ListAvailableCarriers200ResponseInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ListAvailableCarriers200ResponseInner) SetName(v string)`

SetName sets Name field to given value.


### GetSlug

`func (o *ListAvailableCarriers200ResponseInner) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *ListAvailableCarriers200ResponseInner) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *ListAvailableCarriers200ResponseInner) SetSlug(v string)`

SetSlug sets Slug field to given value.


### GetGroup

`func (o *ListAvailableCarriers200ResponseInner) GetGroup() string`

GetGroup returns the Group field if non-nil, zero value otherwise.

### GetGroupOk

`func (o *ListAvailableCarriers200ResponseInner) GetGroupOk() (*string, bool)`

GetGroupOk returns a tuple with the Group field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroup

`func (o *ListAvailableCarriers200ResponseInner) SetGroup(v string)`

SetGroup sets Group field to given value.

### HasGroup

`func (o *ListAvailableCarriers200ResponseInner) HasGroup() bool`

HasGroup returns a boolean if a field has been set.

### GetDescription

`func (o *ListAvailableCarriers200ResponseInner) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ListAvailableCarriers200ResponseInner) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ListAvailableCarriers200ResponseInner) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ListAvailableCarriers200ResponseInner) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetLogo

`func (o *ListAvailableCarriers200ResponseInner) GetLogo() string`

GetLogo returns the Logo field if non-nil, zero value otherwise.

### GetLogoOk

`func (o *ListAvailableCarriers200ResponseInner) GetLogoOk() (*string, bool)`

GetLogoOk returns a tuple with the Logo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogo

`func (o *ListAvailableCarriers200ResponseInner) SetLogo(v string)`

SetLogo sets Logo field to given value.

### HasLogo

`func (o *ListAvailableCarriers200ResponseInner) HasLogo() bool`

HasLogo returns a boolean if a field has been set.

### GetBrandColor

`func (o *ListAvailableCarriers200ResponseInner) GetBrandColor() string`

GetBrandColor returns the BrandColor field if non-nil, zero value otherwise.

### GetBrandColorOk

`func (o *ListAvailableCarriers200ResponseInner) GetBrandColorOk() (*string, bool)`

GetBrandColorOk returns a tuple with the BrandColor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandColor

`func (o *ListAvailableCarriers200ResponseInner) SetBrandColor(v string)`

SetBrandColor sets BrandColor field to given value.

### HasBrandColor

`func (o *ListAvailableCarriers200ResponseInner) HasBrandColor() bool`

HasBrandColor returns a boolean if a field has been set.

### GetLearnMoreUrl

`func (o *ListAvailableCarriers200ResponseInner) GetLearnMoreUrl() string`

GetLearnMoreUrl returns the LearnMoreUrl field if non-nil, zero value otherwise.

### GetLearnMoreUrlOk

`func (o *ListAvailableCarriers200ResponseInner) GetLearnMoreUrlOk() (*string, bool)`

GetLearnMoreUrlOk returns a tuple with the LearnMoreUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLearnMoreUrl

`func (o *ListAvailableCarriers200ResponseInner) SetLearnMoreUrl(v string)`

SetLearnMoreUrl sets LearnMoreUrl field to given value.

### HasLearnMoreUrl

`func (o *ListAvailableCarriers200ResponseInner) HasLearnMoreUrl() bool`

HasLearnMoreUrl returns a boolean if a field has been set.

### GetRequiredFields

`func (o *ListAvailableCarriers200ResponseInner) GetRequiredFields() []ListAvailableCarriers200ResponseInnerRequiredFieldsInner`

GetRequiredFields returns the RequiredFields field if non-nil, zero value otherwise.

### GetRequiredFieldsOk

`func (o *ListAvailableCarriers200ResponseInner) GetRequiredFieldsOk() (*[]ListAvailableCarriers200ResponseInnerRequiredFieldsInner, bool)`

GetRequiredFieldsOk returns a tuple with the RequiredFields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequiredFields

`func (o *ListAvailableCarriers200ResponseInner) SetRequiredFields(v []ListAvailableCarriers200ResponseInnerRequiredFieldsInner)`

SetRequiredFields sets RequiredFields field to given value.

### HasRequiredFields

`func (o *ListAvailableCarriers200ResponseInner) HasRequiredFields() bool`

HasRequiredFields returns a boolean if a field has been set.

### GetOptionalFields

`func (o *ListAvailableCarriers200ResponseInner) GetOptionalFields() []ListAvailableCarriers200ResponseInnerRequiredFieldsInner`

GetOptionalFields returns the OptionalFields field if non-nil, zero value otherwise.

### GetOptionalFieldsOk

`func (o *ListAvailableCarriers200ResponseInner) GetOptionalFieldsOk() (*[]ListAvailableCarriers200ResponseInnerRequiredFieldsInner, bool)`

GetOptionalFieldsOk returns a tuple with the OptionalFields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptionalFields

`func (o *ListAvailableCarriers200ResponseInner) SetOptionalFields(v []ListAvailableCarriers200ResponseInnerRequiredFieldsInner)`

SetOptionalFields sets OptionalFields field to given value.

### HasOptionalFields

`func (o *ListAvailableCarriers200ResponseInner) HasOptionalFields() bool`

HasOptionalFields returns a boolean if a field has been set.

### GetDeprecated

`func (o *ListAvailableCarriers200ResponseInner) GetDeprecated() bool`

GetDeprecated returns the Deprecated field if non-nil, zero value otherwise.

### GetDeprecatedOk

`func (o *ListAvailableCarriers200ResponseInner) GetDeprecatedOk() (*bool, bool)`

GetDeprecatedOk returns a tuple with the Deprecated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeprecated

`func (o *ListAvailableCarriers200ResponseInner) SetDeprecated(v bool)`

SetDeprecated sets Deprecated field to given value.

### HasDeprecated

`func (o *ListAvailableCarriers200ResponseInner) HasDeprecated() bool`

HasDeprecated returns a boolean if a field has been set.

### GetDeprecationMessage

`func (o *ListAvailableCarriers200ResponseInner) GetDeprecationMessage() string`

GetDeprecationMessage returns the DeprecationMessage field if non-nil, zero value otherwise.

### GetDeprecationMessageOk

`func (o *ListAvailableCarriers200ResponseInner) GetDeprecationMessageOk() (*string, bool)`

GetDeprecationMessageOk returns a tuple with the DeprecationMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeprecationMessage

`func (o *ListAvailableCarriers200ResponseInner) SetDeprecationMessage(v string)`

SetDeprecationMessage sets DeprecationMessage field to given value.

### HasDeprecationMessage

`func (o *ListAvailableCarriers200ResponseInner) HasDeprecationMessage() bool`

HasDeprecationMessage returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


