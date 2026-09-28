# GetBillingUsage200ResponseZippyCredits

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Used** | **float32** | Zippy credits used this period, included bundle and metered alike | 
**Included** | **float32** | Credits included in the add-on bundle this period | 
**Billed** | **float32** | Credits beyond the bundle, metered this period | 
**Charges** | **float32** | Metered credit charges so far, in øre (whole packs) | 
**Limit** | **float32** | Maximum Zippy credits per month (-1 for unlimited) | 

## Methods

### NewGetBillingUsage200ResponseZippyCredits

`func NewGetBillingUsage200ResponseZippyCredits(used float32, included float32, billed float32, charges float32, limit float32, ) *GetBillingUsage200ResponseZippyCredits`

NewGetBillingUsage200ResponseZippyCredits instantiates a new GetBillingUsage200ResponseZippyCredits object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetBillingUsage200ResponseZippyCreditsWithDefaults

`func NewGetBillingUsage200ResponseZippyCreditsWithDefaults() *GetBillingUsage200ResponseZippyCredits`

NewGetBillingUsage200ResponseZippyCreditsWithDefaults instantiates a new GetBillingUsage200ResponseZippyCredits object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUsed

`func (o *GetBillingUsage200ResponseZippyCredits) GetUsed() float32`

GetUsed returns the Used field if non-nil, zero value otherwise.

### GetUsedOk

`func (o *GetBillingUsage200ResponseZippyCredits) GetUsedOk() (*float32, bool)`

GetUsedOk returns a tuple with the Used field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsed

`func (o *GetBillingUsage200ResponseZippyCredits) SetUsed(v float32)`

SetUsed sets Used field to given value.


### GetIncluded

`func (o *GetBillingUsage200ResponseZippyCredits) GetIncluded() float32`

GetIncluded returns the Included field if non-nil, zero value otherwise.

### GetIncludedOk

`func (o *GetBillingUsage200ResponseZippyCredits) GetIncludedOk() (*float32, bool)`

GetIncludedOk returns a tuple with the Included field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncluded

`func (o *GetBillingUsage200ResponseZippyCredits) SetIncluded(v float32)`

SetIncluded sets Included field to given value.


### GetBilled

`func (o *GetBillingUsage200ResponseZippyCredits) GetBilled() float32`

GetBilled returns the Billed field if non-nil, zero value otherwise.

### GetBilledOk

`func (o *GetBillingUsage200ResponseZippyCredits) GetBilledOk() (*float32, bool)`

GetBilledOk returns a tuple with the Billed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBilled

`func (o *GetBillingUsage200ResponseZippyCredits) SetBilled(v float32)`

SetBilled sets Billed field to given value.


### GetCharges

`func (o *GetBillingUsage200ResponseZippyCredits) GetCharges() float32`

GetCharges returns the Charges field if non-nil, zero value otherwise.

### GetChargesOk

`func (o *GetBillingUsage200ResponseZippyCredits) GetChargesOk() (*float32, bool)`

GetChargesOk returns a tuple with the Charges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCharges

`func (o *GetBillingUsage200ResponseZippyCredits) SetCharges(v float32)`

SetCharges sets Charges field to given value.


### GetLimit

`func (o *GetBillingUsage200ResponseZippyCredits) GetLimit() float32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *GetBillingUsage200ResponseZippyCredits) GetLimitOk() (*float32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *GetBillingUsage200ResponseZippyCredits) SetLimit(v float32)`

SetLimit sets Limit field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


