# IngestCommitRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TenantId** | Pointer to **NullableString** |  | [optional] 
**AppId** | Pointer to **NullableString** |  | [optional] 
**StoreQuarantine** | Pointer to **bool** |  | [optional] [default to true]
**RetrieverBackend** | Pointer to **NullableString** |  | [optional] 
**SourceAdapter** | Pointer to **NullableString** |  | [optional] 
**Index** | Pointer to **NullableString** |  | [optional] 
**Documents** | [**[]IngestDocument**](IngestDocument.md) |  | 
**Bucket** | Pointer to **NullableString** |  | [optional] 
**DataSourceId** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewIngestCommitRequest

`func NewIngestCommitRequest(documents []IngestDocument, ) *IngestCommitRequest`

NewIngestCommitRequest instantiates a new IngestCommitRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIngestCommitRequestWithDefaults

`func NewIngestCommitRequestWithDefaults() *IngestCommitRequest`

NewIngestCommitRequestWithDefaults instantiates a new IngestCommitRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTenantId

`func (o *IngestCommitRequest) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *IngestCommitRequest) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *IngestCommitRequest) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.

### HasTenantId

`func (o *IngestCommitRequest) HasTenantId() bool`

HasTenantId returns a boolean if a field has been set.

### SetTenantIdNil

`func (o *IngestCommitRequest) SetTenantIdNil(b bool)`

 SetTenantIdNil sets the value for TenantId to be an explicit nil

### UnsetTenantId
`func (o *IngestCommitRequest) UnsetTenantId()`

UnsetTenantId ensures that no value is present for TenantId, not even an explicit nil
### GetAppId

`func (o *IngestCommitRequest) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *IngestCommitRequest) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *IngestCommitRequest) SetAppId(v string)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *IngestCommitRequest) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### SetAppIdNil

`func (o *IngestCommitRequest) SetAppIdNil(b bool)`

 SetAppIdNil sets the value for AppId to be an explicit nil

### UnsetAppId
`func (o *IngestCommitRequest) UnsetAppId()`

UnsetAppId ensures that no value is present for AppId, not even an explicit nil
### GetStoreQuarantine

`func (o *IngestCommitRequest) GetStoreQuarantine() bool`

GetStoreQuarantine returns the StoreQuarantine field if non-nil, zero value otherwise.

### GetStoreQuarantineOk

`func (o *IngestCommitRequest) GetStoreQuarantineOk() (*bool, bool)`

GetStoreQuarantineOk returns a tuple with the StoreQuarantine field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStoreQuarantine

`func (o *IngestCommitRequest) SetStoreQuarantine(v bool)`

SetStoreQuarantine sets StoreQuarantine field to given value.

### HasStoreQuarantine

`func (o *IngestCommitRequest) HasStoreQuarantine() bool`

HasStoreQuarantine returns a boolean if a field has been set.

### GetRetrieverBackend

`func (o *IngestCommitRequest) GetRetrieverBackend() string`

GetRetrieverBackend returns the RetrieverBackend field if non-nil, zero value otherwise.

### GetRetrieverBackendOk

`func (o *IngestCommitRequest) GetRetrieverBackendOk() (*string, bool)`

GetRetrieverBackendOk returns a tuple with the RetrieverBackend field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetrieverBackend

`func (o *IngestCommitRequest) SetRetrieverBackend(v string)`

SetRetrieverBackend sets RetrieverBackend field to given value.

### HasRetrieverBackend

`func (o *IngestCommitRequest) HasRetrieverBackend() bool`

HasRetrieverBackend returns a boolean if a field has been set.

### SetRetrieverBackendNil

`func (o *IngestCommitRequest) SetRetrieverBackendNil(b bool)`

 SetRetrieverBackendNil sets the value for RetrieverBackend to be an explicit nil

### UnsetRetrieverBackend
`func (o *IngestCommitRequest) UnsetRetrieverBackend()`

UnsetRetrieverBackend ensures that no value is present for RetrieverBackend, not even an explicit nil
### GetSourceAdapter

`func (o *IngestCommitRequest) GetSourceAdapter() string`

GetSourceAdapter returns the SourceAdapter field if non-nil, zero value otherwise.

