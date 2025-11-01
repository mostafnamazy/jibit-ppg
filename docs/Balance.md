# Balance

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BalanceType** | Pointer to **string** | Represents the balance type. Its possible values are:  &lt;p&gt;  &#x60;WLT&#x60;: Indicates the default (not settleable) wallet of the client. It is the default balance type.  &#x60;STL&#x60;: Indicates the settleable wallet of client.  &#x60;FEE&#x60;: Indicates the post-paid fee that client needs to pay as the service subscription fee.  &#x60;SHW&#x60;: Indicates the pre-paid fee (Shaparak Wage) that we would subtract from settlement amount as the service subscription fee.  &#x60;BLK&#x60;: Indicates the blocked balance from the client &#x60;STL&#x60; balance type. | [optional] 
**Amount** | Pointer to **int64** | Represents the amount of current balance type. | [optional] 
**Currency** | Pointer to **string** | Represents the currency of current balance type. | [optional] 

## Methods

### NewBalance

`func NewBalance() *Balance`

NewBalance instantiates a new Balance object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBalanceWithDefaults

`func NewBalanceWithDefaults() *Balance`

NewBalanceWithDefaults instantiates a new Balance object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBalanceType

`func (o *Balance) GetBalanceType() string`

GetBalanceType returns the BalanceType field if non-nil, zero value otherwise.

### GetBalanceTypeOk

`func (o *Balance) GetBalanceTypeOk() (*string, bool)`

GetBalanceTypeOk returns a tuple with the BalanceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBalanceType

`func (o *Balance) SetBalanceType(v string)`

SetBalanceType sets BalanceType field to given value.

### HasBalanceType

`func (o *Balance) HasBalanceType() bool`

HasBalanceType returns a boolean if a field has been set.

### GetAmount

`func (o *Balance) GetAmount() int64`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *Balance) GetAmountOk() (*int64, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *Balance) SetAmount(v int64)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *Balance) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetCurrency

`func (o *Balance) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *Balance) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *Balance) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *Balance) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


