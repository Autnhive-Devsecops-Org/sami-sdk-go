# \ORCHESTRATORAPI

All URIs are relative to */rag-defender*

Method | HTTP request | Description
------------- | ------------- | -------------
[**RagQuery**](ORCHESTRATORAPI.md#RagQuery) | **Post** /v1/rag/query | Rag Query



## RagQuery

> RagQueryResponse RagQuery(ctx).RagQueryRequest(ragQueryRequest).Authorization(authorization).XRequestID(xRequestID).Execute()

Rag Query



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
	ragQueryRequest := *openapiclient.NewRagQueryRequest("Query_example") // RagQueryRequest | 
	authorization := "authorization_example" // string |  (optional)
	xRequestID := "xRequestID_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ORCHESTRATORAPI.RagQuery(context.Background()).RagQueryRequest(ragQueryRequest).Authorization(authorization).XRequestID(xRequestID).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ORCHESTRATORAPI.RagQuery``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RagQuery`: RagQueryResponse
	fmt.Fprintf(os.Stdout, "Response from `ORCHESTRATORAPI.RagQuery`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRagQueryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ragQueryRequest** | [**RagQueryRequest**](RagQueryRequest.md) |  | 
 **authorization** | **string** |  | 
 **xRequestID** | **string** |  | 

### Return type

[**RagQueryResponse**](RagQueryResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

