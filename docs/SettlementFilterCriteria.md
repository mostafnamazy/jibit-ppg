# SettlementFilterCriteria

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SettlementId** | Pointer to **int64** | Finds a settlement by its identifier. The &#x60;null&#x60; means no filtering at all. | [optional] 
**Page** | Pointer to **int32** | Represents the page number; One indexed. The &#x60;null&#x60; means the first page.  The max page number is 20. | [optional] 
**Size** | Pointer to **int32** | Represents the page size. The &#x60;null&#x60; means to use default size.  The default page size is 25.  The max page size is 250. | [optional] 

## Methods

### NewSettlementFilterCriteria

`func NewSettlementFilterCriteria() *SettlementFilterCriteria`

NewSettlementFilterCriteria instantiates a new SettlementFilterCriteria object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSettlementFilterCriteriaWithDefaults

`func NewSettlementFilterCriteriaWithDefaults() *SettlementFilterCriteria`

NewSettlementFilterCriteriaWithDefaults instantiates a new SettlementFilterCriteria object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSettlementId

`func (o *SettlementFilterCriteria) GetSettlementId() int64`

GetSettlementId returns the SettlementId field if non-nil, zero value otherwise.

### GetSettlementIdOk

`func (o *SettlementFilterCriteria) GetSettlementIdOk() (*int64, bool)`

GetSettlementIdOk returns a tuple with the SettlementId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettlementId

`func (o *SettlementFilterCriteria) SetSettlementId(v int64)`

SetSettlementId sets SettlementId field to given value.

### HasSettlementId

`func (o *SettlementFilterCriteria) HasSettlementId() bool`

HasSettlementId returns a boolean if a field has been set.

### GetPage

`func (o *SettlementFilterCriteria) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *SettlementFilterCriteria) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *SettlementFilterCriteria) SetPage(v int32)`

SetPage sets Page field to given value.

### HasPage

`func (o *SettlementFilterCriteria) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetSize

`func (o *SettlementFilterCriteria) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *SettlementFilterCriteria) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *SettlementFilterCriteria) SetSize(v int32)`

SetSize sets Size field to given value.

### HasSize

`func (o *SettlementFilterCriteria) HasSize() bool`

HasSize returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


