# ListOrders200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Unique order ID. | 
**OrderNumber** | **string** | Human-readable order number. | 
**CustomerName** | Pointer to **NullableString** | Customer full name. | [optional] 
**CustomerEmail** | Pointer to **NullableString** | Customer email address. | [optional] 
**Status** | **string** | Order fulfilment status derived from its shipments. | 
**BrandId** | **NullableString** | Brand this record belongs to, or null when it is organization-wide | 
**SubtotalAmount** | Pointer to **NullableFloat32** | Order subtotal before shipping and tax. | [optional] 
**TotalAmount** | Pointer to **NullableFloat32** | Order grand total. | [optional] 
**Currency** | Pointer to **NullableString** | ISO 4217 currency code. | [optional] 
**ShipmentCount** | **int32** | Number of shipments created for the order. | 
**OrderChannel** | [**ListOrders200ResponseDataInnerOrderChannel**](ListOrders200ResponseDataInnerOrderChannel.md) |  | 
**CreatedAt** | **string** | Creation timestamp (ISO 8601). | 
**UpdatedAt** | **string** | Last update timestamp (ISO 8601). | 

## Methods

### NewListOrders200ResponseDataInner

`func NewListOrders200ResponseDataInner(id string, orderNumber string, status string, brandId NullableString, shipmentCount int32, orderChannel ListOrders200ResponseDataInnerOrderChannel, createdAt string, updatedAt string, ) *ListOrders200ResponseDataInner`

NewListOrders200ResponseDataInner instantiates a new ListOrders200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListOrders200ResponseDataInnerWithDefaults

`func NewListOrders200ResponseDataInnerWithDefaults() *ListOrders200ResponseDataInner`

NewListOrders200ResponseDataInnerWithDefaults instantiates a new ListOrders200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ListOrders200ResponseDataInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ListOrders200ResponseDataInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ListOrders200ResponseDataInner) SetId(v string)`

SetId sets Id field to given value.


### GetOrderNumber

`func (o *ListOrders200ResponseDataInner) GetOrderNumber() string`

GetOrderNumber returns the OrderNumber field if non-nil, zero value otherwise.

### GetOrderNumberOk

`func (o *ListOrders200ResponseDataInner) GetOrderNumberOk() (*string, bool)`

GetOrderNumberOk returns a tuple with the OrderNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderNumber

`func (o *ListOrders200ResponseDataInner) SetOrderNumber(v string)`

SetOrderNumber sets OrderNumber field to given value.


### GetCustomerName

`func (o *ListOrders200ResponseDataInner) GetCustomerName() string`

GetCustomerName returns the CustomerName field if non-nil, zero value otherwise.

### GetCustomerNameOk

`func (o *ListOrders200ResponseDataInner) GetCustomerNameOk() (*string, bool)`

GetCustomerNameOk returns a tuple with the CustomerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerName

`func (o *ListOrders200ResponseDataInner) SetCustomerName(v string)`

SetCustomerName sets CustomerName field to given value.

### HasCustomerName

`func (o *ListOrders200ResponseDataInner) HasCustomerName() bool`

HasCustomerName returns a boolean if a field has been set.

### SetCustomerNameNil

`func (o *ListOrders200ResponseDataInner) SetCustomerNameNil(b bool)`

 SetCustomerNameNil sets the value for CustomerName to be an explicit nil

### UnsetCustomerName
`func (o *ListOrders200ResponseDataInner) UnsetCustomerName()`

UnsetCustomerName ensures that no value is present for CustomerName, not even an explicit nil
### GetCustomerEmail

`func (o *ListOrders200ResponseDataInner) GetCustomerEmail() string`

GetCustomerEmail returns the CustomerEmail field if non-nil, zero value otherwise.

### GetCustomerEmailOk

`func (o *ListOrders200ResponseDataInner) GetCustomerEmailOk() (*string, bool)`

GetCustomerEmailOk returns a tuple with the CustomerEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerEmail

`func (o *ListOrders200ResponseDataInner) SetCustomerEmail(v string)`

SetCustomerEmail sets CustomerEmail field to given value.

### HasCustomerEmail

`func (o *ListOrders200ResponseDataInner) HasCustomerEmail() bool`

HasCustomerEmail returns a boolean if a field has been set.

### SetCustomerEmailNil

`func (o *ListOrders200ResponseDataInner) SetCustomerEmailNil(b bool)`

 SetCustomerEmailNil sets the value for CustomerEmail to be an explicit nil

### UnsetCustomerEmail
`func (o *ListOrders200ResponseDataInner) UnsetCustomerEmail()`

UnsetCustomerEmail ensures that no value is present for CustomerEmail, not even an explicit nil
### GetStatus

`func (o *ListOrders200ResponseDataInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ListOrders200ResponseDataInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ListOrders200ResponseDataInner) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetBrandId

`func (o *ListOrders200ResponseDataInner) GetBrandId() string`

GetBrandId returns the BrandId field if non-nil, zero value otherwise.

### GetBrandIdOk

