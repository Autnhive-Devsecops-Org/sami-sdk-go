# \SAMIAPI

All URIs are relative to */rag-defender*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApproveQuarantineDoc**](SAMIAPI.md#ApproveQuarantineDoc) | **Post** /v1/quarantine/{doc_id}/approve | Quarantine
[**IngestCommit**](SAMIAPI.md#IngestCommit) | **Post** /v1/ingest | Data Ingestion
[**IngestSync**](SAMIAPI.md#IngestSync) | **Post** /v1/ingest/sync | Ingest Sync
[**RejectQuarantineDoc**](SAMIAPI.md#RejectQuarantineDoc) | **Post** /v1/quarantine/{doc_id}/reject | Reject Quarantine



## ApproveQuarantineDoc

> QuarantineReviewResponse ApproveQuarantineDoc(ctx, docId).QuarantineReviewRequest(quarantineReviewRequest).Authorization(authorization).Execute()

Quarantine



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
	docId := "docId_example" // string | Document ID
	quarantineReviewRequest := *samiclient.NewQuarantineReviewRequest() // QuarantineReviewRequest | 
	authorization := "authorization_example" // string |  (optional)

	configuration := samiclient.NewConfiguration()
	apiClient := samiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SAMIAPI.ApproveQuarantineDoc(context.Background(), docId).QuarantineReviewRequest(quarantineReviewRequest).Authorization(authorization).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SAMIAPI.ApproveQuarantineDoc``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApproveQuarantineDoc`: QuarantineReviewResponse
	fmt.Fprintf(os.Stdout, "Response from `SAMIAPI.ApproveQuarantineDoc`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**docId** | **string** | Document ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiApproveQuarantineDocRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **quarantineReviewRequest** | [**QuarantineReviewRequest**](QuarantineReviewRequest.md) |  | 
 **authorization** | **string** |  | 

### Return type

[**QuarantineReviewResponse**](QuarantineReviewResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## IngestCommit

> IngestCommitResponse IngestCommit(ctx).Authorization(authorization).IngestCommitRequest(ingestCommitRequest).Execute()

Data Ingestion

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
	authorization := "authorization_example" // string |  (optional)
	ingestCommitRequest := *samiclient.NewIngestCommitRequest([]samiclient.IngestDocument{*samiclient.NewIngestDocument("Text_example")}) // IngestCommitRequest |  (optional)

	configuration := samiclient.NewConfiguration()
	apiClient := samiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SAMIAPI.IngestCommit(context.Background()).Authorization(authorization).IngestCommitRequest(ingestCommitRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SAMIAPI.IngestCommit``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `IngestCommit`: IngestCommitResponse
	fmt.Fprintf(os.Stdout, "Response from `SAMIAPI.IngestCommit`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiIngestCommitRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **authorization** | **string** |  | 
 **ingestCommitRequest** | [**IngestCommitRequest**](IngestCommitRequest.md) |  | 

### Return type

[**IngestCommitResponse**](IngestCommitResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## IngestSync

> IngestSyncResponse IngestSync(ctx).Source(source).Authorization(authorization).IngestSyncRequest(ingestSyncRequest).Execute()

Ingest Sync

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
	source := "source_example" // string |  (optional) (default to "static_docs")
	authorization := "authorization_example" // string |  (optional)
	ingestSyncRequest := *samiclient.NewIngestSyncRequest() // IngestSyncRequest |  (optional)

	configuration := samiclient.NewConfiguration()
	apiClient := samiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SAMIAPI.IngestSync(context.Background()).Source(source).Authorization(authorization).IngestSyncRequest(ingestSyncRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SAMIAPI.IngestSync``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `IngestSync`: IngestSyncResponse
	fmt.Fprintf(os.Stdout, "Response from `SAMIAPI.IngestSync`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiIngestSyncRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **source** | **string** |  | [default to &quot;static_docs&quot;]
 **authorization** | **string** |  | 
 **ingestSyncRequest** | [**IngestSyncRequest**](IngestSyncRequest.md) |  | 

### Return type

[**IngestSyncResponse**](IngestSyncResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RejectQuarantineDoc

> QuarantineReviewResponse RejectQuarantineDoc(ctx, docId).QuarantineReviewRequest(quarantineReviewRequest).Authorization(authorization).Execute()

Reject Quarantine



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
	docId := "docId_example" // string | Document ID
	quarantineReviewRequest := *samiclient.NewQuarantineReviewRequest() // QuarantineReviewRequest | 
	authorization := "authorization_example" // string |  (optional)

	configuration := samiclient.NewConfiguration()
	apiClient := samiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SAMIAPI.RejectQuarantineDoc(context.Background(), docId).QuarantineReviewRequest(quarantineReviewRequest).Authorization(authorization).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SAMIAPI.RejectQuarantineDoc``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RejectQuarantineDoc`: QuarantineReviewResponse
	fmt.Fprintf(os.Stdout, "Response from `SAMIAPI.RejectQuarantineDoc`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**docId** | **string** | Document ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiRejectQuarantineDocRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **quarantineReviewRequest** | [**QuarantineReviewRequest**](QuarantineReviewRequest.md) |  | 
 **authorization** | **string** |  | 

### Return type

[**QuarantineReviewResponse**](QuarantineReviewResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

