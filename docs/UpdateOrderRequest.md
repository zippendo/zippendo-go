# UpdateOrderRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrderNumber** | Pointer to **string** | Human-readable order number. | [optional] 
**CustomerName** | Pointer to **NullableString** | Customer full name. | [optional] 
**CustomerEmail** | Pointer to **NullableString** | Customer email address. | [optional] 
**ShippingAddress** | Pointer to [**NullableCreateOrderRequestShippingAddress**](CreateOrderRequestShippingAddress.md) |  | [optional] 
**OrderLines** | Pointer to [**[]CreateOrderRequestOrderLinesInner**](CreateOrderRequestOrderLinesInner.md) | Line items in the order. | [optional] 
**SubtotalAmount** | Pointer to **NullableFloat32** | Order subtotal before shipping and tax. | [optional] 
**TotalAmount** | Pointer to **NullableFloat32** | Order grand total. | [optional] 
**Currency** | Pointer to **NullableString** | ISO 4217 currency code. | [optional] 
**Notes** | Pointer to **NullableString** | Free-form internal notes. | [optional] 
**Status** | Pointer to **string** | Order fulfilment status derived from its shipments. | [optional] 
**ShippingRuleId** | Pointer to **NullableString** | ID of the shipping rule to apply. | [optional] 

## Methods

### NewUpdateOrderRequest

`func NewUpdateOrderRequest() *UpdateOrderRequest`

NewUpdateOrderRequest instantiates a new UpdateOrderRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateOrderRequestWithDefaults

`func NewUpdateOrderRequestWithDefaults() *UpdateOrderRequest`

NewUpdateOrderRequestWithDefaults instantiates a new UpdateOrderRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrderNumber

`func (o *UpdateOrderRequest) GetOrderNumber() string`

GetOrderNumber returns the OrderNumber field if non-nil, zero value otherwise.

### GetOrderNumberOk

`func (o *UpdateOrderRequest) GetOrderNumberOk() (*string, bool)`

GetOrderNumberOk returns a tuple with the OrderNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderNumber

`func (o *UpdateOrderRequest) SetOrderNumber(v string)`

SetOrderNumber sets OrderNumber field to given value.

### HasOrderNumber

`func (o *UpdateOrderRequest) HasOrderNumber() bool`

HasOrderNumber returns a boolean if a field has been set.

### GetCustomerName

`func (o *UpdateOrderRequest) GetCustomerName() string`

GetCustomerName returns the CustomerName field if non-nil, zero value otherwise.

### GetCustomerNameOk

`func (o *UpdateOrderRequest) GetCustomerNameOk() (*string, bool)`

GetCustomerNameOk returns a tuple with the CustomerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerName

`func (o *UpdateOrderRequest) SetCustomerName(v string)`

SetCustomerName sets CustomerName field to given value.

### HasCustomerName

`func (o *UpdateOrderRequest) HasCustomerName() bool`

HasCustomerName returns a boolean if a field has been set.

### SetCustomerNameNil

`func (o *UpdateOrderRequest) SetCustomerNameNil(b bool)`

 SetCustomerNameNil sets the value for CustomerName to be an explicit nil

### UnsetCustomerName
`func (o *UpdateOrderRequest) UnsetCustomerName()`

UnsetCustomerName ensures that no value is present for CustomerName, not even an explicit nil
### GetCustomerEmail

`func (o *UpdateOrderRequest) GetCustomerEmail() string`

GetCustomerEmail returns the CustomerEmail field if non-nil, zero value otherwise.

### GetCustomerEmailOk

`func (o *UpdateOrderRequest) GetCustomerEmailOk() (*string, bool)`

GetCustomerEmailOk returns a tuple with the CustomerEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerEmail

`func (o *UpdateOrderRequest) SetCustomerEmail(v string)`

SetCustomerEmail sets CustomerEmail field to given value.

### HasCustomerEmail

`func (o *UpdateOrderRequest) HasCustomerEmail() bool`

HasCustomerEmail returns a boolean if a field has been set.

### SetCustomerEmailNil

`func (o *UpdateOrderRequest) SetCustomerEmailNil(b bool)`

 SetCustomerEmailNil sets the value for CustomerEmail to be an explicit nil

### UnsetCustomerEmail
`func (o *UpdateOrderRequest) UnsetCustomerEmail()`

UnsetCustomerEmail ensures that no value is present for CustomerEmail, not even an explicit nil
### GetShippingAddress

`func (o *UpdateOrderRequest) GetShippingAddress() CreateOrderRequestShippingAddress`

GetShippingAddress returns the ShippingAddress field if non-nil, zero value otherwise.

### GetShippingAddressOk

`func (o *UpdateOrderRequest) GetShippingAddressOk() (*CreateOrderRequestShippingAddress, bool)`

GetShippingAddressOk returns a tuple with the ShippingAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingAddress

`func (o *UpdateOrderRequest) SetShippingAddress(v CreateOrderRequestShippingAddress)`

SetShippingAddress sets ShippingAddress field to given value.

### HasShippingAddress

`func (o *UpdateOrderRequest) HasShippingAddress() bool`

HasShippingAddress returns a boolean if a field has been set.

### SetShippingAddressNil

