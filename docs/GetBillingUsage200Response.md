# GetBillingUsage200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CurrentPeriod** | [**GetBillingUsage200ResponseCurrentPeriod**](GetBillingUsage200ResponseCurrentPeriod.md) |  | 
**Shipments** | [**GetBillingUsage200ResponseShipments**](GetBillingUsage200ResponseShipments.md) |  | 
**Limits** | [**GetBillingUsage200ResponseLimits**](GetBillingUsage200ResponseLimits.md) |  | 
**AddOns** | [**[]GetBillingUsage200ResponseAddOnsInner**](GetBillingUsage200ResponseAddOnsInner.md) | Active add-ons on the subscription | 
**ZippyMessages** | Pointer to [**GetBillingUsage200ResponseZippyMessages**](GetBillingUsage200ResponseZippyMessages.md) |  | [optional] 

## Methods

### NewGetBillingUsage200Response

`func NewGetBillingUsage200Response(currentPeriod GetBillingUsage200ResponseCurrentPeriod, shipments GetBillingUsage200ResponseShipments, limits GetBillingUsage200ResponseLimits, addOns []GetBillingUsage200ResponseAddOnsInner, ) *GetBillingUsage200Response`

NewGetBillingUsage200Response instantiates a new GetBillingUsage200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetBillingUsage200ResponseWithDefaults

`func NewGetBillingUsage200ResponseWithDefaults() *GetBillingUsage200Response`

NewGetBillingUsage200ResponseWithDefaults instantiates a new GetBillingUsage200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrentPeriod

`func (o *GetBillingUsage200Response) GetCurrentPeriod() GetBillingUsage200ResponseCurrentPeriod`

GetCurrentPeriod returns the CurrentPeriod field if non-nil, zero value otherwise.

### GetCurrentPeriodOk

`func (o *GetBillingUsage200Response) GetCurrentPeriodOk() (*GetBillingUsage200ResponseCurrentPeriod, bool)`

GetCurrentPeriodOk returns a tuple with the CurrentPeriod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentPeriod

`func (o *GetBillingUsage200Response) SetCurrentPeriod(v GetBillingUsage200ResponseCurrentPeriod)`

SetCurrentPeriod sets CurrentPeriod field to given value.


### GetShipments

`func (o *GetBillingUsage200Response) GetShipments() GetBillingUsage200ResponseShipments`

GetShipments returns the Shipments field if non-nil, zero value otherwise.

### GetShipmentsOk

`func (o *GetBillingUsage200Response) GetShipmentsOk() (*GetBillingUsage200ResponseShipments, bool)`

GetShipmentsOk returns a tuple with the Shipments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipments

`func (o *GetBillingUsage200Response) SetShipments(v GetBillingUsage200ResponseShipments)`

SetShipments sets Shipments field to given value.


### GetLimits

`func (o *GetBillingUsage200Response) GetLimits() GetBillingUsage200ResponseLimits`

GetLimits returns the Limits field if non-nil, zero value otherwise.

### GetLimitsOk

`func (o *GetBillingUsage200Response) GetLimitsOk() (*GetBillingUsage200ResponseLimits, bool)`

GetLimitsOk returns a tuple with the Limits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimits

`func (o *GetBillingUsage200Response) SetLimits(v GetBillingUsage200ResponseLimits)`

SetLimits sets Limits field to given value.


### GetAddOns

`func (o *GetBillingUsage200Response) GetAddOns() []GetBillingUsage200ResponseAddOnsInner`

GetAddOns returns the AddOns field if non-nil, zero value otherwise.

### GetAddOnsOk

`func (o *GetBillingUsage200Response) GetAddOnsOk() (*[]GetBillingUsage200ResponseAddOnsInner, bool)`

GetAddOnsOk returns a tuple with the AddOns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddOns

`func (o *GetBillingUsage200Response) SetAddOns(v []GetBillingUsage200ResponseAddOnsInner)`

SetAddOns sets AddOns field to given value.


### GetZippyMessages

`func (o *GetBillingUsage200Response) GetZippyMessages() GetBillingUsage200ResponseZippyMessages`

GetZippyMessages returns the ZippyMessages field if non-nil, zero value otherwise.

### GetZippyMessagesOk

`func (o *GetBillingUsage200Response) GetZippyMessagesOk() (*GetBillingUsage200ResponseZippyMessages, bool)`

GetZippyMessagesOk returns a tuple with the ZippyMessages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZippyMessages

`func (o *GetBillingUsage200Response) SetZippyMessages(v GetBillingUsage200ResponseZippyMessages)`

SetZippyMessages sets ZippyMessages field to given value.

### HasZippyMessages

`func (o *GetBillingUsage200Response) HasZippyMessages() bool`

HasZippyMessages returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


