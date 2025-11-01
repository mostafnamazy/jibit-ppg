# CreatePurchaseRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Amount** | Pointer to **int64** | Represents the amount of purchase. | [optional] 
**Wage** | Pointer to **int64** | Represents the wage of purchase.  The user will pay the &#x60;amount&#x60; + &#x60;wage&#x60;.  The Default value is 0.  &lt;b&gt;This field can not be bigger that 15 % of the &#x60;amount&#x60; value.&lt;/b&gt; | [optional] 
**Currency** | Pointer to **string** | Represents the currency of &#x60;amount&#x60; and &#x60;wage&#x60;. | [optional] 
**ClientReferenceNumber** | Pointer to **string** | Represents a reference number provided by client to trace purchase in our system.  The reference number between client purchases must be unique. We will check this on our side.  The maximum length is 50 characters. | [optional] 
**PayerMobileNumber** | Pointer to **string** | Represents the mobile number of the payer. It will be sent to Psp to autocomplete the payment fields. | [optional] 
**CheckPayerMobileNumber** | Pointer to **bool** | If this flag is set to true, the payment must be paid only by a card which belongs to the owner of the phone number;  Otherwise the purchase will fail. Optional.  ** This feature is not enabled by default on certain PSPs and must be enabled by admin.  If Client uses this feature when it is not enabled, PPG simply ignores it and creates the purchase as normal. **  Note: If this flag is set to true, &#x60;payerMobileNumber&#x60; field cannot be null or else you will get an error. | [optional] 
**PayerCardNumber** | Pointer to **string** | Bank card number which is required to do the transaction.  Only this card number can be used to do the transaction. Optional.  ** This feature is not enabled by default on certain PSPs and must be enabled by admin.  If Client uses this feature when it is not enabled, PPG simply ignores it and creates the purchase as normal. ** | [optional] 
**PayerCardNumbers** | Pointer to **[]string** | Bank card numbers which are required to do the transaction.  Only these card numbers can be used to do the transaction. Optional.  ** This feature is not enabled by default on certain PSPs and must be enabled by admin.  If Client uses this feature when it is not enabled, PPG simply ignores it and creates the purchase as normal. ** | [optional] 
**PayerNationalCode** | Pointer to **string** | Represents the national code of card owner.  If provided, this Field will be matched with the national code of card owner in the IPG,  and if they don&#39;t match, the transaction will fail. Optional.  ** This feature is not enabled by default and must be enabled by admin.  If Client uses this feature when it is not enabled, PPG simply ignores it and creates the purchase as normal. ** | [optional] 
**Description** | Pointer to **string** | Represents the client-provided description. Optional.  The Maximum length is 256 characters. | [optional] 
**Switching** | Pointer to [**TerminalSwitchingDto**](TerminalSwitchingDto.md) |  | [optional] 
**AdditionalData** | Pointer to **map[string]interface{}** | Represents the additional data provided by client in JSON format. Optional. | [optional] 
**CallbackUrl** | Pointer to **string** | Represents a callback which we should call in order to notify the client about a particular purchase state.  For example, when the user pays the purchase, we would redirect the user to this callback and let the client know about  the payment. This must be a valid URL address. Maximum length is 1024 characters. | [optional] 
**UserIdentifier** | Pointer to **string** | Represents the user identifier in the client system.  Maximum length is 50 characters. | [optional] 

## Methods

### NewCreatePurchaseRequest

`func NewCreatePurchaseRequest() *CreatePurchaseRequest`

NewCreatePurchaseRequest instantiates a new CreatePurchaseRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreatePurchaseRequestWithDefaults

`func NewCreatePurchaseRequestWithDefaults() *CreatePurchaseRequest`

NewCreatePurchaseRequestWithDefaults instantiates a new CreatePurchaseRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAmount

`func (o *CreatePurchaseRequest) GetAmount() int64`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *CreatePurchaseRequest) GetAmountOk() (*int64, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *CreatePurchaseRequest) SetAmount(v int64)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *CreatePurchaseRequest) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetWage

`func (o *CreatePurchaseRequest) GetWage() int64`

GetWage returns the Wage field if non-nil, zero value otherwise.

