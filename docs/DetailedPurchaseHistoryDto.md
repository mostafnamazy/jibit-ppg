# DetailedPurchaseHistoryDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PurchaseId** | Pointer to **int64** | Represents the purchase identifier. | [optional] 
**ClientRefNum** | Pointer to **string** | Represents the client reference number.  A string value from client side to trace purchase in our system. This value is unique between client purchases. | [optional] 
**NewState** | Pointer to **string** | Represents the simplified version of purchase new state.  &lt;p&gt;  The following states indicate the purchase had a contradiction and now is resolved.  &lt;p&gt;  * &#x60;MANUALLY_SUCCESS&#x60;: The purchase has been successful manually.  * &#x60;REVERSED&#x60;: The purchase has been reversed manually.  **Note: ** &#x60;REVERSED&#x60; does not indicate a contradiction if the client reverts a purchase. | [optional] 
**CreatedAt** | Pointer to **time.Time** | Represents the creation time of this purchase history, which indicates when purchase status got changed.  Example: 2024-10-20T13:25:30.946Z | [optional] 

## Methods

### NewDetailedPurchaseHistoryDto

`func NewDetailedPurchaseHistoryDto() *DetailedPurchaseHistoryDto`

NewDetailedPurchaseHistoryDto instantiates a new DetailedPurchaseHistoryDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDetailedPurchaseHistoryDtoWithDefaults

`func NewDetailedPurchaseHistoryDtoWithDefaults() *DetailedPurchaseHistoryDto`

NewDetailedPurchaseHistoryDtoWithDefaults instantiates a new DetailedPurchaseHistoryDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPurchaseId

`func (o *DetailedPurchaseHistoryDto) GetPurchaseId() int64`

GetPurchaseId returns the PurchaseId field if non-nil, zero value otherwise.

### GetPurchaseIdOk

`func (o *DetailedPurchaseHistoryDto) GetPurchaseIdOk() (*int64, bool)`

GetPurchaseIdOk returns a tuple with the PurchaseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurchaseId

`func (o *DetailedPurchaseHistoryDto) SetPurchaseId(v int64)`

SetPurchaseId sets PurchaseId field to given value.

### HasPurchaseId

`func (o *DetailedPurchaseHistoryDto) HasPurchaseId() bool`

HasPurchaseId returns a boolean if a field has been set.

### GetClientRefNum

`func (o *DetailedPurchaseHistoryDto) GetClientRefNum() string`

GetClientRefNum returns the ClientRefNum field if non-nil, zero value otherwise.

### GetClientRefNumOk

`func (o *DetailedPurchaseHistoryDto) GetClientRefNumOk() (*string, bool)`

GetClientRefNumOk returns a tuple with the ClientRefNum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientRefNum

`func (o *DetailedPurchaseHistoryDto) SetClientRefNum(v string)`

SetClientRefNum sets ClientRefNum field to given value.

### HasClientRefNum

`func (o *DetailedPurchaseHistoryDto) HasClientRefNum() bool`

HasClientRefNum returns a boolean if a field has been set.

### GetNewState

`func (o *DetailedPurchaseHistoryDto) GetNewState() string`

GetNewState returns the NewState field if non-nil, zero value otherwise.

### GetNewStateOk

`func (o *DetailedPurchaseHistoryDto) GetNewStateOk() (*string, bool)`

GetNewStateOk returns a tuple with the NewState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewState

`func (o *DetailedPurchaseHistoryDto) SetNewState(v string)`

SetNewState sets NewState field to given value.

### HasNewState

`func (o *DetailedPurchaseHistoryDto) HasNewState() bool`

HasNewState returns a boolean if a field has been set.

### GetCreatedAt

`func (o *DetailedPurchaseHistoryDto) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *DetailedPurchaseHistoryDto) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *DetailedPurchaseHistoryDto) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *DetailedPurchaseHistoryDto) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


