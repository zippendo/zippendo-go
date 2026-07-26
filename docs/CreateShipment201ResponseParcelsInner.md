# CreateShipment201ResponseParcelsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Unique parcel identifier. | [optional] 
**Weight** | **float32** | Parcel weight in the given weight unit. | 
**WeightUnit** | **string** | Unit of measurement for parcel weight. | 
**Dimensions** | [**CreateShipment201ResponseParcelsInnerDimensions**](CreateShipment201ResponseParcelsInnerDimensions.md) |  | 
**OrderLines** | [**[]CreateShipment201ResponseParcelsInnerOrderLinesInner**](CreateShipment201ResponseParcelsInnerOrderLinesInner.md) | Order lines contained in this parcel. | 
**TrackingNumber** | Pointer to **NullableString** | Carrier tracking number for this parcel. | [optional] 
**TrackingUrl** | Pointer to **NullableString** | Public carrier tracking URL for this parcel. | [optional] 
**LabelFreeCode** | Pointer to **NullableString** | Label-free drop-off code for the parcel. | [optional] 
**QrCodeLink** | Pointer to **NullableString** | DEPRECATED — use &#x60;qrCodeDataUri&#x60; (embeddable data URI) or &#x60;qrCodeUrl&#x60; (hosted link). Catch-all that carries whichever applies, kept populated for backwards compatibility during the migration and until it is disabled. | [optional] 
**QrCodeDataUri** | Pointer to **NullableString** | Embeddable &#x60;data:&#x60; URI of the QR code image for label-free drop-off — base64 image bytes you can drop straight into an &lt;img&gt;/email. Null when the carrier returns a hosted link instead (see &#x60;qrCodeUrl&#x60;). | [optional] 
**QrCodeUrl** | Pointer to **NullableString** | Carrier-hosted URL of the QR code image for label-free drop-off, returned by carriers (e.g. Bring) that link to the image rather than embedding it. Null when the carrier returns embeddable bytes (see &#x60;qrCodeDataUri&#x60;). | [optional] 

## Methods

### NewCreateShipment201ResponseParcelsInner

`func NewCreateShipment201ResponseParcelsInner(weight float32, weightUnit string, dimensions CreateShipment201ResponseParcelsInnerDimensions, orderLines []CreateShipment201ResponseParcelsInnerOrderLinesInner, ) *CreateShipment201ResponseParcelsInner`

NewCreateShipment201ResponseParcelsInner instantiates a new CreateShipment201ResponseParcelsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateShipment201ResponseParcelsInnerWithDefaults

`func NewCreateShipment201ResponseParcelsInnerWithDefaults() *CreateShipment201ResponseParcelsInner`

NewCreateShipment201ResponseParcelsInnerWithDefaults instantiates a new CreateShipment201ResponseParcelsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreateShipment201ResponseParcelsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateShipment201ResponseParcelsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateShipment201ResponseParcelsInner) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *CreateShipment201ResponseParcelsInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetWeight

`func (o *CreateShipment201ResponseParcelsInner) GetWeight() float32`

GetWeight returns the Weight field if non-nil, zero value otherwise.

### GetWeightOk

`func (o *CreateShipment201ResponseParcelsInner) GetWeightOk() (*float32, bool)`

GetWeightOk returns a tuple with the Weight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeight

`func (o *CreateShipment201ResponseParcelsInner) SetWeight(v float32)`

SetWeight sets Weight field to given value.


### GetWeightUnit

`func (o *CreateShipment201ResponseParcelsInner) GetWeightUnit() string`

GetWeightUnit returns the WeightUnit field if non-nil, zero value otherwise.

### GetWeightUnitOk

`func (o *CreateShipment201ResponseParcelsInner) GetWeightUnitOk() (*string, bool)`

GetWeightUnitOk returns a tuple with the WeightUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeightUnit

`func (o *CreateShipment201ResponseParcelsInner) SetWeightUnit(v string)`

SetWeightUnit sets WeightUnit field to given value.


### GetDimensions

`func (o *CreateShipment201ResponseParcelsInner) GetDimensions() CreateShipment201ResponseParcelsInnerDimensions`

GetDimensions returns the Dimensions field if non-nil, zero value otherwise.

### GetDimensionsOk

