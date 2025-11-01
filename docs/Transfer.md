# Transfer

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RefundId** | Pointer to **int64** | represents the purchase identifier of the refund. | [optional] 
**PartialRefundIndex** | Pointer to **int32** | Represents the position of a partial refund within a batch of refunds for a purchase. It is one-based, meaning it starts at 1.  ** DEPRECATED. Use &#x60;transferId&#x60; instead** | [optional] 
**TransferMode** | Pointer to **string** |  | [optional] 
**Destination** | Pointer to **string** |  | [optional] 
**DestinationFirstName** | Pointer to **string** |  | [optional] 
**DestinationLastName** | Pointer to **string** |  | [optional] 
**Amount** | Pointer to **int64** |  | [optional] 
**Currency** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**Metadata** | Pointer to **string** |  | [optional] 
**Cancellable** | Pointer to **bool** |  | [optional] 
**State** | Pointer to **string** | State can have these following values:  TRANSFERRED means refund is completely done. FAILED means refund is failed. INITIALIZED and IN_PROGRESS mean refund is in progress. CANCELLING means it is in the middle of cancel process. CANCELLED means refund is cancelled. | [optional] 
**FailReason** | Pointer to **string** |  | [optional] 
**FeeCurrency** | Pointer to **string** |  | [optional] 
**FeeAmount** | Pointer to **int64** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**ModifiedAt** | Pointer to **time.Time** |  | [optional] 
**NotifyURL** | Pointer to **string** |  | [optional] 
**PaymentID** | Pointer to **string** |  | [optional] 
**BankTransferID** | Pointer to **string** |  | [optional] 
**TransferID** | Pointer to **string** |  | [optional] 

## Methods

### NewTransfer

`func NewTransfer() *Transfer`

NewTransfer instantiates a new Transfer object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTransferWithDefaults

`func NewTransferWithDefaults() *Transfer`

NewTransferWithDefaults instantiates a new Transfer object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRefundId

`func (o *Transfer) GetRefundId() int64`

GetRefundId returns the RefundId field if non-nil, zero value otherwise.

### GetRefundIdOk

`func (o *Transfer) GetRefundIdOk() (*int64, bool)`

GetRefundIdOk returns a tuple with the RefundId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRefundId

`func (o *Transfer) SetRefundId(v int64)`

SetRefundId sets RefundId field to given value.

### HasRefundId

`func (o *Transfer) HasRefundId() bool`

HasRefundId returns a boolean if a field has been set.

### GetPartialRefundIndex

`func (o *Transfer) GetPartialRefundIndex() int32`

GetPartialRefundIndex returns the PartialRefundIndex field if non-nil, zero value otherwise.

### GetPartialRefundIndexOk

`func (o *Transfer) GetPartialRefundIndexOk() (*int32, bool)`

GetPartialRefundIndexOk returns a tuple with the PartialRefundIndex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartialRefundIndex

`func (o *Transfer) SetPartialRefundIndex(v int32)`

SetPartialRefundIndex sets PartialRefundIndex field to given value.

### HasPartialRefundIndex

`func (o *Transfer) HasPartialRefundIndex() bool`

HasPartialRefundIndex returns a boolean if a field has been set.

### GetTransferMode

`func (o *Transfer) GetTransferMode() string`

GetTransferMode returns the TransferMode field if non-nil, zero value otherwise.

### GetTransferModeOk

`func (o *Transfer) GetTransferModeOk() (*string, bool)`

GetTransferModeOk returns a tuple with the TransferMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransferMode

`func (o *Transfer) SetTransferMode(v string)`

SetTransferMode sets TransferMode field to given value.

### HasTransferMode

`func (o *Transfer) HasTransferMode() bool`

HasTransferMode returns a boolean if a field has been set.

### GetDestination

`func (o *Transfer) GetDestination() string`

GetDestination returns the Destination field if non-nil, zero value otherwise.

### GetDestinationOk

`func (o *Transfer) GetDestinationOk() (*string, bool)`

GetDestinationOk returns a tuple with the Destination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestination

`func (o *Transfer) SetDestination(v string)`

SetDestination sets Destination field to given value.

### HasDestination

`func (o *Transfer) HasDestination() bool`

HasDestination returns a boolean if a field has been set.

### GetDestinationFirstName

`func (o *Transfer) GetDestinationFirstName() string`

GetDestinationFirstName returns the DestinationFirstName field if non-nil, zero value otherwise.

### GetDestinationFirstNameOk

`func (o *Transfer) GetDestinationFirstNameOk() (*string, bool)`

GetDestinationFirstNameOk returns a tuple with the DestinationFirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationFirstName

`func (o *Transfer) SetDestinationFirstName(v string)`

SetDestinationFirstName sets DestinationFirstName field to given value.

### HasDestinationFirstName

`func (o *Transfer) HasDestinationFirstName() bool`

HasDestinationFirstName returns a boolean if a field has been set.

### GetDestinationLastName

`func (o *Transfer) GetDestinationLastName() string`

GetDestinationLastName returns the DestinationLastName field if non-nil, zero value otherwise.

### GetDestinationLastNameOk

`func (o *Transfer) GetDestinationLastNameOk() (*string, bool)`

GetDestinationLastNameOk returns a tuple with the DestinationLastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationLastName

`func (o *Transfer) SetDestinationLastName(v string)`

SetDestinationLastName sets DestinationLastName field to given value.

### HasDestinationLastName

`func (o *Transfer) HasDestinationLastName() bool`

HasDestinationLastName returns a boolean if a field has been set.

### GetAmount

`func (o *Transfer) GetAmount() int64`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *Transfer) GetAmountOk() (*int64, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *Transfer) SetAmount(v int64)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *Transfer) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetCurrency

