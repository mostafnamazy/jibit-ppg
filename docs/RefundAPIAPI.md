# \RefundAPIAPI

All URIs are relative to *https://napi.jibit.ir/ppg*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CancelRefund**](RefundAPIAPI.md#CancelRefund) | **Post** /v3/purchases/refunds/{refundId}/cancel | Cancel Refund
[**IgnoreCancellingRefund**](RefundAPIAPI.md#IgnoreCancellingRefund) | **Post** /v3/purchases/refunds/{refundId}/ignore-cancellable | Ignore Cancelling Refund
[**InquiryRefund**](RefundAPIAPI.md#InquiryRefund) | **Get** /v3/purchases/refunds/{refundId} | Inquiry Refund
[**RefundPurchase**](RefundAPIAPI.md#RefundPurchase) | **Post** /v3/purchases/refund | Refund Purchase
[**RetryRefund**](RefundAPIAPI.md#RetryRefund) | **Post** /v3/purchases/refunds/{refundId}/retry | Retry Refund
[**VerifyRefund**](RefundAPIAPI.md#VerifyRefund) | **Post** /v3/purchases/refunds/{refundId}/verify | Verify Refund



## CancelRefund

> CancelRefund(ctx, refundId).RefundActionRequest(refundActionRequest).Execute()

Cancel Refund



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
	refundId := int64(789) // int64 | 
	refundActionRequest := *openapiclient.NewRefundActionRequest() // RefundActionRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.RefundAPIAPI.CancelRefund(context.Background(), refundId).RefundActionRequest(refundActionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RefundAPIAPI.CancelRefund``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**refundId** | **int64** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCancelRefundRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **refundActionRequest** | [**RefundActionRequest**](RefundActionRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## IgnoreCancellingRefund

> IgnoreCancellingRefund(ctx, refundId).RefundActionRequest(refundActionRequest).Execute()

Ignore Cancelling Refund



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
	refundId := int64(789) // int64 | 
	refundActionRequest := *openapiclient.NewRefundActionRequest() // RefundActionRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.RefundAPIAPI.IgnoreCancellingRefund(context.Background(), refundId).RefundActionRequest(refundActionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RefundAPIAPI.IgnoreCancellingRefund``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**refundId** | **int64** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiIgnoreCancellingRefundRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **refundActionRequest** | [**RefundActionRequest**](RefundActionRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InquiryRefund

> RefundInquiryResult InquiryRefund(ctx, refundId).Execute()

Inquiry Refund



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
	refundId := int64(789) // int64 | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RefundAPIAPI.InquiryRefund(context.Background(), refundId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RefundAPIAPI.InquiryRefund``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InquiryRefund`: RefundInquiryResult
	fmt.Fprintf(os.Stdout, "Response from `RefundAPIAPI.InquiryRefund`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**refundId** | **int64** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiInquiryRefundRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**RefundInquiryResult**](RefundInquiryResult.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RefundPurchase

> RefundPurchaseResult RefundPurchase(ctx).RefundPurchaseRequest(refundPurchaseRequest).Execute()

Refund Purchase



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
	refundPurchaseRequest := *openapiclient.NewRefundPurchaseRequest() // RefundPurchaseRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RefundAPIAPI.RefundPurchase(context.Background()).RefundPurchaseRequest(refundPurchaseRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RefundAPIAPI.RefundPurchase``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RefundPurchase`: RefundPurchaseResult
	fmt.Fprintf(os.Stdout, "Response from `RefundAPIAPI.RefundPurchase`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRefundPurchaseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **refundPurchaseRequest** | [**RefundPurchaseRequest**](RefundPurchaseRequest.md) |  | 

### Return type

[**RefundPurchaseResult**](RefundPurchaseResult.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RetryRefund

> RetryRefund(ctx, refundId).RefundActionRequest(refundActionRequest).Execute()

Retry Refund



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
	refundId := int64(789) // int64 | 
	refundActionRequest := *openapiclient.NewRefundActionRequest() // RefundActionRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.RefundAPIAPI.RetryRefund(context.Background(), refundId).RefundActionRequest(refundActionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RefundAPIAPI.RetryRefund``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**refundId** | **int64** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRetryRefundRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **refundActionRequest** | [**RefundActionRequest**](RefundActionRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## VerifyRefund

> VerifyRefund(ctx, refundId).RefundActionRequest(refundActionRequest).Execute()

Verify Refund



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
	refundId := int64(789) // int64 | 
	refundActionRequest := *openapiclient.NewRefundActionRequest() // RefundActionRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.RefundAPIAPI.VerifyRefund(context.Background(), refundId).RefundActionRequest(refundActionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RefundAPIAPI.VerifyRefund``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**refundId** | **int64** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiVerifyRefundRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **refundActionRequest** | [**RefundActionRequest**](RefundActionRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

