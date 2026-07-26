# CreateShipmentRequestPickupDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Date** | **string** | Requested pickup date (YYYY-MM-DD). | 
**From** | **string** | Requested earliest pickup time (HH:MM:SS). | 
**To** | **string** | Requested latest pickup time (HH:MM:SS). | 
**Instruction** | Pointer to **string** | Pickup instruction to the carrier. | [optional] 

## Methods

### NewCreateShipmentRequestPickupDetails

`func NewCreateShipmentRequestPickupDetails(date string, from string, to string, ) *CreateShipmentRequestPickupDetails`

NewCreateShipmentRequestPickupDetails instantiates a new CreateShipmentRequestPickupDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateShipmentRequestPickupDetailsWithDefaults

`func NewCreateShipmentRequestPickupDetailsWithDefaults() *CreateShipmentRequestPickupDetails`

NewCreateShipmentRequestPickupDetailsWithDefaults instantiates a new CreateShipmentRequestPickupDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDate

`func (o *CreateShipmentRequestPickupDetails) GetDate() string`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *CreateShipmentRequestPickupDetails) GetDateOk() (*string, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *CreateShipmentRequestPickupDetails) SetDate(v string)`

SetDate sets Date field to given value.


### GetFrom

`func (o *CreateShipmentRequestPickupDetails) GetFrom() string`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *CreateShipmentRequestPickupDetails) GetFromOk() (*string, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *CreateShipmentRequestPickupDetails) SetFrom(v string)`

SetFrom sets From field to given value.


### GetTo

`func (o *CreateShipmentRequestPickupDetails) GetTo() string`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *CreateShipmentRequestPickupDetails) GetToOk() (*string, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *CreateShipmentRequestPickupDetails) SetTo(v string)`

SetTo sets To field to given value.


### GetInstruction

`func (o *CreateShipmentRequestPickupDetails) GetInstruction() string`

GetInstruction returns the Instruction field if non-nil, zero value otherwise.

### GetInstructionOk

`func (o *CreateShipmentRequestPickupDetails) GetInstructionOk() (*string, bool)`

GetInstructionOk returns a tuple with the Instruction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstruction

`func (o *CreateShipmentRequestPickupDetails) SetInstruction(v string)`

SetInstruction sets Instruction field to given value.

### HasInstruction

`func (o *CreateShipmentRequestPickupDetails) HasInstruction() bool`

HasInstruction returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