`func (o *CreateShipment201ResponseParcelsInner) GetDimensionsOk() (*CreateShipment201ResponseParcelsInnerDimensions, bool)`

GetDimensionsOk returns a tuple with the Dimensions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDimensions

`func (o *CreateShipment201ResponseParcelsInner) SetDimensions(v CreateShipment201ResponseParcelsInnerDimensions)`

SetDimensions sets Dimensions field to given value.


### GetOrderLines

`func (o *CreateShipment201ResponseParcelsInner) GetOrderLines() []CreateShipment201ResponseParcelsInnerOrderLinesInner`

GetOrderLines returns the OrderLines field if non-nil, zero value otherwise.

### GetOrderLinesOk

`func (o *CreateShipment201ResponseParcelsInner) GetOrderLinesOk() (*[]CreateShipment201ResponseParcelsInnerOrderLinesInner, bool)`

GetOrderLinesOk returns a tuple with the OrderLines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderLines

`func (o *CreateShipment201ResponseParcelsInner) SetOrderLines(v []CreateShipment201ResponseParcelsInnerOrderLinesInner)`

SetOrderLines sets OrderLines field to given value.


### GetTrackingNumber

`func (o *CreateShipment201ResponseParcelsInner) GetTrackingNumber() string`

GetTrackingNumber returns the TrackingNumber field if non-nil, zero value otherwise.

### GetTrackingNumberOk

`func (o *CreateShipment201ResponseParcelsInner) GetTrackingNumberOk() (*string, bool)`

GetTrackingNumberOk returns a tuple with the TrackingNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingNumber

`func (o *CreateShipment201ResponseParcelsInner) SetTrackingNumber(v string)`

SetTrackingNumber sets TrackingNumber field to given value.

### HasTrackingNumber

`func (o *CreateShipment201ResponseParcelsInner) HasTrackingNumber() bool`

HasTrackingNumber returns a boolean if a field has been set.

### SetTrackingNumberNil

`func (o *CreateShipment201ResponseParcelsInner) SetTrackingNumberNil(b bool)`

 SetTrackingNumberNil sets the value for TrackingNumber to be an explicit nil

### UnsetTrackingNumber
`func (o *CreateShipment201ResponseParcelsInner) UnsetTrackingNumber()`

UnsetTrackingNumber ensures that no value is present for TrackingNumber, not even an explicit nil
### GetTrackingUrl

`func (o *CreateShipment201ResponseParcelsInner) GetTrackingUrl() string`

GetTrackingUrl returns the TrackingUrl field if non-nil, zero value otherwise.

### GetTrackingUrlOk

`func (o *CreateShipment201ResponseParcelsInner) GetTrackingUrlOk() (*string, bool)`

GetTrackingUrlOk returns a tuple with the TrackingUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingUrl

`func (o *CreateShipment201ResponseParcelsInner) SetTrackingUrl(v string)`

SetTrackingUrl sets TrackingUrl field to given value.

### HasTrackingUrl

`func (o *CreateShipment201ResponseParcelsInner) HasTrackingUrl() bool`

HasTrackingUrl returns a boolean if a field has been set.

### SetTrackingUrlNil

`func (o *CreateShipment201ResponseParcelsInner) SetTrackingUrlNil(b bool)`

 SetTrackingUrlNil sets the value for TrackingUrl to be an explicit nil

### UnsetTrackingUrl
`func (o *CreateShipment201ResponseParcelsInner) UnsetTrackingUrl()`

UnsetTrackingUrl ensures that no value is present for TrackingUrl, not even an explicit nil
### GetLabelFreeCode

`func (o *CreateShipment201ResponseParcelsInner) GetLabelFreeCode() string`

GetLabelFreeCode returns the LabelFreeCode field if non-nil, zero value otherwise.

### GetLabelFreeCodeOk

`func (o *CreateShipment201ResponseParcelsInner) GetLabelFreeCodeOk() (*string, bool)`

GetLabelFreeCodeOk returns a tuple with the LabelFreeCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabelFreeCode

`func (o *CreateShipment201ResponseParcelsInner) SetLabelFreeCode(v string)`

SetLabelFreeCode sets LabelFreeCode field to given value.

### HasLabelFreeCode

`func (o *CreateShipment201ResponseParcelsInner) HasLabelFreeCode() bool`

HasLabelFreeCode returns a boolean if a field has been set.

