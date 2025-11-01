# \SettlementAPIAPI

All URIs are relative to *https://napi.jibit.ir/ppg*

Method | HTTP request | Description
------------- | ------------- | -------------
[**FilterSettlements**](SettlementAPIAPI.md#FilterSettlements) | **Get** /v3/settlements | Filter Settlements



## FilterSettlements

> PaginatedDetailedSettlementDto FilterSettlements(ctx).Criteria(criteria).Execute()

Filter Settlements



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
	criteria := *openapiclient.NewSettlementFilterCriteria() // SettlementFilterCriteria | Encapsulates the information to filter settlements.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SettlementAPIAPI.FilterSettlements(context.Background()).Criteria(criteria).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SettlementAPIAPI.FilterSettlements``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FilterSettlements`: PaginatedDetailedSettlementDto
	fmt.Fprintf(os.Stdout, "Response from `SettlementAPIAPI.FilterSettlements`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFilterSettlementsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **criteria** | [**SettlementFilterCriteria**](SettlementFilterCriteria.md) | Encapsulates the information to filter settlements. | 

### Return type

[**PaginatedDetailedSettlementDto**](PaginatedDetailedSettlementDto.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

