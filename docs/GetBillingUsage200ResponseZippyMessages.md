# GetBillingUsage200ResponseZippyMessages

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Used** | **float32** | Zippy messages used this period | 
**Charges** | **float32** | Zippy message charges so far, in øre | 
**Limit** | **float32** | Maximum Zippy messages per month (-1 for unlimited) | 

## Methods

### NewGetBillingUsage200ResponseZippyMessages

`func NewGetBillingUsage200ResponseZippyMessages(used float32, charges float32, limit float32, ) *GetBillingUsage200ResponseZippyMessages`

NewGetBillingUsage200ResponseZippyMessages instantiates a new GetBillingUsage200ResponseZippyMessages object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetBillingUsage200ResponseZippyMessagesWithDefaults

`func NewGetBillingUsage200ResponseZippyMessagesWithDefaults() *GetBillingUsage200ResponseZippyMessages`

NewGetBillingUsage200ResponseZippyMessagesWithDefaults instantiates a new GetBillingUsage200ResponseZippyMessages object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUsed

`func (o *GetBillingUsage200ResponseZippyMessages) GetUsed() float32`

GetUsed returns the Used field if non-nil, zero value otherwise.

### GetUsedOk

`func (o *GetBillingUsage200ResponseZippyMessages) GetUsedOk() (*float32, bool)`

GetUsedOk returns a tuple with the Used field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsed

`func (o *GetBillingUsage200ResponseZippyMessages) SetUsed(v float32)`

SetUsed sets Used field to given value.


### GetCharges

`func (o *GetBillingUsage200ResponseZippyMessages) GetCharges() float32`

GetCharges returns the Charges field if non-nil, zero value otherwise.

### GetChargesOk

`func (o *GetBillingUsage200ResponseZippyMessages) GetChargesOk() (*float32, bool)`

GetChargesOk returns a tuple with the Charges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCharges

`func (o *GetBillingUsage200ResponseZippyMessages) SetCharges(v float32)`

SetCharges sets Charges field to given value.


### GetLimit

`func (o *GetBillingUsage200ResponseZippyMessages) GetLimit() float32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *GetBillingUsage200ResponseZippyMessages) GetLimitOk() (*float32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *GetBillingUsage200ResponseZippyMessages) SetLimit(v float32)`

SetLimit sets Limit field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


