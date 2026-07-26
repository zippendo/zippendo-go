# ListOrgWebhookDeliveries200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**[]ListOrgWebhookDeliveries200ResponseDataInner**](ListOrgWebhookDeliveries200ResponseDataInner.md) | Page of results | 
**Total** | **float32** | Total matching items across all pages | 
**Page** | **float32** | Current page number (1-based) | 
**Limit** | **float32** | Items per page | 
**TotalPages** | **float32** | Total number of pages | 

## Methods

### NewListOrgWebhookDeliveries200Response

`func NewListOrgWebhookDeliveries200Response(data []ListOrgWebhookDeliveries200ResponseDataInner, total float32, page float32, limit float32, totalPages float32, ) *ListOrgWebhookDeliveries200Response`

NewListOrgWebhookDeliveries200Response instantiates a new ListOrgWebhookDeliveries200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListOrgWebhookDeliveries200ResponseWithDefaults

`func NewListOrgWebhookDeliveries200ResponseWithDefaults() *ListOrgWebhookDeliveries200Response`

NewListOrgWebhookDeliveries200ResponseWithDefaults instantiates a new ListOrgWebhookDeliveries200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ListOrgWebhookDeliveries200Response) GetData() []ListOrgWebhookDeliveries200ResponseDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ListOrgWebhookDeliveries200Response) GetDataOk() (*[]ListOrgWebhookDeliveries200ResponseDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ListOrgWebhookDeliveries200Response) SetData(v []ListOrgWebhookDeliveries200ResponseDataInner)`

SetData sets Data field to given value.


### GetTotal

`func (o *ListOrgWebhookDeliveries200Response) GetTotal() float32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *ListOrgWebhookDeliveries200Response) GetTotalOk() (*float32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *ListOrgWebhookDeliveries200Response) SetTotal(v float32)`

SetTotal sets Total field to given value.


### GetPage

`func (o *ListOrgWebhookDeliveries200Response) GetPage() float32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *ListOrgWebhookDeliveries200Response) GetPageOk() (*float32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *ListOrgWebhookDeliveries200Response) SetPage(v float32)`

SetPage sets Page field to given value.


### GetLimit

`func (o *ListOrgWebhookDeliveries200Response) GetLimit() float32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *ListOrgWebhookDeliveries200Response) GetLimitOk() (*float32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *ListOrgWebhookDeliveries200Response) SetLimit(v float32)`

SetLimit sets Limit field to given value.


### GetTotalPages

`func (o *ListOrgWebhookDeliveries200Response) GetTotalPages() float32`

GetTotalPages returns the TotalPages field if non-nil, zero value otherwise.

### GetTotalPagesOk

`func (o *ListOrgWebhookDeliveries200Response) GetTotalPagesOk() (*float32, bool)`

GetTotalPagesOk returns a tuple with the TotalPages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPages

`func (o *ListOrgWebhookDeliveries200Response) SetTotalPages(v float32)`

SetTotalPages sets TotalPages field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


