# CreateShipmentRequestParcelsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Unique parcel identifier. | [optional] 
**Weight** | **float32** | Parcel weight in the given weight unit. | 
**WeightUnit** | **string** | Unit of measurement for parcel weight. | 
**Dimensions** | [**CreateShipmentRequestParcelsInnerDimensions**](CreateShipmentRequestParcelsInnerDimensions.md) |  | 
**OrderLines** | [**[]CreateShipmentRequestParcelsInnerOrderLinesInner**](CreateShipmentRequestParcelsInnerOrderLinesInner.md) | Order lines contained in this parcel. | 
**TrackingNumber** | Pointer to **NullableString** | Carrier tracking number for this parcel. | [optional] 
**TrackingUrl** | Pointer to **NullableString** | Public carrier tracking URL for this parcel. | [optional] 
**LabelFreeCode** | Pointer to **NullableString** | Label-free drop-off code for the parcel. | [optional] 
**QrCodeLink** | Pointer to **NullableString** | DEPRECATED — use &#x60;qrCodeDataUri&#x60; (embeddable data URI) or &#x60;qrCodeUrl&#x60; (hosted link). Catch-all that carries whichever applies, kept populated for backwards compatibility during the migration and until it is disabled. | [optional] 
**QrCodeDataUri** | Pointer to **NullableString** | Embeddable &#x60;data:&#x60; URI of the QR code image for label-free drop-off — base64 image bytes you can drop straight into an &lt;img&gt;/email. Populated whenever the image bytes are available, including for carriers that host the image (it is fetched and inlined); null if the carrier published no QR code or its image could not be retrieved. | [optional] 
**QrCodeUrl** | Pointer to **NullableString** | Carrier-hosted URL of the QR code image for label-free drop-off, returned by carriers (e.g. Bring) that link to the image rather than embedding it. Independent of &#x60;qrCodeDataUri&#x60; — both are set when the hosted image was inlined successfully; null for carriers that only return embedded bytes. | [optional] 

## Methods

### NewCreateShipmentRequestParcelsInner

`func NewCreateShipmentRequestParcelsInner(weight float32, weightUnit string, dimensions CreateShipmentRequestParcelsInnerDimensions, orderLines []CreateShipmentRequestParcelsInnerOrderLinesInner, ) *CreateShipmentRequestParcelsInner`

NewCreateShipmentRequestParcelsInner instantiates a new CreateShipmentRequestParcelsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateShipmentRequestParcelsInnerWithDefaults

`func NewCreateShipmentRequestParcelsInnerWithDefaults() *CreateShipmentRequestParcelsInner`

NewCreateShipmentRequestParcelsInnerWithDefaults instantiates a new CreateShipmentRequestParcelsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreateShipmentRequestParcelsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateShipmentRequestParcelsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateShipmentRequestParcelsInner) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *CreateShipmentRequestParcelsInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetWeight

`func (o *CreateShipmentRequestParcelsInner) GetWeight() float32`

GetWeight returns the Weight field if non-nil, zero value otherwise.

### GetWeightOk

`func (o *CreateShipmentRequestParcelsInner) GetWeightOk() (*float32, bool)`

GetWeightOk returns a tuple with the Weight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeight

`func (o *CreateShipmentRequestParcelsInner) SetWeight(v float32)`

SetWeight sets Weight field to given value.


### GetWeightUnit

`func (o *CreateShipmentRequestParcelsInner) GetWeightUnit() string`

GetWeightUnit returns the WeightUnit field if non-nil, zero value otherwise.

### GetWeightUnitOk

`func (o *CreateShipmentRequestParcelsInner) GetWeightUnitOk() (*string, bool)`

GetWeightUnitOk returns a tuple with the WeightUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeightUnit

`func (o *CreateShipmentRequestParcelsInner) SetWeightUnit(v string)`

SetWeightUnit sets WeightUnit field to given value.


### GetDimensions

`func (o *CreateShipmentRequestParcelsInner) GetDimensions() CreateShipmentRequestParcelsInnerDimensions`

GetDimensions returns the Dimensions field if non-nil, zero value otherwise.

### GetDimensionsOk

`func (o *CreateShipmentRequestParcelsInner) GetDimensionsOk() (*CreateShipmentRequestParcelsInnerDimensions, bool)`

