# TerminalDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NaturalId** | Pointer to **string** | Represents the unique natural identifier of a terminal. | [optional] 
**ClientCode** | Pointer to **string** | Represents the unique code associated with a client. | [optional] 
**ClientName** | Pointer to **string** | Represents the name of the client associated with the terminal. &#x60;Snapp Pay&#x60; | [optional] 
**PspName** | Pointer to **string** | Represents the name of payment service provider (PSP) associated with the terminal.                                        Possible values are: &#x60;saman-ipg&#x60;, &#x60;sepehr-ipg&#x60;, &#x60;behpardakht-ipg&#x60; | [optional] 
**PspTerminalId** | Pointer to **string** | The unique identifier of the PSP terminal.                                        This ID is used to associate a terminal with a specific PSP                                        and is essential for processing transactions through that terminal. | [optional] 
**PspMerchantNumber** | Pointer to **string** | Represents the merchant number associated with a specific PSP.                                        This field is used to uniquely identify a merchant in the PSP system. | [optional] 
**Type** | Pointer to **string** | Represents the type of the terminal in the system.                                        It indicates the category of the terminal and is used to define                                        its behavior and processing type. The terminal can belong to                                        various types such as normal, payment facilitation, or auto-settling. | [optional] 
**DirectSettlement** | Pointer to **bool** | Represents whether the terminal supports direct settlement.                                        A terminal with direct settlement enabled allows funds to be                                        transferred directly to the settlement account without intermediary steps. | [optional] 
**Priority** | Pointer to **int32** | Represents the priority of the terminal.                                        This value generally determines the importance level                                        of the terminal in processing or ordering operations.                                        &lt;p&gt;                                        Higher priority means a greater chance for terminal to be used. | [optional] 
**IsAutoVerifyEnabled** | Pointer to **bool** | Indicates whether auto-verification is enabled for the terminal. | [optional] 
**IsCheckPayerMobileNumberActive** | Pointer to **bool** | Indicates whether the functionality to check if the payer&#39;s mobile number is active                                        is enabled or not. This field is used in scenarios where verifying the active status                                        of the payer&#39;s mobile number is required for processing. | [optional] 
**IsCheckPayerNationalCodeActive** | Pointer to **bool** | Indicates whether the functionality to check if the payer&#39;s national code is                                        enabled or not. | [optional] 
**IsSingleCardFreezeActive** | Pointer to **bool** | Indicates whether the functionality to freeze a single card number in IPG page                                        is enabled or not. | [optional] 
**CreatedAt** | Pointer to **time.Time** | Represents the timestamp indicating when the &#x60;TerminalDto&#x60; instance was created.                                        This field is expected to store the creation time in the UTC timezone. | [optional] 

## Methods

### NewTerminalDto

`func NewTerminalDto() *TerminalDto`

NewTerminalDto instantiates a new TerminalDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTerminalDtoWithDefaults

`func NewTerminalDtoWithDefaults() *TerminalDto`

NewTerminalDtoWithDefaults instantiates a new TerminalDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNaturalId

`func (o *TerminalDto) GetNaturalId() string`

GetNaturalId returns the NaturalId field if non-nil, zero value otherwise.

### GetNaturalIdOk

`func (o *TerminalDto) GetNaturalIdOk() (*string, bool)`

GetNaturalIdOk returns a tuple with the NaturalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNaturalId

`func (o *TerminalDto) SetNaturalId(v string)`

SetNaturalId sets NaturalId field to given value.

### HasNaturalId

`func (o *TerminalDto) HasNaturalId() bool`

HasNaturalId returns a boolean if a field has been set.

### GetClientCode

`func (o *TerminalDto) GetClientCode() string`

GetClientCode returns the ClientCode field if non-nil, zero value otherwise.

### GetClientCodeOk

`func (o *TerminalDto) GetClientCodeOk() (*string, bool)`

GetClientCodeOk returns a tuple with the ClientCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientCode

