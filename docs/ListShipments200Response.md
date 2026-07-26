# ListShipments200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**[]ListShipments200ResponseDataInner**](ListShipments200ResponseDataInner.md) | Page of results | 
**Total** | **float32** | Total matching items across all pages | 
**Page** | **float32** | Current page number (1-based) | 
**Limit** | **float32** | Items per page | 
**TotalPages** | **float32** | Total number of pages | 

## Methods

### NewListShipments200Response

`func NewListShipments200Response(data []ListShipments200ResponseDataInner, total float32, page float32, limit float32, totalPages float32, ) *ListShipments200Response`

NewListShipments200Response instantiates a new ListShipments200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListShipments200ResponseWithDefaults

`func NewListShipments200ResponseWithDefaults() *ListShipments200Response`

NewListShipments200ResponseWithDefaults instantiates a new ListShipments200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ListShipments200Response) GetData() []ListShipments200ResponseDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ListShipments200Response) GetDataOk() (*[]ListShipments200ResponseDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ListShipments200Response) SetData(v []ListShipments200ResponseDataInner)`

SetData sets Data field to given value.


### GetTotal

`func (o *ListShipments200Response) GetTotal() float32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *ListShipments200Response) GetTotalOk() (*float32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *ListShipments200Response) SetTotal(v float32)`

SetTotal sets Total field to given value.


### GetPage

`func (o *ListShipments200Response) GetPage() float32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *ListShipments200Response) GetPageOk() (*float32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *ListShipments200Response) SetPage(v float32)`

SetPage sets Page field to given value.


### GetLimit

`func (o *ListShipments200Response) GetLimit() float32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *ListShipments200Response) GetLimitOk() (*float32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *ListShipments200Response) SetLimit(v float32)`

SetLimit sets Limit field to given value.


### GetTotalPages

`func (o *ListShipments200Response) GetTotalPages() float32`

GetTotalPages returns the TotalPages field if non-nil, zero value otherwise.

### GetTotalPagesOk

`func (o *ListShipments200Response) GetTotalPagesOk() (*float32, bool)`

GetTotalPagesOk returns a tuple with the TotalPages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPages

`func (o *ListShipments200Response) SetTotalPages(v float32)`

SetTotalPages sets TotalPages field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


