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
	samiclient "github.com/Autnhive-Devsecops-Org/sami-sdk-go"
)

func main() {
	// Build the request body. NewRagQueryRequest takes the required query;
	// optional fields are set with the typed setters.
	ragQueryRequest := *samiclient.NewRagQueryRequest("what is vulnerability") // RagQueryRequest |
	ragQueryRequest.SetRetrieverBackend("weaviate")
	ragQueryRequest.SetTopK(15)

	// dummy token, replace with your API key
	authorization := "Bearer sk_llm-XXXXXXXX-XXXXXXXX-XXXXXXXX-XXXXXXXX" // string |  (optional)

	configuration := samiclient.NewConfiguration()
	configuration.Servers = samiclient.ServerConfigurations{
		{URL: "https://dev-sami.autnhive.net/rag-defender"},
	}
	apiClient := samiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ORCHESTRATORAPI.RagQuery(context.Background()).RagQueryRequest(ragQueryRequest).Authorization(authorization).Execute()
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

