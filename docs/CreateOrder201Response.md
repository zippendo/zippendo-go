# CreateOrder201Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Unique order ID. | 
**OrderNumber** | **string** | Human-readable order number. | 
**ExternalId** | Pointer to **NullableString** | Identifier of the order in the source platform. | [optional] 
**CustomerName** | Pointer to **NullableString** | Customer full name. | [optional] 
**CustomerEmail** | Pointer to **NullableString** | Customer email address. | [optional] 
**ShippingAddress** | Pointer to [**NullableCreateOrder201ResponseShippingAddress**](CreateOrder201ResponseShippingAddress.md) |  | [optional] 
**OrderLines** | [**[]CreateOrder201ResponseOrderLinesInner**](CreateOrder201ResponseOrderLinesInner.md) | Line items in the order. | 
**SubtotalAmount** | Pointer to **NullableFloat32** | Order subtotal before shipping and tax. | [optional] 
**TotalAmount** | Pointer to **NullableFloat32** | Order grand total. | [optional] 
**Currency** | Pointer to **NullableString** | ISO 4217 currency code. | [optional] 
**Status** | **string** | Order fulfilment status derived from its shipments. | 
**ShippingRuleId** | Pointer to **NullableString** | ID of the applied shipping rule. | [optional] 
**Notes** | Pointer to **NullableString** | Free-form internal notes. | [optional] 
**ExternalData** | Pointer to **map[string]interface{}** | Raw platform-specific payload for reference. | [optional] 
**OrderChannelId** | **string** | ID of the order channel this order belongs to. | 
**OrgId** | **string** | Owning organization ID. | 
**CreatedAt** | **string** | Creation timestamp (ISO 8601). | 
**UpdatedAt** | **string** | Last update timestamp (ISO 8601). | 

## Methods

### NewCreateOrder201Response

`func NewCreateOrder201Response(id string, orderNumber string, orderLines []CreateOrder201ResponseOrderLinesInner, status string, orderChannelId string, orgId string, createdAt string, updatedAt string, ) *CreateOrder201Response`

NewCreateOrder201Response instantiates a new CreateOrder201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateOrder201ResponseWithDefaults

`func NewCreateOrder201ResponseWithDefaults() *CreateOrder201Response`

