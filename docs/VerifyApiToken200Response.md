# VerifyApiToken200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Valid** | **bool** | Whether the token is valid | 
**TokenId** | Pointer to **string** | Token identifier | [optional] 
**UserId** | Pointer to **string** | User identifier the token belongs to | [optional] 
**OrgId** | Pointer to **string** | Organization identifier the token belongs to | [optional] 
**Scopes** | Pointer to **[]string** | Permission scopes granted by the token | [optional] 
**ExpiresAt** | Pointer to **NullableString** | Expiry timestamp (ISO 8601), null if it never expires | [optional] 

## Methods

### NewVerifyApiToken200Response

`func NewVerifyApiToken200Response(valid bool, ) *VerifyApiToken200Response`

NewVerifyApiToken200Response instantiates a new VerifyApiToken200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVerifyApiToken200ResponseWithDefaults

`func NewVerifyApiToken200ResponseWithDefaults() *VerifyApiToken200Response`

NewVerifyApiToken200ResponseWithDefaults instantiates a new VerifyApiToken200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetValid

`func (o *VerifyApiToken200Response) GetValid() bool`

GetValid returns the Valid field if non-nil, zero value otherwise.

### GetValidOk

`func (o *VerifyApiToken200Response) GetValidOk() (*bool, bool)`

GetValidOk returns a tuple with the Valid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValid

`func (o *VerifyApiToken200Response) SetValid(v bool)`

SetValid sets Valid field to given value.


### GetTokenId

`func (o *VerifyApiToken200Response) GetTokenId() string`

GetTokenId returns the TokenId field if non-nil, zero value otherwise.

### GetTokenIdOk

`func (o *VerifyApiToken200Response) GetTokenIdOk() (*string, bool)`

GetTokenIdOk returns a tuple with the TokenId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokenId

`func (o *VerifyApiToken200Response) SetTokenId(v string)`

SetTokenId sets TokenId field to given value.

### HasTokenId

`func (o *VerifyApiToken200Response) HasTokenId() bool`

HasTokenId returns a boolean if a field has been set.

### GetUserId

`func (o *VerifyApiToken200Response) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *VerifyApiToken200Response) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *VerifyApiToken200Response) SetUserId(v string)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *VerifyApiToken200Response) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetOrgId

`func (o *VerifyApiToken200Response) GetOrgId() string`

GetOrgId returns the OrgId field if non-nil, zero value otherwise.

### GetOrgIdOk

`func (o *VerifyApiToken200Response) GetOrgIdOk() (*string, bool)`

GetOrgIdOk returns a tuple with the OrgId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrgId

`func (o *VerifyApiToken200Response) SetOrgId(v string)`

SetOrgId sets OrgId field to given value.

### HasOrgId

`func (o *VerifyApiToken200Response) HasOrgId() bool`

HasOrgId returns a boolean if a field has been set.

### GetScopes

`func (o *VerifyApiToken200Response) GetScopes() []string`

GetScopes returns the Scopes field if non-nil, zero value otherwise.

### GetScopesOk

`func (o *VerifyApiToken200Response) GetScopesOk() (*[]string, bool)`

GetScopesOk returns a tuple with the Scopes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScopes

`func (o *VerifyApiToken200Response) SetScopes(v []string)`

SetScopes sets Scopes field to given value.

### HasScopes

`func (o *VerifyApiToken200Response) HasScopes() bool`

HasScopes returns a boolean if a field has been set.

### GetExpiresAt

`func (o *VerifyApiToken200Response) GetExpiresAt() string`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *VerifyApiToken200Response) GetExpiresAtOk() (*string, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *VerifyApiToken200Response) SetExpiresAt(v string)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *VerifyApiToken200Response) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### SetExpiresAtNil

`func (o *VerifyApiToken200Response) SetExpiresAtNil(b bool)`

 SetExpiresAtNil sets the value for ExpiresAt to be an explicit nil

### UnsetExpiresAt
`func (o *VerifyApiToken200Response) UnsetExpiresAt()`

UnsetExpiresAt ensures that no value is present for ExpiresAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


