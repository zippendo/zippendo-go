# ListAddresses200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**[]ListAddresses200ResponseDataInner**](ListAddresses200ResponseDataInner.md) | Page of results | 
**Total** | **float32** | Total matching items across all pages | 
**Page** | **float32** | Current page number (1-based) | 
**Limit** | **float32** | Items per page | 
**TotalPages** | **float32** | Total number of pages | 

## Methods

### NewListAddresses200Response

`func NewListAddresses200Response(data []ListAddresses200ResponseDataInner, total float32, page float32, limit float32, totalPages float32, ) *ListAddresses200Response`

NewListAddresses200Response instantiates a new ListAddresses200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListAddresses200ResponseWithDefaults

`func NewListAddresses200ResponseWithDefaults() *ListAddresses200Response`

NewListAddresses200ResponseWithDefaults instantiates a new ListAddresses200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ListAddresses200Response) GetData() []ListAddresses200ResponseDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ListAddresses200Response) GetDataOk() (*[]ListAddresses200ResponseDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ListAddresses200Response) SetData(v []ListAddresses200ResponseDataInner)`

SetData sets Data field to given value.


### GetTotal

`func (o *ListAddresses200Response) GetTotal() float32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *ListAddresses200Response) GetTotalOk() (*float32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *ListAddresses200Response) SetTotal(v float32)`

SetTotal sets Total field to given value.


### GetPage

`func (o *ListAddresses200Response) GetPage() float32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *ListAddresses200Response) GetPageOk() (*float32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *ListAddresses200Response) SetPage(v float32)`

SetPage sets Page field to given value.


### GetLimit

`func (o *ListAddresses200Response) GetLimit() float32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *ListAddresses200Response) GetLimitOk() (*float32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *ListAddresses200Response) SetLimit(v float32)`

SetLimit sets Limit field to given value.


### GetTotalPages

`func (o *ListAddresses200Response) GetTotalPages() float32`

GetTotalPages returns the TotalPages field if non-nil, zero value otherwise.

### GetTotalPagesOk

`func (o *ListAddresses200Response) GetTotalPagesOk() (*float32, bool)`

GetTotalPagesOk returns a tuple with the TotalPages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPages

`func (o *ListAddresses200Response) SetTotalPages(v float32)`

SetTotalPages sets TotalPages field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