NewCreateOrder201ResponseWithDefaults instantiates a new CreateOrder201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreateOrder201Response) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateOrder201Response) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateOrder201Response) SetId(v string)`

SetId sets Id field to given value.


### GetOrderNumber

`func (o *CreateOrder201Response) GetOrderNumber() string`

GetOrderNumber returns the OrderNumber field if non-nil, zero value otherwise.

### GetOrderNumberOk

`func (o *CreateOrder201Response) GetOrderNumberOk() (*string, bool)`

GetOrderNumberOk returns a tuple with the OrderNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderNumber

`func (o *CreateOrder201Response) SetOrderNumber(v string)`

SetOrderNumber sets OrderNumber field to given value.


### GetExternalId

`func (o *CreateOrder201Response) GetExternalId() string`

GetExternalId returns the ExternalId field if non-nil, zero value otherwise.

### GetExternalIdOk

`func (o *CreateOrder201Response) GetExternalIdOk() (*string, bool)`

GetExternalIdOk returns a tuple with the ExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalId

`func (o *CreateOrder201Response) SetExternalId(v string)`

SetExternalId sets ExternalId field to given value.

### HasExternalId

`func (o *CreateOrder201Response) HasExternalId() bool`

HasExternalId returns a boolean if a field has been set.

### SetExternalIdNil

`func (o *CreateOrder201Response) SetExternalIdNil(b bool)`

 SetExternalIdNil sets the value for ExternalId to be an explicit nil

### UnsetExternalId
`func (o *CreateOrder201Response) UnsetExternalId()`

UnsetExternalId ensures that no value is present for ExternalId, not even an explicit nil
### GetCustomerName

`func (o *CreateOrder201Response) GetCustomerName() string`

GetCustomerName returns the CustomerName field if non-nil, zero value otherwise.

### GetCustomerNameOk

`func (o *CreateOrder201Response) GetCustomerNameOk() (*string, bool)`

GetCustomerNameOk returns a tuple with the CustomerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerName

`func (o *CreateOrder201Response) SetCustomerName(v string)`

SetCustomerName sets CustomerName field to given value.

### HasCustomerName

`func (o *CreateOrder201Response) HasCustomerName() bool`

HasCustomerName returns a boolean if a field has been set.

### SetCustomerNameNil

`func (o *CreateOrder201Response) SetCustomerNameNil(b bool)`

 SetCustomerNameNil sets the value for CustomerName to be an explicit nil

### UnsetCustomerName
`func (o *CreateOrder201Response) UnsetCustomerName()`

UnsetCustomerName ensures that no value is present for CustomerName, not even an explicit nil
### GetCustomerEmail

`func (o *CreateOrder201Response) GetCustomerEmail() string`

GetCustomerEmail returns the CustomerEmail field if non-nil, zero value otherwise.

### GetCustomerEmailOk

`func (o *CreateOrder201Response) GetCustomerEmailOk() (*string, bool)`

GetCustomerEmailOk returns a tuple with the CustomerEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerEmail

`func (o *CreateOrder201Response) SetCustomerEmail(v string)`

SetCustomerEmail sets CustomerEmail field to given value.

### HasCustomerEmail

`func (o *CreateOrder201Response) HasCustomerEmail() bool`

HasCustomerEmail returns a boolean if a field has been set.

### SetCustomerEmailNil

`func (o *CreateOrder201Response) SetCustomerEmailNil(b bool)`

 SetCustomerEmailNil sets the value for CustomerEmail to be an explicit nil

### UnsetCustomerEmail
`func (o *CreateOrder201Response) UnsetCustomerEmail()`

UnsetCustomerEmail ensures that no value is present for CustomerEmail, not even an explicit nil
### GetShippingAddress

`func (o *CreateOrder201Response) GetShippingAddress() CreateOrder201ResponseShippingAddress`

GetShippingAddress returns the ShippingAddress field if non-nil, zero value otherwise.

### GetShippingAddressOk

`func (o *CreateOrder201Response) GetShippingAddressOk() (*CreateOrder201ResponseShippingAddress, bool)`

GetShippingAddressOk returns a tuple with the ShippingAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingAddress

`func (o *CreateOrder201Response) SetShippingAddress(v CreateOrder201ResponseShippingAddress)`

SetShippingAddress sets ShippingAddress field to given value.

### HasShippingAddress

`func (o *CreateOrder201Response) HasShippingAddress() bool`

HasShippingAddress returns a boolean if a field has been set.

### SetShippingAddressNil

`func (o *CreateOrder201Response) SetShippingAddressNil(b bool)`

 SetShippingAddressNil sets the value for ShippingAddress to be an explicit nil

### UnsetShippingAddress
`func (o *CreateOrder201Response) UnsetShippingAddress()`

UnsetShippingAddress ensures that no value is present for ShippingAddress, not even an explicit nil
### GetOrderLines

`func (o *CreateOrder201Response) GetOrderLines() []CreateOrder201ResponseOrderLinesInner`

GetOrderLines returns the OrderLines field if non-nil, zero value otherwise.

### GetOrderLinesOk

`func (o *CreateOrder201Response) GetOrderLinesOk() (*[]CreateOrder201ResponseOrderLinesInner, bool)`

GetOrderLinesOk returns a tuple with the OrderLines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderLines

`func (o *CreateOrder201Response) SetOrderLines(v []CreateOrder201ResponseOrderLinesInner)`

SetOrderLines sets OrderLines field to given value.


### GetSubtotalAmount

`func (o *CreateOrder201Response) GetSubtotalAmount() float32`

GetSubtotalAmount returns the SubtotalAmount field if non-nil, zero value otherwise.

### GetSubtotalAmountOk

`func (o *CreateOrder201Response) GetSubtotalAmountOk() (*float32, bool)`

GetSubtotalAmountOk returns a tuple with the SubtotalAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubtotalAmount

`func (o *CreateOrder201Response) SetSubtotalAmount(v float32)`

SetSubtotalAmount sets SubtotalAmount field to given value.

### HasSubtotalAmount

`func (o *CreateOrder201Response) HasSubtotalAmount() bool`

HasSubtotalAmount returns a boolean if a field has been set.

### SetSubtotalAmountNil

`func (o *CreateOrder201Response) SetSubtotalAmountNil(b bool)`

 SetSubtotalAmountNil sets the value for SubtotalAmount to be an explicit nil

### UnsetSubtotalAmount
`func (o *CreateOrder201Response) UnsetSubtotalAmount()`

UnsetSubtotalAmount ensures that no value is present for SubtotalAmount, not even an explicit nil
### GetTotalAmount

`func (o *CreateOrder201Response) GetTotalAmount() float32`

GetTotalAmount returns the TotalAmount field if non-nil, zero value otherwise.

### GetTotalAmountOk

`func (o *CreateOrder201Response) GetTotalAmountOk() (*float32, bool)`

GetTotalAmountOk returns a tuple with the TotalAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalAmount

`func (o *CreateOrder201Response) SetTotalAmount(v float32)`

SetTotalAmount sets TotalAmount field to given value.

### HasTotalAmount

`func (o *CreateOrder201Response) HasTotalAmount() bool`

HasTotalAmount returns a boolean if a field has been set.

### SetTotalAmountNil

`func (o *CreateOrder201Response) SetTotalAmountNil(b bool)`

 SetTotalAmountNil sets the value for TotalAmount to be an explicit nil

### UnsetTotalAmount
`func (o *CreateOrder201Response) UnsetTotalAmount()`

UnsetTotalAmount ensures that no value is present for TotalAmount, not even an explicit nil
### GetCurrency

`func (o *CreateOrder201Response) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *CreateOrder201Response) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *CreateOrder201Response) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *CreateOrder201Response) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### SetCurrencyNil

