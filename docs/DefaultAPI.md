# \DefaultAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**FileSanitization**](DefaultAPI.md#FileSanitization) | **Post** /ai-firewall/firewall/v1/file/sanitization | Replace content in uploaded files
[**MultimodalChat**](DefaultAPI.md#MultimodalChat) | **Post** /ai-firewall/firewall/v1/prompt | Multimodal chat completions



## FileSanitization

> []string FileSanitization(ctx).SignedUrlPayload(signedUrlPayload).Execute()

Replace content in uploaded files

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
	signedUrlPayload := *openapiclient.NewSignedUrlPayload([]openapiclient.Job{*openapiclient.NewJob("Id_example", "SignedUrl_example", "FileName_example", []string{"PolicyPacks_example"})}) // SignedUrlPayload | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.FileSanitization(context.Background()).SignedUrlPayload(signedUrlPayload).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.FileSanitization``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FileSanitization`: []string
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.FileSanitization`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFileSanitizationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **signedUrlPayload** | [**SignedUrlPayload**](SignedUrlPayload.md) |  | 

### Return type

**[]string**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MultimodalChat

> map[string]interface{} MultimodalChat(ctx).Prompt(prompt).Content(content).Text(text).Input(input).File(file).Docx(docx).Pdf(pdf).Image(image).Audio(audio).Model(model).Execute()

Multimodal chat completions

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
	prompt := "prompt_example" // string | Free-form prompt text (optional)
	content := "content_example" // string | Optional content payload (optional)
	text := "text_example" // string | Optional text input (optional)
	input := "input_example" // string | Optional input input (optional)
	file := os.NewFile(1234, "some_file") // *os.File | Generic file upload (optional) (optional)
	docx := os.NewFile(1234, "some_file") // *os.File | DOCX upload (optional) (optional)
	pdf := os.NewFile(1234, "some_file") // *os.File | PDF upload (optional) (optional)
	image := os.NewFile(1234, "some_file") // *os.File | Image upload (optional) (optional)
	audio := os.NewFile(1234, "some_file") // *os.File | Audio upload (optional) (optional)
	model := "model_example" // string | Optional model name (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.MultimodalChat(context.Background()).Prompt(prompt).Content(content).Text(text).Input(input).File(file).Docx(docx).Pdf(pdf).Image(image).Audio(audio).Model(model).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.MultimodalChat``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MultimodalChat`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.MultimodalChat`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiMultimodalChatRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **prompt** | **string** | Free-form prompt text | 
 **content** | **string** | Optional content payload | 
 **text** | **string** | Optional text input | 
 **input** | **string** | Optional input input | 
 **file** | ***os.File** | Generic file upload (optional) | 
 **docx** | ***os.File** | DOCX upload (optional) | 
 **pdf** | ***os.File** | PDF upload (optional) | 
 **image** | ***os.File** | Image upload (optional) | 
 **audio** | ***os.File** | Audio upload (optional) | 
 **model** | **string** | Optional model name | 

### Return type

**map[string]interface{}**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

