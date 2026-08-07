# ListShipments200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Unique shipment identifier. | 
**Reference** | **string** | Customer-facing shipment reference. | 
**Type** | **string** | Direction of the shipment relative to the organization. | 
**CarrierSettings** | [**ListShipments200ResponseDataInnerCarrierSettings**](ListShipments200ResponseDataInnerCarrierSettings.md) |  | 
**Status** | **string** | Lifecycle status of the shipment. | 
**BrandId** | **NullableString** | Brand this record belongs to, or null when it is organization-wide | 
**Address** | Pointer to [**NullableListShipments200ResponseDataInnerAddress**](ListShipments200ResponseDataInnerAddress.md) |  | [optional] 
**CreatedAt** | **string** | Timestamp when the shipment was created. | 
**UpdatedAt** | **string** | Timestamp when the shipment was last updated. | 

## Methods

### NewListShipments200ResponseDataInner

`func NewListShipments200ResponseDataInner(id string, reference string, type_ string, carrierSettings ListShipments200ResponseDataInnerCarrierSettings, status string, brandId NullableString, createdAt string, updatedAt string, ) *ListShipments200ResponseDataInner`

NewListShipments200ResponseDataInner instantiates a new ListShipments200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListShipments200ResponseDataInnerWithDefaults

`func NewListShipments200ResponseDataInnerWithDefaults() *ListShipments200ResponseDataInner`

NewListShipments200ResponseDataInnerWithDefaults instantiates a new ListShipments200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ListShipments200ResponseDataInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ListShipments200ResponseDataInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ListShipments200ResponseDataInner) SetId(v string)`

SetId sets Id field to given value.


### GetReference

`func (o *ListShipments200ResponseDataInner) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *ListShipments200ResponseDataInner) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *ListShipments200ResponseDataInner) SetReference(v string)`

SetReference sets Reference field to given value.


### GetType

`func (o *ListShipments200ResponseDataInner) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ListShipments200ResponseDataInner) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ListShipments200ResponseDataInner) SetType(v string)`

SetType sets Type field to given value.


### GetCarrierSettings

`func (o *ListShipments200ResponseDataInner) GetCarrierSettings() ListShipments200ResponseDataInnerCarrierSettings`

GetCarrierSettings returns the CarrierSettings field if non-nil, zero value otherwise.

### GetCarrierSettingsOk

`func (o *ListShipments200ResponseDataInner) GetCarrierSettingsOk() (*ListShipments200ResponseDataInnerCarrierSettings, bool)`

GetCarrierSettingsOk returns a tuple with the CarrierSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierSettings

`func (o *ListShipments200ResponseDataInner) SetCarrierSettings(v ListShipments200ResponseDataInnerCarrierSettings)`

SetCarrierSettings sets CarrierSettings field to given value.


### GetStatus

`func (o *ListShipments200ResponseDataInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ListShipments200ResponseDataInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ListShipments200ResponseDataInner) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetBrandId

`func (o *ListShipments200ResponseDataInner) GetBrandId() string`

GetBrandId returns the BrandId field if non-nil, zero value otherwise.

### GetBrandIdOk

`func (o *ListShipments200ResponseDataInner) GetBrandIdOk() (*string, bool)`

GetBrandIdOk returns a tuple with the BrandId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandId

`func (o *ListShipments200ResponseDataInner) SetBrandId(v string)`

SetBrandId sets BrandId field to given value.


### SetBrandIdNil

`func (o *ListShipments200ResponseDataInner) SetBrandIdNil(b bool)`

 SetBrandIdNil sets the value for BrandId to be an explicit nil

### UnsetBrandId
`func (o *ListShipments200ResponseDataInner) UnsetBrandId()`

UnsetBrandId ensures that no value is present for BrandId, not even an explicit nil
### GetAddress

`func (o *ListShipments200ResponseDataInner) GetAddress() ListShipments200ResponseDataInnerAddress`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *ListShipments200ResponseDataInner) GetAddressOk() (*ListShipments200ResponseDataInnerAddress, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *ListShipments200ResponseDataInner) SetAddress(v ListShipments200ResponseDataInnerAddress)`

SetAddress sets Address field to given value.

### HasAddress

`func (o *ListShipments200ResponseDataInner) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### SetAddressNil

`func (o *ListShipments200ResponseDataInner) SetAddressNil(b bool)`

 SetAddressNil sets the value for Address to be an explicit nil

### UnsetAddress
`func (o *ListShipments200ResponseDataInner) UnsetAddress()`

UnsetAddress ensures that no value is present for Address, not even an explicit nil
### GetCreatedAt

`func (o *ListShipments200ResponseDataInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ListShipments200ResponseDataInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ListShipments200ResponseDataInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *ListShipments200ResponseDataInner) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ListShipments200ResponseDataInner) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ListShipments200ResponseDataInner) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


