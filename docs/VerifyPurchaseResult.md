# VerifyPurchaseResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | Pointer to **string** | It is the status of verification.  **Possible values:**  - &#x60;SUCCESSFUL&#x60;: The verification was successful.  - &#x60;FAILED&#x60;: The verification failed. The payment amount will be returned to the user&#39;s bank account. See  step 10.  - &#x60;UNKNOWN&#x60;: The verification was unknown (typically due to a network failure). The client can retry verification before expiration or inquire about the purchase later to determine the final state.  - &#x60;ALREADY_VERIFIED&#x60;: The purchase is already verified, such as a purchase with a &#x60;SUCCESS&#x60; state.  - &#x60;NOT_VERIFIABLE&#x60;: The purchase is not ready for verification and cannot be verified. Only purchases in the &#x60;READY_TO_VERIFY&#x60; state can be verified. | [optional] 

## Methods

### NewVerifyPurchaseResult

`func NewVerifyPurchaseResult() *VerifyPurchaseResult`

NewVerifyPurchaseResult instantiates a new VerifyPurchaseResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVerifyPurchaseResultWithDefaults

`func NewVerifyPurchaseResultWithDefaults() *VerifyPurchaseResult`

NewVerifyPurchaseResultWithDefaults instantiates a new VerifyPurchaseResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *VerifyPurchaseResult) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *VerifyPurchaseResult) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *VerifyPurchaseResult) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *VerifyPurchaseResult) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


