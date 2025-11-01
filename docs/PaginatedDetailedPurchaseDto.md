# PaginatedDetailedPurchaseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PageNumber** | Pointer to **int32** | The current 1-index page number. | [optional] 
**Size** | Pointer to **int32** | The size of current page. | [optional] 
**NumberOfElements** | Pointer to **int64** | Total number of elements. | [optional] 
**HasNext** | Pointer to **bool** | Can this page be followed by another page after it? | [optional] 
**HasPrevious** | Pointer to **bool** | Is there a previous page for this page? | [optional] 
**Elements** | Pointer to [**[]DetailedPurchaseDto**](DetailedPurchaseDto.md) | The actual paginated elements. | [optional] 

## Methods

### NewPaginatedDetailedPurchaseDto

`func NewPaginatedDetailedPurchaseDto() *PaginatedDetailedPurchaseDto`

NewPaginatedDetailedPurchaseDto instantiates a new PaginatedDetailedPurchaseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPaginatedDetailedPurchaseDtoWithDefaults

`func NewPaginatedDetailedPurchaseDtoWithDefaults() *PaginatedDetailedPurchaseDto`

NewPaginatedDetailedPurchaseDtoWithDefaults instantiates a new PaginatedDetailedPurchaseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPageNumber

`func (o *PaginatedDetailedPurchaseDto) GetPageNumber() int32`

GetPageNumber returns the PageNumber field if non-nil, zero value otherwise.

### GetPageNumberOk

`func (o *PaginatedDetailedPurchaseDto) GetPageNumberOk() (*int32, bool)`

GetPageNumberOk returns a tuple with the PageNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageNumber

`func (o *PaginatedDetailedPurchaseDto) SetPageNumber(v int32)`

SetPageNumber sets PageNumber field to given value.

### HasPageNumber

`func (o *PaginatedDetailedPurchaseDto) HasPageNumber() bool`

HasPageNumber returns a boolean if a field has been set.

### GetSize

`func (o *PaginatedDetailedPurchaseDto) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *PaginatedDetailedPurchaseDto) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *PaginatedDetailedPurchaseDto) SetSize(v int32)`

SetSize sets Size field to given value.

### HasSize

`func (o *PaginatedDetailedPurchaseDto) HasSize() bool`

HasSize returns a boolean if a field has been set.

### GetNumberOfElements

`func (o *PaginatedDetailedPurchaseDto) GetNumberOfElements() int64`

GetNumberOfElements returns the NumberOfElements field if non-nil, zero value otherwise.

### GetNumberOfElementsOk

`func (o *PaginatedDetailedPurchaseDto) GetNumberOfElementsOk() (*int64, bool)`

GetNumberOfElementsOk returns a tuple with the NumberOfElements field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumberOfElements

`func (o *PaginatedDetailedPurchaseDto) SetNumberOfElements(v int64)`

SetNumberOfElements sets NumberOfElements field to given value.

### HasNumberOfElements

`func (o *PaginatedDetailedPurchaseDto) HasNumberOfElements() bool`

HasNumberOfElements returns a boolean if a field has been set.

### GetHasNext

`func (o *PaginatedDetailedPurchaseDto) GetHasNext() bool`

GetHasNext returns the HasNext field if non-nil, zero value otherwise.

### GetHasNextOk

`func (o *PaginatedDetailedPurchaseDto) GetHasNextOk() (*bool, bool)`

GetHasNextOk returns a tuple with the HasNext field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasNext

`func (o *PaginatedDetailedPurchaseDto) SetHasNext(v bool)`

SetHasNext sets HasNext field to given value.

### HasHasNext

`func (o *PaginatedDetailedPurchaseDto) HasHasNext() bool`

HasHasNext returns a boolean if a field has been set.

### GetHasPrevious

`func (o *PaginatedDetailedPurchaseDto) GetHasPrevious() bool`

GetHasPrevious returns the HasPrevious field if non-nil, zero value otherwise.

### GetHasPreviousOk

`func (o *PaginatedDetailedPurchaseDto) GetHasPreviousOk() (*bool, bool)`

GetHasPreviousOk returns a tuple with the HasPrevious field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasPrevious

`func (o *PaginatedDetailedPurchaseDto) SetHasPrevious(v bool)`

SetHasPrevious sets HasPrevious field to given value.

### HasHasPrevious

`func (o *PaginatedDetailedPurchaseDto) HasHasPrevious() bool`

HasHasPrevious returns a boolean if a field has been set.

### GetElements

`func (o *PaginatedDetailedPurchaseDto) GetElements() []DetailedPurchaseDto`

GetElements returns the Elements field if non-nil, zero value otherwise.

### GetElementsOk

`func (o *PaginatedDetailedPurchaseDto) GetElementsOk() (*[]DetailedPurchaseDto, bool)`

GetElementsOk returns a tuple with the Elements field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetElements

`func (o *PaginatedDetailedPurchaseDto) SetElements(v []DetailedPurchaseDto)`

SetElements sets Elements field to given value.

### HasElements

`func (o *PaginatedDetailedPurchaseDto) HasElements() bool`

HasElements returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


