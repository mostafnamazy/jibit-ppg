# \PurchaseAPIAPI

All URIs are relative to *https://napi.jibit.ir/ppg*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreatePurchase**](PurchaseAPIAPI.md#CreatePurchase) | **Post** /v3/purchases | Create Purchase
[**FilterPurchaseHistories**](PurchaseAPIAPI.md#FilterPurchaseHistories) | **Get** /v3/purchases/histories | Filter Purchase Histories
[**FilterPurchases**](PurchaseAPIAPI.md#FilterPurchases) | **Get** /v3/purchases | Filter Purchases
[**ReversePurchase**](PurchaseAPIAPI.md#ReversePurchase) | **Post** /v3/purchases/reverse | Reverse Purchase
[**VerifyPurchase**](PurchaseAPIAPI.md#VerifyPurchase) | **Post** /v3/purchases/{purchaseId}/verify | Verify Purchase



## CreatePurchase

> CreatePurchaseResult CreatePurchase(ctx).CreatePurchaseRequest(createPurchaseRequest).Execute()

Create Purchase



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/mostafnamazy/jibit-ppg"
)

func main() {
	createPurchaseRequest := *openapiclient.NewCreatePurchaseRequest() // CreatePurchaseRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PurchaseAPIAPI.CreatePurchase(context.Background()).CreatePurchaseRequest(createPurchaseRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseAPIAPI.CreatePurchase``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreatePurchase`: CreatePurchaseResult
	fmt.Fprintf(os.Stdout, "Response from `PurchaseAPIAPI.CreatePurchase`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreatePurchaseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createPurchaseRequest** | [**CreatePurchaseRequest**](CreatePurchaseRequest.md) |  | 

### Return type

[**CreatePurchaseResult**](CreatePurchaseResult.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FilterPurchaseHistories

> IdPaginatedDetailedPurchaseHistoryDto FilterPurchaseHistories(ctx).Criteria(criteria).Execute()

Filter Purchase Histories



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/mostafnamazy/jibit-ppg"
)

func main() {
	criteria := *openapiclient.NewPurchaseHistoryFilterCriteria() // PurchaseHistoryFilterCriteria | Encapsulates the criteria for querying purchase history within a specified date range.  Supports pagination via `nextPageId` for faster loading, and optional page/size parameters.  <p>  Example Usage:  from: `2024-10-15T13:00:00Z`  to:   `2024-10-15T14:00:00Z`

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PurchaseAPIAPI.FilterPurchaseHistories(context.Background()).Criteria(criteria).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseAPIAPI.FilterPurchaseHistories``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FilterPurchaseHistories`: IdPaginatedDetailedPurchaseHistoryDto
	fmt.Fprintf(os.Stdout, "Response from `PurchaseAPIAPI.FilterPurchaseHistories`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFilterPurchaseHistoriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **criteria** | [**PurchaseHistoryFilterCriteria**](PurchaseHistoryFilterCriteria.md) | Encapsulates the criteria for querying purchase history within a specified date range.  Supports pagination via &#x60;nextPageId&#x60; for faster loading, and optional page/size parameters.  &lt;p&gt;  Example Usage:  from: &#x60;2024-10-15T13:00:00Z&#x60;  to:   &#x60;2024-10-15T14:00:00Z&#x60; | 

### Return type

[**IdPaginatedDetailedPurchaseHistoryDto**](IdPaginatedDetailedPurchaseHistoryDto.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FilterPurchases

> PaginatedDetailedPurchaseDto FilterPurchases(ctx).Criteria(criteria).Execute()

Filter Purchases



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/mostafnamazy/jibit-ppg"
)

func main() {
	criteria := *openapiclient.NewPurchaseFilterCriteria() // PurchaseFilterCriteria | Encapsulates the information to filter purchases.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PurchaseAPIAPI.FilterPurchases(context.Background()).Criteria(criteria).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseAPIAPI.FilterPurchases``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FilterPurchases`: PaginatedDetailedPurchaseDto
	fmt.Fprintf(os.Stdout, "Response from `PurchaseAPIAPI.FilterPurchases`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFilterPurchasesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **criteria** | [**PurchaseFilterCriteria**](PurchaseFilterCriteria.md) | Encapsulates the information to filter purchases. | 

### Return type

[**PaginatedDetailedPurchaseDto**](PaginatedDetailedPurchaseDto.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ReversePurchase

> ReversePurchaseResult ReversePurchase(ctx).ReversePurchaseRequest(reversePurchaseRequest).Execute()

Reverse Purchase



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/mostafnamazy/jibit-ppg"
)

func main() {
	reversePurchaseRequest := *openapiclient.NewReversePurchaseRequest() // ReversePurchaseRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PurchaseAPIAPI.ReversePurchase(context.Background()).ReversePurchaseRequest(reversePurchaseRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseAPIAPI.ReversePurchase``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ReversePurchase`: ReversePurchaseResult
	fmt.Fprintf(os.Stdout, "Response from `PurchaseAPIAPI.ReversePurchase`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiReversePurchaseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **reversePurchaseRequest** | [**ReversePurchaseRequest**](ReversePurchaseRequest.md) |  | 

### Return type

[**ReversePurchaseResult**](ReversePurchaseResult.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## VerifyPurchase

> VerifyPurchaseResult VerifyPurchase(ctx, purchaseId).Execute()

Verify Purchase



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/mostafnamazy/jibit-ppg"
)

func main() {
	purchaseId := int64(789) // int64 | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PurchaseAPIAPI.VerifyPurchase(context.Background(), purchaseId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseAPIAPI.VerifyPurchase``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `VerifyPurchase`: VerifyPurchaseResult
	fmt.Fprintf(os.Stdout, "Response from `PurchaseAPIAPI.VerifyPurchase`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**purchaseId** | **int64** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiVerifyPurchaseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**VerifyPurchaseResult**](VerifyPurchaseResult.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

