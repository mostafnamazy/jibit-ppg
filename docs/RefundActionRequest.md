# RefundActionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TransferId** | Pointer to **string** | This is the unique identifier of a partial refund.  * If there is only one refund in the batch, you do not need to specify &#x60;transferId&#x60;.  * If there are multiple refunds in the batch: You must specify &#x60;transferId&#x60; to indicate the position of the partial refund. | [optional] 

## Methods

### NewRefundActionRequest

`func NewRefundActionRequest() *RefundActionRequest`

NewRefundActionRequest instantiates a new RefundActionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRefundActionRequestWithDefaults

`func NewRefundActionRequestWithDefaults() *RefundActionRequest`

NewRefundActionRequestWithDefaults instantiates a new RefundActionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTransferId

`func (o *RefundActionRequest) GetTransferId() string`

GetTransferId returns the TransferId field if non-nil, zero value otherwise.

### GetTransferIdOk

`func (o *RefundActionRequest) GetTransferIdOk() (*string, bool)`

GetTransferIdOk returns a tuple with the TransferId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransferId

`func (o *RefundActionRequest) SetTransferId(v string)`

SetTransferId sets TransferId field to given value.

### HasTransferId

`func (o *RefundActionRequest) HasTransferId() bool`

HasTransferId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


