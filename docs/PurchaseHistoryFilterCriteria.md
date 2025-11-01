# PurchaseHistoryFilterCriteria

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**From** | Pointer to **time.Time** | The start of the date range (inclusive) for querying purchase history. | [optional] 
**To** | Pointer to **time.Time** | The end of the date range (exclusive) for querying purchase history. | [optional] 
**PurchaseId** | Pointer to **int64** | Represents the unique identifier for a purchase.  This field is used to filter purchase history records  based on a specific purchase. | [optional] 
**Statuses** | Pointer to **[]string** | A list representing the statuses of a purchase history.  Each state corresponds to a different status of the purchase,  such as manually successful, reversed, or unknown. | [optional] 
**NextPageId** | Pointer to **int64** | The identifier for fetching the next page of results.  Using &#x60;nextPageId&#x60; allows faster pagination than a page number parameter.  If provided, the &#x60;page&#x60; parameter will be ignored. | [optional] 
**Page** | Pointer to **int32** | The page number to fetch (1-indexed). If null, it means the first page.  Note: The max page number is 10. Use &#x60;nextPageId&#x60; for faster results.  If &#x60;nextPageId&#x60; is provided, this field is ignored. | [optional] 
**Size** | Pointer to **int32** | The number of results per page. If null, the default size will be used.  The default page size is 10,000, and the maximum allowed size is 20,000. | [optional] 

## Methods

### NewPurchaseHistoryFilterCriteria

`func NewPurchaseHistoryFilterCriteria() *PurchaseHistoryFilterCriteria`

NewPurchaseHistoryFilterCriteria instantiates a new PurchaseHistoryFilterCriteria object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPurchaseHistoryFilterCriteriaWithDefaults

`func NewPurchaseHistoryFilterCriteriaWithDefaults() *PurchaseHistoryFilterCriteria`

NewPurchaseHistoryFilterCriteriaWithDefaults instantiates a new PurchaseHistoryFilterCriteria object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFrom

`func (o *PurchaseHistoryFilterCriteria) GetFrom() time.Time`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *PurchaseHistoryFilterCriteria) GetFromOk() (*time.Time, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *PurchaseHistoryFilterCriteria) SetFrom(v time.Time)`

SetFrom sets From field to given value.

### HasFrom

`func (o *PurchaseHistoryFilterCriteria) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### GetTo

`func (o *PurchaseHistoryFilterCriteria) GetTo() time.Time`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *PurchaseHistoryFilterCriteria) GetToOk() (*time.Time, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *PurchaseHistoryFilterCriteria) SetTo(v time.Time)`

SetTo sets To field to given value.

### HasTo

`func (o *PurchaseHistoryFilterCriteria) HasTo() bool`

HasTo returns a boolean if a field has been set.

### GetPurchaseId

`func (o *PurchaseHistoryFilterCriteria) GetPurchaseId() int64`

GetPurchaseId returns the PurchaseId field if non-nil, zero value otherwise.

### GetPurchaseIdOk

`func (o *PurchaseHistoryFilterCriteria) GetPurchaseIdOk() (*int64, bool)`

GetPurchaseIdOk returns a tuple with the PurchaseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurchaseId

`func (o *PurchaseHistoryFilterCriteria) SetPurchaseId(v int64)`

SetPurchaseId sets PurchaseId field to given value.

### HasPurchaseId

`func (o *PurchaseHistoryFilterCriteria) HasPurchaseId() bool`

HasPurchaseId returns a boolean if a field has been set.

### GetStatuses

`func (o *PurchaseHistoryFilterCriteria) GetStatuses() []string`

GetStatuses returns the Statuses field if non-nil, zero value otherwise.

### GetStatusesOk

`func (o *PurchaseHistoryFilterCriteria) GetStatusesOk() (*[]string, bool)`

GetStatusesOk returns a tuple with the Statuses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatuses

`func (o *PurchaseHistoryFilterCriteria) SetStatuses(v []string)`

SetStatuses sets Statuses field to given value.

### HasStatuses

`func (o *PurchaseHistoryFilterCriteria) HasStatuses() bool`

HasStatuses returns a boolean if a field has been set.

### GetNextPageId

`func (o *PurchaseHistoryFilterCriteria) GetNextPageId() int64`

GetNextPageId returns the NextPageId field if non-nil, zero value otherwise.

### GetNextPageIdOk

`func (o *PurchaseHistoryFilterCriteria) GetNextPageIdOk() (*int64, bool)`

GetNextPageIdOk returns a tuple with the NextPageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextPageId

`func (o *PurchaseHistoryFilterCriteria) SetNextPageId(v int64)`

SetNextPageId sets NextPageId field to given value.

### HasNextPageId

`func (o *PurchaseHistoryFilterCriteria) HasNextPageId() bool`

HasNextPageId returns a boolean if a field has been set.

### GetPage

`func (o *PurchaseHistoryFilterCriteria) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *PurchaseHistoryFilterCriteria) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *PurchaseHistoryFilterCriteria) SetPage(v int32)`

SetPage sets Page field to given value.

### HasPage

`func (o *PurchaseHistoryFilterCriteria) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetSize

`func (o *PurchaseHistoryFilterCriteria) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *PurchaseHistoryFilterCriteria) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *PurchaseHistoryFilterCriteria) SetSize(v int32)`

SetSize sets Size field to given value.

### HasSize

`func (o *PurchaseHistoryFilterCriteria) HasSize() bool`

HasSize returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