### GetSourceAdapterOk

`func (o *IngestCommitRequest) GetSourceAdapterOk() (*string, bool)`

GetSourceAdapterOk returns a tuple with the SourceAdapter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceAdapter

`func (o *IngestCommitRequest) SetSourceAdapter(v string)`

SetSourceAdapter sets SourceAdapter field to given value.

### HasSourceAdapter

`func (o *IngestCommitRequest) HasSourceAdapter() bool`

HasSourceAdapter returns a boolean if a field has been set.

### SetSourceAdapterNil

`func (o *IngestCommitRequest) SetSourceAdapterNil(b bool)`

 SetSourceAdapterNil sets the value for SourceAdapter to be an explicit nil

### UnsetSourceAdapter
`func (o *IngestCommitRequest) UnsetSourceAdapter()`

UnsetSourceAdapter ensures that no value is present for SourceAdapter, not even an explicit nil
### GetIndex

`func (o *IngestCommitRequest) GetIndex() string`

GetIndex returns the Index field if non-nil, zero value otherwise.

### GetIndexOk

`func (o *IngestCommitRequest) GetIndexOk() (*string, bool)`

GetIndexOk returns a tuple with the Index field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndex

`func (o *IngestCommitRequest) SetIndex(v string)`

SetIndex sets Index field to given value.

### HasIndex

`func (o *IngestCommitRequest) HasIndex() bool`

HasIndex returns a boolean if a field has been set.

### SetIndexNil

`func (o *IngestCommitRequest) SetIndexNil(b bool)`

 SetIndexNil sets the value for Index to be an explicit nil

### UnsetIndex
`func (o *IngestCommitRequest) UnsetIndex()`

UnsetIndex ensures that no value is present for Index, not even an explicit nil
### GetDocuments

`func (o *IngestCommitRequest) GetDocuments() []IngestDocument`

GetDocuments returns the Documents field if non-nil, zero value otherwise.

### GetDocumentsOk

`func (o *IngestCommitRequest) GetDocumentsOk() (*[]IngestDocument, bool)`

GetDocumentsOk returns a tuple with the Documents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocuments

`func (o *IngestCommitRequest) SetDocuments(v []IngestDocument)`

SetDocuments sets Documents field to given value.


### GetBucket

`func (o *IngestCommitRequest) GetBucket() string`

GetBucket returns the Bucket field if non-nil, zero value otherwise.

### GetBucketOk

`func (o *IngestCommitRequest) GetBucketOk() (*string, bool)`

GetBucketOk returns a tuple with the Bucket field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBucket

`func (o *IngestCommitRequest) SetBucket(v string)`

SetBucket sets Bucket field to given value.

### HasBucket

`func (o *IngestCommitRequest) HasBucket() bool`

HasBucket returns a boolean if a field has been set.

### SetBucketNil

`func (o *IngestCommitRequest) SetBucketNil(b bool)`

 SetBucketNil sets the value for Bucket to be an explicit nil

### UnsetBucket
`func (o *IngestCommitRequest) UnsetBucket()`

UnsetBucket ensures that no value is present for Bucket, not even an explicit nil
### GetDataSourceId

`func (o *IngestCommitRequest) GetDataSourceId() string`

GetDataSourceId returns the DataSourceId field if non-nil, zero value otherwise.

### GetDataSourceIdOk

`func (o *IngestCommitRequest) GetDataSourceIdOk() (*string, bool)`

GetDataSourceIdOk returns a tuple with the DataSourceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataSourceId

`func (o *IngestCommitRequest) SetDataSourceId(v string)`

SetDataSourceId sets DataSourceId field to given value.

### HasDataSourceId

`func (o *IngestCommitRequest) HasDataSourceId() bool`

HasDataSourceId returns a boolean if a field has been set.

### SetDataSourceIdNil

`func (o *IngestCommitRequest) SetDataSourceIdNil(b bool)`

 SetDataSourceIdNil sets the value for DataSourceId to be an explicit nil

### UnsetDataSourceId
`func (o *IngestCommitRequest) UnsetDataSourceId()`

UnsetDataSourceId ensures that no value is present for DataSourceId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


