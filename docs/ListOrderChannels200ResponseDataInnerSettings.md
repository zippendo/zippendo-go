# ListOrderChannels200ResponseDataInnerSettings

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UseWebhooks** | **bool** | Use webhooks for real-time order sync. | [default to true]
**WebhookId** | Pointer to **NullableString** | External webhook identifier for management. | [optional] 
**WebhookIds** | Pointer to **[]int32** | Registered WooCommerce webhook ids. | [optional] 
**WebhookSecretCreatedAt** | Pointer to **NullableTime** | When the custom channel&#39;s webhook signing secret was issued. A non-secret signal so clients can show that a secret exists; the secret itself is never returned after creation. | [optional] 
**SiteUrl** | Pointer to **string** | WooCommerce store URL. | [optional] 
**AutoFulfill** | Pointer to **bool** | Push tracking back to the platform when a shipment is dispatched. Enabled by default (opt-out) — set to false to disable write-back; an unset value still syncs. | [optional] 
**CheckoutTokenCreatedAt** | Pointer to **NullableTime** | When the checkout token was issued (internal; never exposed in API responses). | [optional] 
**AutoSync** | **bool** | Periodically poll the channel for new orders. | [default to false]
**SyncIntervalMinutes** | **int32** | Polling interval in minutes (5-1440). | [default to 15]
**AutoShipOnCreate** | **bool** | Create a shipment automatically when an order arrives. | [default to false]
**DefaultCarrierId** | Pointer to **NullableString** | Default carrier ID for auto-shipping. | [optional] 
**DefaultProductId** | Pointer to **NullableString** | Default carrier product ID for auto-shipping. | [optional] 
**DefaultAddressId** | Pointer to **NullableString** | Default sender address ID for auto-shipping. | [optional] 
**ShippingMethodMappings** | Pointer to [**[]ListOrderChannels200ResponseDataInnerSettingsShippingMethodMappingsInner**](ListOrderChannels200ResponseDataInnerSettingsShippingMethodMappingsInner.md) | Map imported shipping-method titles to shipping rules, for channels without checkout rate integration. | [optional] 
**SyncOnlyUnfulfilled** | **bool** | Only import orders that are not yet fulfilled. | [default to true]
**SyncOrdersSince** | Pointer to **NullableTime** | Only sync orders placed at or after this timestamp. | [optional] 
**ServicePointCount** | **int32** | Number of service points to show at checkout (1-20). | [default to 6]

## Methods

### NewListOrderChannels200ResponseDataInnerSettings

`func NewListOrderChannels200ResponseDataInnerSettings(useWebhooks bool, autoSync bool, syncIntervalMinutes int32, autoShipOnCreate bool, syncOnlyUnfulfilled bool, servicePointCount int32, ) *ListOrderChannels200ResponseDataInnerSettings`

NewListOrderChannels200ResponseDataInnerSettings instantiates a new ListOrderChannels200ResponseDataInnerSettings object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListOrderChannels200ResponseDataInnerSettingsWithDefaults

`func NewListOrderChannels200ResponseDataInnerSettingsWithDefaults() *ListOrderChannels200ResponseDataInnerSettings`

NewListOrderChannels200ResponseDataInnerSettingsWithDefaults instantiates a new ListOrderChannels200ResponseDataInnerSettings object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUseWebhooks

`func (o *ListOrderChannels200ResponseDataInnerSettings) GetUseWebhooks() bool`

GetUseWebhooks returns the UseWebhooks field if non-nil, zero value otherwise.

### GetUseWebhooksOk

`func (o *ListOrderChannels200ResponseDataInnerSettings) GetUseWebhooksOk() (*bool, bool)`

GetUseWebhooksOk returns a tuple with the UseWebhooks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseWebhooks

`func (o *ListOrderChannels200ResponseDataInnerSettings) SetUseWebhooks(v bool)`

SetUseWebhooks sets UseWebhooks field to given value.


### GetWebhookId

`func (o *ListOrderChannels200ResponseDataInnerSettings) GetWebhookId() string`

GetWebhookId returns the WebhookId field if non-nil, zero value otherwise.

### GetWebhookIdOk

