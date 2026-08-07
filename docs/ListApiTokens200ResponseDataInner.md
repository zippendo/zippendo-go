# ListApiTokens200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Unique API token identifier | 
**Name** | **string** | Token name for identification | 
**TokenPrefix** | **string** | First 12 chars of the token for identification | 
**Scopes** | **[]string** | Permission scopes granted by the token | 
**BrandId** | **NullableString** | Brand this token is restricted to, or null for organization-wide access | 
**LastUsedAt** | **NullableString** | Timestamp the token was last used (ISO 8601), null if never used | 
**ExpiresAt** | **NullableString** | Expiry timestamp (ISO 8601), null if it never expires | 
**CreatedAt** | **string** | Creation timestamp (ISO 8601) | 
**CreatedBy** | [**ListApiTokens200ResponseDataInnerCreatedBy**](ListApiTokens200ResponseDataInnerCreatedBy.md) |  | 

## Methods

### NewListApiTokens200ResponseDataInner

`func NewListApiTokens200ResponseDataInner(id string, name string, tokenPrefix string, scopes []string, brandId NullableString, lastUsedAt NullableString, expiresAt NullableString, createdAt string, createdBy ListApiTokens200ResponseDataInnerCreatedBy, ) *ListApiTokens200ResponseDataInner`

NewListApiTokens200ResponseDataInner instantiates a new ListApiTokens200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListApiTokens200ResponseDataInnerWithDefaults

`func NewListApiTokens200ResponseDataInnerWithDefaults() *ListApiTokens200ResponseDataInner`

NewListApiTokens200ResponseDataInnerWithDefaults instantiates a new ListApiTokens200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ListApiTokens200ResponseDataInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ListApiTokens200ResponseDataInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ListApiTokens200ResponseDataInner) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *ListApiTokens200ResponseDataInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ListApiTokens200ResponseDataInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ListApiTokens200ResponseDataInner) SetName(v string)`

SetName sets Name field to given value.


### GetTokenPrefix

`func (o *ListApiTokens200ResponseDataInner) GetTokenPrefix() string`

GetTokenPrefix returns the TokenPrefix field if non-nil, zero value otherwise.

### GetTokenPrefixOk

`func (o *ListApiTokens200ResponseDataInner) GetTokenPrefixOk() (*string, bool)`

GetTokenPrefixOk returns a tuple with the TokenPrefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokenPrefix

`func (o *ListApiTokens200ResponseDataInner) SetTokenPrefix(v string)`

SetTokenPrefix sets TokenPrefix field to given value.


### GetScopes

`func (o *ListApiTokens200ResponseDataInner) GetScopes() []string`

GetScopes returns the Scopes field if non-nil, zero value otherwise.

### GetScopesOk

`func (o *ListApiTokens200ResponseDataInner) GetScopesOk() (*[]string, bool)`

GetScopesOk returns a tuple with the Scopes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScopes

`func (o *ListApiTokens200ResponseDataInner) SetScopes(v []string)`

SetScopes sets Scopes field to given value.


### GetBrandId

`func (o *ListApiTokens200ResponseDataInner) GetBrandId() string`

GetBrandId returns the BrandId field if non-nil, zero value otherwise.

### GetBrandIdOk

`func (o *ListApiTokens200ResponseDataInner) GetBrandIdOk() (*string, bool)`

GetBrandIdOk returns a tuple with the BrandId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandId

`func (o *ListApiTokens200ResponseDataInner) SetBrandId(v string)`

SetBrandId sets BrandId field to given value.


### SetBrandIdNil

`func (o *ListApiTokens200ResponseDataInner) SetBrandIdNil(b bool)`

 SetBrandIdNil sets the value for BrandId to be an explicit nil

### UnsetBrandId
`func (o *ListApiTokens200ResponseDataInner) UnsetBrandId()`

UnsetBrandId ensures that no value is present for BrandId, not even an explicit nil
### GetLastUsedAt

`func (o *ListApiTokens200ResponseDataInner) GetLastUsedAt() string`

GetLastUsedAt returns the LastUsedAt field if non-nil, zero value otherwise.

### GetLastUsedAtOk

`func (o *ListApiTokens200ResponseDataInner) GetLastUsedAtOk() (*string, bool)`

GetLastUsedAtOk returns a tuple with the LastUsedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastUsedAt

`func (o *ListApiTokens200ResponseDataInner) SetLastUsedAt(v string)`

SetLastUsedAt sets LastUsedAt field to given value.


### SetLastUsedAtNil

`func (o *ListApiTokens200ResponseDataInner) SetLastUsedAtNil(b bool)`

 SetLastUsedAtNil sets the value for LastUsedAt to be an explicit nil

### UnsetLastUsedAt
`func (o *ListApiTokens200ResponseDataInner) UnsetLastUsedAt()`

UnsetLastUsedAt ensures that no value is present for LastUsedAt, not even an explicit nil
### GetExpiresAt

`func (o *ListApiTokens200ResponseDataInner) GetExpiresAt() string`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *ListApiTokens200ResponseDataInner) GetExpiresAtOk() (*string, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *ListApiTokens200ResponseDataInner) SetExpiresAt(v string)`

SetExpiresAt sets ExpiresAt field to given value.


### SetExpiresAtNil

`func (o *ListApiTokens200ResponseDataInner) SetExpiresAtNil(b bool)`

 SetExpiresAtNil sets the value for ExpiresAt to be an explicit nil

### UnsetExpiresAt
`func (o *ListApiTokens200ResponseDataInner) UnsetExpiresAt()`

UnsetExpiresAt ensures that no value is present for ExpiresAt, not even an explicit nil
### GetCreatedAt

`func (o *ListApiTokens200ResponseDataInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ListApiTokens200ResponseDataInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ListApiTokens200ResponseDataInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCreatedBy

`func (o *ListApiTokens200ResponseDataInner) GetCreatedBy() ListApiTokens200ResponseDataInnerCreatedBy`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *ListApiTokens200ResponseDataInner) GetCreatedByOk() (*ListApiTokens200ResponseDataInnerCreatedBy, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *ListApiTokens200ResponseDataInner) SetCreatedBy(v ListApiTokens200ResponseDataInnerCreatedBy)`

SetCreatedBy sets CreatedBy field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


