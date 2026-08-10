# CreateShipment201ResponseTracking

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | Pointer to **NullableString** | Public carrier tracking URL. | [optional] 
**Number** | Pointer to **NullableString** | Carrier tracking number. | [optional] 
**LabelFreeCode** | Pointer to **NullableString** | Label-free drop-off code. | [optional] 
**QrCodeLink** | Pointer to **NullableString** | DEPRECATED — use &#x60;qrCodeDataUri&#x60; (embeddable data URI) or &#x60;qrCodeUrl&#x60; (hosted link). Catch-all that carries whichever applies, kept populated for backwards compatibility during the migration and until it is disabled. | [optional] 
**QrCodeDataUri** | Pointer to **NullableString** | Embeddable &#x60;data:&#x60; URI of the QR code image for label-free drop-off — base64 image bytes you can drop straight into an &lt;img&gt;/email. Populated whenever the image bytes are available, including for carriers that host the image (it is fetched and inlined); null if the carrier published no QR code or its image could not be retrieved. | [optional] 
**QrCodeUrl** | Pointer to **NullableString** | Carrier-hosted URL of the QR code image for label-free drop-off, returned by carriers (e.g. Bring) that link to the image rather than embedding it. Independent of &#x60;qrCodeDataUri&#x60; — both are set when the hosted image was inlined successfully; null for carriers that only return embedded bytes. | [optional] 

## Methods

### NewCreateShipment201ResponseTracking

`func NewCreateShipment201ResponseTracking() *CreateShipment201ResponseTracking`

NewCreateShipment201ResponseTracking instantiates a new CreateShipment201ResponseTracking object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateShipment201ResponseTrackingWithDefaults

`func NewCreateShipment201ResponseTrackingWithDefaults() *CreateShipment201ResponseTracking`

NewCreateShipment201ResponseTrackingWithDefaults instantiates a new CreateShipment201ResponseTracking object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrl

`func (o *CreateShipment201ResponseTracking) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *CreateShipment201ResponseTracking) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *CreateShipment201ResponseTracking) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *CreateShipment201ResponseTracking) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### SetUrlNil

`func (o *CreateShipment201ResponseTracking) SetUrlNil(b bool)`

 SetUrlNil sets the value for Url to be an explicit nil

### UnsetUrl
`func (o *CreateShipment201ResponseTracking) UnsetUrl()`

UnsetUrl ensures that no value is present for Url, not even an explicit nil
### GetNumber

`func (o *CreateShipment201ResponseTracking) GetNumber() string`

GetNumber returns the Number field if non-nil, zero value otherwise.

### GetNumberOk

`func (o *CreateShipment201ResponseTracking) GetNumberOk() (*string, bool)`

GetNumberOk returns a tuple with the Number field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumber

`func (o *CreateShipment201ResponseTracking) SetNumber(v string)`

SetNumber sets Number field to given value.

### HasNumber

`func (o *CreateShipment201ResponseTracking) HasNumber() bool`

HasNumber returns a boolean if a field has been set.

### SetNumberNil

`func (o *CreateShipment201ResponseTracking) SetNumberNil(b bool)`

 SetNumberNil sets the value for Number to be an explicit nil

### UnsetNumber
`func (o *CreateShipment201ResponseTracking) UnsetNumber()`

UnsetNumber ensures that no value is present for Number, not even an explicit nil
### GetLabelFreeCode

`func (o *CreateShipment201ResponseTracking) GetLabelFreeCode() string`

GetLabelFreeCode returns the LabelFreeCode field if non-nil, zero value otherwise.

### GetLabelFreeCodeOk

`func (o *CreateShipment201ResponseTracking) GetLabelFreeCodeOk() (*string, bool)`

GetLabelFreeCodeOk returns a tuple with the LabelFreeCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabelFreeCode

`func (o *CreateShipment201ResponseTracking) SetLabelFreeCode(v string)`

SetLabelFreeCode sets LabelFreeCode field to given value.

### HasLabelFreeCode

`func (o *CreateShipment201ResponseTracking) HasLabelFreeCode() bool`

HasLabelFreeCode returns a boolean if a field has been set.

### SetLabelFreeCodeNil

`func (o *CreateShipment201ResponseTracking) SetLabelFreeCodeNil(b bool)`

 SetLabelFreeCodeNil sets the value for LabelFreeCode to be an explicit nil

### UnsetLabelFreeCode
`func (o *CreateShipment201ResponseTracking) UnsetLabelFreeCode()`

UnsetLabelFreeCode ensures that no value is present for LabelFreeCode, not even an explicit nil
### GetQrCodeLink

`func (o *CreateShipment201ResponseTracking) GetQrCodeLink() string`

GetQrCodeLink returns the QrCodeLink field if non-nil, zero value otherwise.

### GetQrCodeLinkOk

`func (o *CreateShipment201ResponseTracking) GetQrCodeLinkOk() (*string, bool)`

GetQrCodeLinkOk returns a tuple with the QrCodeLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQrCodeLink

`func (o *CreateShipment201ResponseTracking) SetQrCodeLink(v string)`

SetQrCodeLink sets QrCodeLink field to given value.

### HasQrCodeLink

`func (o *CreateShipment201ResponseTracking) HasQrCodeLink() bool`

HasQrCodeLink returns a boolean if a field has been set.

### SetQrCodeLinkNil

`func (o *CreateShipment201ResponseTracking) SetQrCodeLinkNil(b bool)`

 SetQrCodeLinkNil sets the value for QrCodeLink to be an explicit nil

### UnsetQrCodeLink
`func (o *CreateShipment201ResponseTracking) UnsetQrCodeLink()`

UnsetQrCodeLink ensures that no value is present for QrCodeLink, not even an explicit nil
### GetQrCodeDataUri

`func (o *CreateShipment201ResponseTracking) GetQrCodeDataUri() string`

GetQrCodeDataUri returns the QrCodeDataUri field if non-nil, zero value otherwise.

### GetQrCodeDataUriOk

`func (o *CreateShipment201ResponseTracking) GetQrCodeDataUriOk() (*string, bool)`

GetQrCodeDataUriOk returns a tuple with the QrCodeDataUri field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQrCodeDataUri

`func (o *CreateShipment201ResponseTracking) SetQrCodeDataUri(v string)`

SetQrCodeDataUri sets QrCodeDataUri field to given value.

### HasQrCodeDataUri

`func (o *CreateShipment201ResponseTracking) HasQrCodeDataUri() bool`

HasQrCodeDataUri returns a boolean if a field has been set.

### SetQrCodeDataUriNil

`func (o *CreateShipment201ResponseTracking) SetQrCodeDataUriNil(b bool)`

 SetQrCodeDataUriNil sets the value for QrCodeDataUri to be an explicit nil

### UnsetQrCodeDataUri
`func (o *CreateShipment201ResponseTracking) UnsetQrCodeDataUri()`

UnsetQrCodeDataUri ensures that no value is present for QrCodeDataUri, not even an explicit nil
### GetQrCodeUrl

`func (o *CreateShipment201ResponseTracking) GetQrCodeUrl() string`

GetQrCodeUrl returns the QrCodeUrl field if non-nil, zero value otherwise.

### GetQrCodeUrlOk

`func (o *CreateShipment201ResponseTracking) GetQrCodeUrlOk() (*string, bool)`

GetQrCodeUrlOk returns a tuple with the QrCodeUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQrCodeUrl

`func (o *CreateShipment201ResponseTracking) SetQrCodeUrl(v string)`

SetQrCodeUrl sets QrCodeUrl field to given value.

### HasQrCodeUrl

`func (o *CreateShipment201ResponseTracking) HasQrCodeUrl() bool`

HasQrCodeUrl returns a boolean if a field has been set.

### SetQrCodeUrlNil

`func (o *CreateShipment201ResponseTracking) SetQrCodeUrlNil(b bool)`

 SetQrCodeUrlNil sets the value for QrCodeUrl to be an explicit nil

### UnsetQrCodeUrl
`func (o *CreateShipment201ResponseTracking) UnsetQrCodeUrl()`

UnsetQrCodeUrl ensures that no value is present for QrCodeUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


