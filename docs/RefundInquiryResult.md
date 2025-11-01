# RefundInquiryResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Transfers** | Pointer to [**[]Transfer**](Transfer.md) | Represents the list of Transfers. | [optional] 
**BatchID** | Pointer to **string** | Represents the batch id. | [optional] 
**RefundedAmount** | Pointer to **int64** |  | [optional] 

## Methods

### NewRefundInquiryResult

`func NewRefundInquiryResult() *RefundInquiryResult`

NewRefundInquiryResult instantiates a new RefundInquiryResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRefundInquiryResultWithDefaults

`func NewRefundInquiryResultWithDefaults() *RefundInquiryResult`

NewRefundInquiryResultWithDefaults instantiates a new RefundInquiryResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTransfers

`func (o *RefundInquiryResult) GetTransfers() []Transfer`

GetTransfers returns the Transfers field if non-nil, zero value otherwise.

### GetTransfersOk

`func (o *RefundInquiryResult) GetTransfersOk() (*[]Transfer, bool)`

GetTransfersOk returns a tuple with the Transfers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransfers

`func (o *RefundInquiryResult) SetTransfers(v []Transfer)`

SetTransfers sets Transfers field to given value.

### HasTransfers

`func (o *RefundInquiryResult) HasTransfers() bool`

HasTransfers returns a boolean if a field has been set.

### GetBatchID

`func (o *RefundInquiryResult) GetBatchID() string`

GetBatchID returns the BatchID field if non-nil, zero value otherwise.

### GetBatchIDOk

`func (o *RefundInquiryResult) GetBatchIDOk() (*string, bool)`

GetBatchIDOk returns a tuple with the BatchID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatchID

`func (o *RefundInquiryResult) SetBatchID(v string)`

SetBatchID sets BatchID field to given value.

### HasBatchID

`func (o *RefundInquiryResult) HasBatchID() bool`

HasBatchID returns a boolean if a field has been set.

### GetRefundedAmount

`func (o *RefundInquiryResult) GetRefundedAmount() int64`

GetRefundedAmount returns the RefundedAmount field if non-nil, zero value otherwise.

### GetRefundedAmountOk

`func (o *RefundInquiryResult) GetRefundedAmountOk() (*int64, bool)`

GetRefundedAmountOk returns a tuple with the RefundedAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRefundedAmount

`func (o *RefundInquiryResult) SetRefundedAmount(v int64)`

SetRefundedAmount sets RefundedAmount field to given value.

### HasRefundedAmount

`func (o *RefundInquiryResult) HasRefundedAmount() bool`

HasRefundedAmount returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


