# CreateOrderChannelRequestSettings

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UseWebhooks** | Pointer to **bool** | Use webhooks for real-time order sync. | [optional] [default to true]
**SiteUrl** | Pointer to **string** | WooCommerce store URL. | [optional] 
**AutoFulfill** | Pointer to **bool** | Push tracking back to the platform when a shipment is dispatched. Enabled by default (opt-out) — set to false to disable write-back; an unset value still syncs. | [optional] 
**AutoSync** | Pointer to **bool** | Periodically poll the channel for new orders. | [optional] [default to false]
**SyncIntervalMinutes** | Pointer to **int32** | Polling interval in minutes (5-1440). | [optional] [default to 15]
**AutoShipOnCreate** | Pointer to **bool** | Create a shipment automatically when an order arrives. | [optional] [default to false]
**DefaultCarrierId** | Pointer to **NullableString** | Default carrier ID for auto-shipping. | [optional] 
**DefaultProductId** | Pointer to **NullableString** | Default carrier product ID for auto-shipping. | [optional] 
**DefaultAddressId** | Pointer to **NullableString** | Default sender address ID for auto-shipping. | [optional] 
**ShippingMethodMappings** | Pointer to [**[]CreateOrderChannelRequestSettingsShippingMethodMappingsInner**](CreateOrderChannelRequestSettingsShippingMethodMappingsInner.md) | Map imported shipping-method titles to shipping rules, for channels without checkout rate integration. | [optional] 
**SyncOnlyUnfulfilled** | Pointer to **bool** | Only import orders that are not yet fulfilled. | [optional] [default to true]
**SyncOrdersSince** | Pointer to **NullableTime** | Only sync orders placed at or after this timestamp. | [optional] 
**ServicePointCount** | Pointer to **int32** | Number of service points to show at checkout (1-20). | [optional] [default to 6]

## Methods

### NewCreateOrderChannelRequestSettings

`func NewCreateOrderChannelRequestSettings() *CreateOrderChannelRequestSettings`

NewCreateOrderChannelRequestSettings instantiates a new CreateOrderChannelRequestSettings object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateOrderChannelRequestSettingsWithDefaults

`func NewCreateOrderChannelRequestSettingsWithDefaults() *CreateOrderChannelRequestSettings`

NewCreateOrderChannelRequestSettingsWithDefaults instantiates a new CreateOrderChannelRequestSettings object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUseWebhooks

`func (o *CreateOrderChannelRequestSettings) GetUseWebhooks() bool`

GetUseWebhooks returns the UseWebhooks field if non-nil, zero value otherwise.

### GetUseWebhooksOk

`func (o *CreateOrderChannelRequestSettings) GetUseWebhooksOk() (*bool, bool)`

GetUseWebhooksOk returns a tuple with the UseWebhooks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseWebhooks

`func (o *CreateOrderChannelRequestSettings) SetUseWebhooks(v bool)`

SetUseWebhooks sets UseWebhooks field to given value.

### HasUseWebhooks

`func (o *CreateOrderChannelRequestSettings) HasUseWebhooks() bool`

HasUseWebhooks returns a boolean if a field has been set.

### GetSiteUrl

`func (o *CreateOrderChannelRequestSettings) GetSiteUrl() string`

GetSiteUrl returns the SiteUrl field if non-nil, zero value otherwise.

### GetSiteUrlOk

`func (o *CreateOrderChannelRequestSettings) GetSiteUrlOk() (*string, bool)`

GetSiteUrlOk returns a tuple with the SiteUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSiteUrl

`func (o *CreateOrderChannelRequestSettings) SetSiteUrl(v string)`

SetSiteUrl sets SiteUrl field to given value.

### HasSiteUrl

`func (o *CreateOrderChannelRequestSettings) HasSiteUrl() bool`

HasSiteUrl returns a boolean if a field has been set.

### GetAutoFulfill

`func (o *CreateOrderChannelRequestSettings) GetAutoFulfill() bool`

GetAutoFulfill returns the AutoFulfill field if non-nil, zero value otherwise.

### GetAutoFulfillOk

`func (o *CreateOrderChannelRequestSettings) GetAutoFulfillOk() (*bool, bool)`

GetAutoFulfillOk returns a tuple with the AutoFulfill field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoFulfill

`func (o *CreateOrderChannelRequestSettings) SetAutoFulfill(v bool)`

SetAutoFulfill sets AutoFulfill field to given value.

### HasAutoFulfill

`func (o *CreateOrderChannelRequestSettings) HasAutoFulfill() bool`

HasAutoFulfill returns a boolean if a field has been set.

### GetAutoSync

`func (o *CreateOrderChannelRequestSettings) GetAutoSync() bool`

GetAutoSync returns the AutoSync field if non-nil, zero value otherwise.

### GetAutoSyncOk

`func (o *CreateOrderChannelRequestSettings) GetAutoSyncOk() (*bool, bool)`

GetAutoSyncOk returns a tuple with the AutoSync field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoSync

