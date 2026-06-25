# \ChatAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AdapterChat**](ChatAPI.md#AdapterChat) | **Post** /ai-firewall/firewall/v1/prompt/text | Firewall text chat endpoint



## AdapterChat

> map[string]interface{} AdapterChat(ctx).RequestBody(requestBody).Execute()

Firewall text chat endpoint

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	samiapiclient "github.com/Autnhive-Devsecops-Org/sami-sdk-go.git"
)

func main() {
	requestBody := map[string]interface{}{"key": interface{}(123)} // map[string]interface{} | 

	configuration := samiapiclient.NewConfiguration()
	apiClient := samiapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChatAPI.AdapterChat(context.Background()).RequestBody(requestBody).Execute()
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
 **requestBody** | **map[string]interface{}** |  | 

### Return type

**map[string]interface{}**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

