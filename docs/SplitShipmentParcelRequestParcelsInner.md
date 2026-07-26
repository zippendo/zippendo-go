# SplitShipmentParcelRequestParcelsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Existing parcel ID to update. Omit to create a new parcel. | [optional] 
**OrderLines** | [**[]BatchSplitShipmentRequestShipmentsInnerOrderLinesInner**](BatchSplitShipmentRequestShipmentsInnerOrderLinesInner.md) | Order lines and quantities to place in this parcel. | 

## Methods

### NewSplitShipmentParcelRequestParcelsInner

`func NewSplitShipmentParcelRequestParcelsInner(orderLines []BatchSplitShipmentRequestShipmentsInnerOrderLinesInner, ) *SplitShipmentParcelRequestParcelsInner`

NewSplitShipmentParcelRequestParcelsInner instantiates a new SplitShipmentParcelRequestParcelsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSplitShipmentParcelRequestParcelsInnerWithDefaults

`func NewSplitShipmentParcelRequestParcelsInnerWithDefaults() *SplitShipmentParcelRequestParcelsInner`

NewSplitShipmentParcelRequestParcelsInnerWithDefaults instantiates a new SplitShipmentParcelRequestParcelsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SplitShipmentParcelRequestParcelsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SplitShipmentParcelRequestParcelsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SplitShipmentParcelRequestParcelsInner) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SplitShipmentParcelRequestParcelsInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetOrderLines

`func (o *SplitShipmentParcelRequestParcelsInner) GetOrderLines() []BatchSplitShipmentRequestShipmentsInnerOrderLinesInner`

GetOrderLines returns the OrderLines field if non-nil, zero value otherwise.

### GetOrderLinesOk

`func (o *SplitShipmentParcelRequestParcelsInner) GetOrderLinesOk() (*[]BatchSplitShipmentRequestShipmentsInnerOrderLinesInner, bool)`

GetOrderLinesOk returns a tuple with the OrderLines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderLines

`func (o *SplitShipmentParcelRequestParcelsInner) SetOrderLines(v []BatchSplitShipmentRequestShipmentsInnerOrderLinesInner)`

SetOrderLines sets OrderLines field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