`func (o *CreateOrderChannelRequestSettings) SetAutoSync(v bool)`

SetAutoSync sets AutoSync field to given value.

### HasAutoSync

`func (o *CreateOrderChannelRequestSettings) HasAutoSync() bool`

HasAutoSync returns a boolean if a field has been set.

### GetSyncIntervalMinutes

`func (o *CreateOrderChannelRequestSettings) GetSyncIntervalMinutes() int32`

GetSyncIntervalMinutes returns the SyncIntervalMinutes field if non-nil, zero value otherwise.

### GetSyncIntervalMinutesOk

`func (o *CreateOrderChannelRequestSettings) GetSyncIntervalMinutesOk() (*int32, bool)`

GetSyncIntervalMinutesOk returns a tuple with the SyncIntervalMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSyncIntervalMinutes

`func (o *CreateOrderChannelRequestSettings) SetSyncIntervalMinutes(v int32)`

SetSyncIntervalMinutes sets SyncIntervalMinutes field to given value.

### HasSyncIntervalMinutes

`func (o *CreateOrderChannelRequestSettings) HasSyncIntervalMinutes() bool`

HasSyncIntervalMinutes returns a boolean if a field has been set.

### GetAutoShipOnCreate

`func (o *CreateOrderChannelRequestSettings) GetAutoShipOnCreate() bool`

GetAutoShipOnCreate returns the AutoShipOnCreate field if non-nil, zero value otherwise.

### GetAutoShipOnCreateOk

`func (o *CreateOrderChannelRequestSettings) GetAutoShipOnCreateOk() (*bool, bool)`

GetAutoShipOnCreateOk returns a tuple with the AutoShipOnCreate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoShipOnCreate

`func (o *CreateOrderChannelRequestSettings) SetAutoShipOnCreate(v bool)`

SetAutoShipOnCreate sets AutoShipOnCreate field to given value.

### HasAutoShipOnCreate

`func (o *CreateOrderChannelRequestSettings) HasAutoShipOnCreate() bool`

HasAutoShipOnCreate returns a boolean if a field has been set.

### GetDefaultCarrierId

`func (o *CreateOrderChannelRequestSettings) GetDefaultCarrierId() string`

GetDefaultCarrierId returns the DefaultCarrierId field if non-nil, zero value otherwise.

### GetDefaultCarrierIdOk

`func (o *CreateOrderChannelRequestSettings) GetDefaultCarrierIdOk() (*string, bool)`

GetDefaultCarrierIdOk returns a tuple with the DefaultCarrierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultCarrierId

`func (o *CreateOrderChannelRequestSettings) SetDefaultCarrierId(v string)`

SetDefaultCarrierId sets DefaultCarrierId field to given value.

### HasDefaultCarrierId

`func (o *CreateOrderChannelRequestSettings) HasDefaultCarrierId() bool`

HasDefaultCarrierId returns a boolean if a field has been set.

### SetDefaultCarrierIdNil

`func (o *CreateOrderChannelRequestSettings) SetDefaultCarrierIdNil(b bool)`

 SetDefaultCarrierIdNil sets the value for DefaultCarrierId to be an explicit nil

### UnsetDefaultCarrierId
`func (o *CreateOrderChannelRequestSettings) UnsetDefaultCarrierId()`

UnsetDefaultCarrierId ensures that no value is present for DefaultCarrierId, not even an explicit nil
### GetDefaultProductId

`func (o *CreateOrderChannelRequestSettings) GetDefaultProductId() string`

GetDefaultProductId returns the DefaultProductId field if non-nil, zero value otherwise.

### GetDefaultProductIdOk

`func (o *CreateOrderChannelRequestSettings) GetDefaultProductIdOk() (*string, bool)`

GetDefaultProductIdOk returns a tuple with the DefaultProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultProductId

`func (o *CreateOrderChannelRequestSettings) SetDefaultProductId(v string)`

SetDefaultProductId sets DefaultProductId field to given value.

### HasDefaultProductId

`func (o *CreateOrderChannelRequestSettings) HasDefaultProductId() bool`

HasDefaultProductId returns a boolean if a field has been set.

### SetDefaultProductIdNil

`func (o *CreateOrderChannelRequestSettings) SetDefaultProductIdNil(b bool)`

 SetDefaultProductIdNil sets the value for DefaultProductId to be an explicit nil

### UnsetDefaultProductId
`func (o *CreateOrderChannelRequestSettings) UnsetDefaultProductId()`

UnsetDefaultProductId ensures that no value is present for DefaultProductId, not even an explicit nil
### GetDefaultAddressId

`func (o *CreateOrderChannelRequestSettings) GetDefaultAddressId() string`

GetDefaultAddressId returns the DefaultAddressId field if non-nil, zero value otherwise.

### GetDefaultAddressIdOk

`func (o *CreateOrderChannelRequestSettings) GetDefaultAddressIdOk() (*string, bool)`

