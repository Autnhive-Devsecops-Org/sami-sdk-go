# \DEFENDERAPI

All URIs are relative to */rag-defender*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DefendV1DefendPost**](DEFENDERAPI.md#DefendV1DefendPost) | **Post** /v1/defend | Defend



## DefendV1DefendPost

> DefendResponseModel DefendV1DefendPost(ctx).DefendRequestModel(defendRequestModel).XRequestId(xRequestId).XTenantId(xTenantId).Execute()

Defend

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	defendRequestModel := *openapiclient.NewDefendRequestModel("Query_example", []string{"Documents_example"}) // DefendRequestModel | 
	xRequestId := "xRequestId_example" // string |  (optional)
	xTenantId := "xTenantId_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DEFENDERAPI.DefendV1DefendPost(context.Background()).DefendRequestModel(defendRequestModel).XRequestId(xRequestId).XTenantId(xTenantId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DEFENDERAPI.DefendV1DefendPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DefendV1DefendPost`: DefendResponseModel
	fmt.Fprintf(os.Stdout, "Response from `DEFENDERAPI.DefendV1DefendPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDefendV1DefendPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **defendRequestModel** | [**DefendRequestModel**](DefendRequestModel.md) |  | 
 **xRequestId** | **string** |  | 
 **xTenantId** | **string** |  | 

### Return type

[**DefendResponseModel**](DefendResponseModel.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