`func (o *TerminalDto) SetClientCode(v string)`

SetClientCode sets ClientCode field to given value.

### HasClientCode

`func (o *TerminalDto) HasClientCode() bool`

HasClientCode returns a boolean if a field has been set.

### GetClientName

`func (o *TerminalDto) GetClientName() string`

GetClientName returns the ClientName field if non-nil, zero value otherwise.

### GetClientNameOk

`func (o *TerminalDto) GetClientNameOk() (*string, bool)`

GetClientNameOk returns a tuple with the ClientName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientName

`func (o *TerminalDto) SetClientName(v string)`

SetClientName sets ClientName field to given value.

### HasClientName

`func (o *TerminalDto) HasClientName() bool`

HasClientName returns a boolean if a field has been set.

### GetPspName

`func (o *TerminalDto) GetPspName() string`

GetPspName returns the PspName field if non-nil, zero value otherwise.

### GetPspNameOk

`func (o *TerminalDto) GetPspNameOk() (*string, bool)`

GetPspNameOk returns a tuple with the PspName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPspName

`func (o *TerminalDto) SetPspName(v string)`

SetPspName sets PspName field to given value.

### HasPspName

`func (o *TerminalDto) HasPspName() bool`

HasPspName returns a boolean if a field has been set.

### GetPspTerminalId

`func (o *TerminalDto) GetPspTerminalId() string`

GetPspTerminalId returns the PspTerminalId field if non-nil, zero value otherwise.

### GetPspTerminalIdOk

`func (o *TerminalDto) GetPspTerminalIdOk() (*string, bool)`

GetPspTerminalIdOk returns a tuple with the PspTerminalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPspTerminalId

`func (o *TerminalDto) SetPspTerminalId(v string)`

SetPspTerminalId sets PspTerminalId field to given value.

### HasPspTerminalId

`func (o *TerminalDto) HasPspTerminalId() bool`

HasPspTerminalId returns a boolean if a field has been set.

### GetPspMerchantNumber

`func (o *TerminalDto) GetPspMerchantNumber() string`

GetPspMerchantNumber returns the PspMerchantNumber field if non-nil, zero value otherwise.

### GetPspMerchantNumberOk

`func (o *TerminalDto) GetPspMerchantNumberOk() (*string, bool)`

GetPspMerchantNumberOk returns a tuple with the PspMerchantNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPspMerchantNumber

`func (o *TerminalDto) SetPspMerchantNumber(v string)`

SetPspMerchantNumber sets PspMerchantNumber field to given value.

### HasPspMerchantNumber

`func (o *TerminalDto) HasPspMerchantNumber() bool`

HasPspMerchantNumber returns a boolean if a field has been set.

### GetType

`func (o *TerminalDto) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *TerminalDto) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *TerminalDto) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *TerminalDto) HasType() bool`

HasType returns a boolean if a field has been set.

### GetDirectSettlement

`func (o *TerminalDto) GetDirectSettlement() bool`

GetDirectSettlement returns the DirectSettlement field if non-nil, zero value otherwise.

### GetDirectSettlementOk

`func (o *TerminalDto) GetDirectSettlementOk() (*bool, bool)`

GetDirectSettlementOk returns a tuple with the DirectSettlement field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDirectSettlement

`func (o *TerminalDto) SetDirectSettlement(v bool)`

SetDirectSettlement sets DirectSettlement field to given value.

### HasDirectSettlement

`func (o *TerminalDto) HasDirectSettlement() bool`

HasDirectSettlement returns a boolean if a field has been set.

### GetPriority

