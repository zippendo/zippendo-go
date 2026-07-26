# CreateShippingQuoteRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Destination** | [**CreateShippingQuoteRequestDestination**](CreateShippingQuoteRequestDestination.md) |  | 
**Items** | [**[]CreateShippingQuoteRequestItemsInner**](CreateShippingQuoteRequestItemsInner.md) | Cart items | 
**Currency** | **string** | ISO 4217 currency code | 
**TotalPriceCents** | Pointer to **float32** | Total price in cents after discounts (optional, enables total-based conditions) | [optional] 

## Methods

### NewCreateShippingQuoteRequest

`func NewCreateShippingQuoteRequest(destination CreateShippingQuoteRequestDestination, items []CreateShippingQuoteRequestItemsInner, currency string, ) *CreateShippingQuoteRequest`

NewCreateShippingQuoteRequest instantiates a new CreateShippingQuoteRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateShippingQuoteRequestWithDefaults

`func NewCreateShippingQuoteRequestWithDefaults() *CreateShippingQuoteRequest`

NewCreateShippingQuoteRequestWithDefaults instantiates a new CreateShippingQuoteRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDestination

`func (o *CreateShippingQuoteRequest) GetDestination() CreateShippingQuoteRequestDestination`

GetDestination returns the Destination field if non-nil, zero value otherwise.

### GetDestinationOk

`func (o *CreateShippingQuoteRequest) GetDestinationOk() (*CreateShippingQuoteRequestDestination, bool)`

GetDestinationOk returns a tuple with the Destination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestination

`func (o *CreateShippingQuoteRequest) SetDestination(v CreateShippingQuoteRequestDestination)`

SetDestination sets Destination field to given value.


### GetItems

`func (o *CreateShippingQuoteRequest) GetItems() []CreateShippingQuoteRequestItemsInner`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *CreateShippingQuoteRequest) GetItemsOk() (*[]CreateShippingQuoteRequestItemsInner, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *CreateShippingQuoteRequest) SetItems(v []CreateShippingQuoteRequestItemsInner)`

SetItems sets Items field to given value.


### GetCurrency

`func (o *CreateShippingQuoteRequest) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *CreateShippingQuoteRequest) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *CreateShippingQuoteRequest) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetTotalPriceCents

`func (o *CreateShippingQuoteRequest) GetTotalPriceCents() float32`

GetTotalPriceCents returns the TotalPriceCents field if non-nil, zero value otherwise.

### GetTotalPriceCentsOk

`func (o *CreateShippingQuoteRequest) GetTotalPriceCentsOk() (*float32, bool)`

GetTotalPriceCentsOk returns a tuple with the TotalPriceCents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPriceCents

`func (o *CreateShippingQuoteRequest) SetTotalPriceCents(v float32)`

SetTotalPriceCents sets TotalPriceCents field to given value.

### HasTotalPriceCents

`func (o *CreateShippingQuoteRequest) HasTotalPriceCents() bool`

HasTotalPriceCents returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