`func (o *CreateOrder201Response) SetCurrencyNil(b bool)`

 SetCurrencyNil sets the value for Currency to be an explicit nil

### UnsetCurrency
`func (o *CreateOrder201Response) UnsetCurrency()`

UnsetCurrency ensures that no value is present for Currency, not even an explicit nil
### GetStatus

`func (o *CreateOrder201Response) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CreateOrder201Response) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CreateOrder201Response) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetShippingRuleId

`func (o *CreateOrder201Response) GetShippingRuleId() string`

GetShippingRuleId returns the ShippingRuleId field if non-nil, zero value otherwise.

### GetShippingRuleIdOk

`func (o *CreateOrder201Response) GetShippingRuleIdOk() (*string, bool)`

GetShippingRuleIdOk returns a tuple with the ShippingRuleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingRuleId

`func (o *CreateOrder201Response) SetShippingRuleId(v string)`

SetShippingRuleId sets ShippingRuleId field to given value.

### HasShippingRuleId

`func (o *CreateOrder201Response) HasShippingRuleId() bool`

HasShippingRuleId returns a boolean if a field has been set.

### SetShippingRuleIdNil

`func (o *CreateOrder201Response) SetShippingRuleIdNil(b bool)`

 SetShippingRuleIdNil sets the value for ShippingRuleId to be an explicit nil

### UnsetShippingRuleId
`func (o *CreateOrder201Response) UnsetShippingRuleId()`

UnsetShippingRuleId ensures that no value is present for ShippingRuleId, not even an explicit nil
### GetNotes

`func (o *CreateOrder201Response) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *CreateOrder201Response) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *CreateOrder201Response) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *CreateOrder201Response) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *CreateOrder201Response) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *CreateOrder201Response) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetExternalData

`func (o *CreateOrder201Response) GetExternalData() map[string]interface{}`

GetExternalData returns the ExternalData field if non-nil, zero value otherwise.

### GetExternalDataOk

`func (o *CreateOrder201Response) GetExternalDataOk() (*map[string]interface{}, bool)`

GetExternalDataOk returns a tuple with the ExternalData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalData

`func (o *CreateOrder201Response) SetExternalData(v map[string]interface{})`

SetExternalData sets ExternalData field to given value.

### HasExternalData

`func (o *CreateOrder201Response) HasExternalData() bool`

HasExternalData returns a boolean if a field has been set.

### SetExternalDataNil

`func (o *CreateOrder201Response) SetExternalDataNil(b bool)`

 SetExternalDataNil sets the value for ExternalData to be an explicit nil

### UnsetExternalData
`func (o *CreateOrder201Response) UnsetExternalData()`

UnsetExternalData ensures that no value is present for ExternalData, not even an explicit nil
### GetOrderChannelId

`func (o *CreateOrder201Response) GetOrderChannelId() string`

GetOrderChannelId returns the OrderChannelId field if non-nil, zero value otherwise.

### GetOrderChannelIdOk

`func (o *CreateOrder201Response) GetOrderChannelIdOk() (*string, bool)`

GetOrderChannelIdOk returns a tuple with the OrderChannelId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderChannelId

`func (o *CreateOrder201Response) SetOrderChannelId(v string)`

SetOrderChannelId sets OrderChannelId field to given value.


### GetOrgId

`func (o *CreateOrder201Response) GetOrgId() string`

GetOrgId returns the OrgId field if non-nil, zero value otherwise.

### GetOrgIdOk

`func (o *CreateOrder201Response) GetOrgIdOk() (*string, bool)`

GetOrgIdOk returns a tuple with the OrgId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrgId

`func (o *CreateOrder201Response) SetOrgId(v string)`

SetOrgId sets OrgId field to given value.


### GetCreatedAt

`func (o *CreateOrder201Response) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CreateOrder201Response) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CreateOrder201Response) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *CreateOrder201Response) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *CreateOrder201Response) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *CreateOrder201Response) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


