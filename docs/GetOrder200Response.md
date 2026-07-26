# GetOrder200Response

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
**OrderChannel** | [**ListOrders200ResponseDataInnerOrderChannel**](ListOrders200ResponseDataInnerOrderChannel.md) |  | 
**ShippingRule** | Pointer to [**NullableGetOrder200ResponseShippingRule**](GetOrder200ResponseShippingRule.md) |  | [optional] 
**Shipments** | [**[]GetOrder200ResponseShipmentsInner**](GetOrder200ResponseShipmentsInner.md) |  | 

## Methods

### NewGetOrder200Response

`func NewGetOrder200Response(id string, orderNumber string, orderLines []CreateOrder201ResponseOrderLinesInner, status string, orderChannelId string, orgId string, createdAt string, updatedAt string, orderChannel ListOrders200ResponseDataInnerOrderChannel, shipments []GetOrder200ResponseShipmentsInner, ) *GetOrder200Response`

NewGetOrder200Response instantiates a new GetOrder200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetOrder200ResponseWithDefaults

`func NewGetOrder200ResponseWithDefaults() *GetOrder200Response`

NewGetOrder200ResponseWithDefaults instantiates a new GetOrder200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GetOrder200Response) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GetOrder200Response) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GetOrder200Response) SetId(v string)`

SetId sets Id field to given value.


### GetOrderNumber

`func (o *GetOrder200Response) GetOrderNumber() string`

GetOrderNumber returns the OrderNumber field if non-nil, zero value otherwise.

### GetOrderNumberOk

`func (o *GetOrder200Response) GetOrderNumberOk() (*string, bool)`

GetOrderNumberOk returns a tuple with the OrderNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderNumber

`func (o *GetOrder200Response) SetOrderNumber(v string)`

SetOrderNumber sets OrderNumber field to given value.


### GetExternalId

`func (o *GetOrder200Response) GetExternalId() string`

GetExternalId returns the ExternalId field if non-nil, zero value otherwise.

### GetExternalIdOk

`func (o *GetOrder200Response) GetExternalIdOk() (*string, bool)`

GetExternalIdOk returns a tuple with the ExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalId

`func (o *GetOrder200Response) SetExternalId(v string)`

SetExternalId sets ExternalId field to given value.

### HasExternalId

`func (o *GetOrder200Response) HasExternalId() bool`

HasExternalId returns a boolean if a field has been set.

### SetExternalIdNil

`func (o *GetOrder200Response) SetExternalIdNil(b bool)`

 SetExternalIdNil sets the value for ExternalId to be an explicit nil

### UnsetExternalId
`func (o *GetOrder200Response) UnsetExternalId()`

UnsetExternalId ensures that no value is present for ExternalId, not even an explicit nil
### GetCustomerName

`func (o *GetOrder200Response) GetCustomerName() string`

GetCustomerName returns the CustomerName field if non-nil, zero value otherwise.

### GetCustomerNameOk

`func (o *GetOrder200Response) GetCustomerNameOk() (*string, bool)`

GetCustomerNameOk returns a tuple with the CustomerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerName

`func (o *GetOrder200Response) SetCustomerName(v string)`

SetCustomerName sets CustomerName field to given value.

### HasCustomerName

`func (o *GetOrder200Response) HasCustomerName() bool`

HasCustomerName returns a boolean if a field has been set.

### SetCustomerNameNil

`func (o *GetOrder200Response) SetCustomerNameNil(b bool)`

 SetCustomerNameNil sets the value for CustomerName to be an explicit nil

### UnsetCustomerName
`func (o *GetOrder200Response) UnsetCustomerName()`

UnsetCustomerName ensures that no value is present for CustomerName, not even an explicit nil
### GetCustomerEmail

`func (o *GetOrder200Response) GetCustomerEmail() string`

GetCustomerEmail returns the CustomerEmail field if non-nil, zero value otherwise.

### GetCustomerEmailOk

`func (o *GetOrder200Response) GetCustomerEmailOk() (*string, bool)`

GetCustomerEmailOk returns a tuple with the CustomerEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerEmail

`func (o *GetOrder200Response) SetCustomerEmail(v string)`

SetCustomerEmail sets CustomerEmail field to given value.

### HasCustomerEmail

`func (o *GetOrder200Response) HasCustomerEmail() bool`

HasCustomerEmail returns a boolean if a field has been set.

### SetCustomerEmailNil

`func (o *GetOrder200Response) SetCustomerEmailNil(b bool)`

 SetCustomerEmailNil sets the value for CustomerEmail to be an explicit nil

### UnsetCustomerEmail
`func (o *GetOrder200Response) UnsetCustomerEmail()`

UnsetCustomerEmail ensures that no value is present for CustomerEmail, not even an explicit nil
### GetShippingAddress

`func (o *GetOrder200Response) GetShippingAddress() CreateOrder201ResponseShippingAddress`

GetShippingAddress returns the ShippingAddress field if non-nil, zero value otherwise.

### GetShippingAddressOk

`func (o *GetOrder200Response) GetShippingAddressOk() (*CreateOrder201ResponseShippingAddress, bool)`

GetShippingAddressOk returns a tuple with the ShippingAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingAddress

`func (o *GetOrder200Response) SetShippingAddress(v CreateOrder201ResponseShippingAddress)`

SetShippingAddress sets ShippingAddress field to given value.

### HasShippingAddress

`func (o *GetOrder200Response) HasShippingAddress() bool`

HasShippingAddress returns a boolean if a field has been set.

### SetShippingAddressNil

`func (o *GetOrder200Response) SetShippingAddressNil(b bool)`

 SetShippingAddressNil sets the value for ShippingAddress to be an explicit nil

### UnsetShippingAddress
`func (o *GetOrder200Response) UnsetShippingAddress()`

UnsetShippingAddress ensures that no value is present for ShippingAddress, not even an explicit nil
### GetOrderLines

`func (o *GetOrder200Response) GetOrderLines() []CreateOrder201ResponseOrderLinesInner`

GetOrderLines returns the OrderLines field if non-nil, zero value otherwise.

### GetOrderLinesOk

`func (o *GetOrder200Response) GetOrderLinesOk() (*[]CreateOrder201ResponseOrderLinesInner, bool)`

GetOrderLinesOk returns a tuple with the OrderLines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderLines

`func (o *GetOrder200Response) SetOrderLines(v []CreateOrder201ResponseOrderLinesInner)`

SetOrderLines sets OrderLines field to given value.


### GetSubtotalAmount

`func (o *GetOrder200Response) GetSubtotalAmount() float32`

GetSubtotalAmount returns the SubtotalAmount field if non-nil, zero value otherwise.

### GetSubtotalAmountOk

`func (o *GetOrder200Response) GetSubtotalAmountOk() (*float32, bool)`

GetSubtotalAmountOk returns a tuple with the SubtotalAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubtotalAmount

`func (o *GetOrder200Response) SetSubtotalAmount(v float32)`

SetSubtotalAmount sets SubtotalAmount field to given value.

### HasSubtotalAmount

`func (o *GetOrder200Response) HasSubtotalAmount() bool`

HasSubtotalAmount returns a boolean if a field has been set.

### SetSubtotalAmountNil

`func (o *GetOrder200Response) SetSubtotalAmountNil(b bool)`

 SetSubtotalAmountNil sets the value for SubtotalAmount to be an explicit nil

### UnsetSubtotalAmount
`func (o *GetOrder200Response) UnsetSubtotalAmount()`

UnsetSubtotalAmount ensures that no value is present for SubtotalAmount, not even an explicit nil
### GetTotalAmount

`func (o *GetOrder200Response) GetTotalAmount() float32`

GetTotalAmount returns the TotalAmount field if non-nil, zero value otherwise.

### GetTotalAmountOk

`func (o *GetOrder200Response) GetTotalAmountOk() (*float32, bool)`

GetTotalAmountOk returns a tuple with the TotalAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalAmount

`func (o *GetOrder200Response) SetTotalAmount(v float32)`

SetTotalAmount sets TotalAmount field to given value.

### HasTotalAmount

`func (o *GetOrder200Response) HasTotalAmount() bool`

HasTotalAmount returns a boolean if a field has been set.

### SetTotalAmountNil

`func (o *GetOrder200Response) SetTotalAmountNil(b bool)`

 SetTotalAmountNil sets the value for TotalAmount to be an explicit nil

### UnsetTotalAmount
`func (o *GetOrder200Response) UnsetTotalAmount()`

UnsetTotalAmount ensures that no value is present for TotalAmount, not even an explicit nil
### GetCurrency

`func (o *GetOrder200Response) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *GetOrder200Response) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *GetOrder200Response) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *GetOrder200Response) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### SetCurrencyNil

