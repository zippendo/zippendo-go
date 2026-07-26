# CreateOrderRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrderNumber** | **string** | Human-readable order number. | 
**ExternalId** | Pointer to **NullableString** | Identifier of the order in the source platform. | [optional] 
**OrderChannelId** | **string** | ID of the order channel this order belongs to. | 
**CustomerName** | Pointer to **NullableString** | Customer full name. | [optional] 
**CustomerEmail** | Pointer to **NullableString** | Customer email address. | [optional] 
**ShippingAddress** | Pointer to [**NullableCreateOrderRequestShippingAddress**](CreateOrderRequestShippingAddress.md) |  | [optional] 
**OrderLines** | [**[]CreateOrderRequestOrderLinesInner**](CreateOrderRequestOrderLinesInner.md) | Line items in the order. | 
**SubtotalAmount** | Pointer to **NullableFloat32** | Order subtotal before shipping and tax. | [optional] 
**TotalAmount** | Pointer to **NullableFloat32** | Order grand total. | [optional] 
**Currency** | Pointer to **NullableString** | ISO 4217 currency code. | [optional] 
**Notes** | Pointer to **NullableString** | Free-form internal notes. | [optional] 
**ExternalData** | Pointer to **map[string]interface{}** | Raw platform-specific payload for reference. | [optional] 

## Methods

### NewCreateOrderRequest

`func NewCreateOrderRequest(orderNumber string, orderChannelId string, orderLines []CreateOrderRequestOrderLinesInner, ) *CreateOrderRequest`

NewCreateOrderRequest instantiates a new CreateOrderRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateOrderRequestWithDefaults

`func NewCreateOrderRequestWithDefaults() *CreateOrderRequest`

NewCreateOrderRequestWithDefaults instantiates a new CreateOrderRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrderNumber

`func (o *CreateOrderRequest) GetOrderNumber() string`

GetOrderNumber returns the OrderNumber field if non-nil, zero value otherwise.

### GetOrderNumberOk

`func (o *CreateOrderRequest) GetOrderNumberOk() (*string, bool)`

GetOrderNumberOk returns a tuple with the OrderNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderNumber

`func (o *CreateOrderRequest) SetOrderNumber(v string)`

SetOrderNumber sets OrderNumber field to given value.


### GetExternalId

`func (o *CreateOrderRequest) GetExternalId() string`

GetExternalId returns the ExternalId field if non-nil, zero value otherwise.

### GetExternalIdOk

`func (o *CreateOrderRequest) GetExternalIdOk() (*string, bool)`

GetExternalIdOk returns a tuple with the ExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalId

`func (o *CreateOrderRequest) SetExternalId(v string)`

SetExternalId sets ExternalId field to given value.

### HasExternalId

`func (o *CreateOrderRequest) HasExternalId() bool`

HasExternalId returns a boolean if a field has been set.

### SetExternalIdNil

`func (o *CreateOrderRequest) SetExternalIdNil(b bool)`

 SetExternalIdNil sets the value for ExternalId to be an explicit nil

### UnsetExternalId
`func (o *CreateOrderRequest) UnsetExternalId()`

UnsetExternalId ensures that no value is present for ExternalId, not even an explicit nil
### GetOrderChannelId

`func (o *CreateOrderRequest) GetOrderChannelId() string`

GetOrderChannelId returns the OrderChannelId field if non-nil, zero value otherwise.

### GetOrderChannelIdOk

`func (o *CreateOrderRequest) GetOrderChannelIdOk() (*string, bool)`

GetOrderChannelIdOk returns a tuple with the OrderChannelId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderChannelId

`func (o *CreateOrderRequest) SetOrderChannelId(v string)`

SetOrderChannelId sets OrderChannelId field to given value.


### GetCustomerName

`func (o *CreateOrderRequest) GetCustomerName() string`

GetCustomerName returns the CustomerName field if non-nil, zero value otherwise.

### GetCustomerNameOk

`func (o *CreateOrderRequest) GetCustomerNameOk() (*string, bool)`

GetCustomerNameOk returns a tuple with the CustomerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerName

`func (o *CreateOrderRequest) SetCustomerName(v string)`

SetCustomerName sets CustomerName field to given value.

### HasCustomerName

`func (o *CreateOrderRequest) HasCustomerName() bool`

HasCustomerName returns a boolean if a field has been set.

### SetCustomerNameNil

`func (o *CreateOrderRequest) SetCustomerNameNil(b bool)`

 SetCustomerNameNil sets the value for CustomerName to be an explicit nil

### UnsetCustomerName
`func (o *CreateOrderRequest) UnsetCustomerName()`

UnsetCustomerName ensures that no value is present for CustomerName, not even an explicit nil
### GetCustomerEmail

`func (o *CreateOrderRequest) GetCustomerEmail() string`

GetCustomerEmail returns the CustomerEmail field if non-nil, zero value otherwise.

### GetCustomerEmailOk

`func (o *CreateOrderRequest) GetCustomerEmailOk() (*string, bool)`

GetCustomerEmailOk returns a tuple with the CustomerEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerEmail

`func (o *CreateOrderRequest) SetCustomerEmail(v string)`

SetCustomerEmail sets CustomerEmail field to given value.

### HasCustomerEmail

`func (o *CreateOrderRequest) HasCustomerEmail() bool`

HasCustomerEmail returns a boolean if a field has been set.

### SetCustomerEmailNil

`func (o *CreateOrderRequest) SetCustomerEmailNil(b bool)`

 SetCustomerEmailNil sets the value for CustomerEmail to be an explicit nil

### UnsetCustomerEmail
`func (o *CreateOrderRequest) UnsetCustomerEmail()`