`func (o *ListOrderChannels200ResponseDataInnerSettings) GetWebhookIdOk() (*string, bool)`

GetWebhookIdOk returns a tuple with the WebhookId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebhookId

`func (o *ListOrderChannels200ResponseDataInnerSettings) SetWebhookId(v string)`

SetWebhookId sets WebhookId field to given value.

### HasWebhookId

`func (o *ListOrderChannels200ResponseDataInnerSettings) HasWebhookId() bool`

HasWebhookId returns a boolean if a field has been set.

### SetWebhookIdNil

`func (o *ListOrderChannels200ResponseDataInnerSettings) SetWebhookIdNil(b bool)`

 SetWebhookIdNil sets the value for WebhookId to be an explicit nil

### UnsetWebhookId
`func (o *ListOrderChannels200ResponseDataInnerSettings) UnsetWebhookId()`

UnsetWebhookId ensures that no value is present for WebhookId, not even an explicit nil
### GetWebhookIds

`func (o *ListOrderChannels200ResponseDataInnerSettings) GetWebhookIds() []int32`

GetWebhookIds returns the WebhookIds field if non-nil, zero value otherwise.

### GetWebhookIdsOk

`func (o *ListOrderChannels200ResponseDataInnerSettings) GetWebhookIdsOk() (*[]int32, bool)`

GetWebhookIdsOk returns a tuple with the WebhookIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebhookIds

`func (o *ListOrderChannels200ResponseDataInnerSettings) SetWebhookIds(v []int32)`

SetWebhookIds sets WebhookIds field to given value.

### HasWebhookIds

`func (o *ListOrderChannels200ResponseDataInnerSettings) HasWebhookIds() bool`

HasWebhookIds returns a boolean if a field has been set.

### GetWebhookSecretCreatedAt

`func (o *ListOrderChannels200ResponseDataInnerSettings) GetWebhookSecretCreatedAt() time.Time`

GetWebhookSecretCreatedAt returns the WebhookSecretCreatedAt field if non-nil, zero value otherwise.

### GetWebhookSecretCreatedAtOk

`func (o *ListOrderChannels200ResponseDataInnerSettings) GetWebhookSecretCreatedAtOk() (*time.Time, bool)`

GetWebhookSecretCreatedAtOk returns a tuple with the WebhookSecretCreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebhookSecretCreatedAt

`func (o *ListOrderChannels200ResponseDataInnerSettings) SetWebhookSecretCreatedAt(v time.Time)`

SetWebhookSecretCreatedAt sets WebhookSecretCreatedAt field to given value.

### HasWebhookSecretCreatedAt

`func (o *ListOrderChannels200ResponseDataInnerSettings) HasWebhookSecretCreatedAt() bool`

HasWebhookSecretCreatedAt returns a boolean if a field has been set.

### SetWebhookSecretCreatedAtNil

`func (o *ListOrderChannels200ResponseDataInnerSettings) SetWebhookSecretCreatedAtNil(b bool)`

 SetWebhookSecretCreatedAtNil sets the value for WebhookSecretCreatedAt to be an explicit nil

### UnsetWebhookSecretCreatedAt
`func (o *ListOrderChannels200ResponseDataInnerSettings) UnsetWebhookSecretCreatedAt()`

UnsetWebhookSecretCreatedAt ensures that no value is present for WebhookSecretCreatedAt, not even an explicit nil
### GetSiteUrl

`func (o *ListOrderChannels200ResponseDataInnerSettings) GetSiteUrl() string`

GetSiteUrl returns the SiteUrl field if non-nil, zero value otherwise.

### GetSiteUrlOk

`func (o *ListOrderChannels200ResponseDataInnerSettings) GetSiteUrlOk() (*string, bool)`

GetSiteUrlOk returns a tuple with the SiteUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSiteUrl

`func (o *ListOrderChannels200ResponseDataInnerSettings) SetSiteUrl(v string)`

SetSiteUrl sets SiteUrl field to given value.

### HasSiteUrl

`func (o *ListOrderChannels200ResponseDataInnerSettings) HasSiteUrl() bool`

HasSiteUrl returns a boolean if a field has been set.

### GetAutoFulfill