`func (o *GetOrder200Response) SetCurrencyNil(b bool)`

 SetCurrencyNil sets the value for Currency to be an explicit nil

### UnsetCurrency
`func (o *GetOrder200Response) UnsetCurrency()`

UnsetCurrency ensures that no value is present for Currency, not even an explicit nil
### GetStatus

`func (o *GetOrder200Response) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *GetOrder200Response) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *GetOrder200Response) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetShippingRuleId

`func (o *GetOrder200Response) GetShippingRuleId() string`

GetShippingRuleId returns the ShippingRuleId field if non-nil, zero value otherwise.

### GetShippingRuleIdOk

`func (o *GetOrder200Response) GetShippingRuleIdOk() (*string, bool)`

GetShippingRuleIdOk returns a tuple with the ShippingRuleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingRuleId

`func (o *GetOrder200Response) SetShippingRuleId(v string)`

SetShippingRuleId sets ShippingRuleId field to given value.

### HasShippingRuleId

`func (o *GetOrder200Response) HasShippingRuleId() bool`

HasShippingRuleId returns a boolean if a field has been set.

### SetShippingRuleIdNil

`func (o *GetOrder200Response) SetShippingRuleIdNil(b bool)`

 SetShippingRuleIdNil sets the value for ShippingRuleId to be an explicit nil

### UnsetShippingRuleId
`func (o *GetOrder200Response) UnsetShippingRuleId()`

UnsetShippingRuleId ensures that no value is present for ShippingRuleId, not even an explicit nil
### GetNotes

`func (o *GetOrder200Response) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *GetOrder200Response) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *GetOrder200Response) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *GetOrder200Response) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *GetOrder200Response) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *GetOrder200Response) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetExternalData

`func (o *GetOrder200Response) GetExternalData() map[string]interface{}`

GetExternalData returns the ExternalData field if non-nil, zero value otherwise.

### GetExternalDataOk

`func (o *GetOrder200Response) GetExternalDataOk() (*map[string]interface{}, bool)`

GetExternalDataOk returns a tuple with the ExternalData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalData

`func (o *GetOrder200Response) SetExternalData(v map[string]interface{})`

SetExternalData sets ExternalData field to given value.

### HasExternalData

`func (o *GetOrder200Response) HasExternalData() bool`

HasExternalData returns a boolean if a field has been set.

### SetExternalDataNil

`func (o *GetOrder200Response) SetExternalDataNil(b bool)`

 SetExternalDataNil sets the value for ExternalData to be an explicit nil

### UnsetExternalData
`func (o *GetOrder200Response) UnsetExternalData()`

UnsetExternalData ensures that no value is present for ExternalData, not even an explicit nil
### GetOrderChannelId

`func (o *GetOrder200Response) GetOrderChannelId() string`

GetOrderChannelId returns the OrderChannelId field if non-nil, zero value otherwise.

### GetOrderChannelIdOk

`func (o *GetOrder200Response) GetOrderChannelIdOk() (*string, bool)`

GetOrderChannelIdOk returns a tuple with the OrderChannelId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderChannelId

`func (o *GetOrder200Response) SetOrderChannelId(v string)`

SetOrderChannelId sets OrderChannelId field to given value.


### GetOrgId

`func (o *GetOrder200Response) GetOrgId() string`

GetOrgId returns the OrgId field if non-nil, zero value otherwise.

### GetOrgIdOk

`func (o *GetOrder200Response) GetOrgIdOk() (*string, bool)`

GetOrgIdOk returns a tuple with the OrgId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrgId

`func (o *GetOrder200Response) SetOrgId(v string)`

SetOrgId sets OrgId field to given value.


### GetCreatedAt

`func (o *GetOrder200Response) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GetOrder200Response) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GetOrder200Response) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *GetOrder200Response) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *GetOrder200Response) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *GetOrder200Response) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetOrderChannel

`func (o *GetOrder200Response) GetOrderChannel() ListOrders200ResponseDataInnerOrderChannel`

GetOrderChannel returns the OrderChannel field if non-nil, zero value otherwise.

### GetOrderChannelOk

`func (o *GetOrder200Response) GetOrderChannelOk() (*ListOrders200ResponseDataInnerOrderChannel, bool)`

GetOrderChannelOk returns a tuple with the OrderChannel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderChannel

`func (o *GetOrder200Response) SetOrderChannel(v ListOrders200ResponseDataInnerOrderChannel)`

SetOrderChannel sets OrderChannel field to given value.


### GetShippingRule

`func (o *GetOrder200Response) GetShippingRule() GetOrder200ResponseShippingRule`

GetShippingRule returns the ShippingRule field if non-nil, zero value otherwise.

### GetShippingRuleOk

`func (o *GetOrder200Response) GetShippingRuleOk() (*GetOrder200ResponseShippingRule, bool)`

GetShippingRuleOk returns a tuple with the ShippingRule field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingRule

`func (o *GetOrder200Response) SetShippingRule(v GetOrder200ResponseShippingRule)`

SetShippingRule sets ShippingRule field to given value.

### HasShippingRule

`func (o *GetOrder200Response) HasShippingRule() bool`

HasShippingRule returns a boolean if a field has been set.

### SetShippingRuleNil

`func (o *GetOrder200Response) SetShippingRuleNil(b bool)`

 SetShippingRuleNil sets the value for ShippingRule to be an explicit nil

### UnsetShippingRule
`func (o *GetOrder200Response) UnsetShippingRule()`

UnsetShippingRule ensures that no value is present for ShippingRule, not even an explicit nil
### GetShipments

`func (o *GetOrder200Response) GetShipments() []GetOrder200ResponseShipmentsInner`

GetShipments returns the Shipments field if non-nil, zero value otherwise.

### GetShipmentsOk

`func (o *GetOrder200Response) GetShipmentsOk() (*[]GetOrder200ResponseShipmentsInner, bool)`

GetShipmentsOk returns a tuple with the Shipments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipments

`func (o *GetOrder200Response) SetShipments(v []GetOrder200ResponseShipmentsInner)`

SetShipments sets Shipments field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


