# PurchaseFilterCriteria

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PurchaseId** | Pointer to **int64** | Finds a purchase by its identifier. Can be used to find an exact purchase. The &#x60;null&#x60; means no filtering at all. | [optional] 
**Status** | Pointer to **string** | Filters purchases based on their state. The &#x60;null&#x60; means no filtering at all. | [optional] 
**ClientReferenceNumber** | Pointer to **string** | Finds a purchase by its client reference number. The &#x60;null&#x60; means no filtering at all. | [optional] 
**PspReferenceNumber** | Pointer to **string** | Filters purchases by their PSP reference number. The &#x60;null&#x60; means no filtering at all. | [optional] 
**PspRrn** | Pointer to **string** | Filters purchases by their PSP RRN. The &#x60;null&#x60; means no filtering at all. | [optional] 
**PspTraceNumber** | Pointer to **string** | Filters purchases by their PSP trace number. The &#x60;null&#x60; means no filtering at all. | [optional] 
**UserIdentifier** | Pointer to **string** | Filters purchases based on their user identifier. The &#x60;null&#x60; means no filtering at all. | [optional] 
**From** | Pointer to **time.Time** | Filters purchases from their creation date inclusively. The &#x60;null&#x60; means no filtering at all. | [optional] 
**To** | Pointer to **time.Time** | Filters purchases to their creation date exclusively. The &#x60;null&#x60; means no filtering at all. | [optional] 
**Page** | Pointer to **int32** | Represents the page number; One indexed. The &#x60;null&#x60; means the first page.  The max page number is 20. | [optional] 
**Size** | Pointer to **int32** | Represents the page size. The &#x60;null&#x60; means to use default size.  The default page size is 25.  The max page size is 250. | [optional] 

## Methods

### NewPurchaseFilterCriteria

`func NewPurchaseFilterCriteria() *PurchaseFilterCriteria`

NewPurchaseFilterCriteria instantiates a new PurchaseFilterCriteria object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPurchaseFilterCriteriaWithDefaults

`func NewPurchaseFilterCriteriaWithDefaults() *PurchaseFilterCriteria`

NewPurchaseFilterCriteriaWithDefaults instantiates a new PurchaseFilterCriteria object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPurchaseId

`func (o *PurchaseFilterCriteria) GetPurchaseId() int64`

GetPurchaseId returns the PurchaseId field if non-nil, zero value otherwise.

### GetPurchaseIdOk

`func (o *PurchaseFilterCriteria) GetPurchaseIdOk() (*int64, bool)`

GetPurchaseIdOk returns a tuple with the PurchaseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurchaseId

`func (o *PurchaseFilterCriteria) SetPurchaseId(v int64)`

SetPurchaseId sets PurchaseId field to given value.

### HasPurchaseId

`func (o *PurchaseFilterCriteria) HasPurchaseId() bool`

HasPurchaseId returns a boolean if a field has been set.

### GetStatus