`func (o *TerminalDto) GetPriority() int32`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *TerminalDto) GetPriorityOk() (*int32, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *TerminalDto) SetPriority(v int32)`

SetPriority sets Priority field to given value.

### HasPriority

`func (o *TerminalDto) HasPriority() bool`

HasPriority returns a boolean if a field has been set.

### GetIsAutoVerifyEnabled

`func (o *TerminalDto) GetIsAutoVerifyEnabled() bool`

GetIsAutoVerifyEnabled returns the IsAutoVerifyEnabled field if non-nil, zero value otherwise.

### GetIsAutoVerifyEnabledOk

`func (o *TerminalDto) GetIsAutoVerifyEnabledOk() (*bool, bool)`

GetIsAutoVerifyEnabledOk returns a tuple with the IsAutoVerifyEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsAutoVerifyEnabled

`func (o *TerminalDto) SetIsAutoVerifyEnabled(v bool)`

SetIsAutoVerifyEnabled sets IsAutoVerifyEnabled field to given value.

### HasIsAutoVerifyEnabled

`func (o *TerminalDto) HasIsAutoVerifyEnabled() bool`

HasIsAutoVerifyEnabled returns a boolean if a field has been set.

### GetIsCheckPayerMobileNumberActive

`func (o *TerminalDto) GetIsCheckPayerMobileNumberActive() bool`

GetIsCheckPayerMobileNumberActive returns the IsCheckPayerMobileNumberActive field if non-nil, zero value otherwise.

### GetIsCheckPayerMobileNumberActiveOk

`func (o *TerminalDto) GetIsCheckPayerMobileNumberActiveOk() (*bool, bool)`

GetIsCheckPayerMobileNumberActiveOk returns a tuple with the IsCheckPayerMobileNumberActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsCheckPayerMobileNumberActive

`func (o *TerminalDto) SetIsCheckPayerMobileNumberActive(v bool)`

SetIsCheckPayerMobileNumberActive sets IsCheckPayerMobileNumberActive field to given value.

### HasIsCheckPayerMobileNumberActive

`func (o *TerminalDto) HasIsCheckPayerMobileNumberActive() bool`

HasIsCheckPayerMobileNumberActive returns a boolean if a field has been set.

### GetIsCheckPayerNationalCodeActive

`func (o *TerminalDto) GetIsCheckPayerNationalCodeActive() bool`

GetIsCheckPayerNationalCodeActive returns the IsCheckPayerNationalCodeActive field if non-nil, zero value otherwise.

### GetIsCheckPayerNationalCodeActiveOk

`func (o *TerminalDto) GetIsCheckPayerNationalCodeActiveOk() (*bool, bool)`

GetIsCheckPayerNationalCodeActiveOk returns a tuple with the IsCheckPayerNationalCodeActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsCheckPayerNationalCodeActive

`func (o *TerminalDto) SetIsCheckPayerNationalCodeActive(v bool)`

SetIsCheckPayerNationalCodeActive sets IsCheckPayerNationalCodeActive field to given value.

### HasIsCheckPayerNationalCodeActive

`func (o *TerminalDto) HasIsCheckPayerNationalCodeActive() bool`

HasIsCheckPayerNationalCodeActive returns a boolean if a field has been set.

### GetIsSingleCardFreezeActive

`func (o *TerminalDto) GetIsSingleCardFreezeActive() bool`

GetIsSingleCardFreezeActive returns the IsSingleCardFreezeActive field if non-nil, zero value otherwise.

### GetIsSingleCardFreezeActiveOk

`func (o *TerminalDto) GetIsSingleCardFreezeActiveOk() (*bool, bool)`

GetIsSingleCardFreezeActiveOk returns a tuple with the IsSingleCardFreezeActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsSingleCardFreezeActive

`func (o *TerminalDto) SetIsSingleCardFreezeActive(v bool)`

SetIsSingleCardFreezeActive sets IsSingleCardFreezeActive field to given value.

### HasIsSingleCardFreezeActive

`func (o *TerminalDto) HasIsSingleCardFreezeActive() bool`

HasIsSingleCardFreezeActive returns a boolean if a field has been set.

### GetCreatedAt

`func (o *TerminalDto) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *TerminalDto) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *TerminalDto) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *TerminalDto) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


