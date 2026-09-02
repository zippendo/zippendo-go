# ListOrderChannels200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Unique order channel ID. | 
**Name** | **string** | Display name of the channel. | 
**Type** | **string** | Type of the order channel (sales platform). | 
**Enabled** | **bool** | Whether the channel is active. | 
**BrandId** | **NullableString** | Brand this channel belongs to, or null for organization-wide. Orders synced from this channel inherit it, and so do the shipments and documents made from them. | 
**HasCredentials** | **bool** | Whether credentials are configured (values are never exposed). | 
**Settings** | [**ListOrderChannels200ResponseDataInnerSettings**](ListOrderChannels200ResponseDataInnerSettings.md) |  | 
**WebhooksEnabled** | Pointer to **bool** | Whether real-time webhooks are enabled. | [optional] 
**LastSyncAt** | Pointer to **NullableTime** | Timestamp of the last successful sync. | [optional] 
**LastSyncError** | Pointer to **NullableString** | Error message from the last failed sync. | [optional] 
**ShippingRuleIds** | Pointer to **[]string** | IDs of shipping rules linked to this channel. | [optional] 
**OrgId** | **string** | Owning organization ID. | 
**CreatedAt** | **string** | Creation timestamp (ISO 8601). | 
**UpdatedAt** | **string** | Last update timestamp (ISO 8601). | 

## Methods

### NewListOrderChannels200ResponseDataInner

`func NewListOrderChannels200ResponseDataInner(id string, name string, type_ string, enabled bool, brandId NullableString, hasCredentials bool, settings ListOrderChannels200ResponseDataInnerSettings, orgId string, createdAt string, updatedAt string, ) *ListOrderChannels200ResponseDataInner`

NewListOrderChannels200ResponseDataInner instantiates a new ListOrderChannels200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListOrderChannels200ResponseDataInnerWithDefaults

`func NewListOrderChannels200ResponseDataInnerWithDefaults() *ListOrderChannels200ResponseDataInner`

NewListOrderChannels200ResponseDataInnerWithDefaults instantiates a new ListOrderChannels200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ListOrderChannels200ResponseDataInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ListOrderChannels200ResponseDataInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ListOrderChannels200ResponseDataInner) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *ListOrderChannels200ResponseDataInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ListOrderChannels200ResponseDataInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ListOrderChannels200ResponseDataInner) SetName(v string)`

SetName sets Name field to given value.


### GetType

`func (o *ListOrderChannels200ResponseDataInner) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ListOrderChannels200ResponseDataInner) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ListOrderChannels200ResponseDataInner) SetType(v string)`

SetType sets Type field to given value.


### GetEnabled

`func (o *ListOrderChannels200ResponseDataInner) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *ListOrderChannels200ResponseDataInner) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *ListOrderChannels200ResponseDataInner) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetBrandId

`func (o *ListOrderChannels200ResponseDataInner) GetBrandId() string`

GetBrandId returns the BrandId field if non-nil, zero value otherwise.

### GetBrandIdOk

`func (o *ListOrderChannels200ResponseDataInner) GetBrandIdOk() (*string, bool)`

GetBrandIdOk returns a tuple with the BrandId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandId

`func (o *ListOrderChannels200ResponseDataInner) SetBrandId(v string)`

SetBrandId sets BrandId field to given value.


### SetBrandIdNil

`func (o *ListOrderChannels200ResponseDataInner) SetBrandIdNil(b bool)`

 SetBrandIdNil sets the value for BrandId to be an explicit nil

### UnsetBrandId
`func (o *ListOrderChannels200ResponseDataInner) UnsetBrandId()`

UnsetBrandId ensures that no value is present for BrandId, not even an explicit nil
### GetHasCredentials

`func (o *ListOrderChannels200ResponseDataInner) GetHasCredentials() bool`

GetHasCredentials returns the HasCredentials field if non-nil, zero value otherwise.

### GetHasCredentialsOk

`func (o *ListOrderChannels200ResponseDataInner) GetHasCredentialsOk() (*bool, bool)`

GetHasCredentialsOk returns a tuple with the HasCredentials field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasCredentials

`func (o *ListOrderChannels200ResponseDataInner) SetHasCredentials(v bool)`

SetHasCredentials sets HasCredentials field to given value.


### GetSettings

`func (o *ListOrderChannels200ResponseDataInner) GetSettings() ListOrderChannels200ResponseDataInnerSettings`

GetSettings returns the Settings field if non-nil, zero value otherwise.

### GetSettingsOk

`func (o *ListOrderChannels200ResponseDataInner) GetSettingsOk() (*ListOrderChannels200ResponseDataInnerSettings, bool)`

GetSettingsOk returns a tuple with the Settings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettings

`func (o *ListOrderChannels200ResponseDataInner) SetSettings(v ListOrderChannels200ResponseDataInnerSettings)`

SetSettings sets Settings field to given value.