`func (o *ListOrderChannels200ResponseDataInnerSettings) GetAutoFulfill() bool`

GetAutoFulfill returns the AutoFulfill field if non-nil, zero value otherwise.

### GetAutoFulfillOk

`func (o *ListOrderChannels200ResponseDataInnerSettings) GetAutoFulfillOk() (*bool, bool)`

GetAutoFulfillOk returns a tuple with the AutoFulfill field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoFulfill

`func (o *ListOrderChannels200ResponseDataInnerSettings) SetAutoFulfill(v bool)`

SetAutoFulfill sets AutoFulfill field to given value.

### HasAutoFulfill

`func (o *ListOrderChannels200ResponseDataInnerSettings) HasAutoFulfill() bool`

HasAutoFulfill returns a boolean if a field has been set.

### GetCheckoutTokenCreatedAt

`func (o *ListOrderChannels200ResponseDataInnerSettings) GetCheckoutTokenCreatedAt() time.Time`

GetCheckoutTokenCreatedAt returns the CheckoutTokenCreatedAt field if non-nil, zero value otherwise.

### GetCheckoutTokenCreatedAtOk

`func (o *ListOrderChannels200ResponseDataInnerSettings) GetCheckoutTokenCreatedAtOk() (*time.Time, bool)`

GetCheckoutTokenCreatedAtOk returns a tuple with the CheckoutTokenCreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckoutTokenCreatedAt

`func (o *ListOrderChannels200ResponseDataInnerSettings) SetCheckoutTokenCreatedAt(v time.Time)`

SetCheckoutTokenCreatedAt sets CheckoutTokenCreatedAt field to given value.

### HasCheckoutTokenCreatedAt

`func (o *ListOrderChannels200ResponseDataInnerSettings) HasCheckoutTokenCreatedAt() bool`

HasCheckoutTokenCreatedAt returns a boolean if a field has been set.

### SetCheckoutTokenCreatedAtNil

`func (o *ListOrderChannels200ResponseDataInnerSettings) SetCheckoutTokenCreatedAtNil(b bool)`

 SetCheckoutTokenCreatedAtNil sets the value for CheckoutTokenCreatedAt to be an explicit nil

### UnsetCheckoutTokenCreatedAt
`func (o *ListOrderChannels200ResponseDataInnerSettings) UnsetCheckoutTokenCreatedAt()`

UnsetCheckoutTokenCreatedAt ensures that no value is present for CheckoutTokenCreatedAt, not even an explicit nil
### GetAutoSync

`func (o *ListOrderChannels200ResponseDataInnerSettings) GetAutoSync() bool`

GetAutoSync returns the AutoSync field if non-nil, zero value otherwise.

### GetAutoSyncOk

`func (o *ListOrderChannels200ResponseDataInnerSettings) GetAutoSyncOk() (*bool, bool)`

GetAutoSyncOk returns a tuple with the AutoSync field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoSync

`func (o *ListOrderChannels200ResponseDataInnerSettings) SetAutoSync(v bool)`

SetAutoSync sets AutoSync field to given value.


### GetSyncIntervalMinutes

`func (o *ListOrderChannels200ResponseDataInnerSettings) GetSyncIntervalMinutes() int32`

GetSyncIntervalMinutes returns the SyncIntervalMinutes field if non-nil, zero value otherwise.

### GetSyncIntervalMinutesOk

`func (o *ListOrderChannels200ResponseDataInnerSettings) GetSyncIntervalMinutesOk() (*int32, bool)`

GetSyncIntervalMinutesOk returns a tuple with the SyncIntervalMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSyncIntervalMinutes

`func (o *ListOrderChannels200ResponseDataInnerSettings) SetSyncIntervalMinutes(v int32)`

SetSyncIntervalMinutes sets SyncIntervalMinutes field to given value.


### GetAutoShipOnCreate

`func (o *ListOrderChannels200ResponseDataInnerSettings) GetAutoShipOnCreate() bool`

GetAutoShipOnCreate returns the AutoShipOnCreate field if non-nil, zero value otherwise.

### GetAutoShipOnCreateOk

`func (o *ListOrderChannels200ResponseDataInnerSettings) GetAutoShipOnCreateOk() (*bool, bool)`

