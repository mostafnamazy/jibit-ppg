# \AppAPIAPI

All URIs are relative to *https://napi.jibit.ir/ppg*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CheckHealthStatus**](AppAPIAPI.md#CheckHealthStatus) | **Get** /v3/app/health | Check Health Status



## CheckHealthStatus

> HealthDto CheckHealthStatus(ctx).Execute()

Check Health Status



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
	resp, r, err := apiClient.AppAPIAPI.CheckHealthStatus(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppAPIAPI.CheckHealthStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CheckHealthStatus`: HealthDto
	fmt.Fprintf(os.Stdout, "Response from `AppAPIAPI.CheckHealthStatus`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiCheckHealthStatusRequest struct via the builder pattern


### Return type

[**HealthDto**](HealthDto.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

