# CreateShipment201ResponseDocumentsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Unique document identifier. | 
**ShipmentId** | **string** | Identifier of the shipment this document belongs to. | 
**DocumentType** | **string** | Type of shipment document. | 
**Format** | **string** | File format of the document content. | 
**Content** | **string** | Base64-encoded document/label content. | 
**Size** | **string** | Physical print size of the document. | [default to "A4"]
**CreatedAt** | **string** | Timestamp when the document was created. | 
**UpdatedAt** | **string** | Timestamp when the document was last updated. | 

## Methods

### NewCreateShipment201ResponseDocumentsInner

`func NewCreateShipment201ResponseDocumentsInner(id string, shipmentId string, documentType string, format string, content string, size string, createdAt string, updatedAt string, ) *CreateShipment201ResponseDocumentsInner`

NewCreateShipment201ResponseDocumentsInner instantiates a new CreateShipment201ResponseDocumentsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateShipment201ResponseDocumentsInnerWithDefaults

`func NewCreateShipment201ResponseDocumentsInnerWithDefaults() *CreateShipment201ResponseDocumentsInner`

NewCreateShipment201ResponseDocumentsInnerWithDefaults instantiates a new CreateShipment201ResponseDocumentsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreateShipment201ResponseDocumentsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateShipment201ResponseDocumentsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateShipment201ResponseDocumentsInner) SetId(v string)`

SetId sets Id field to given value.


### GetShipmentId

`func (o *CreateShipment201ResponseDocumentsInner) GetShipmentId() string`

GetShipmentId returns the ShipmentId field if non-nil, zero value otherwise.

### GetShipmentIdOk

`func (o *CreateShipment201ResponseDocumentsInner) GetShipmentIdOk() (*string, bool)`

GetShipmentIdOk returns a tuple with the ShipmentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipmentId

`func (o *CreateShipment201ResponseDocumentsInner) SetShipmentId(v string)`

SetShipmentId sets ShipmentId field to given value.


### GetDocumentType

`func (o *CreateShipment201ResponseDocumentsInner) GetDocumentType() string`

GetDocumentType returns the DocumentType field if non-nil, zero value otherwise.

### GetDocumentTypeOk

`func (o *CreateShipment201ResponseDocumentsInner) GetDocumentTypeOk() (*string, bool)`

GetDocumentTypeOk returns a tuple with the DocumentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocumentType

`func (o *CreateShipment201ResponseDocumentsInner) SetDocumentType(v string)`

SetDocumentType sets DocumentType field to given value.


### GetFormat

`func (o *CreateShipment201ResponseDocumentsInner) GetFormat() string`

GetFormat returns the Format field if non-nil, zero value otherwise.

### GetFormatOk

`func (o *CreateShipment201ResponseDocumentsInner) GetFormatOk() (*string, bool)`

GetFormatOk returns a tuple with the Format field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormat

`func (o *CreateShipment201ResponseDocumentsInner) SetFormat(v string)`

SetFormat sets Format field to given value.


### GetContent

`func (o *CreateShipment201ResponseDocumentsInner) GetContent() string`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *CreateShipment201ResponseDocumentsInner) GetContentOk() (*string, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *CreateShipment201ResponseDocumentsInner) SetContent(v string)`

SetContent sets Content field to given value.


### GetSize

`func (o *CreateShipment201ResponseDocumentsInner) GetSize() string`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *CreateShipment201ResponseDocumentsInner) GetSizeOk() (*string, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *CreateShipment201ResponseDocumentsInner) SetSize(v string)`

SetSize sets Size field to given value.


### GetCreatedAt

`func (o *CreateShipment201ResponseDocumentsInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CreateShipment201ResponseDocumentsInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CreateShipment201ResponseDocumentsInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *CreateShipment201ResponseDocumentsInner) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *CreateShipment201ResponseDocumentsInner) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *CreateShipment201ResponseDocumentsInner) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