`func (o *PurchaseFilterCriteria) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PurchaseFilterCriteria) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PurchaseFilterCriteria) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *PurchaseFilterCriteria) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetClientReferenceNumber

`func (o *PurchaseFilterCriteria) GetClientReferenceNumber() string`

GetClientReferenceNumber returns the ClientReferenceNumber field if non-nil, zero value otherwise.

### GetClientReferenceNumberOk

`func (o *PurchaseFilterCriteria) GetClientReferenceNumberOk() (*string, bool)`

GetClientReferenceNumberOk returns a tuple with the ClientReferenceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientReferenceNumber

`func (o *PurchaseFilterCriteria) SetClientReferenceNumber(v string)`

SetClientReferenceNumber sets ClientReferenceNumber field to given value.

### HasClientReferenceNumber

`func (o *PurchaseFilterCriteria) HasClientReferenceNumber() bool`

HasClientReferenceNumber returns a boolean if a field has been set.

### GetPspReferenceNumber

`func (o *PurchaseFilterCriteria) GetPspReferenceNumber() string`

GetPspReferenceNumber returns the PspReferenceNumber field if non-nil, zero value otherwise.

### GetPspReferenceNumberOk

`func (o *PurchaseFilterCriteria) GetPspReferenceNumberOk() (*string, bool)`

GetPspReferenceNumberOk returns a tuple with the PspReferenceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPspReferenceNumber

`func (o *PurchaseFilterCriteria) SetPspReferenceNumber(v string)`

SetPspReferenceNumber sets PspReferenceNumber field to given value.

### HasPspReferenceNumber

`func (o *PurchaseFilterCriteria) HasPspReferenceNumber() bool`

HasPspReferenceNumber returns a boolean if a field has been set.

### GetPspRrn

`func (o *PurchaseFilterCriteria) GetPspRrn() string`

GetPspRrn returns the PspRrn field if non-nil, zero value otherwise.

### GetPspRrnOk

`func (o *PurchaseFilterCriteria) GetPspRrnOk() (*string, bool)`

GetPspRrnOk returns a tuple with the PspRrn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPspRrn

`func (o *PurchaseFilterCriteria) SetPspRrn(v string)`

SetPspRrn sets PspRrn field to given value.

### HasPspRrn

`func (o *PurchaseFilterCriteria) HasPspRrn() bool`

HasPspRrn returns a boolean if a field has been set.

### GetPspTraceNumber

`func (o *PurchaseFilterCriteria) GetPspTraceNumber() string`

GetPspTraceNumber returns the PspTraceNumber field if non-nil, zero value otherwise.

### GetPspTraceNumberOk

`func (o *PurchaseFilterCriteria) GetPspTraceNumberOk() (*string, bool)`

GetPspTraceNumberOk returns a tuple with the PspTraceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPspTraceNumber

`func (o *PurchaseFilterCriteria) SetPspTraceNumber(v string)`

SetPspTraceNumber sets PspTraceNumber field to given value.

### HasPspTraceNumber

`func (o *PurchaseFilterCriteria) HasPspTraceNumber() bool`

HasPspTraceNumber returns a boolean if a field has been set.

### GetUserIdentifier

`func (o *PurchaseFilterCriteria) GetUserIdentifier() string`

GetUserIdentifier returns the UserIdentifier field if non-nil, zero value otherwise.

### GetUserIdentifierOk

`func (o *PurchaseFilterCriteria) GetUserIdentifierOk() (*string, bool)`

GetUserIdentifierOk returns a tuple with the UserIdentifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserIdentifier

`func (o *PurchaseFilterCriteria) SetUserIdentifier(v string)`

SetUserIdentifier sets UserIdentifier field to given value.

### HasUserIdentifier

`func (o *PurchaseFilterCriteria) HasUserIdentifier() bool`

HasUserIdentifier returns a boolean if a field has been set.

### GetFrom

`func (o *PurchaseFilterCriteria) GetFrom() time.Time`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *PurchaseFilterCriteria) GetFromOk() (*time.Time, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *PurchaseFilterCriteria) SetFrom(v time.Time)`

SetFrom sets From field to given value.

### HasFrom

`func (o *PurchaseFilterCriteria) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### GetTo

`func (o *PurchaseFilterCriteria) GetTo() time.Time`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *PurchaseFilterCriteria) GetToOk() (*time.Time, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *PurchaseFilterCriteria) SetTo(v time.Time)`

SetTo sets To field to given value.

### HasTo

`func (o *PurchaseFilterCriteria) HasTo() bool`

HasTo returns a boolean if a field has been set.

### GetPage

`func (o *PurchaseFilterCriteria) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *PurchaseFilterCriteria) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *PurchaseFilterCriteria) SetPage(v int32)`

SetPage sets Page field to given value.

### HasPage

`func (o *PurchaseFilterCriteria) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetSize

`func (o *PurchaseFilterCriteria) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *PurchaseFilterCriteria) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *PurchaseFilterCriteria) SetSize(v int32)`

SetSize sets Size field to given value.

### HasSize

`func (o *PurchaseFilterCriteria) HasSize() bool`

HasSize returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