GetDimensionsOk returns a tuple with the Dimensions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDimensions

`func (o *CreateShipmentRequestParcelsInner) SetDimensions(v CreateShipmentRequestParcelsInnerDimensions)`

SetDimensions sets Dimensions field to given value.


### GetOrderLines

`func (o *CreateShipmentRequestParcelsInner) GetOrderLines() []CreateShipmentRequestParcelsInnerOrderLinesInner`

GetOrderLines returns the OrderLines field if non-nil, zero value otherwise.

### GetOrderLinesOk

`func (o *CreateShipmentRequestParcelsInner) GetOrderLinesOk() (*[]CreateShipmentRequestParcelsInnerOrderLinesInner, bool)`

GetOrderLinesOk returns a tuple with the OrderLines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderLines

`func (o *CreateShipmentRequestParcelsInner) SetOrderLines(v []CreateShipmentRequestParcelsInnerOrderLinesInner)`

SetOrderLines sets OrderLines field to given value.


### GetTrackingNumber

`func (o *CreateShipmentRequestParcelsInner) GetTrackingNumber() string`

GetTrackingNumber returns the TrackingNumber field if non-nil, zero value otherwise.

### GetTrackingNumberOk

`func (o *CreateShipmentRequestParcelsInner) GetTrackingNumberOk() (*string, bool)`

GetTrackingNumberOk returns a tuple with the TrackingNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingNumber

`func (o *CreateShipmentRequestParcelsInner) SetTrackingNumber(v string)`

SetTrackingNumber sets TrackingNumber field to given value.

### HasTrackingNumber

`func (o *CreateShipmentRequestParcelsInner) HasTrackingNumber() bool`

HasTrackingNumber returns a boolean if a field has been set.

### SetTrackingNumberNil

`func (o *CreateShipmentRequestParcelsInner) SetTrackingNumberNil(b bool)`

 SetTrackingNumberNil sets the value for TrackingNumber to be an explicit nil

### UnsetTrackingNumber
`func (o *CreateShipmentRequestParcelsInner) UnsetTrackingNumber()`

UnsetTrackingNumber ensures that no value is present for TrackingNumber, not even an explicit nil
### GetTrackingUrl

`func (o *CreateShipmentRequestParcelsInner) GetTrackingUrl() string`

GetTrackingUrl returns the TrackingUrl field if non-nil, zero value otherwise.

### GetTrackingUrlOk

`func (o *CreateShipmentRequestParcelsInner) GetTrackingUrlOk() (*string, bool)`

GetTrackingUrlOk returns a tuple with the TrackingUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingUrl

`func (o *CreateShipmentRequestParcelsInner) SetTrackingUrl(v string)`

SetTrackingUrl sets TrackingUrl field to given value.

### HasTrackingUrl

`func (o *CreateShipmentRequestParcelsInner) HasTrackingUrl() bool`

HasTrackingUrl returns a boolean if a field has been set.

### SetTrackingUrlNil

`func (o *CreateShipmentRequestParcelsInner) SetTrackingUrlNil(b bool)`

 SetTrackingUrlNil sets the value for TrackingUrl to be an explicit nil

### UnsetTrackingUrl
`func (o *CreateShipmentRequestParcelsInner) UnsetTrackingUrl()`

UnsetTrackingUrl ensures that no value is present for TrackingUrl, not even an explicit nil
### GetLabelFreeCode

`func (o *CreateShipmentRequestParcelsInner) GetLabelFreeCode() string`

GetLabelFreeCode returns the LabelFreeCode field if non-nil, zero value otherwise.

### GetLabelFreeCodeOk

`func (o *CreateShipmentRequestParcelsInner) GetLabelFreeCodeOk() (*string, bool)`

GetLabelFreeCodeOk returns a tuple with the LabelFreeCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabelFreeCode

`func (o *CreateShipmentRequestParcelsInner) SetLabelFreeCode(v string)`

SetLabelFreeCode sets LabelFreeCode field to given value.

### HasLabelFreeCode

`func (o *CreateShipmentRequestParcelsInner) HasLabelFreeCode() bool`

HasLabelFreeCode returns a boolean if a field has been set.