GetAutoShipOnCreateOk returns a tuple with the AutoShipOnCreate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoShipOnCreate

`func (o *ListOrderChannels200ResponseDataInnerSettings) SetAutoShipOnCreate(v bool)`

SetAutoShipOnCreate sets AutoShipOnCreate field to given value.


### GetDefaultCarrierId

`func (o *ListOrderChannels200ResponseDataInnerSettings) GetDefaultCarrierId() string`

GetDefaultCarrierId returns the DefaultCarrierId field if non-nil, zero value otherwise.

### GetDefaultCarrierIdOk

`func (o *ListOrderChannels200ResponseDataInnerSettings) GetDefaultCarrierIdOk() (*string, bool)`

GetDefaultCarrierIdOk returns a tuple with the DefaultCarrierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultCarrierId

`func (o *ListOrderChannels200ResponseDataInnerSettings) SetDefaultCarrierId(v string)`

SetDefaultCarrierId sets DefaultCarrierId field to given value.

### HasDefaultCarrierId

`func (o *ListOrderChannels200ResponseDataInnerSettings) HasDefaultCarrierId() bool`

HasDefaultCarrierId returns a boolean if a field has been set.

### SetDefaultCarrierIdNil

`func (o *ListOrderChannels200ResponseDataInnerSettings) SetDefaultCarrierIdNil(b bool)`

 SetDefaultCarrierIdNil sets the value for DefaultCarrierId to be an explicit nil

### UnsetDefaultCarrierId
`func (o *ListOrderChannels200ResponseDataInnerSettings) UnsetDefaultCarrierId()`

UnsetDefaultCarrierId ensures that no value is present for DefaultCarrierId, not even an explicit nil
### GetDefaultProductId

`func (o *ListOrderChannels200ResponseDataInnerSettings) GetDefaultProductId() string`

GetDefaultProductId returns the DefaultProductId field if non-nil, zero value otherwise.

### GetDefaultProductIdOk

`func (o *ListOrderChannels200ResponseDataInnerSettings) GetDefaultProductIdOk() (*string, bool)`

GetDefaultProductIdOk returns a tuple with the DefaultProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultProductId

`func (o *ListOrderChannels200ResponseDataInnerSettings) SetDefaultProductId(v string)`

SetDefaultProductId sets DefaultProductId field to given value.

### HasDefaultProductId

`func (o *ListOrderChannels200ResponseDataInnerSettings) HasDefaultProductId() bool`

HasDefaultProductId returns a boolean if a field has been set.

### SetDefaultProductIdNil

`func (o *ListOrderChannels200ResponseDataInnerSettings) SetDefaultProductIdNil(b bool)`

 SetDefaultProductIdNil sets the value for DefaultProductId to be an explicit nil

### UnsetDefaultProductId
`func (o *ListOrderChannels200ResponseDataInnerSettings) UnsetDefaultProductId()`

UnsetDefaultProductId ensures that no value is present for DefaultProductId, not even an explicit nil
### GetDefaultAddressId

`func (o *ListOrderChannels200ResponseDataInnerSettings) GetDefaultAddressId() string`

GetDefaultAddressId returns the DefaultAddressId field if non-nil, zero value otherwise.

### GetDefaultAddressIdOk

`func (o *ListOrderChannels200ResponseDataInnerSettings) GetDefaultAddressIdOk() (*string, bool)`

GetDefaultAddressIdOk returns a tuple with the DefaultAddressId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultAddressId

`func (o *ListOrderChannels200ResponseDataInnerSettings) SetDefaultAddressId(v string)`

SetDefaultAddressId sets DefaultAddressId field to given value.

### HasDefaultAddressId

`func (o *ListOrderChannels200ResponseDataInnerSettings) HasDefaultAddressId() bool`

HasDefaultAddressId returns a boolean if a field has been set.

### SetDefaultAddressIdNil

`func (o *ListOrderChannels200ResponseDataInnerSettings) SetDefaultAddressIdNil(b bool)`

 SetDefaultAddressIdNil sets the value for DefaultAddressId to be an explicit nil

### UnsetDefaultAddressId
`func (o *ListOrderChannels200ResponseDataInnerSettings) UnsetDefaultAddressId()`

