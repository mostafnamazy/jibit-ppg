# HealthDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | Pointer to **string** | The current health status of the service.                      UP if the service is operational, or DOWN if it is not. | [optional] 
**PspStatusMap** | Pointer to **map[string]string** | A map containing the health status of various PSP vendors. | [optional] 

## Methods

### NewHealthDto

`func NewHealthDto() *HealthDto`

NewHealthDto instantiates a new HealthDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHealthDtoWithDefaults

`func NewHealthDtoWithDefaults() *HealthDto`

NewHealthDtoWithDefaults instantiates a new HealthDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *HealthDto) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *HealthDto) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *HealthDto) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *HealthDto) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetPspStatusMap

`func (o *HealthDto) GetPspStatusMap() map[string]string`

GetPspStatusMap returns the PspStatusMap field if non-nil, zero value otherwise.

### GetPspStatusMapOk

`func (o *HealthDto) GetPspStatusMapOk() (*map[string]string, bool)`

GetPspStatusMapOk returns a tuple with the PspStatusMap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPspStatusMap

`func (o *HealthDto) SetPspStatusMap(v map[string]string)`

SetPspStatusMap sets PspStatusMap field to given value.

### HasPspStatusMap

`func (o *HealthDto) HasPspStatusMap() bool`

HasPspStatusMap returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


