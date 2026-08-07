# CreateApiToken201Response

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
**Token** | **string** | Full API token (only shown once) | 

## Methods

### NewCreateApiToken201Response

`func NewCreateApiToken201Response(id string, name string, tokenPrefix string, scopes []string, brandId NullableString, lastUsedAt NullableString, expiresAt NullableString, createdAt string, token string, ) *CreateApiToken201Response`

NewCreateApiToken201Response instantiates a new CreateApiToken201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateApiToken201ResponseWithDefaults

`func NewCreateApiToken201ResponseWithDefaults() *CreateApiToken201Response`

NewCreateApiToken201ResponseWithDefaults instantiates a new CreateApiToken201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreateApiToken201Response) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateApiToken201Response) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateApiToken201Response) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *CreateApiToken201Response) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateApiToken201Response) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateApiToken201Response) SetName(v string)`

SetName sets Name field to given value.


### GetTokenPrefix

`func (o *CreateApiToken201Response) GetTokenPrefix() string`

GetTokenPrefix returns the TokenPrefix field if non-nil, zero value otherwise.

### GetTokenPrefixOk

`func (o *CreateApiToken201Response) GetTokenPrefixOk() (*string, bool)`

GetTokenPrefixOk returns a tuple with the TokenPrefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokenPrefix

`func (o *CreateApiToken201Response) SetTokenPrefix(v string)`

SetTokenPrefix sets TokenPrefix field to given value.


### GetScopes

`func (o *CreateApiToken201Response) GetScopes() []string`

GetScopes returns the Scopes field if non-nil, zero value otherwise.

### GetScopesOk

`func (o *CreateApiToken201Response) GetScopesOk() (*[]string, bool)`

GetScopesOk returns a tuple with the Scopes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScopes

`func (o *CreateApiToken201Response) SetScopes(v []string)`

SetScopes sets Scopes field to given value.


### GetBrandId

`func (o *CreateApiToken201Response) GetBrandId() string`

GetBrandId returns the BrandId field if non-nil, zero value otherwise.

### GetBrandIdOk

`func (o *CreateApiToken201Response) GetBrandIdOk() (*string, bool)`

GetBrandIdOk returns a tuple with the BrandId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandId

`func (o *CreateApiToken201Response) SetBrandId(v string)`

SetBrandId sets BrandId field to given value.


### SetBrandIdNil

`func (o *CreateApiToken201Response) SetBrandIdNil(b bool)`

 SetBrandIdNil sets the value for BrandId to be an explicit nil

### UnsetBrandId
`func (o *CreateApiToken201Response) UnsetBrandId()`

UnsetBrandId ensures that no value is present for BrandId, not even an explicit nil
### GetLastUsedAt

`func (o *CreateApiToken201Response) GetLastUsedAt() string`

GetLastUsedAt returns the LastUsedAt field if non-nil, zero value otherwise.

### GetLastUsedAtOk

`func (o *CreateApiToken201Response) GetLastUsedAtOk() (*string, bool)`

GetLastUsedAtOk returns a tuple with the LastUsedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastUsedAt

`func (o *CreateApiToken201Response) SetLastUsedAt(v string)`

SetLastUsedAt sets LastUsedAt field to given value.


### SetLastUsedAtNil

`func (o *CreateApiToken201Response) SetLastUsedAtNil(b bool)`

 SetLastUsedAtNil sets the value for LastUsedAt to be an explicit nil

### UnsetLastUsedAt
`func (o *CreateApiToken201Response) UnsetLastUsedAt()`

UnsetLastUsedAt ensures that no value is present for LastUsedAt, not even an explicit nil
### GetExpiresAt

`func (o *CreateApiToken201Response) GetExpiresAt() string`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *CreateApiToken201Response) GetExpiresAtOk() (*string, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *CreateApiToken201Response) SetExpiresAt(v string)`

SetExpiresAt sets ExpiresAt field to given value.


### SetExpiresAtNil

`func (o *CreateApiToken201Response) SetExpiresAtNil(b bool)`

 SetExpiresAtNil sets the value for ExpiresAt to be an explicit nil

### UnsetExpiresAt
`func (o *CreateApiToken201Response) UnsetExpiresAt()`

UnsetExpiresAt ensures that no value is present for ExpiresAt, not even an explicit nil
### GetCreatedAt

`func (o *CreateApiToken201Response) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CreateApiToken201Response) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CreateApiToken201Response) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetToken

`func (o *CreateApiToken201Response) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *CreateApiToken201Response) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *CreateApiToken201Response) SetToken(v string)`

SetToken sets Token field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