### SetLabelFreeCodeNil

`func (o *CreateShipmentRequestParcelsInner) SetLabelFreeCodeNil(b bool)`

 SetLabelFreeCodeNil sets the value for LabelFreeCode to be an explicit nil

### UnsetLabelFreeCode
`func (o *CreateShipmentRequestParcelsInner) UnsetLabelFreeCode()`

UnsetLabelFreeCode ensures that no value is present for LabelFreeCode, not even an explicit nil
### GetQrCodeLink

`func (o *CreateShipmentRequestParcelsInner) GetQrCodeLink() string`

GetQrCodeLink returns the QrCodeLink field if non-nil, zero value otherwise.

### GetQrCodeLinkOk

`func (o *CreateShipmentRequestParcelsInner) GetQrCodeLinkOk() (*string, bool)`

GetQrCodeLinkOk returns a tuple with the QrCodeLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQrCodeLink

`func (o *CreateShipmentRequestParcelsInner) SetQrCodeLink(v string)`

SetQrCodeLink sets QrCodeLink field to given value.

### HasQrCodeLink

`func (o *CreateShipmentRequestParcelsInner) HasQrCodeLink() bool`

HasQrCodeLink returns a boolean if a field has been set.

### SetQrCodeLinkNil

`func (o *CreateShipmentRequestParcelsInner) SetQrCodeLinkNil(b bool)`

 SetQrCodeLinkNil sets the value for QrCodeLink to be an explicit nil

### UnsetQrCodeLink
`func (o *CreateShipmentRequestParcelsInner) UnsetQrCodeLink()`

UnsetQrCodeLink ensures that no value is present for QrCodeLink, not even an explicit nil
### GetQrCodeDataUri

`func (o *CreateShipmentRequestParcelsInner) GetQrCodeDataUri() string`

GetQrCodeDataUri returns the QrCodeDataUri field if non-nil, zero value otherwise.

### GetQrCodeDataUriOk

`func (o *CreateShipmentRequestParcelsInner) GetQrCodeDataUriOk() (*string, bool)`

GetQrCodeDataUriOk returns a tuple with the QrCodeDataUri field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQrCodeDataUri

`func (o *CreateShipmentRequestParcelsInner) SetQrCodeDataUri(v string)`

SetQrCodeDataUri sets QrCodeDataUri field to given value.

### HasQrCodeDataUri

`func (o *CreateShipmentRequestParcelsInner) HasQrCodeDataUri() bool`

HasQrCodeDataUri returns a boolean if a field has been set.

### SetQrCodeDataUriNil

`func (o *CreateShipmentRequestParcelsInner) SetQrCodeDataUriNil(b bool)`

 SetQrCodeDataUriNil sets the value for QrCodeDataUri to be an explicit nil

### UnsetQrCodeDataUri
`func (o *CreateShipmentRequestParcelsInner) UnsetQrCodeDataUri()`

UnsetQrCodeDataUri ensures that no value is present for QrCodeDataUri, not even an explicit nil
### GetQrCodeUrl

`func (o *CreateShipmentRequestParcelsInner) GetQrCodeUrl() string`

GetQrCodeUrl returns the QrCodeUrl field if non-nil, zero value otherwise.

### GetQrCodeUrlOk

`func (o *CreateShipmentRequestParcelsInner) GetQrCodeUrlOk() (*string, bool)`

GetQrCodeUrlOk returns a tuple with the QrCodeUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQrCodeUrl

`func (o *CreateShipmentRequestParcelsInner) SetQrCodeUrl(v string)`

SetQrCodeUrl sets QrCodeUrl field to given value.

### HasQrCodeUrl

`func (o *CreateShipmentRequestParcelsInner) HasQrCodeUrl() bool`

HasQrCodeUrl returns a boolean if a field has been set.

### SetQrCodeUrlNil

`func (o *CreateShipmentRequestParcelsInner) SetQrCodeUrlNil(b bool)`

 SetQrCodeUrlNil sets the value for QrCodeUrl to be an explicit nil

### UnsetQrCodeUrl
`func (o *CreateShipmentRequestParcelsInner) UnsetQrCodeUrl()`

UnsetQrCodeUrl ensures that no value is present for QrCodeUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