UnsetCustomerEmail ensures that no value is present for CustomerEmail, not even an explicit nil
### GetShippingAddress

`func (o *CreateOrderRequest) GetShippingAddress() CreateOrderRequestShippingAddress`

GetShippingAddress returns the ShippingAddress field if non-nil, zero value otherwise.

### GetShippingAddressOk

`func (o *CreateOrderRequest) GetShippingAddressOk() (*CreateOrderRequestShippingAddress, bool)`

GetShippingAddressOk returns a tuple with the ShippingAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingAddress

`func (o *CreateOrderRequest) SetShippingAddress(v CreateOrderRequestShippingAddress)`

SetShippingAddress sets ShippingAddress field to given value.

### HasShippingAddress

`func (o *CreateOrderRequest) HasShippingAddress() bool`

HasShippingAddress returns a boolean if a field has been set.

### SetShippingAddressNil

`func (o *CreateOrderRequest) SetShippingAddressNil(b bool)`

 SetShippingAddressNil sets the value for ShippingAddress to be an explicit nil

### UnsetShippingAddress
`func (o *CreateOrderRequest) UnsetShippingAddress()`

UnsetShippingAddress ensures that no value is present for ShippingAddress, not even an explicit nil
### GetOrderLines

`func (o *CreateOrderRequest) GetOrderLines() []CreateOrderRequestOrderLinesInner`

GetOrderLines returns the OrderLines field if non-nil, zero value otherwise.

### GetOrderLinesOk

`func (o *CreateOrderRequest) GetOrderLinesOk() (*[]CreateOrderRequestOrderLinesInner, bool)`

GetOrderLinesOk returns a tuple with the OrderLines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderLines

`func (o *CreateOrderRequest) SetOrderLines(v []CreateOrderRequestOrderLinesInner)`

SetOrderLines sets OrderLines field to given value.


### GetSubtotalAmount

`func (o *CreateOrderRequest) GetSubtotalAmount() float32`

GetSubtotalAmount returns the SubtotalAmount field if non-nil, zero value otherwise.

### GetSubtotalAmountOk

`func (o *CreateOrderRequest) GetSubtotalAmountOk() (*float32, bool)`

GetSubtotalAmountOk returns a tuple with the SubtotalAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubtotalAmount

`func (o *CreateOrderRequest) SetSubtotalAmount(v float32)`

SetSubtotalAmount sets SubtotalAmount field to given value.

### HasSubtotalAmount

`func (o *CreateOrderRequest) HasSubtotalAmount() bool`

HasSubtotalAmount returns a boolean if a field has been set.

### SetSubtotalAmountNil

`func (o *CreateOrderRequest) SetSubtotalAmountNil(b bool)`

 SetSubtotalAmountNil sets the value for SubtotalAmount to be an explicit nil

### UnsetSubtotalAmount
`func (o *CreateOrderRequest) UnsetSubtotalAmount()`

UnsetSubtotalAmount ensures that no value is present for SubtotalAmount, not even an explicit nil
### GetTotalAmount

`func (o *CreateOrderRequest) GetTotalAmount() float32`

GetTotalAmount returns the TotalAmount field if non-nil, zero value otherwise.

### GetTotalAmountOk

`func (o *CreateOrderRequest) GetTotalAmountOk() (*float32, bool)`

GetTotalAmountOk returns a tuple with the TotalAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalAmount

`func (o *CreateOrderRequest) SetTotalAmount(v float32)`

SetTotalAmount sets TotalAmount field to given value.

### HasTotalAmount

`func (o *CreateOrderRequest) HasTotalAmount() bool`

HasTotalAmount returns a boolean if a field has been set.

### SetTotalAmountNil

`func (o *CreateOrderRequest) SetTotalAmountNil(b bool)`

 SetTotalAmountNil sets the value for TotalAmount to be an explicit nil

### UnsetTotalAmount
`func (o *CreateOrderRequest) UnsetTotalAmount()`

UnsetTotalAmount ensures that no value is present for TotalAmount, not even an explicit nil
### GetCurrency

`func (o *CreateOrderRequest) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *CreateOrderRequest) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *CreateOrderRequest) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *CreateOrderRequest) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### SetCurrencyNil

`func (o *CreateOrderRequest) SetCurrencyNil(b bool)`

 SetCurrencyNil sets the value for Currency to be an explicit nil

### UnsetCurrency
`func (o *CreateOrderRequest) UnsetCurrency()`

UnsetCurrency ensures that no value is present for Currency, not even an explicit nil
### GetNotes

`func (o *CreateOrderRequest) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *CreateOrderRequest) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *CreateOrderRequest) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *CreateOrderRequest) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *CreateOrderRequest) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *CreateOrderRequest) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetExternalData

`func (o *CreateOrderRequest) GetExternalData() map[string]interface{}`

GetExternalData returns the ExternalData field if non-nil, zero value otherwise.

### GetExternalDataOk

`func (o *CreateOrderRequest) GetExternalDataOk() (*map[string]interface{}, bool)`

GetExternalDataOk returns a tuple with the ExternalData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalData

`func (o *CreateOrderRequest) SetExternalData(v map[string]interface{})`

SetExternalData sets ExternalData field to given value.

### HasExternalData

`func (o *CreateOrderRequest) HasExternalData() bool`

HasExternalData returns a boolean if a field has been set.

### SetExternalDataNil

`func (o *CreateOrderRequest) SetExternalDataNil(b bool)`

 SetExternalDataNil sets the value for ExternalData to be an explicit nil

### UnsetExternalData
`func (o *CreateOrderRequest) UnsetExternalData()`

UnsetExternalData ensures that no value is present for ExternalData, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


