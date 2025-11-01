# RefundPurchaseRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ClientReferenceNumber** | Pointer to **string** | Represents the reference number provided by client to trace the purchase in our system. | [optional] 
**PurchaseId** | Pointer to **int64** | Represents the purchase id. | [optional] 
**Amount** | Pointer to **int64** | Represents the refund amount. | [optional] 
**Cancellable** | Pointer to **bool** | Whether to pend the refund request and perform it after one hour. | [optional] 

## Methods

### NewRefundPurchaseRequest

`func NewRefundPurchaseRequest() *RefundPurchaseRequest`

NewRefundPurchaseRequest instantiates a new RefundPurchaseRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRefundPurchaseRequestWithDefaults

`func NewRefundPurchaseRequestWithDefaults() *RefundPurchaseRequest`

NewRefundPurchaseRequestWithDefaults instantiates a new RefundPurchaseRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetClientReferenceNumber

`func (o *RefundPurchaseRequest) GetClientReferenceNumber() string`

GetClientReferenceNumber returns the ClientReferenceNumber field if non-nil, zero value otherwise.

### GetClientReferenceNumberOk

`func (o *RefundPurchaseRequest) GetClientReferenceNumberOk() (*string, bool)`

GetClientReferenceNumberOk returns a tuple with the ClientReferenceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientReferenceNumber

`func (o *RefundPurchaseRequest) SetClientReferenceNumber(v string)`

SetClientReferenceNumber sets ClientReferenceNumber field to given value.

### HasClientReferenceNumber

`func (o *RefundPurchaseRequest) HasClientReferenceNumber() bool`

HasClientReferenceNumber returns a boolean if a field has been set.

### GetPurchaseId

`func (o *RefundPurchaseRequest) GetPurchaseId() int64`

GetPurchaseId returns the PurchaseId field if non-nil, zero value otherwise.

### GetPurchaseIdOk

`func (o *RefundPurchaseRequest) GetPurchaseIdOk() (*int64, bool)`

GetPurchaseIdOk returns a tuple with the PurchaseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurchaseId

`func (o *RefundPurchaseRequest) SetPurchaseId(v int64)`

SetPurchaseId sets PurchaseId field to given value.

### HasPurchaseId

`func (o *RefundPurchaseRequest) HasPurchaseId() bool`

HasPurchaseId returns a boolean if a field has been set.

### GetAmount

`func (o *RefundPurchaseRequest) GetAmount() int64`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *RefundPurchaseRequest) GetAmountOk() (*int64, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *RefundPurchaseRequest) SetAmount(v int64)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *RefundPurchaseRequest) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetCancellable

`func (o *RefundPurchaseRequest) GetCancellable() bool`

GetCancellable returns the Cancellable field if non-nil, zero value otherwise.

### GetCancellableOk

`func (o *RefundPurchaseRequest) GetCancellableOk() (*bool, bool)`

GetCancellableOk returns a tuple with the Cancellable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancellable

`func (o *RefundPurchaseRequest) SetCancellable(v bool)`

SetCancellable sets Cancellable field to given value.

### HasCancellable

`func (o *RefundPurchaseRequest) HasCancellable() bool`

HasCancellable returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


