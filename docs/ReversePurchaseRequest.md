# ReversePurchaseRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ClientReferenceNumber** | Pointer to **string** | Represents the reference number provided by client to trace the purchase in our system. | [optional] 
**PurchaseId** | Pointer to **int64** | Represents the purchase id. | [optional] 

## Methods

### NewReversePurchaseRequest

`func NewReversePurchaseRequest() *ReversePurchaseRequest`

NewReversePurchaseRequest instantiates a new ReversePurchaseRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReversePurchaseRequestWithDefaults

`func NewReversePurchaseRequestWithDefaults() *ReversePurchaseRequest`

NewReversePurchaseRequestWithDefaults instantiates a new ReversePurchaseRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetClientReferenceNumber

`func (o *ReversePurchaseRequest) GetClientReferenceNumber() string`

GetClientReferenceNumber returns the ClientReferenceNumber field if non-nil, zero value otherwise.

### GetClientReferenceNumberOk

`func (o *ReversePurchaseRequest) GetClientReferenceNumberOk() (*string, bool)`

GetClientReferenceNumberOk returns a tuple with the ClientReferenceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientReferenceNumber

`func (o *ReversePurchaseRequest) SetClientReferenceNumber(v string)`

SetClientReferenceNumber sets ClientReferenceNumber field to given value.

### HasClientReferenceNumber

`func (o *ReversePurchaseRequest) HasClientReferenceNumber() bool`

HasClientReferenceNumber returns a boolean if a field has been set.

### GetPurchaseId

`func (o *ReversePurchaseRequest) GetPurchaseId() int64`

GetPurchaseId returns the PurchaseId field if non-nil, zero value otherwise.

### GetPurchaseIdOk

`func (o *ReversePurchaseRequest) GetPurchaseIdOk() (*int64, bool)`

GetPurchaseIdOk returns a tuple with the PurchaseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurchaseId

`func (o *ReversePurchaseRequest) SetPurchaseId(v int64)`

SetPurchaseId sets PurchaseId field to given value.

### HasPurchaseId

`func (o *ReversePurchaseRequest) HasPurchaseId() bool`

HasPurchaseId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


