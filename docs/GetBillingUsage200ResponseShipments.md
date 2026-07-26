# GetBillingUsage200ResponseShipments

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Used** | **float32** | Shipments created this period | 
**Included** | **float32** | Shipments included in the plan | 
**Overage** | **float32** | Shipments above the included allowance | 
**OverageCharges** | **float32** | Overage charges so far, in øre | 

## Methods

### NewGetBillingUsage200ResponseShipments

`func NewGetBillingUsage200ResponseShipments(used float32, included float32, overage float32, overageCharges float32, ) *GetBillingUsage200ResponseShipments`

NewGetBillingUsage200ResponseShipments instantiates a new GetBillingUsage200ResponseShipments object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetBillingUsage200ResponseShipmentsWithDefaults

`func NewGetBillingUsage200ResponseShipmentsWithDefaults() *GetBillingUsage200ResponseShipments`

NewGetBillingUsage200ResponseShipmentsWithDefaults instantiates a new GetBillingUsage200ResponseShipments object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUsed

`func (o *GetBillingUsage200ResponseShipments) GetUsed() float32`

GetUsed returns the Used field if non-nil, zero value otherwise.

### GetUsedOk

`func (o *GetBillingUsage200ResponseShipments) GetUsedOk() (*float32, bool)`

GetUsedOk returns a tuple with the Used field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsed

`func (o *GetBillingUsage200ResponseShipments) SetUsed(v float32)`

SetUsed sets Used field to given value.


### GetIncluded

`func (o *GetBillingUsage200ResponseShipments) GetIncluded() float32`

GetIncluded returns the Included field if non-nil, zero value otherwise.

### GetIncludedOk

`func (o *GetBillingUsage200ResponseShipments) GetIncludedOk() (*float32, bool)`

GetIncludedOk returns a tuple with the Included field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncluded

`func (o *GetBillingUsage200ResponseShipments) SetIncluded(v float32)`

SetIncluded sets Included field to given value.


### GetOverage

`func (o *GetBillingUsage200ResponseShipments) GetOverage() float32`

GetOverage returns the Overage field if non-nil, zero value otherwise.

### GetOverageOk

`func (o *GetBillingUsage200ResponseShipments) GetOverageOk() (*float32, bool)`

GetOverageOk returns a tuple with the Overage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverage

`func (o *GetBillingUsage200ResponseShipments) SetOverage(v float32)`

SetOverage sets Overage field to given value.


### GetOverageCharges

`func (o *GetBillingUsage200ResponseShipments) GetOverageCharges() float32`

GetOverageCharges returns the OverageCharges field if non-nil, zero value otherwise.

### GetOverageChargesOk

`func (o *GetBillingUsage200ResponseShipments) GetOverageChargesOk() (*float32, bool)`

GetOverageChargesOk returns a tuple with the OverageCharges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverageCharges

`func (o *GetBillingUsage200ResponseShipments) SetOverageCharges(v float32)`

SetOverageCharges sets OverageCharges field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