### SetLabelFreeCodeNil

`func (o *CreateShipment201ResponseParcelsInner) SetLabelFreeCodeNil(b bool)`

 SetLabelFreeCodeNil sets the value for LabelFreeCode to be an explicit nil

### UnsetLabelFreeCode
`func (o *CreateShipment201ResponseParcelsInner) UnsetLabelFreeCode()`

UnsetLabelFreeCode ensures that no value is present for LabelFreeCode, not even an explicit nil
### GetQrCodeLink

`func (o *CreateShipment201ResponseParcelsInner) GetQrCodeLink() string`

GetQrCodeLink returns the QrCodeLink field if non-nil, zero value otherwise.

### GetQrCodeLinkOk

`func (o *CreateShipment201ResponseParcelsInner) GetQrCodeLinkOk() (*string, bool)`

GetQrCodeLinkOk returns a tuple with the QrCodeLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQrCodeLink

`func (o *CreateShipment201ResponseParcelsInner) SetQrCodeLink(v string)`

SetQrCodeLink sets QrCodeLink field to given value.

### HasQrCodeLink

`func (o *CreateShipment201ResponseParcelsInner) HasQrCodeLink() bool`

HasQrCodeLink returns a boolean if a field has been set.

### SetQrCodeLinkNil

`func (o *CreateShipment201ResponseParcelsInner) SetQrCodeLinkNil(b bool)`

 SetQrCodeLinkNil sets the value for QrCodeLink to be an explicit nil

### UnsetQrCodeLink
`func (o *CreateShipment201ResponseParcelsInner) UnsetQrCodeLink()`

UnsetQrCodeLink ensures that no value is present for QrCodeLink, not even an explicit nil
### GetQrCodeDataUri

`func (o *CreateShipment201ResponseParcelsInner) GetQrCodeDataUri() string`

GetQrCodeDataUri returns the QrCodeDataUri field if non-nil, zero value otherwise.

### GetQrCodeDataUriOk

`func (o *CreateShipment201ResponseParcelsInner) GetQrCodeDataUriOk() (*string, bool)`

GetQrCodeDataUriOk returns a tuple with the QrCodeDataUri field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQrCodeDataUri

`func (o *CreateShipment201ResponseParcelsInner) SetQrCodeDataUri(v string)`

SetQrCodeDataUri sets QrCodeDataUri field to given value.

### HasQrCodeDataUri

`func (o *CreateShipment201ResponseParcelsInner) HasQrCodeDataUri() bool`

HasQrCodeDataUri returns a boolean if a field has been set.

### SetQrCodeDataUriNil

`func (o *CreateShipment201ResponseParcelsInner) SetQrCodeDataUriNil(b bool)`

 SetQrCodeDataUriNil sets the value for QrCodeDataUri to be an explicit nil

### UnsetQrCodeDataUri
`func (o *CreateShipment201ResponseParcelsInner) UnsetQrCodeDataUri()`

UnsetQrCodeDataUri ensures that no value is present for QrCodeDataUri, not even an explicit nil
### GetQrCodeUrl

`func (o *CreateShipment201ResponseParcelsInner) GetQrCodeUrl() string`

GetQrCodeUrl returns the QrCodeUrl field if non-nil, zero value otherwise.

### GetQrCodeUrlOk

`func (o *CreateShipment201ResponseParcelsInner) GetQrCodeUrlOk() (*string, bool)`

GetQrCodeUrlOk returns a tuple with the QrCodeUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQrCodeUrl

`func (o *CreateShipment201ResponseParcelsInner) SetQrCodeUrl(v string)`

SetQrCodeUrl sets QrCodeUrl field to given value.

### HasQrCodeUrl

`func (o *CreateShipment201ResponseParcelsInner) HasQrCodeUrl() bool`

HasQrCodeUrl returns a boolean if a field has been set.

### SetQrCodeUrlNil

`func (o *CreateShipment201ResponseParcelsInner) SetQrCodeUrlNil(b bool)`

 SetQrCodeUrlNil sets the value for QrCodeUrl to be an explicit nil

### UnsetQrCodeUrl
`func (o *CreateShipment201ResponseParcelsInner) UnsetQrCodeUrl()`

UnsetQrCodeUrl ensures that no value is present for QrCodeUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


