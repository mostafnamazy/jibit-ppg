# ReversePurchaseResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | Pointer to **string** | It is the status of reverse. Possible states are:  &lt;p&gt;  * &#x60;SUCCESSFUL&#x60;: The reverse was successful.  * &#x60;UNKNOWN&#x60;: The reverse was unknown (typically because of a network failure). The client must retry the reverse for this purchase.  * &#x60;ALREADY_REVERSED&#x60;: The purchase is already reversed.  * &#x60;NOT_REVERSIBLE&#x60;: The purchase is not prepared to reverse and thus is not reversible.  * &#x60;FAILED&#x60;: The purchase reversion failed on PSP side. | [optional] 

## Methods

### NewReversePurchaseResult

`func NewReversePurchaseResult() *ReversePurchaseResult`

NewReversePurchaseResult instantiates a new ReversePurchaseResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReversePurchaseResultWithDefaults

`func NewReversePurchaseResultWithDefaults() *ReversePurchaseResult`

NewReversePurchaseResultWithDefaults instantiates a new ReversePurchaseResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *ReversePurchaseResult) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ReversePurchaseResult) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ReversePurchaseResult) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ReversePurchaseResult) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


