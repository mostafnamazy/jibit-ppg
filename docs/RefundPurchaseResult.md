# RefundPurchaseResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RefundId** | Pointer to **int64** | represents the purchase identifier of the refund. | [optional] 
**PartialRefundIndex** | Pointer to **int32** | Represents the position of a partial refund within a batch of refunds for a purchase. It is one-based, meaning it starts at 1.  ** DEPRECATED. Use &#x60;transferId&#x60; instead** | [optional] 
**BatchId** | Pointer to **string** | The batch id returned from transferor. | [optional] 
**TransferId** | Pointer to **string** | The transfer id returned from transferor. | [optional] 

## Methods

### NewRefundPurchaseResult

`func NewRefundPurchaseResult() *RefundPurchaseResult`

NewRefundPurchaseResult instantiates a new RefundPurchaseResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRefundPurchaseResultWithDefaults

`func NewRefundPurchaseResultWithDefaults() *RefundPurchaseResult`

NewRefundPurchaseResultWithDefaults instantiates a new RefundPurchaseResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRefundId

`func (o *RefundPurchaseResult) GetRefundId() int64`

GetRefundId returns the RefundId field if non-nil, zero value otherwise.

### GetRefundIdOk

`func (o *RefundPurchaseResult) GetRefundIdOk() (*int64, bool)`

GetRefundIdOk returns a tuple with the RefundId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRefundId

`func (o *RefundPurchaseResult) SetRefundId(v int64)`

SetRefundId sets RefundId field to given value.

### HasRefundId

`func (o *RefundPurchaseResult) HasRefundId() bool`

HasRefundId returns a boolean if a field has been set.

### GetPartialRefundIndex

`func (o *RefundPurchaseResult) GetPartialRefundIndex() int32`

GetPartialRefundIndex returns the PartialRefundIndex field if non-nil, zero value otherwise.

### GetPartialRefundIndexOk

`func (o *RefundPurchaseResult) GetPartialRefundIndexOk() (*int32, bool)`

GetPartialRefundIndexOk returns a tuple with the PartialRefundIndex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartialRefundIndex

`func (o *RefundPurchaseResult) SetPartialRefundIndex(v int32)`

SetPartialRefundIndex sets PartialRefundIndex field to given value.

### HasPartialRefundIndex

`func (o *RefundPurchaseResult) HasPartialRefundIndex() bool`

HasPartialRefundIndex returns a boolean if a field has been set.

### GetBatchId

`func (o *RefundPurchaseResult) GetBatchId() string`

GetBatchId returns the BatchId field if non-nil, zero value otherwise.

### GetBatchIdOk

`func (o *RefundPurchaseResult) GetBatchIdOk() (*string, bool)`

GetBatchIdOk returns a tuple with the BatchId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatchId

`func (o *RefundPurchaseResult) SetBatchId(v string)`

SetBatchId sets BatchId field to given value.

### HasBatchId

`func (o *RefundPurchaseResult) HasBatchId() bool`

HasBatchId returns a boolean if a field has been set.

### GetTransferId

`func (o *RefundPurchaseResult) GetTransferId() string`

GetTransferId returns the TransferId field if non-nil, zero value otherwise.

### GetTransferIdOk

`func (o *RefundPurchaseResult) GetTransferIdOk() (*string, bool)`

GetTransferIdOk returns a tuple with the TransferId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransferId

`func (o *RefundPurchaseResult) SetTransferId(v string)`

SetTransferId sets TransferId field to given value.

### HasTransferId

`func (o *RefundPurchaseResult) HasTransferId() bool`

HasTransferId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