`func (o *Transfer) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *Transfer) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *Transfer) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *Transfer) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetDescription

`func (o *Transfer) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *Transfer) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *Transfer) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *Transfer) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetMetadata

`func (o *Transfer) GetMetadata() string`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *Transfer) GetMetadataOk() (*string, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *Transfer) SetMetadata(v string)`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *Transfer) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetCancellable

`func (o *Transfer) GetCancellable() bool`

GetCancellable returns the Cancellable field if non-nil, zero value otherwise.

### GetCancellableOk

`func (o *Transfer) GetCancellableOk() (*bool, bool)`

GetCancellableOk returns a tuple with the Cancellable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancellable

`func (o *Transfer) SetCancellable(v bool)`

SetCancellable sets Cancellable field to given value.

### HasCancellable

`func (o *Transfer) HasCancellable() bool`

HasCancellable returns a boolean if a field has been set.

### GetState

`func (o *Transfer) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *Transfer) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *Transfer) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *Transfer) HasState() bool`

HasState returns a boolean if a field has been set.

### GetFailReason

`func (o *Transfer) GetFailReason() string`

GetFailReason returns the FailReason field if non-nil, zero value otherwise.

### GetFailReasonOk

`func (o *Transfer) GetFailReasonOk() (*string, bool)`

GetFailReasonOk returns a tuple with the FailReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailReason

`func (o *Transfer) SetFailReason(v string)`

SetFailReason sets FailReason field to given value.

### HasFailReason

`func (o *Transfer) HasFailReason() bool`

HasFailReason returns a boolean if a field has been set.

### GetFeeCurrency

`func (o *Transfer) GetFeeCurrency() string`

GetFeeCurrency returns the FeeCurrency field if non-nil, zero value otherwise.

### GetFeeCurrencyOk

`func (o *Transfer) GetFeeCurrencyOk() (*string, bool)`

GetFeeCurrencyOk returns a tuple with the FeeCurrency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeeCurrency

`func (o *Transfer) SetFeeCurrency(v string)`

SetFeeCurrency sets FeeCurrency field to given value.

### HasFeeCurrency

`func (o *Transfer) HasFeeCurrency() bool`

HasFeeCurrency returns a boolean if a field has been set.

### GetFeeAmount

`func (o *Transfer) GetFeeAmount() int64`

GetFeeAmount returns the FeeAmount field if non-nil, zero value otherwise.

### GetFeeAmountOk

`func (o *Transfer) GetFeeAmountOk() (*int64, bool)`

GetFeeAmountOk returns a tuple with the FeeAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeeAmount

`func (o *Transfer) SetFeeAmount(v int64)`

SetFeeAmount sets FeeAmount field to given value.

### HasFeeAmount

`func (o *Transfer) HasFeeAmount() bool`

HasFeeAmount returns a boolean if a field has been set.

### GetCreatedAt

`func (o *Transfer) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Transfer) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Transfer) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Transfer) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetModifiedAt

`func (o *Transfer) GetModifiedAt() time.Time`

GetModifiedAt returns the ModifiedAt field if non-nil, zero value otherwise.

### GetModifiedAtOk

`func (o *Transfer) GetModifiedAtOk() (*time.Time, bool)`

GetModifiedAtOk returns a tuple with the ModifiedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedAt

`func (o *Transfer) SetModifiedAt(v time.Time)`

SetModifiedAt sets ModifiedAt field to given value.

### HasModifiedAt

`func (o *Transfer) HasModifiedAt() bool`

HasModifiedAt returns a boolean if a field has been set.

### GetNotifyURL

`func (o *Transfer) GetNotifyURL() string`

GetNotifyURL returns the NotifyURL field if non-nil, zero value otherwise.

### GetNotifyURLOk

`func (o *Transfer) GetNotifyURLOk() (*string, bool)`

GetNotifyURLOk returns a tuple with the NotifyURL field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifyURL

`func (o *Transfer) SetNotifyURL(v string)`

SetNotifyURL sets NotifyURL field to given value.

### HasNotifyURL

`func (o *Transfer) HasNotifyURL() bool`

HasNotifyURL returns a boolean if a field has been set.

### GetPaymentID

`func (o *Transfer) GetPaymentID() string`

GetPaymentID returns the PaymentID field if non-nil, zero value otherwise.

### GetPaymentIDOk

`func (o *Transfer) GetPaymentIDOk() (*string, bool)`

GetPaymentIDOk returns a tuple with the PaymentID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentID

`func (o *Transfer) SetPaymentID(v string)`

SetPaymentID sets PaymentID field to given value.

### HasPaymentID

`func (o *Transfer) HasPaymentID() bool`

HasPaymentID returns a boolean if a field has been set.

### GetBankTransferID

`func (o *Transfer) GetBankTransferID() string`

GetBankTransferID returns the BankTransferID field if non-nil, zero value otherwise.

### GetBankTransferIDOk

`func (o *Transfer) GetBankTransferIDOk() (*string, bool)`

GetBankTransferIDOk returns a tuple with the BankTransferID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankTransferID

`func (o *Transfer) SetBankTransferID(v string)`

SetBankTransferID sets BankTransferID field to given value.

### HasBankTransferID

`func (o *Transfer) HasBankTransferID() bool`

HasBankTransferID returns a boolean if a field has been set.

### GetTransferID

`func (o *Transfer) GetTransferID() string`

GetTransferID returns the TransferID field if non-nil, zero value otherwise.

### GetTransferIDOk

`func (o *Transfer) GetTransferIDOk() (*string, bool)`

GetTransferIDOk returns a tuple with the TransferID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransferID

`func (o *Transfer) SetTransferID(v string)`

SetTransferID sets TransferID field to given value.

### HasTransferID

`func (o *Transfer) HasTransferID() bool`

HasTransferID returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


