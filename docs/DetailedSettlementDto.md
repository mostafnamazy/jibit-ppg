# DetailedSettlementDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SettlementId** | Pointer to **int64** | Represents the settlement identifier. | [optional] 
**TerminalId** | Pointer to **string** | Represents the terminal Id. | [optional] 
**FileName** | Pointer to **string** | Represents the file name which was sent to shaparak. | [optional] 
**State** | Pointer to **string** | Represents the settlement state. | [optional] 
**Amount** | Pointer to **int64** | Represents the settlement amount. | [optional] 
**Wage** | Pointer to **int64** | Represents the settlement wage. | [optional] 
**DirectSettlement** | Pointer to **bool** | Represents whether settlement is direct settled. | [optional] 
**Currency** | Pointer to **string** | Represents the currency type. | [optional] 
**Cutoff** | Pointer to **string** | Cutoff time. | [optional] 
**AcceptorCode** | Pointer to **string** | Represents the acceptor code. | [optional] 
**LedgerAccount** | Pointer to **string** | Represents ledger account of client. | [optional] 
**Iin** | Pointer to **int64** | Represents the iin. | [optional] 
**PaymentFacilitatorIban** | Pointer to **string** | Represents the pf Iban. | [optional] 
**SettlementIban** | Pointer to **string** | Represents the settlement Iban. | [optional] 
**ResellerCode** | Pointer to **string** | Represents the reseller code | [optional] 
**AffiliateFee** | Pointer to **int64** | Represents the reseller&#39;s affiliate fee. | [optional] 
**ShaparakFailReason** | Pointer to **string** | Represents the shaparak fail reason. | [optional] 
**ShaparakReferenceNumber** | Pointer to **string** | Represents the shaparak reference number. | [optional] 
**ShaparakTrackingNumber** | Pointer to **string** | Represents the shaparak tracking number. | [optional] 
**ShaparakTransactionId** | Pointer to **string** | Represents the shaparak tracking id. | [optional] 
**CreatedAt** | Pointer to **time.Time** | When was the settlement created. | [optional] 
**ModifiedAt** | Pointer to **time.Time** | When was the settlement modified. | [optional] 
**SettledAt** | Pointer to **time.Time** | When was the settlement settled. | [optional] 

## Methods

### NewDetailedSettlementDto

`func NewDetailedSettlementDto() *DetailedSettlementDto`

NewDetailedSettlementDto instantiates a new DetailedSettlementDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDetailedSettlementDtoWithDefaults

`func NewDetailedSettlementDtoWithDefaults() *DetailedSettlementDto`

NewDetailedSettlementDtoWithDefaults instantiates a new DetailedSettlementDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSettlementId

`func (o *DetailedSettlementDto) GetSettlementId() int64`

GetSettlementId returns the SettlementId field if non-nil, zero value otherwise.

### GetSettlementIdOk

`func (o *DetailedSettlementDto) GetSettlementIdOk() (*int64, bool)`

GetSettlementIdOk returns a tuple with the SettlementId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettlementId

`func (o *DetailedSettlementDto) SetSettlementId(v int64)`

SetSettlementId sets SettlementId field to given value.

### HasSettlementId

`func (o *DetailedSettlementDto) HasSettlementId() bool`

HasSettlementId returns a boolean if a field has been set.

### GetTerminalId

`func (o *DetailedSettlementDto) GetTerminalId() string`

GetTerminalId returns the TerminalId field if non-nil, zero value otherwise.

### GetTerminalIdOk

`func (o *DetailedSettlementDto) GetTerminalIdOk() (*string, bool)`

GetTerminalIdOk returns a tuple with the TerminalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTerminalId

`func (o *DetailedSettlementDto) SetTerminalId(v string)`

SetTerminalId sets TerminalId field to given value.

### HasTerminalId

`func (o *DetailedSettlementDto) HasTerminalId() bool`

HasTerminalId returns a boolean if a field has been set.

### GetFileName

`func (o *DetailedSettlementDto) GetFileName() string`

GetFileName returns the FileName field if non-nil, zero value otherwise.

### GetFileNameOk