UnsetDefaultAddressId ensures that no value is present for DefaultAddressId, not even an explicit nil
### GetShippingMethodMappings

`func (o *ListOrderChannels200ResponseDataInnerSettings) GetShippingMethodMappings() []ListOrderChannels200ResponseDataInnerSettingsShippingMethodMappingsInner`

GetShippingMethodMappings returns the ShippingMethodMappings field if non-nil, zero value otherwise.

### GetShippingMethodMappingsOk

`func (o *ListOrderChannels200ResponseDataInnerSettings) GetShippingMethodMappingsOk() (*[]ListOrderChannels200ResponseDataInnerSettingsShippingMethodMappingsInner, bool)`

GetShippingMethodMappingsOk returns a tuple with the ShippingMethodMappings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingMethodMappings

`func (o *ListOrderChannels200ResponseDataInnerSettings) SetShippingMethodMappings(v []ListOrderChannels200ResponseDataInnerSettingsShippingMethodMappingsInner)`

SetShippingMethodMappings sets ShippingMethodMappings field to given value.

### HasShippingMethodMappings

`func (o *ListOrderChannels200ResponseDataInnerSettings) HasShippingMethodMappings() bool`

HasShippingMethodMappings returns a boolean if a field has been set.

### GetSyncOnlyUnfulfilled

`func (o *ListOrderChannels200ResponseDataInnerSettings) GetSyncOnlyUnfulfilled() bool`

GetSyncOnlyUnfulfilled returns the SyncOnlyUnfulfilled field if non-nil, zero value otherwise.

### GetSyncOnlyUnfulfilledOk

`func (o *ListOrderChannels200ResponseDataInnerSettings) GetSyncOnlyUnfulfilledOk() (*bool, bool)`

GetSyncOnlyUnfulfilledOk returns a tuple with the SyncOnlyUnfulfilled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSyncOnlyUnfulfilled

`func (o *ListOrderChannels200ResponseDataInnerSettings) SetSyncOnlyUnfulfilled(v bool)`

SetSyncOnlyUnfulfilled sets SyncOnlyUnfulfilled field to given value.


### GetSyncOrdersSince

`func (o *ListOrderChannels200ResponseDataInnerSettings) GetSyncOrdersSince() time.Time`

GetSyncOrdersSince returns the SyncOrdersSince field if non-nil, zero value otherwise.

### GetSyncOrdersSinceOk

`func (o *ListOrderChannels200ResponseDataInnerSettings) GetSyncOrdersSinceOk() (*time.Time, bool)`

GetSyncOrdersSinceOk returns a tuple with the SyncOrdersSince field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSyncOrdersSince

`func (o *ListOrderChannels200ResponseDataInnerSettings) SetSyncOrdersSince(v time.Time)`

SetSyncOrdersSince sets SyncOrdersSince field to given value.

### HasSyncOrdersSince

`func (o *ListOrderChannels200ResponseDataInnerSettings) HasSyncOrdersSince() bool`

HasSyncOrdersSince returns a boolean if a field has been set.

### SetSyncOrdersSinceNil

`func (o *ListOrderChannels200ResponseDataInnerSettings) SetSyncOrdersSinceNil(b bool)`

 SetSyncOrdersSinceNil sets the value for SyncOrdersSince to be an explicit nil

### UnsetSyncOrdersSince
`func (o *ListOrderChannels200ResponseDataInnerSettings) UnsetSyncOrdersSince()`

UnsetSyncOrdersSince ensures that no value is present for SyncOrdersSince, not even an explicit nil
### GetServicePointCount

`func (o *ListOrderChannels200ResponseDataInnerSettings) GetServicePointCount() int32`

GetServicePointCount returns the ServicePointCount field if non-nil, zero value otherwise.

### GetServicePointCountOk

`func (o *ListOrderChannels200ResponseDataInnerSettings) GetServicePointCountOk() (*int32, bool)`

GetServicePointCountOk returns a tuple with the ServicePointCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServicePointCount

`func (o *ListOrderChannels200ResponseDataInnerSettings) SetServicePointCount(v int32)`

SetServicePointCount sets ServicePointCount field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


