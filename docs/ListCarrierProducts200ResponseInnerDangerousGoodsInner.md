# ListCarrierProducts200ResponseInnerDangerousGoodsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Kind** | **string** | &#x60;limited_quantity&#x60;: dangerous goods packed in limited quantities (LQ). &#x60;regulated&#x60;: fully regulated dangerous goods (ADR). | 
**ServiceId** | **string** | The service that declares these dangerous goods to the carrier. | 
**Parameters** | [**ListCarrierProducts200ResponseInnerDangerousGoodsInnerParameters**](ListCarrierProducts200ResponseInnerDangerousGoodsInnerParameters.md) |  | 
**OwnedParameters** | Pointer to **[]string** | Every additional parameter that describes the declared goods, including those &#x60;parameters&#x60; does not fill. A declaration replaces them all, so a value saved for other goods is never sent. | [optional] 
**SingleParcel** | Pointer to **bool** | The carrier takes this declaration on a shipment of one parcel only. | [optional] 

## Methods

### NewListCarrierProducts200ResponseInnerDangerousGoodsInner

`func NewListCarrierProducts200ResponseInnerDangerousGoodsInner(kind string, serviceId string, parameters ListCarrierProducts200ResponseInnerDangerousGoodsInnerParameters, ) *ListCarrierProducts200ResponseInnerDangerousGoodsInner`

NewListCarrierProducts200ResponseInnerDangerousGoodsInner instantiates a new ListCarrierProducts200ResponseInnerDangerousGoodsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListCarrierProducts200ResponseInnerDangerousGoodsInnerWithDefaults

`func NewListCarrierProducts200ResponseInnerDangerousGoodsInnerWithDefaults() *ListCarrierProducts200ResponseInnerDangerousGoodsInner`

NewListCarrierProducts200ResponseInnerDangerousGoodsInnerWithDefaults instantiates a new ListCarrierProducts200ResponseInnerDangerousGoodsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKind

`func (o *ListCarrierProducts200ResponseInnerDangerousGoodsInner) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *ListCarrierProducts200ResponseInnerDangerousGoodsInner) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *ListCarrierProducts200ResponseInnerDangerousGoodsInner) SetKind(v string)`

SetKind sets Kind field to given value.


### GetServiceId

`func (o *ListCarrierProducts200ResponseInnerDangerousGoodsInner) GetServiceId() string`

GetServiceId returns the ServiceId field if non-nil, zero value otherwise.

### GetServiceIdOk

`func (o *ListCarrierProducts200ResponseInnerDangerousGoodsInner) GetServiceIdOk() (*string, bool)`

GetServiceIdOk returns a tuple with the ServiceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceId

`func (o *ListCarrierProducts200ResponseInnerDangerousGoodsInner) SetServiceId(v string)`

SetServiceId sets ServiceId field to given value.


### GetParameters

`func (o *ListCarrierProducts200ResponseInnerDangerousGoodsInner) GetParameters() ListCarrierProducts200ResponseInnerDangerousGoodsInnerParameters`

GetParameters returns the Parameters field if non-nil, zero value otherwise.

### GetParametersOk

`func (o *ListCarrierProducts200ResponseInnerDangerousGoodsInner) GetParametersOk() (*ListCarrierProducts200ResponseInnerDangerousGoodsInnerParameters, bool)`

GetParametersOk returns a tuple with the Parameters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParameters

`func (o *ListCarrierProducts200ResponseInnerDangerousGoodsInner) SetParameters(v ListCarrierProducts200ResponseInnerDangerousGoodsInnerParameters)`

SetParameters sets Parameters field to given value.


### GetOwnedParameters

`func (o *ListCarrierProducts200ResponseInnerDangerousGoodsInner) GetOwnedParameters() []string`

GetOwnedParameters returns the OwnedParameters field if non-nil, zero value otherwise.

### GetOwnedParametersOk

`func (o *ListCarrierProducts200ResponseInnerDangerousGoodsInner) GetOwnedParametersOk() (*[]string, bool)`

GetOwnedParametersOk returns a tuple with the OwnedParameters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnedParameters

`func (o *ListCarrierProducts200ResponseInnerDangerousGoodsInner) SetOwnedParameters(v []string)`

SetOwnedParameters sets OwnedParameters field to given value.

### HasOwnedParameters

`func (o *ListCarrierProducts200ResponseInnerDangerousGoodsInner) HasOwnedParameters() bool`

HasOwnedParameters returns a boolean if a field has been set.

### GetSingleParcel

`func (o *ListCarrierProducts200ResponseInnerDangerousGoodsInner) GetSingleParcel() bool`

GetSingleParcel returns the SingleParcel field if non-nil, zero value otherwise.

### GetSingleParcelOk

`func (o *ListCarrierProducts200ResponseInnerDangerousGoodsInner) GetSingleParcelOk() (*bool, bool)`

GetSingleParcelOk returns a tuple with the SingleParcel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSingleParcel

`func (o *ListCarrierProducts200ResponseInnerDangerousGoodsInner) SetSingleParcel(v bool)`

SetSingleParcel sets SingleParcel field to given value.

### HasSingleParcel

`func (o *ListCarrierProducts200ResponseInnerDangerousGoodsInner) HasSingleParcel() bool`

HasSingleParcel returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