`func (o *DetailedSettlementDto) GetFileNameOk() (*string, bool)`

GetFileNameOk returns a tuple with the FileName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileName

`func (o *DetailedSettlementDto) SetFileName(v string)`

SetFileName sets FileName field to given value.

### HasFileName

`func (o *DetailedSettlementDto) HasFileName() bool`

HasFileName returns a boolean if a field has been set.

### GetState

`func (o *DetailedSettlementDto) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *DetailedSettlementDto) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *DetailedSettlementDto) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *DetailedSettlementDto) HasState() bool`

HasState returns a boolean if a field has been set.

### GetAmount

`func (o *DetailedSettlementDto) GetAmount() int64`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *DetailedSettlementDto) GetAmountOk() (*int64, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *DetailedSettlementDto) SetAmount(v int64)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *DetailedSettlementDto) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetWage

`func (o *DetailedSettlementDto) GetWage() int64`

GetWage returns the Wage field if non-nil, zero value otherwise.

### GetWageOk

`func (o *DetailedSettlementDto) GetWageOk() (*int64, bool)`

GetWageOk returns a tuple with the Wage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWage

`func (o *DetailedSettlementDto) SetWage(v int64)`

SetWage sets Wage field to given value.

### HasWage

`func (o *DetailedSettlementDto) HasWage() bool`

HasWage returns a boolean if a field has been set.

### GetDirectSettlement

`func (o *DetailedSettlementDto) GetDirectSettlement() bool`

GetDirectSettlement returns the DirectSettlement field if non-nil, zero value otherwise.

### GetDirectSettlementOk

`func (o *DetailedSettlementDto) GetDirectSettlementOk() (*bool, bool)`

GetDirectSettlementOk returns a tuple with the DirectSettlement field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDirectSettlement

`func (o *DetailedSettlementDto) SetDirectSettlement(v bool)`

SetDirectSettlement sets DirectSettlement field to given value.

### HasDirectSettlement

`func (o *DetailedSettlementDto) HasDirectSettlement() bool`

HasDirectSettlement returns a boolean if a field has been set.

### GetCurrency

