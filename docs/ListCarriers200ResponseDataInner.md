# ListCarriers200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Unique carrier identifier | 
**Name** | **string** | Carrier display name | 
**CarrierSlug** | **string** | Carrier slug identifier | 
**Config** | [**map[string]ListCarriers200ResponseDataInnerConfigValue**](ListCarriers200ResponseDataInnerConfigValue.md) | Carrier configuration (required and optional fields) | 
**OrgId** | **string** | Owning organization ID | 
**BrandId** | **NullableString** | Brand this record belongs to, or null when it is organization-wide | 
**CreatedAt** | **string** | Creation timestamp (ISO 8601) | 
**UpdatedAt** | **string** | Last update timestamp (ISO 8601) | 
**Logo** | Pointer to **string** | Carrier logo URL | [optional] 
**BrandColor** | Pointer to **string** | Carrier brand color (hex) | [optional] 
**Deprecated** | Pointer to **bool** | Whether this carrier integration is deprecated (still works, but discouraged) | [optional] 
**DeprecationMessage** | Pointer to **string** | Guidance shown alongside the deprecated tag (e.g. what to migrate to) | [optional] 

## Methods

### NewListCarriers200ResponseDataInner

`func NewListCarriers200ResponseDataInner(id string, name string, carrierSlug string, config map[string]ListCarriers200ResponseDataInnerConfigValue, orgId string, brandId NullableString, createdAt string, updatedAt string, ) *ListCarriers200ResponseDataInner`

NewListCarriers200ResponseDataInner instantiates a new ListCarriers200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListCarriers200ResponseDataInnerWithDefaults

`func NewListCarriers200ResponseDataInnerWithDefaults() *ListCarriers200ResponseDataInner`

NewListCarriers200ResponseDataInnerWithDefaults instantiates a new ListCarriers200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ListCarriers200ResponseDataInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ListCarriers200ResponseDataInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ListCarriers200ResponseDataInner) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *ListCarriers200ResponseDataInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ListCarriers200ResponseDataInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ListCarriers200ResponseDataInner) SetName(v string)`

SetName sets Name field to given value.


### GetCarrierSlug

`func (o *ListCarriers200ResponseDataInner) GetCarrierSlug() string`

GetCarrierSlug returns the CarrierSlug field if non-nil, zero value otherwise.

### GetCarrierSlugOk

`func (o *ListCarriers200ResponseDataInner) GetCarrierSlugOk() (*string, bool)`

GetCarrierSlugOk returns a tuple with the CarrierSlug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierSlug

`func (o *ListCarriers200ResponseDataInner) SetCarrierSlug(v string)`

SetCarrierSlug sets CarrierSlug field to given value.


### GetConfig

`func (o *ListCarriers200ResponseDataInner) GetConfig() map[string]ListCarriers200ResponseDataInnerConfigValue`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *ListCarriers200ResponseDataInner) GetConfigOk() (*map[string]ListCarriers200ResponseDataInnerConfigValue, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *ListCarriers200ResponseDataInner) SetConfig(v map[string]ListCarriers200ResponseDataInnerConfigValue)`

SetConfig sets Config field to given value.


### GetOrgId

`func (o *ListCarriers200ResponseDataInner) GetOrgId() string`

GetOrgId returns the OrgId field if non-nil, zero value otherwise.

### GetOrgIdOk

`func (o *ListCarriers200ResponseDataInner) GetOrgIdOk() (*string, bool)`

GetOrgIdOk returns a tuple with the OrgId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrgId

`func (o *ListCarriers200ResponseDataInner) SetOrgId(v string)`

SetOrgId sets OrgId field to given value.


### GetBrandId

`func (o *ListCarriers200ResponseDataInner) GetBrandId() string`

GetBrandId returns the BrandId field if non-nil, zero value otherwise.

### GetBrandIdOk

`func (o *ListCarriers200ResponseDataInner) GetBrandIdOk() (*string, bool)`

GetBrandIdOk returns a tuple with the BrandId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandId

`func (o *ListCarriers200ResponseDataInner) SetBrandId(v string)`

SetBrandId sets BrandId field to given value.


### SetBrandIdNil

`func (o *ListCarriers200ResponseDataInner) SetBrandIdNil(b bool)`

 SetBrandIdNil sets the value for BrandId to be an explicit nil

### UnsetBrandId
`func (o *ListCarriers200ResponseDataInner) UnsetBrandId()`

UnsetBrandId ensures that no value is present for BrandId, not even an explicit nil
### GetCreatedAt

`func (o *ListCarriers200ResponseDataInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ListCarriers200ResponseDataInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ListCarriers200ResponseDataInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *ListCarriers200ResponseDataInner) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ListCarriers200ResponseDataInner) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ListCarriers200ResponseDataInner) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetLogo

`func (o *ListCarriers200ResponseDataInner) GetLogo() string`

GetLogo returns the Logo field if non-nil, zero value otherwise.

### GetLogoOk

`func (o *ListCarriers200ResponseDataInner) GetLogoOk() (*string, bool)`

GetLogoOk returns a tuple with the Logo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogo

`func (o *ListCarriers200ResponseDataInner) SetLogo(v string)`

SetLogo sets Logo field to given value.

### HasLogo

`func (o *ListCarriers200ResponseDataInner) HasLogo() bool`

HasLogo returns a boolean if a field has been set.

### GetBrandColor

`func (o *ListCarriers200ResponseDataInner) GetBrandColor() string`

GetBrandColor returns the BrandColor field if non-nil, zero value otherwise.

### GetBrandColorOk

`func (o *ListCarriers200ResponseDataInner) GetBrandColorOk() (*string, bool)`

GetBrandColorOk returns a tuple with the BrandColor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandColor

`func (o *ListCarriers200ResponseDataInner) SetBrandColor(v string)`

SetBrandColor sets BrandColor field to given value.

### HasBrandColor

`func (o *ListCarriers200ResponseDataInner) HasBrandColor() bool`

HasBrandColor returns a boolean if a field has been set.

### GetDeprecated

`func (o *ListCarriers200ResponseDataInner) GetDeprecated() bool`

GetDeprecated returns the Deprecated field if non-nil, zero value otherwise.

### GetDeprecatedOk

`func (o *ListCarriers200ResponseDataInner) GetDeprecatedOk() (*bool, bool)`

GetDeprecatedOk returns a tuple with the Deprecated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeprecated

`func (o *ListCarriers200ResponseDataInner) SetDeprecated(v bool)`

SetDeprecated sets Deprecated field to given value.

### HasDeprecated

`func (o *ListCarriers200ResponseDataInner) HasDeprecated() bool`

HasDeprecated returns a boolean if a field has been set.

### GetDeprecationMessage

`func (o *ListCarriers200ResponseDataInner) GetDeprecationMessage() string`

GetDeprecationMessage returns the DeprecationMessage field if non-nil, zero value otherwise.

### GetDeprecationMessageOk

`func (o *ListCarriers200ResponseDataInner) GetDeprecationMessageOk() (*string, bool)`

GetDeprecationMessageOk returns a tuple with the DeprecationMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeprecationMessage

`func (o *ListCarriers200ResponseDataInner) SetDeprecationMessage(v string)`

SetDeprecationMessage sets DeprecationMessage field to given value.

### HasDeprecationMessage

`func (o *ListCarriers200ResponseDataInner) HasDeprecationMessage() bool`

HasDeprecationMessage returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


