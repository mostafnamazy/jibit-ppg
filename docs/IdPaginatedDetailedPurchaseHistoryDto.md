# IdPaginatedDetailedPurchaseHistoryDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Size** | Pointer to **int32** | The number of elements in the current page. | [optional] 
**TotalCount** | Pointer to **int64** | The total number of elements. If null, the total count was not calculated for faster response times. | [optional] 
**HasNext** | Pointer to **bool** | Indicates if there is another page following the current one. | [optional] 
**NextPageId** | Pointer to **string** | The identifier for fetching the next page of results.  This provides more efficient pagination compared to using a traditional page number.  Note: This can be null if there are no more results or if the result set is empty. | [optional] 
**Elements** | Pointer to [**[]DetailedPurchaseHistoryDto**](DetailedPurchaseHistoryDto.md) | The list of elements in the current page. | [optional] 

## Methods

### NewIdPaginatedDetailedPurchaseHistoryDto

`func NewIdPaginatedDetailedPurchaseHistoryDto() *IdPaginatedDetailedPurchaseHistoryDto`

NewIdPaginatedDetailedPurchaseHistoryDto instantiates a new IdPaginatedDetailedPurchaseHistoryDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIdPaginatedDetailedPurchaseHistoryDtoWithDefaults

`func NewIdPaginatedDetailedPurchaseHistoryDtoWithDefaults() *IdPaginatedDetailedPurchaseHistoryDto`

NewIdPaginatedDetailedPurchaseHistoryDtoWithDefaults instantiates a new IdPaginatedDetailedPurchaseHistoryDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSize

`func (o *IdPaginatedDetailedPurchaseHistoryDto) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *IdPaginatedDetailedPurchaseHistoryDto) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *IdPaginatedDetailedPurchaseHistoryDto) SetSize(v int32)`

SetSize sets Size field to given value.

### HasSize

`func (o *IdPaginatedDetailedPurchaseHistoryDto) HasSize() bool`

HasSize returns a boolean if a field has been set.

### GetTotalCount

`func (o *IdPaginatedDetailedPurchaseHistoryDto) GetTotalCount() int64`

GetTotalCount returns the TotalCount field if non-nil, zero value otherwise.

### GetTotalCountOk

`func (o *IdPaginatedDetailedPurchaseHistoryDto) GetTotalCountOk() (*int64, bool)`

GetTotalCountOk returns a tuple with the TotalCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCount

`func (o *IdPaginatedDetailedPurchaseHistoryDto) SetTotalCount(v int64)`

SetTotalCount sets TotalCount field to given value.

### HasTotalCount

`func (o *IdPaginatedDetailedPurchaseHistoryDto) HasTotalCount() bool`

HasTotalCount returns a boolean if a field has been set.

### GetHasNext

`func (o *IdPaginatedDetailedPurchaseHistoryDto) GetHasNext() bool`

GetHasNext returns the HasNext field if non-nil, zero value otherwise.

### GetHasNextOk

`func (o *IdPaginatedDetailedPurchaseHistoryDto) GetHasNextOk() (*bool, bool)`

GetHasNextOk returns a tuple with the HasNext field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasNext

`func (o *IdPaginatedDetailedPurchaseHistoryDto) SetHasNext(v bool)`

SetHasNext sets HasNext field to given value.

### HasHasNext

`func (o *IdPaginatedDetailedPurchaseHistoryDto) HasHasNext() bool`

HasHasNext returns a boolean if a field has been set.

### GetNextPageId

`func (o *IdPaginatedDetailedPurchaseHistoryDto) GetNextPageId() string`

GetNextPageId returns the NextPageId field if non-nil, zero value otherwise.

### GetNextPageIdOk

`func (o *IdPaginatedDetailedPurchaseHistoryDto) GetNextPageIdOk() (*string, bool)`

GetNextPageIdOk returns a tuple with the NextPageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextPageId

`func (o *IdPaginatedDetailedPurchaseHistoryDto) SetNextPageId(v string)`

SetNextPageId sets NextPageId field to given value.

### HasNextPageId

`func (o *IdPaginatedDetailedPurchaseHistoryDto) HasNextPageId() bool`

HasNextPageId returns a boolean if a field has been set.

### GetElements

`func (o *IdPaginatedDetailedPurchaseHistoryDto) GetElements() []DetailedPurchaseHistoryDto`

GetElements returns the Elements field if non-nil, zero value otherwise.

### GetElementsOk

`func (o *IdPaginatedDetailedPurchaseHistoryDto) GetElementsOk() (*[]DetailedPurchaseHistoryDto, bool)`

GetElementsOk returns a tuple with the Elements field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetElements

`func (o *IdPaginatedDetailedPurchaseHistoryDto) SetElements(v []DetailedPurchaseHistoryDto)`

SetElements sets Elements field to given value.

### HasElements

`func (o *IdPaginatedDetailedPurchaseHistoryDto) HasElements() bool`

HasElements returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


