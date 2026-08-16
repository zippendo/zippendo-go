# ListShippingRules200ResponseDataInnerCarrier

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

## Methods

### NewListShippingRules200ResponseDataInnerCarrier

`func NewListShippingRules200ResponseDataInnerCarrier(id string, name string, carrierSlug string, config map[string]ListCarriers200ResponseDataInnerConfigValue, orgId string, brandId NullableString, createdAt string, updatedAt string, ) *ListShippingRules200ResponseDataInnerCarrier`

NewListShippingRules200ResponseDataInnerCarrier instantiates a new ListShippingRules200ResponseDataInnerCarrier object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListShippingRules200ResponseDataInnerCarrierWithDefaults

`func NewListShippingRules200ResponseDataInnerCarrierWithDefaults() *ListShippingRules200ResponseDataInnerCarrier`

NewListShippingRules200ResponseDataInnerCarrierWithDefaults instantiates a new ListShippingRules200ResponseDataInnerCarrier object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ListShippingRules200ResponseDataInnerCarrier) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ListShippingRules200ResponseDataInnerCarrier) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ListShippingRules200ResponseDataInnerCarrier) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *ListShippingRules200ResponseDataInnerCarrier) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ListShippingRules200ResponseDataInnerCarrier) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ListShippingRules200ResponseDataInnerCarrier) SetName(v string)`

SetName sets Name field to given value.


### GetCarrierSlug

`func (o *ListShippingRules200ResponseDataInnerCarrier) GetCarrierSlug() string`

GetCarrierSlug returns the CarrierSlug field if non-nil, zero value otherwise.

### GetCarrierSlugOk

`func (o *ListShippingRules200ResponseDataInnerCarrier) GetCarrierSlugOk() (*string, bool)`

GetCarrierSlugOk returns a tuple with the CarrierSlug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierSlug

`func (o *ListShippingRules200ResponseDataInnerCarrier) SetCarrierSlug(v string)`

SetCarrierSlug sets CarrierSlug field to given value.


### GetConfig

`func (o *ListShippingRules200ResponseDataInnerCarrier) GetConfig() map[string]ListCarriers200ResponseDataInnerConfigValue`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *ListShippingRules200ResponseDataInnerCarrier) GetConfigOk() (*map[string]ListCarriers200ResponseDataInnerConfigValue, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *ListShippingRules200ResponseDataInnerCarrier) SetConfig(v map[string]ListCarriers200ResponseDataInnerConfigValue)`

SetConfig sets Config field to given value.


### GetOrgId

`func (o *ListShippingRules200ResponseDataInnerCarrier) GetOrgId() string`

GetOrgId returns the OrgId field if non-nil, zero value otherwise.

### GetOrgIdOk

`func (o *ListShippingRules200ResponseDataInnerCarrier) GetOrgIdOk() (*string, bool)`

GetOrgIdOk returns a tuple with the OrgId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrgId

`func (o *ListShippingRules200ResponseDataInnerCarrier) SetOrgId(v string)`

SetOrgId sets OrgId field to given value.


### GetBrandId

`func (o *ListShippingRules200ResponseDataInnerCarrier) GetBrandId() string`

GetBrandId returns the BrandId field if non-nil, zero value otherwise.

### GetBrandIdOk

`func (o *ListShippingRules200ResponseDataInnerCarrier) GetBrandIdOk() (*string, bool)`

GetBrandIdOk returns a tuple with the BrandId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandId

`func (o *ListShippingRules200ResponseDataInnerCarrier) SetBrandId(v string)`

SetBrandId sets BrandId field to given value.


### SetBrandIdNil

`func (o *ListShippingRules200ResponseDataInnerCarrier) SetBrandIdNil(b bool)`

 SetBrandIdNil sets the value for BrandId to be an explicit nil

### UnsetBrandId
`func (o *ListShippingRules200ResponseDataInnerCarrier) UnsetBrandId()`

UnsetBrandId ensures that no value is present for BrandId, not even an explicit nil
### GetCreatedAt

`func (o *ListShippingRules200ResponseDataInnerCarrier) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ListShippingRules200ResponseDataInnerCarrier) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ListShippingRules200ResponseDataInnerCarrier) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *ListShippingRules200ResponseDataInnerCarrier) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ListShippingRules200ResponseDataInnerCarrier) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ListShippingRules200ResponseDataInnerCarrier) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


