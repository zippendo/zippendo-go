# CreateShippingQuote200ResponseRatesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ServiceName** | **string** | Display name of the shipping option | 
**ServiceCode** | **string** | Unique identifier for this shipping option | 
**TotalPrice** | **string** | Total shipping price in cents as string | 
**Currency** | **string** | ISO 4217 currency code | 
**Description** | Pointer to **string** | Optional description | [optional] 
**MinDeliveryDate** | Pointer to **string** | Minimum delivery date (ISO 8601) | [optional] 
**MaxDeliveryDate** | Pointer to **string** | Maximum delivery date (ISO 8601) | [optional] 
**CarrierName** | Pointer to **string** | Carrier display name | [optional] 
**CarrierSlug** | Pointer to **string** | Carrier slug identifier | [optional] 
**ProductId** | Pointer to **string** | Carrier product ID | [optional] 
**ShippingRuleId** | **string** | Shipping rule ID that generated this rate | 

## Methods

### NewCreateShippingQuote200ResponseRatesInner

`func NewCreateShippingQuote200ResponseRatesInner(serviceName string, serviceCode string, totalPrice string, currency string, shippingRuleId string, ) *CreateShippingQuote200ResponseRatesInner`

NewCreateShippingQuote200ResponseRatesInner instantiates a new CreateShippingQuote200ResponseRatesInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateShippingQuote200ResponseRatesInnerWithDefaults

`func NewCreateShippingQuote200ResponseRatesInnerWithDefaults() *CreateShippingQuote200ResponseRatesInner`

NewCreateShippingQuote200ResponseRatesInnerWithDefaults instantiates a new CreateShippingQuote200ResponseRatesInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetServiceName

`func (o *CreateShippingQuote200ResponseRatesInner) GetServiceName() string`

GetServiceName returns the ServiceName field if non-nil, zero value otherwise.

### GetServiceNameOk

`func (o *CreateShippingQuote200ResponseRatesInner) GetServiceNameOk() (*string, bool)`

GetServiceNameOk returns a tuple with the ServiceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceName

`func (o *CreateShippingQuote200ResponseRatesInner) SetServiceName(v string)`

SetServiceName sets ServiceName field to given value.


### GetServiceCode

`func (o *CreateShippingQuote200ResponseRatesInner) GetServiceCode() string`

GetServiceCode returns the ServiceCode field if non-nil, zero value otherwise.

### GetServiceCodeOk

`func (o *CreateShippingQuote200ResponseRatesInner) GetServiceCodeOk() (*string, bool)`

GetServiceCodeOk returns a tuple with the ServiceCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceCode

`func (o *CreateShippingQuote200ResponseRatesInner) SetServiceCode(v string)`

SetServiceCode sets ServiceCode field to given value.


### GetTotalPrice

`func (o *CreateShippingQuote200ResponseRatesInner) GetTotalPrice() string`

GetTotalPrice returns the TotalPrice field if non-nil, zero value otherwise.

### GetTotalPriceOk

`func (o *CreateShippingQuote200ResponseRatesInner) GetTotalPriceOk() (*string, bool)`

GetTotalPriceOk returns a tuple with the TotalPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPrice

`func (o *CreateShippingQuote200ResponseRatesInner) SetTotalPrice(v string)`

SetTotalPrice sets TotalPrice field to given value.


### GetCurrency

`func (o *CreateShippingQuote200ResponseRatesInner) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *CreateShippingQuote200ResponseRatesInner) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *CreateShippingQuote200ResponseRatesInner) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetDescription

`func (o *CreateShippingQuote200ResponseRatesInner) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateShippingQuote200ResponseRatesInner) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateShippingQuote200ResponseRatesInner) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CreateShippingQuote200ResponseRatesInner) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetMinDeliveryDate

`func (o *CreateShippingQuote200ResponseRatesInner) GetMinDeliveryDate() string`

GetMinDeliveryDate returns the MinDeliveryDate field if non-nil, zero value otherwise.

### GetMinDeliveryDateOk

