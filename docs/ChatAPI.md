# \ChatAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AdapterChat**](ChatAPI.md#AdapterChat) | **Post** /ai-firewall/firewall/v1/prompt/text | Firewall text chat endpoint



## AdapterChat

> map[string]interface{} AdapterChat(ctx).ChatCompletionRequest(chatCompletionRequest).Execute()

Firewall text chat endpoint

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	samiapiclient "github.com/Autnhive-Devsecops-Org/sami-sdk-go"
)

func main() {
	chatCompletionRequest := *openapiclient.NewChatCompletionRequest([]openapiclient.ChatMessage{*openapiclient.NewChatMessage("Role_example", "Content_example")}) // ChatCompletionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChatAPI.AdapterChat(context.Background()).ChatCompletionRequest(chatCompletionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChatAPI.AdapterChat``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AdapterChat`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `ChatAPI.AdapterChat`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiAdapterChatRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **chatCompletionRequest** | [**ChatCompletionRequest**](ChatCompletionRequest.md) |  | 

### Return type

**map[string]interface{}**

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

