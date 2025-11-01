# ClientBalances

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Balances** | Pointer to [**[]Balance**](Balance.md) | Represents the list of ledger account balances which may contain the default wallet and pre-paid/post-paid fees and settleable wallet. | [optional] 

## Methods

### NewClientBalances

`func NewClientBalances() *ClientBalances`

NewClientBalances instantiates a new ClientBalances object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClientBalancesWithDefaults

`func NewClientBalancesWithDefaults() *ClientBalances`

NewClientBalancesWithDefaults instantiates a new ClientBalances object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBalances

`func (o *ClientBalances) GetBalances() []Balance`

GetBalances returns the Balances field if non-nil, zero value otherwise.

### GetBalancesOk

`func (o *ClientBalances) GetBalancesOk() (*[]Balance, bool)`

GetBalancesOk returns a tuple with the Balances field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBalances

`func (o *ClientBalances) SetBalances(v []Balance)`

SetBalances sets Balances field to given value.

### HasBalances

`func (o *ClientBalances) HasBalances() bool`

HasBalances returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


