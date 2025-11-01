# \ClientAPIAPI

All URIs are relative to *https://napi.jibit.ir/ppg*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetClientBalances**](ClientAPIAPI.md#GetClientBalances) | **Get** /v3/balances | Get Client Balances



## GetClientBalances

> ClientBalances GetClientBalances(ctx).Execute()

Get Client Balances



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientAPIAPI.GetClientBalances(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientAPIAPI.GetClientBalances``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetClientBalances`: ClientBalances
	fmt.Fprintf(os.Stdout, "Response from `ClientAPIAPI.GetClientBalances`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetClientBalancesRequest struct via the builder pattern


### Return type

[**ClientBalances**](ClientBalances.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

