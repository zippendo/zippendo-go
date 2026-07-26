# CreateShipment201ResponsePickupDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Date** | **string** | Requested pickup date (YYYY-MM-DD). | 
**From** | **string** | Requested earliest pickup time (HH:MM:SS). | 
**To** | **string** | Requested latest pickup time (HH:MM:SS). | 
**Instruction** | Pointer to **string** | Pickup instruction to the carrier. | [optional] 

## Methods

### NewCreateShipment201ResponsePickupDetails

`func NewCreateShipment201ResponsePickupDetails(date string, from string, to string, ) *CreateShipment201ResponsePickupDetails`

NewCreateShipment201ResponsePickupDetails instantiates a new CreateShipment201ResponsePickupDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateShipment201ResponsePickupDetailsWithDefaults

`func NewCreateShipment201ResponsePickupDetailsWithDefaults() *CreateShipment201ResponsePickupDetails`

NewCreateShipment201ResponsePickupDetailsWithDefaults instantiates a new CreateShipment201ResponsePickupDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDate

`func (o *CreateShipment201ResponsePickupDetails) GetDate() string`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *CreateShipment201ResponsePickupDetails) GetDateOk() (*string, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *CreateShipment201ResponsePickupDetails) SetDate(v string)`

SetDate sets Date field to given value.


### GetFrom

`func (o *CreateShipment201ResponsePickupDetails) GetFrom() string`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *CreateShipment201ResponsePickupDetails) GetFromOk() (*string, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *CreateShipment201ResponsePickupDetails) SetFrom(v string)`

SetFrom sets From field to given value.


### GetTo

`func (o *CreateShipment201ResponsePickupDetails) GetTo() string`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *CreateShipment201ResponsePickupDetails) GetToOk() (*string, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *CreateShipment201ResponsePickupDetails) SetTo(v string)`

SetTo sets To field to given value.


### GetInstruction

`func (o *CreateShipment201ResponsePickupDetails) GetInstruction() string`

GetInstruction returns the Instruction field if non-nil, zero value otherwise.

### GetInstructionOk

`func (o *CreateShipment201ResponsePickupDetails) GetInstructionOk() (*string, bool)`

GetInstructionOk returns a tuple with the Instruction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstruction

`func (o *CreateShipment201ResponsePickupDetails) SetInstruction(v string)`

SetInstruction sets Instruction field to given value.

### HasInstruction

`func (o *CreateShipment201ResponsePickupDetails) HasInstruction() bool`

HasInstruction returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