GetDefaultAddressIdOk returns a tuple with the DefaultAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultAddressId

`func (o *CreateOrderChannelRequestSettings) SetDefaultAddressId(v string)`

SetDefaultAddressId sets DefaultAddressId field to given value.

### HasDefaultAddressId

`func (o *CreateOrderChannelRequestSettings) HasDefaultAddressId() bool`

HasDefaultAddressId returns a boolean if a field has been set.

### SetDefaultAddressIdNil

`func (o *CreateOrderChannelRequestSettings) SetDefaultAddressIdNil(b bool)`

 SetDefaultAddressIdNil sets the value for DefaultAddressId to be an explicit nil

### UnsetDefaultAddressId
`func (o *CreateOrderChannelRequestSettings) UnsetDefaultAddressId()`

UnsetDefaultAddressId ensures that no value is present for DefaultAddressId, not even an explicit nil
### GetShippingMethodMappings

`func (o *CreateOrderChannelRequestSettings) GetShippingMethodMappings() []CreateOrderChannelRequestSettingsShippingMethodMappingsInner`

GetShippingMethodMappings returns the ShippingMethodMappings field if non-nil, zero value otherwise.

### GetShippingMethodMappingsOk

`func (o *CreateOrderChannelRequestSettings) GetShippingMethodMappingsOk() (*[]CreateOrderChannelRequestSettingsShippingMethodMappingsInner, bool)`

GetShippingMethodMappingsOk returns a tuple with the ShippingMethodMappings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingMethodMappings

`func (o *CreateOrderChannelRequestSettings) SetShippingMethodMappings(v []CreateOrderChannelRequestSettingsShippingMethodMappingsInner)`

SetShippingMethodMappings sets ShippingMethodMappings field to given value.

### HasShippingMethodMappings

`func (o *CreateOrderChannelRequestSettings) HasShippingMethodMappings() bool`

HasShippingMethodMappings returns a boolean if a field has been set.

### GetSyncOnlyUnfulfilled

`func (o *CreateOrderChannelRequestSettings) GetSyncOnlyUnfulfilled() bool`

GetSyncOnlyUnfulfilled returns the SyncOnlyUnfulfilled field if non-nil, zero value otherwise.

### GetSyncOnlyUnfulfilledOk

`func (o *CreateOrderChannelRequestSettings) GetSyncOnlyUnfulfilledOk() (*bool, bool)`

GetSyncOnlyUnfulfilledOk returns a tuple with the SyncOnlyUnfulfilled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSyncOnlyUnfulfilled

`func (o *CreateOrderChannelRequestSettings) SetSyncOnlyUnfulfilled(v bool)`

SetSyncOnlyUnfulfilled sets SyncOnlyUnfulfilled field to given value.

### HasSyncOnlyUnfulfilled

`func (o *CreateOrderChannelRequestSettings) HasSyncOnlyUnfulfilled() bool`

HasSyncOnlyUnfulfilled returns a boolean if a field has been set.

### GetSyncOrdersSince

`func (o *CreateOrderChannelRequestSettings) GetSyncOrdersSince() time.Time`

GetSyncOrdersSince returns the SyncOrdersSince field if non-nil, zero value otherwise.

### GetSyncOrdersSinceOk

`func (o *CreateOrderChannelRequestSettings) GetSyncOrdersSinceOk() (*time.Time, bool)`

GetSyncOrdersSinceOk returns a tuple with the SyncOrdersSince field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSyncOrdersSince

`func (o *CreateOrderChannelRequestSettings) SetSyncOrdersSince(v time.Time)`

SetSyncOrdersSince sets SyncOrdersSince field to given value.

### HasSyncOrdersSince

`func (o *CreateOrderChannelRequestSettings) HasSyncOrdersSince() bool`

HasSyncOrdersSince returns a boolean if a field has been set.

### SetSyncOrdersSinceNil

`func (o *CreateOrderChannelRequestSettings) SetSyncOrdersSinceNil(b bool)`

 SetSyncOrdersSinceNil sets the value for SyncOrdersSince to be an explicit nil

### UnsetSyncOrdersSince
`func (o *CreateOrderChannelRequestSettings) UnsetSyncOrdersSince()`

UnsetSyncOrdersSince ensures that no value is present for SyncOrdersSince, not even an explicit nil
### GetServicePointCount

`func (o *CreateOrderChannelRequestSettings) GetServicePointCount() int32`

GetServicePointCount returns the ServicePointCount field if non-nil, zero value otherwise.

### GetServicePointCountOk

`func (o *CreateOrderChannelRequestSettings) GetServicePointCountOk() (*int32, bool)`

GetServicePointCountOk returns a tuple with the ServicePointCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServicePointCount

`func (o *CreateOrderChannelRequestSettings) SetServicePointCount(v int32)`

SetServicePointCount sets ServicePointCount field to given value.

### HasServicePointCount

`func (o *CreateOrderChannelRequestSettings) HasServicePointCount() bool`

HasServicePointCount returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