`func (o *UpdateOrderRequest) SetShippingAddressNil(b bool)`

 SetShippingAddressNil sets the value for ShippingAddress to be an explicit nil

### UnsetShippingAddress
`func (o *UpdateOrderRequest) UnsetShippingAddress()`

UnsetShippingAddress ensures that no value is present for ShippingAddress, not even an explicit nil
### GetOrderLines

`func (o *UpdateOrderRequest) GetOrderLines() []CreateOrderRequestOrderLinesInner`

GetOrderLines returns the OrderLines field if non-nil, zero value otherwise.

### GetOrderLinesOk

`func (o *UpdateOrderRequest) GetOrderLinesOk() (*[]CreateOrderRequestOrderLinesInner, bool)`

GetOrderLinesOk returns a tuple with the OrderLines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderLines

`func (o *UpdateOrderRequest) SetOrderLines(v []CreateOrderRequestOrderLinesInner)`

SetOrderLines sets OrderLines field to given value.

### HasOrderLines

`func (o *UpdateOrderRequest) HasOrderLines() bool`

HasOrderLines returns a boolean if a field has been set.

### GetSubtotalAmount

`func (o *UpdateOrderRequest) GetSubtotalAmount() float32`

GetSubtotalAmount returns the SubtotalAmount field if non-nil, zero value otherwise.

### GetSubtotalAmountOk

`func (o *UpdateOrderRequest) GetSubtotalAmountOk() (*float32, bool)`

GetSubtotalAmountOk returns a tuple with the SubtotalAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubtotalAmount

`func (o *UpdateOrderRequest) SetSubtotalAmount(v float32)`

SetSubtotalAmount sets SubtotalAmount field to given value.

### HasSubtotalAmount

`func (o *UpdateOrderRequest) HasSubtotalAmount() bool`

HasSubtotalAmount returns a boolean if a field has been set.

### SetSubtotalAmountNil

`func (o *UpdateOrderRequest) SetSubtotalAmountNil(b bool)`

 SetSubtotalAmountNil sets the value for SubtotalAmount to be an explicit nil

### UnsetSubtotalAmount
`func (o *UpdateOrderRequest) UnsetSubtotalAmount()`

UnsetSubtotalAmount ensures that no value is present for SubtotalAmount, not even an explicit nil
### GetTotalAmount

`func (o *UpdateOrderRequest) GetTotalAmount() float32`

GetTotalAmount returns the TotalAmount field if non-nil, zero value otherwise.

### GetTotalAmountOk

`func (o *UpdateOrderRequest) GetTotalAmountOk() (*float32, bool)`

GetTotalAmountOk returns a tuple with the TotalAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalAmount

`func (o *UpdateOrderRequest) SetTotalAmount(v float32)`

SetTotalAmount sets TotalAmount field to given value.

### HasTotalAmount

`func (o *UpdateOrderRequest) HasTotalAmount() bool`

HasTotalAmount returns a boolean if a field has been set.

### SetTotalAmountNil

`func (o *UpdateOrderRequest) SetTotalAmountNil(b bool)`

 SetTotalAmountNil sets the value for TotalAmount to be an explicit nil

### UnsetTotalAmount
`func (o *UpdateOrderRequest) UnsetTotalAmount()`

UnsetTotalAmount ensures that no value is present for TotalAmount, not even an explicit nil
### GetCurrency

`func (o *UpdateOrderRequest) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *UpdateOrderRequest) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *UpdateOrderRequest) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *UpdateOrderRequest) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### SetCurrencyNil

`func (o *UpdateOrderRequest) SetCurrencyNil(b bool)`

 SetCurrencyNil sets the value for Currency to be an explicit nil

### UnsetCurrency
`func (o *UpdateOrderRequest) UnsetCurrency()`

UnsetCurrency ensures that no value is present for Currency, not even an explicit nil
### GetNotes

`func (o *UpdateOrderRequest) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *UpdateOrderRequest) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *UpdateOrderRequest) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *UpdateOrderRequest) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *UpdateOrderRequest) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *UpdateOrderRequest) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetStatus

`func (o *UpdateOrderRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *UpdateOrderRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *UpdateOrderRequest) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *UpdateOrderRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetShippingRuleId

`func (o *UpdateOrderRequest) GetShippingRuleId() string`

GetShippingRuleId returns the ShippingRuleId field if non-nil, zero value otherwise.

### GetShippingRuleIdOk

`func (o *UpdateOrderRequest) GetShippingRuleIdOk() (*string, bool)`

GetShippingRuleIdOk returns a tuple with the ShippingRuleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingRuleId

`func (o *UpdateOrderRequest) SetShippingRuleId(v string)`

SetShippingRuleId sets ShippingRuleId field to given value.

### HasShippingRuleId

`func (o *UpdateOrderRequest) HasShippingRuleId() bool`

HasShippingRuleId returns a boolean if a field has been set.

### SetShippingRuleIdNil

`func (o *UpdateOrderRequest) SetShippingRuleIdNil(b bool)`

 SetShippingRuleIdNil sets the value for ShippingRuleId to be an explicit nil

### UnsetShippingRuleId
`func (o *UpdateOrderRequest) UnsetShippingRuleId()`

UnsetShippingRuleId ensures that no value is present for ShippingRuleId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


