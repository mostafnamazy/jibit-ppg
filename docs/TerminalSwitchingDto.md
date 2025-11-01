# TerminalSwitchingDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TerminalIds** | Pointer to **[]string** | A list of terminal natural IDs required for terminal switching.  Terminals and their natural IDs can be retrieved via the .  The list&#39;s first entry has the highest priority for initializing the purchase, while the last entry has the lowest priority. | [optional] 
**AutoSwitching** | Pointer to **bool** | Determines whether terminal switching is automatic or manual.  Defaults to &#x60;true&#x60;, which enables automatic switching while prioritizing terminals in the &#x60;terminalIds&#x60; list.  If set to &#x60;false&#x60;, only the specified terminals will be used without automatic switching. | [optional] 

## Methods

### NewTerminalSwitchingDto

`func NewTerminalSwitchingDto() *TerminalSwitchingDto`

NewTerminalSwitchingDto instantiates a new TerminalSwitchingDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTerminalSwitchingDtoWithDefaults

`func NewTerminalSwitchingDtoWithDefaults() *TerminalSwitchingDto`

NewTerminalSwitchingDtoWithDefaults instantiates a new TerminalSwitchingDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTerminalIds

`func (o *TerminalSwitchingDto) GetTerminalIds() []string`

GetTerminalIds returns the TerminalIds field if non-nil, zero value otherwise.

### GetTerminalIdsOk

`func (o *TerminalSwitchingDto) GetTerminalIdsOk() (*[]string, bool)`

GetTerminalIdsOk returns a tuple with the TerminalIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTerminalIds

`func (o *TerminalSwitchingDto) SetTerminalIds(v []string)`

SetTerminalIds sets TerminalIds field to given value.

### HasTerminalIds

`func (o *TerminalSwitchingDto) HasTerminalIds() bool`

HasTerminalIds returns a boolean if a field has been set.

### GetAutoSwitching

`func (o *TerminalSwitchingDto) GetAutoSwitching() bool`

GetAutoSwitching returns the AutoSwitching field if non-nil, zero value otherwise.

### GetAutoSwitchingOk

`func (o *TerminalSwitchingDto) GetAutoSwitchingOk() (*bool, bool)`

GetAutoSwitchingOk returns a tuple with the AutoSwitching field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoSwitching

`func (o *TerminalSwitchingDto) SetAutoSwitching(v bool)`

SetAutoSwitching sets AutoSwitching field to given value.

### HasAutoSwitching

`func (o *TerminalSwitchingDto) HasAutoSwitching() bool`

HasAutoSwitching returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