`func (o *ListOrders200ResponseDataInner) GetBrandIdOk() (*string, bool)`

GetBrandIdOk returns a tuple with the BrandId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandId

`func (o *ListOrders200ResponseDataInner) SetBrandId(v string)`

SetBrandId sets BrandId field to given value.


### SetBrandIdNil

`func (o *ListOrders200ResponseDataInner) SetBrandIdNil(b bool)`

 SetBrandIdNil sets the value for BrandId to be an explicit nil

### UnsetBrandId
`func (o *ListOrders200ResponseDataInner) UnsetBrandId()`

UnsetBrandId ensures that no value is present for BrandId, not even an explicit nil
### GetSubtotalAmount

`func (o *ListOrders200ResponseDataInner) GetSubtotalAmount() float32`

GetSubtotalAmount returns the SubtotalAmount field if non-nil, zero value otherwise.

### GetSubtotalAmountOk

`func (o *ListOrders200ResponseDataInner) GetSubtotalAmountOk() (*float32, bool)`

GetSubtotalAmountOk returns a tuple with the SubtotalAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubtotalAmount

`func (o *ListOrders200ResponseDataInner) SetSubtotalAmount(v float32)`

SetSubtotalAmount sets SubtotalAmount field to given value.

### HasSubtotalAmount

`func (o *ListOrders200ResponseDataInner) HasSubtotalAmount() bool`

HasSubtotalAmount returns a boolean if a field has been set.

### SetSubtotalAmountNil

`func (o *ListOrders200ResponseDataInner) SetSubtotalAmountNil(b bool)`

 SetSubtotalAmountNil sets the value for SubtotalAmount to be an explicit nil

### UnsetSubtotalAmount
`func (o *ListOrders200ResponseDataInner) UnsetSubtotalAmount()`

UnsetSubtotalAmount ensures that no value is present for SubtotalAmount, not even an explicit nil
### GetTotalAmount

`func (o *ListOrders200ResponseDataInner) GetTotalAmount() float32`

GetTotalAmount returns the TotalAmount field if non-nil, zero value otherwise.

### GetTotalAmountOk

`func (o *ListOrders200ResponseDataInner) GetTotalAmountOk() (*float32, bool)`

GetTotalAmountOk returns a tuple with the TotalAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalAmount

`func (o *ListOrders200ResponseDataInner) SetTotalAmount(v float32)`

SetTotalAmount sets TotalAmount field to given value.

### HasTotalAmount

`func (o *ListOrders200ResponseDataInner) HasTotalAmount() bool`

HasTotalAmount returns a boolean if a field has been set.

### SetTotalAmountNil

`func (o *ListOrders200ResponseDataInner) SetTotalAmountNil(b bool)`

 SetTotalAmountNil sets the value for TotalAmount to be an explicit nil

### UnsetTotalAmount
`func (o *ListOrders200ResponseDataInner) UnsetTotalAmount()`

UnsetTotalAmount ensures that no value is present for TotalAmount, not even an explicit nil
### GetCurrency

`func (o *ListOrders200ResponseDataInner) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *ListOrders200ResponseDataInner) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *ListOrders200ResponseDataInner) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *ListOrders200ResponseDataInner) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### SetCurrencyNil

`func (o *ListOrders200ResponseDataInner) SetCurrencyNil(b bool)`

 SetCurrencyNil sets the value for Currency to be an explicit nil

### UnsetCurrency
`func (o *ListOrders200ResponseDataInner) UnsetCurrency()`

UnsetCurrency ensures that no value is present for Currency, not even an explicit nil
### GetShipmentCount

`func (o *ListOrders200ResponseDataInner) GetShipmentCount() int32`

GetShipmentCount returns the ShipmentCount field if non-nil, zero value otherwise.

### GetShipmentCountOk

`func (o *ListOrders200ResponseDataInner) GetShipmentCountOk() (*int32, bool)`

GetShipmentCountOk returns a tuple with the ShipmentCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipmentCount

`func (o *ListOrders200ResponseDataInner) SetShipmentCount(v int32)`

SetShipmentCount sets ShipmentCount field to given value.


### GetOrderChannel

`func (o *ListOrders200ResponseDataInner) GetOrderChannel() ListOrders200ResponseDataInnerOrderChannel`

GetOrderChannel returns the OrderChannel field if non-nil, zero value otherwise.

### GetOrderChannelOk

`func (o *ListOrders200ResponseDataInner) GetOrderChannelOk() (*ListOrders200ResponseDataInnerOrderChannel, bool)`

GetOrderChannelOk returns a tuple with the OrderChannel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderChannel

`func (o *ListOrders200ResponseDataInner) SetOrderChannel(v ListOrders200ResponseDataInnerOrderChannel)`

SetOrderChannel sets OrderChannel field to given value.


### GetCreatedAt

`func (o *ListOrders200ResponseDataInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ListOrders200ResponseDataInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ListOrders200ResponseDataInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *ListOrders200ResponseDataInner) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ListOrders200ResponseDataInner) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ListOrders200ResponseDataInner) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


