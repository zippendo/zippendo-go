# CreateApiTokenRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | Token name for identification | 
**Scopes** | **[]string** | Permission scopes for the token | 
**ExpiresInDays** | Pointer to **int32** | Token expiry in days (optional, max 365) | [optional] 

## Methods

### NewCreateApiTokenRequest

`func NewCreateApiTokenRequest(name string, scopes []string, ) *CreateApiTokenRequest`

NewCreateApiTokenRequest instantiates a new CreateApiTokenRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateApiTokenRequestWithDefaults

`func NewCreateApiTokenRequestWithDefaults() *CreateApiTokenRequest`

NewCreateApiTokenRequestWithDefaults instantiates a new CreateApiTokenRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateApiTokenRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateApiTokenRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateApiTokenRequest) SetName(v string)`

SetName sets Name field to given value.


### GetScopes

`func (o *CreateApiTokenRequest) GetScopes() []string`

GetScopes returns the Scopes field if non-nil, zero value otherwise.

### GetScopesOk

`func (o *CreateApiTokenRequest) GetScopesOk() (*[]string, bool)`

GetScopesOk returns a tuple with the Scopes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScopes

`func (o *CreateApiTokenRequest) SetScopes(v []string)`

SetScopes sets Scopes field to given value.


### GetExpiresInDays

`func (o *CreateApiTokenRequest) GetExpiresInDays() int32`

GetExpiresInDays returns the ExpiresInDays field if non-nil, zero value otherwise.

### GetExpiresInDaysOk

`func (o *CreateApiTokenRequest) GetExpiresInDaysOk() (*int32, bool)`

GetExpiresInDaysOk returns a tuple with the ExpiresInDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresInDays

`func (o *CreateApiTokenRequest) SetExpiresInDays(v int32)`

SetExpiresInDays sets ExpiresInDays field to given value.

### HasExpiresInDays

`func (o *CreateApiTokenRequest) HasExpiresInDays() bool`

HasExpiresInDays returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