`func (o *CreateShippingQuote200ResponseRatesInner) GetMinDeliveryDateOk() (*string, bool)`

GetMinDeliveryDateOk returns a tuple with the MinDeliveryDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinDeliveryDate

`func (o *CreateShippingQuote200ResponseRatesInner) SetMinDeliveryDate(v string)`

SetMinDeliveryDate sets MinDeliveryDate field to given value.

### HasMinDeliveryDate

`func (o *CreateShippingQuote200ResponseRatesInner) HasMinDeliveryDate() bool`

HasMinDeliveryDate returns a boolean if a field has been set.

### GetMaxDeliveryDate

`func (o *CreateShippingQuote200ResponseRatesInner) GetMaxDeliveryDate() string`

GetMaxDeliveryDate returns the MaxDeliveryDate field if non-nil, zero value otherwise.

### GetMaxDeliveryDateOk

`func (o *CreateShippingQuote200ResponseRatesInner) GetMaxDeliveryDateOk() (*string, bool)`

GetMaxDeliveryDateOk returns a tuple with the MaxDeliveryDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxDeliveryDate

`func (o *CreateShippingQuote200ResponseRatesInner) SetMaxDeliveryDate(v string)`

SetMaxDeliveryDate sets MaxDeliveryDate field to given value.

### HasMaxDeliveryDate

`func (o *CreateShippingQuote200ResponseRatesInner) HasMaxDeliveryDate() bool`

HasMaxDeliveryDate returns a boolean if a field has been set.

### GetCarrierName

`func (o *CreateShippingQuote200ResponseRatesInner) GetCarrierName() string`

GetCarrierName returns the CarrierName field if non-nil, zero value otherwise.

### GetCarrierNameOk

`func (o *CreateShippingQuote200ResponseRatesInner) GetCarrierNameOk() (*string, bool)`

GetCarrierNameOk returns a tuple with the CarrierName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierName

`func (o *CreateShippingQuote200ResponseRatesInner) SetCarrierName(v string)`

SetCarrierName sets CarrierName field to given value.

### HasCarrierName

`func (o *CreateShippingQuote200ResponseRatesInner) HasCarrierName() bool`

HasCarrierName returns a boolean if a field has been set.

### GetCarrierSlug

`func (o *CreateShippingQuote200ResponseRatesInner) GetCarrierSlug() string`

GetCarrierSlug returns the CarrierSlug field if non-nil, zero value otherwise.

### GetCarrierSlugOk

`func (o *CreateShippingQuote200ResponseRatesInner) GetCarrierSlugOk() (*string, bool)`

GetCarrierSlugOk returns a tuple with the CarrierSlug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierSlug

`func (o *CreateShippingQuote200ResponseRatesInner) SetCarrierSlug(v string)`

SetCarrierSlug sets CarrierSlug field to given value.

### HasCarrierSlug

`func (o *CreateShippingQuote200ResponseRatesInner) HasCarrierSlug() bool`

HasCarrierSlug returns a boolean if a field has been set.

### GetProductId

`func (o *CreateShippingQuote200ResponseRatesInner) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *CreateShippingQuote200ResponseRatesInner) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *CreateShippingQuote200ResponseRatesInner) SetProductId(v string)`

SetProductId sets ProductId field to given value.

### HasProductId

`func (o *CreateShippingQuote200ResponseRatesInner) HasProductId() bool`

HasProductId returns a boolean if a field has been set.

### GetShippingRuleId

`func (o *CreateShippingQuote200ResponseRatesInner) GetShippingRuleId() string`

GetShippingRuleId returns the ShippingRuleId field if non-nil, zero value otherwise.

### GetShippingRuleIdOk

`func (o *CreateShippingQuote200ResponseRatesInner) GetShippingRuleIdOk() (*string, bool)`

GetShippingRuleIdOk returns a tuple with the ShippingRuleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingRuleId

`func (o *CreateShippingQuote200ResponseRatesInner) SetShippingRuleId(v string)`

SetShippingRuleId sets ShippingRuleId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