`func (o *DetailedSettlementDto) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *DetailedSettlementDto) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *DetailedSettlementDto) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *DetailedSettlementDto) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetCutoff

`func (o *DetailedSettlementDto) GetCutoff() string`

GetCutoff returns the Cutoff field if non-nil, zero value otherwise.

### GetCutoffOk

`func (o *DetailedSettlementDto) GetCutoffOk() (*string, bool)`

GetCutoffOk returns a tuple with the Cutoff field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCutoff

`func (o *DetailedSettlementDto) SetCutoff(v string)`

SetCutoff sets Cutoff field to given value.

### HasCutoff

`func (o *DetailedSettlementDto) HasCutoff() bool`

HasCutoff returns a boolean if a field has been set.

### GetAcceptorCode

`func (o *DetailedSettlementDto) GetAcceptorCode() string`

GetAcceptorCode returns the AcceptorCode field if non-nil, zero value otherwise.

### GetAcceptorCodeOk

`func (o *DetailedSettlementDto) GetAcceptorCodeOk() (*string, bool)`

GetAcceptorCodeOk returns a tuple with the AcceptorCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcceptorCode

`func (o *DetailedSettlementDto) SetAcceptorCode(v string)`

SetAcceptorCode sets AcceptorCode field to given value.

### HasAcceptorCode

`func (o *DetailedSettlementDto) HasAcceptorCode() bool`

HasAcceptorCode returns a boolean if a field has been set.

### GetLedgerAccount

`func (o *DetailedSettlementDto) GetLedgerAccount() string`

GetLedgerAccount returns the LedgerAccount field if non-nil, zero value otherwise.

### GetLedgerAccountOk

`func (o *DetailedSettlementDto) GetLedgerAccountOk() (*string, bool)`

GetLedgerAccountOk returns a tuple with the LedgerAccount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLedgerAccount

`func (o *DetailedSettlementDto) SetLedgerAccount(v string)`

SetLedgerAccount sets LedgerAccount field to given value.

### HasLedgerAccount

`func (o *DetailedSettlementDto) HasLedgerAccount() bool`

HasLedgerAccount returns a boolean if a field has been set.

### GetIin

`func (o *DetailedSettlementDto) GetIin() int64`

GetIin returns the Iin field if non-nil, zero value otherwise.

### GetIinOk

`func (o *DetailedSettlementDto) GetIinOk() (*int64, bool)`

GetIinOk returns a tuple with the Iin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIin

`func (o *DetailedSettlementDto) SetIin(v int64)`

SetIin sets Iin field to given value.

### HasIin

`func (o *DetailedSettlementDto) HasIin() bool`

HasIin returns a boolean if a field has been set.

### GetPaymentFacilitatorIban

`func (o *DetailedSettlementDto) GetPaymentFacilitatorIban() string`

GetPaymentFacilitatorIban returns the PaymentFacilitatorIban field if non-nil, zero value otherwise.

### GetPaymentFacilitatorIbanOk

`func (o *DetailedSettlementDto) GetPaymentFacilitatorIbanOk() (*string, bool)`

GetPaymentFacilitatorIbanOk returns a tuple with the PaymentFacilitatorIban field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentFacilitatorIban

`func (o *DetailedSettlementDto) SetPaymentFacilitatorIban(v string)`

SetPaymentFacilitatorIban sets PaymentFacilitatorIban field to given value.

### HasPaymentFacilitatorIban

`func (o *DetailedSettlementDto) HasPaymentFacilitatorIban() bool`

HasPaymentFacilitatorIban returns a boolean if a field has been set.

### GetSettlementIban

`func (o *DetailedSettlementDto) GetSettlementIban() string`

GetSettlementIban returns the SettlementIban field if non-nil, zero value otherwise.

### GetSettlementIbanOk

`func (o *DetailedSettlementDto) GetSettlementIbanOk() (*string, bool)`

GetSettlementIbanOk returns a tuple with the SettlementIban field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettlementIban

`func (o *DetailedSettlementDto) SetSettlementIban(v string)`

SetSettlementIban sets SettlementIban field to given value.

### HasSettlementIban

`func (o *DetailedSettlementDto) HasSettlementIban() bool`

HasSettlementIban returns a boolean if a field has been set.

### GetResellerCode

`func (o *DetailedSettlementDto) GetResellerCode() string`

GetResellerCode returns the ResellerCode field if non-nil, zero value otherwise.

### GetResellerCodeOk

`func (o *DetailedSettlementDto) GetResellerCodeOk() (*string, bool)`

GetResellerCodeOk returns a tuple with the ResellerCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResellerCode

`func (o *DetailedSettlementDto) SetResellerCode(v string)`

SetResellerCode sets ResellerCode field to given value.

### HasResellerCode

`func (o *DetailedSettlementDto) HasResellerCode() bool`

HasResellerCode returns a boolean if a field has been set.

### GetAffiliateFee

`func (o *DetailedSettlementDto) GetAffiliateFee() int64`

GetAffiliateFee returns the AffiliateFee field if non-nil, zero value otherwise.

### GetAffiliateFeeOk

`func (o *DetailedSettlementDto) GetAffiliateFeeOk() (*int64, bool)`

GetAffiliateFeeOk returns a tuple with the AffiliateFee field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAffiliateFee

`func (o *DetailedSettlementDto) SetAffiliateFee(v int64)`

SetAffiliateFee sets AffiliateFee field to given value.

### HasAffiliateFee

`func (o *DetailedSettlementDto) HasAffiliateFee() bool`

HasAffiliateFee returns a boolean if a field has been set.

### GetShaparakFailReason

`func (o *DetailedSettlementDto) GetShaparakFailReason() string`

GetShaparakFailReason returns the ShaparakFailReason field if non-nil, zero value otherwise.

### GetShaparakFailReasonOk

`func (o *DetailedSettlementDto) GetShaparakFailReasonOk() (*string, bool)`

GetShaparakFailReasonOk returns a tuple with the ShaparakFailReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShaparakFailReason

`func (o *DetailedSettlementDto) SetShaparakFailReason(v string)`

SetShaparakFailReason sets ShaparakFailReason field to given value.

### HasShaparakFailReason

`func (o *DetailedSettlementDto) HasShaparakFailReason() bool`

HasShaparakFailReason returns a boolean if a field has been set.

### GetShaparakReferenceNumber

`func (o *DetailedSettlementDto) GetShaparakReferenceNumber() string`

GetShaparakReferenceNumber returns the ShaparakReferenceNumber field if non-nil, zero value otherwise.

### GetShaparakReferenceNumberOk

`func (o *DetailedSettlementDto) GetShaparakReferenceNumberOk() (*string, bool)`

GetShaparakReferenceNumberOk returns a tuple with the ShaparakReferenceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShaparakReferenceNumber

`func (o *DetailedSettlementDto) SetShaparakReferenceNumber(v string)`

SetShaparakReferenceNumber sets ShaparakReferenceNumber field to given value.

### HasShaparakReferenceNumber

`func (o *DetailedSettlementDto) HasShaparakReferenceNumber() bool`

HasShaparakReferenceNumber returns a boolean if a field has been set.

### GetShaparakTrackingNumber

`func (o *DetailedSettlementDto) GetShaparakTrackingNumber() string`

GetShaparakTrackingNumber returns the ShaparakTrackingNumber field if non-nil, zero value otherwise.

### GetShaparakTrackingNumberOk

`func (o *DetailedSettlementDto) GetShaparakTrackingNumberOk() (*string, bool)`

GetShaparakTrackingNumberOk returns a tuple with the ShaparakTrackingNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShaparakTrackingNumber

`func (o *DetailedSettlementDto) SetShaparakTrackingNumber(v string)`

SetShaparakTrackingNumber sets ShaparakTrackingNumber field to given value.

### HasShaparakTrackingNumber

`func (o *DetailedSettlementDto) HasShaparakTrackingNumber() bool`

HasShaparakTrackingNumber returns a boolean if a field has been set.

### GetShaparakTransactionId

`func (o *DetailedSettlementDto) GetShaparakTransactionId() string`

GetShaparakTransactionId returns the ShaparakTransactionId field if non-nil, zero value otherwise.

### GetShaparakTransactionIdOk

`func (o *DetailedSettlementDto) GetShaparakTransactionIdOk() (*string, bool)`

GetShaparakTransactionIdOk returns a tuple with the ShaparakTransactionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShaparakTransactionId

`func (o *DetailedSettlementDto) SetShaparakTransactionId(v string)`

SetShaparakTransactionId sets ShaparakTransactionId field to given value.

### HasShaparakTransactionId

`func (o *DetailedSettlementDto) HasShaparakTransactionId() bool`

HasShaparakTransactionId returns a boolean if a field has been set.

### GetCreatedAt

`func (o *DetailedSettlementDto) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *DetailedSettlementDto) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *DetailedSettlementDto) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *DetailedSettlementDto) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetModifiedAt

`func (o *DetailedSettlementDto) GetModifiedAt() time.Time`

GetModifiedAt returns the ModifiedAt field if non-nil, zero value otherwise.

### GetModifiedAtOk

`func (o *DetailedSettlementDto) GetModifiedAtOk() (*time.Time, bool)`

GetModifiedAtOk returns a tuple with the ModifiedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedAt

`func (o *DetailedSettlementDto) SetModifiedAt(v time.Time)`

SetModifiedAt sets ModifiedAt field to given value.

### HasModifiedAt

`func (o *DetailedSettlementDto) HasModifiedAt() bool`

HasModifiedAt returns a boolean if a field has been set.

### GetSettledAt

`func (o *DetailedSettlementDto) GetSettledAt() time.Time`

GetSettledAt returns the SettledAt field if non-nil, zero value otherwise.

### GetSettledAtOk

`func (o *DetailedSettlementDto) GetSettledAtOk() (*time.Time, bool)`

GetSettledAtOk returns a tuple with the SettledAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettledAt

`func (o *DetailedSettlementDto) SetSettledAt(v time.Time)`

SetSettledAt sets SettledAt field to given value.

### HasSettledAt

`func (o *DetailedSettlementDto) HasSettledAt() bool`

HasSettledAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