### GetWageOk

`func (o *CreatePurchaseRequest) GetWageOk() (*int64, bool)`

GetWageOk returns a tuple with the Wage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWage

`func (o *CreatePurchaseRequest) SetWage(v int64)`

SetWage sets Wage field to given value.

### HasWage

`func (o *CreatePurchaseRequest) HasWage() bool`

HasWage returns a boolean if a field has been set.

### GetCurrency

`func (o *CreatePurchaseRequest) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *CreatePurchaseRequest) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *CreatePurchaseRequest) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *CreatePurchaseRequest) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetClientReferenceNumber

`func (o *CreatePurchaseRequest) GetClientReferenceNumber() string`

GetClientReferenceNumber returns the ClientReferenceNumber field if non-nil, zero value otherwise.

### GetClientReferenceNumberOk

`func (o *CreatePurchaseRequest) GetClientReferenceNumberOk() (*string, bool)`

GetClientReferenceNumberOk returns a tuple with the ClientReferenceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientReferenceNumber

`func (o *CreatePurchaseRequest) SetClientReferenceNumber(v string)`

SetClientReferenceNumber sets ClientReferenceNumber field to given value.

### HasClientReferenceNumber

`func (o *CreatePurchaseRequest) HasClientReferenceNumber() bool`

HasClientReferenceNumber returns a boolean if a field has been set.

### GetPayerMobileNumber

`func (o *CreatePurchaseRequest) GetPayerMobileNumber() string`

GetPayerMobileNumber returns the PayerMobileNumber field if non-nil, zero value otherwise.

### GetPayerMobileNumberOk

`func (o *CreatePurchaseRequest) GetPayerMobileNumberOk() (*string, bool)`

GetPayerMobileNumberOk returns a tuple with the PayerMobileNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayerMobileNumber

`func (o *CreatePurchaseRequest) SetPayerMobileNumber(v string)`

SetPayerMobileNumber sets PayerMobileNumber field to given value.

### HasPayerMobileNumber

`func (o *CreatePurchaseRequest) HasPayerMobileNumber() bool`

HasPayerMobileNumber returns a boolean if a field has been set.

### GetCheckPayerMobileNumber

`func (o *CreatePurchaseRequest) GetCheckPayerMobileNumber() bool`

GetCheckPayerMobileNumber returns the CheckPayerMobileNumber field if non-nil, zero value otherwise.

### GetCheckPayerMobileNumberOk

`func (o *CreatePurchaseRequest) GetCheckPayerMobileNumberOk() (*bool, bool)`

GetCheckPayerMobileNumberOk returns a tuple with the CheckPayerMobileNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckPayerMobileNumber

`func (o *CreatePurchaseRequest) SetCheckPayerMobileNumber(v bool)`

SetCheckPayerMobileNumber sets CheckPayerMobileNumber field to given value.

### HasCheckPayerMobileNumber

`func (o *CreatePurchaseRequest) HasCheckPayerMobileNumber() bool`

HasCheckPayerMobileNumber returns a boolean if a field has been set.

### GetPayerCardNumber

`func (o *CreatePurchaseRequest) GetPayerCardNumber() string`

GetPayerCardNumber returns the PayerCardNumber field if non-nil, zero value otherwise.

### GetPayerCardNumberOk

`func (o *CreatePurchaseRequest) GetPayerCardNumberOk() (*string, bool)`

GetPayerCardNumberOk returns a tuple with the PayerCardNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayerCardNumber

`func (o *CreatePurchaseRequest) SetPayerCardNumber(v string)`

SetPayerCardNumber sets PayerCardNumber field to given value.

### HasPayerCardNumber

`func (o *CreatePurchaseRequest) HasPayerCardNumber() bool`

HasPayerCardNumber returns a boolean if a field has been set.

### GetPayerCardNumbers

`func (o *CreatePurchaseRequest) GetPayerCardNumbers() []string`

GetPayerCardNumbers returns the PayerCardNumbers field if non-nil, zero value otherwise.

### GetPayerCardNumbersOk

`func (o *CreatePurchaseRequest) GetPayerCardNumbersOk() (*[]string, bool)`

GetPayerCardNumbersOk returns a tuple with the PayerCardNumbers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayerCardNumbers

`func (o *CreatePurchaseRequest) SetPayerCardNumbers(v []string)`

SetPayerCardNumbers sets PayerCardNumbers field to given value.

### HasPayerCardNumbers

`func (o *CreatePurchaseRequest) HasPayerCardNumbers() bool`

HasPayerCardNumbers returns a boolean if a field has been set.

### GetPayerNationalCode

`func (o *CreatePurchaseRequest) GetPayerNationalCode() string`

GetPayerNationalCode returns the PayerNationalCode field if non-nil, zero value otherwise.

### GetPayerNationalCodeOk

`func (o *CreatePurchaseRequest) GetPayerNationalCodeOk() (*string, bool)`

GetPayerNationalCodeOk returns a tuple with the PayerNationalCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayerNationalCode

`func (o *CreatePurchaseRequest) SetPayerNationalCode(v string)`

SetPayerNationalCode sets PayerNationalCode field to given value.

### HasPayerNationalCode

`func (o *CreatePurchaseRequest) HasPayerNationalCode() bool`

HasPayerNationalCode returns a boolean if a field has been set.

### GetDescription

`func (o *CreatePurchaseRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreatePurchaseRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreatePurchaseRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CreatePurchaseRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetSwitching

`func (o *CreatePurchaseRequest) GetSwitching() TerminalSwitchingDto`

GetSwitching returns the Switching field if non-nil, zero value otherwise.

### GetSwitchingOk

`func (o *CreatePurchaseRequest) GetSwitchingOk() (*TerminalSwitchingDto, bool)`

GetSwitchingOk returns a tuple with the Switching field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSwitching

`func (o *CreatePurchaseRequest) SetSwitching(v TerminalSwitchingDto)`

SetSwitching sets Switching field to given value.

### HasSwitching

`func (o *CreatePurchaseRequest) HasSwitching() bool`

HasSwitching returns a boolean if a field has been set.

### GetAdditionalData

`func (o *CreatePurchaseRequest) GetAdditionalData() map[string]interface{}`

GetAdditionalData returns the AdditionalData field if non-nil, zero value otherwise.

### GetAdditionalDataOk

`func (o *CreatePurchaseRequest) GetAdditionalDataOk() (*map[string]interface{}, bool)`

GetAdditionalDataOk returns a tuple with the AdditionalData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditionalData

`func (o *CreatePurchaseRequest) SetAdditionalData(v map[string]interface{})`

SetAdditionalData sets AdditionalData field to given value.

### HasAdditionalData

`func (o *CreatePurchaseRequest) HasAdditionalData() bool`

HasAdditionalData returns a boolean if a field has been set.

### GetCallbackUrl

`func (o *CreatePurchaseRequest) GetCallbackUrl() string`

GetCallbackUrl returns the CallbackUrl field if non-nil, zero value otherwise.

### GetCallbackUrlOk

`func (o *CreatePurchaseRequest) GetCallbackUrlOk() (*string, bool)`

GetCallbackUrlOk returns a tuple with the CallbackUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallbackUrl

`func (o *CreatePurchaseRequest) SetCallbackUrl(v string)`

SetCallbackUrl sets CallbackUrl field to given value.

### HasCallbackUrl

`func (o *CreatePurchaseRequest) HasCallbackUrl() bool`

HasCallbackUrl returns a boolean if a field has been set.

### GetUserIdentifier

`func (o *CreatePurchaseRequest) GetUserIdentifier() string`

GetUserIdentifier returns the UserIdentifier field if non-nil, zero value otherwise.

### GetUserIdentifierOk

`func (o *CreatePurchaseRequest) GetUserIdentifierOk() (*string, bool)`

GetUserIdentifierOk returns a tuple with the UserIdentifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserIdentifier

`func (o *CreatePurchaseRequest) SetUserIdentifier(v string)`

SetUserIdentifier sets UserIdentifier field to given value.

### HasUserIdentifier

`func (o *CreatePurchaseRequest) HasUserIdentifier() bool`

HasUserIdentifier returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


