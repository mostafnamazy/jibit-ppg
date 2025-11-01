# \TerminalAPIAPI

All URIs are relative to *https://napi.jibit.ir/ppg*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ListActiveTerminals**](TerminalAPIAPI.md#ListActiveTerminals) | **Get** /v3/terminals/list | List Active Terminals



## ListActiveTerminals

> CollectionResponseTerminalDto ListActiveTerminals(ctx).Execute()

List Active Terminals



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
	resp, r, err := apiClient.TerminalAPIAPI.ListActiveTerminals(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TerminalAPIAPI.ListActiveTerminals``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListActiveTerminals`: CollectionResponseTerminalDto
	fmt.Fprintf(os.Stdout, "Response from `TerminalAPIAPI.ListActiveTerminals`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListActiveTerminalsRequest struct via the builder pattern


### Return type

[**CollectionResponseTerminalDto**](CollectionResponseTerminalDto.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

