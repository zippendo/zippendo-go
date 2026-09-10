# GetOrder200ResponseShipmentsInnerParcelsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Parcel ID. | 
**Weight** | **float32** | Parcel weight in the given unit. | 
**WeightUnit** | **string** | Unit of measurement for parcel weight. | 
**Dimensions** | [**CreateShipment201ResponseParcelsInnerDimensions**](CreateShipment201ResponseParcelsInnerDimensions.md) |  | 
**OrderLines** | [**[]GetOrder200ResponseShipmentsInnerParcelsInnerOrderLinesInner**](GetOrder200ResponseShipmentsInnerParcelsInnerOrderLinesInner.md) | Contents of this parcel. | 

## Methods

### NewGetOrder200ResponseShipmentsInnerParcelsInner

`func NewGetOrder200ResponseShipmentsInnerParcelsInner(id string, weight float32, weightUnit string, dimensions CreateShipment201ResponseParcelsInnerDimensions, orderLines []GetOrder200ResponseShipmentsInnerParcelsInnerOrderLinesInner, ) *GetOrder200ResponseShipmentsInnerParcelsInner`

NewGetOrder200ResponseShipmentsInnerParcelsInner instantiates a new GetOrder200ResponseShipmentsInnerParcelsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetOrder200ResponseShipmentsInnerParcelsInnerWithDefaults

`func NewGetOrder200ResponseShipmentsInnerParcelsInnerWithDefaults() *GetOrder200ResponseShipmentsInnerParcelsInner`

NewGetOrder200ResponseShipmentsInnerParcelsInnerWithDefaults instantiates a new GetOrder200ResponseShipmentsInnerParcelsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GetOrder200ResponseShipmentsInnerParcelsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GetOrder200ResponseShipmentsInnerParcelsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GetOrder200ResponseShipmentsInnerParcelsInner) SetId(v string)`

SetId sets Id field to given value.


### GetWeight

`func (o *GetOrder200ResponseShipmentsInnerParcelsInner) GetWeight() float32`

GetWeight returns the Weight field if non-nil, zero value otherwise.

### GetWeightOk

`func (o *GetOrder200ResponseShipmentsInnerParcelsInner) GetWeightOk() (*float32, bool)`

GetWeightOk returns a tuple with the Weight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeight

`func (o *GetOrder200ResponseShipmentsInnerParcelsInner) SetWeight(v float32)`

SetWeight sets Weight field to given value.


### GetWeightUnit

`func (o *GetOrder200ResponseShipmentsInnerParcelsInner) GetWeightUnit() string`

GetWeightUnit returns the WeightUnit field if non-nil, zero value otherwise.

### GetWeightUnitOk

`func (o *GetOrder200ResponseShipmentsInnerParcelsInner) GetWeightUnitOk() (*string, bool)`

GetWeightUnitOk returns a tuple with the WeightUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeightUnit

`func (o *GetOrder200ResponseShipmentsInnerParcelsInner) SetWeightUnit(v string)`

SetWeightUnit sets WeightUnit field to given value.


### GetDimensions

`func (o *GetOrder200ResponseShipmentsInnerParcelsInner) GetDimensions() CreateShipment201ResponseParcelsInnerDimensions`

GetDimensions returns the Dimensions field if non-nil, zero value otherwise.

### GetDimensionsOk

`func (o *GetOrder200ResponseShipmentsInnerParcelsInner) GetDimensionsOk() (*CreateShipment201ResponseParcelsInnerDimensions, bool)`

GetDimensionsOk returns a tuple with the Dimensions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDimensions

`func (o *GetOrder200ResponseShipmentsInnerParcelsInner) SetDimensions(v CreateShipment201ResponseParcelsInnerDimensions)`

SetDimensions sets Dimensions field to given value.


### GetOrderLines

`func (o *GetOrder200ResponseShipmentsInnerParcelsInner) GetOrderLines() []GetOrder200ResponseShipmentsInnerParcelsInnerOrderLinesInner`

GetOrderLines returns the OrderLines field if non-nil, zero value otherwise.

### GetOrderLinesOk

`func (o *GetOrder200ResponseShipmentsInnerParcelsInner) GetOrderLinesOk() (*[]GetOrder200ResponseShipmentsInnerParcelsInnerOrderLinesInner, bool)`

GetOrderLinesOk returns a tuple with the OrderLines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderLines

`func (o *GetOrder200ResponseShipmentsInnerParcelsInner) SetOrderLines(v []GetOrder200ResponseShipmentsInnerParcelsInnerOrderLinesInner)`

SetOrderLines sets OrderLines field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