### GetWebhooksEnabled

`func (o *ListOrderChannels200ResponseDataInner) GetWebhooksEnabled() bool`

GetWebhooksEnabled returns the WebhooksEnabled field if non-nil, zero value otherwise.

### GetWebhooksEnabledOk

`func (o *ListOrderChannels200ResponseDataInner) GetWebhooksEnabledOk() (*bool, bool)`

GetWebhooksEnabledOk returns a tuple with the WebhooksEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebhooksEnabled

`func (o *ListOrderChannels200ResponseDataInner) SetWebhooksEnabled(v bool)`

SetWebhooksEnabled sets WebhooksEnabled field to given value.

### HasWebhooksEnabled

`func (o *ListOrderChannels200ResponseDataInner) HasWebhooksEnabled() bool`

HasWebhooksEnabled returns a boolean if a field has been set.

### GetLastSyncAt

`func (o *ListOrderChannels200ResponseDataInner) GetLastSyncAt() time.Time`

GetLastSyncAt returns the LastSyncAt field if non-nil, zero value otherwise.

### GetLastSyncAtOk

`func (o *ListOrderChannels200ResponseDataInner) GetLastSyncAtOk() (*time.Time, bool)`

GetLastSyncAtOk returns a tuple with the LastSyncAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastSyncAt

`func (o *ListOrderChannels200ResponseDataInner) SetLastSyncAt(v time.Time)`

SetLastSyncAt sets LastSyncAt field to given value.

### HasLastSyncAt

`func (o *ListOrderChannels200ResponseDataInner) HasLastSyncAt() bool`

HasLastSyncAt returns a boolean if a field has been set.

### SetLastSyncAtNil

`func (o *ListOrderChannels200ResponseDataInner) SetLastSyncAtNil(b bool)`

 SetLastSyncAtNil sets the value for LastSyncAt to be an explicit nil

### UnsetLastSyncAt
`func (o *ListOrderChannels200ResponseDataInner) UnsetLastSyncAt()`

UnsetLastSyncAt ensures that no value is present for LastSyncAt, not even an explicit nil
### GetLastSyncError

`func (o *ListOrderChannels200ResponseDataInner) GetLastSyncError() string`

GetLastSyncError returns the LastSyncError field if non-nil, zero value otherwise.

### GetLastSyncErrorOk

`func (o *ListOrderChannels200ResponseDataInner) GetLastSyncErrorOk() (*string, bool)`

GetLastSyncErrorOk returns a tuple with the LastSyncError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastSyncError

`func (o *ListOrderChannels200ResponseDataInner) SetLastSyncError(v string)`

SetLastSyncError sets LastSyncError field to given value.

### HasLastSyncError

`func (o *ListOrderChannels200ResponseDataInner) HasLastSyncError() bool`

HasLastSyncError returns a boolean if a field has been set.

### SetLastSyncErrorNil

`func (o *ListOrderChannels200ResponseDataInner) SetLastSyncErrorNil(b bool)`

 SetLastSyncErrorNil sets the value for LastSyncError to be an explicit nil

### UnsetLastSyncError
`func (o *ListOrderChannels200ResponseDataInner) UnsetLastSyncError()`

UnsetLastSyncError ensures that no value is present for LastSyncError, not even an explicit nil
### GetShippingRuleIds

`func (o *ListOrderChannels200ResponseDataInner) GetShippingRuleIds() []string`

GetShippingRuleIds returns the ShippingRuleIds field if non-nil, zero value otherwise.

### GetShippingRuleIdsOk

`func (o *ListOrderChannels200ResponseDataInner) GetShippingRuleIdsOk() (*[]string, bool)`

GetShippingRuleIdsOk returns a tuple with the ShippingRuleIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingRuleIds

`func (o *ListOrderChannels200ResponseDataInner) SetShippingRuleIds(v []string)`

SetShippingRuleIds sets ShippingRuleIds field to given value.

### HasShippingRuleIds

`func (o *ListOrderChannels200ResponseDataInner) HasShippingRuleIds() bool`

HasShippingRuleIds returns a boolean if a field has been set.

### GetOrgId

`func (o *ListOrderChannels200ResponseDataInner) GetOrgId() string`

GetOrgId returns the OrgId field if non-nil, zero value otherwise.

### GetOrgIdOk

`func (o *ListOrderChannels200ResponseDataInner) GetOrgIdOk() (*string, bool)`

GetOrgIdOk returns a tuple with the OrgId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrgId

`func (o *ListOrderChannels200ResponseDataInner) SetOrgId(v string)`

SetOrgId sets OrgId field to given value.


### GetCreatedAt

`func (o *ListOrderChannels200ResponseDataInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ListOrderChannels200ResponseDataInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ListOrderChannels200ResponseDataInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *ListOrderChannels200ResponseDataInner) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ListOrderChannels200ResponseDataInner) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ListOrderChannels200ResponseDataInner) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


