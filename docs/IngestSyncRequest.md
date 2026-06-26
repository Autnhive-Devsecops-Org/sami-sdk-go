# IngestSyncRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TenantId** | Pointer to **NullableString** |  | [optional] 
**AppId** | Pointer to **NullableString** |  | [optional] 
**StoreQuarantine** | Pointer to **bool** |  | [optional] [default to true]
**Bucket** | Pointer to **NullableString** |  | [optional] 
**DataSourceId** | Pointer to **NullableString** |  | [optional] 
**Files** | Pointer to **[]string** |  | [optional] 

## Methods

### NewIngestSyncRequest

`func NewIngestSyncRequest() *IngestSyncRequest`

NewIngestSyncRequest instantiates a new IngestSyncRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIngestSyncRequestWithDefaults

`func NewIngestSyncRequestWithDefaults() *IngestSyncRequest`

NewIngestSyncRequestWithDefaults instantiates a new IngestSyncRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTenantId

`func (o *IngestSyncRequest) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *IngestSyncRequest) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *IngestSyncRequest) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.

### HasTenantId

`func (o *IngestSyncRequest) HasTenantId() bool`

HasTenantId returns a boolean if a field has been set.

### SetTenantIdNil

`func (o *IngestSyncRequest) SetTenantIdNil(b bool)`

 SetTenantIdNil sets the value for TenantId to be an explicit nil

### UnsetTenantId
`func (o *IngestSyncRequest) UnsetTenantId()`

UnsetTenantId ensures that no value is present for TenantId, not even an explicit nil
### GetAppId

`func (o *IngestSyncRequest) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *IngestSyncRequest) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *IngestSyncRequest) SetAppId(v string)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *IngestSyncRequest) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### SetAppIdNil

`func (o *IngestSyncRequest) SetAppIdNil(b bool)`

 SetAppIdNil sets the value for AppId to be an explicit nil

### UnsetAppId
`func (o *IngestSyncRequest) UnsetAppId()`

UnsetAppId ensures that no value is present for AppId, not even an explicit nil
### GetStoreQuarantine

`func (o *IngestSyncRequest) GetStoreQuarantine() bool`

GetStoreQuarantine returns the StoreQuarantine field if non-nil, zero value otherwise.

### GetStoreQuarantineOk

`func (o *IngestSyncRequest) GetStoreQuarantineOk() (*bool, bool)`

GetStoreQuarantineOk returns a tuple with the StoreQuarantine field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStoreQuarantine

`func (o *IngestSyncRequest) SetStoreQuarantine(v bool)`

SetStoreQuarantine sets StoreQuarantine field to given value.

### HasStoreQuarantine

`func (o *IngestSyncRequest) HasStoreQuarantine() bool`

HasStoreQuarantine returns a boolean if a field has been set.

### GetBucket

`func (o *IngestSyncRequest) GetBucket() string`

GetBucket returns the Bucket field if non-nil, zero value otherwise.

### GetBucketOk

`func (o *IngestSyncRequest) GetBucketOk() (*string, bool)`

GetBucketOk returns a tuple with the Bucket field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBucket

`func (o *IngestSyncRequest) SetBucket(v string)`

SetBucket sets Bucket field to given value.

### HasBucket

`func (o *IngestSyncRequest) HasBucket() bool`

HasBucket returns a boolean if a field has been set.

### SetBucketNil

`func (o *IngestSyncRequest) SetBucketNil(b bool)`

 SetBucketNil sets the value for Bucket to be an explicit nil

### UnsetBucket
`func (o *IngestSyncRequest) UnsetBucket()`

UnsetBucket ensures that no value is present for Bucket, not even an explicit nil
### GetDataSourceId

`func (o *IngestSyncRequest) GetDataSourceId() string`

GetDataSourceId returns the DataSourceId field if non-nil, zero value otherwise.

### GetDataSourceIdOk

`func (o *IngestSyncRequest) GetDataSourceIdOk() (*string, bool)`

GetDataSourceIdOk returns a tuple with the DataSourceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataSourceId

`func (o *IngestSyncRequest) SetDataSourceId(v string)`

SetDataSourceId sets DataSourceId field to given value.

### HasDataSourceId

`func (o *IngestSyncRequest) HasDataSourceId() bool`

HasDataSourceId returns a boolean if a field has been set.

### SetDataSourceIdNil

`func (o *IngestSyncRequest) SetDataSourceIdNil(b bool)`

 SetDataSourceIdNil sets the value for DataSourceId to be an explicit nil

### UnsetDataSourceId
`func (o *IngestSyncRequest) UnsetDataSourceId()`

UnsetDataSourceId ensures that no value is present for DataSourceId, not even an explicit nil
### GetFiles

`func (o *IngestSyncRequest) GetFiles() []string`

GetFiles returns the Files field if non-nil, zero value otherwise.

### GetFilesOk

`func (o *IngestSyncRequest) GetFilesOk() (*[]string, bool)`

GetFilesOk returns a tuple with the Files field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFiles

`func (o *IngestSyncRequest) SetFiles(v []string)`

SetFiles sets Files field to given value.

### HasFiles

`func (o *IngestSyncRequest) HasFiles() bool`

HasFiles returns a boolean if a field has been set.

### SetFilesNil

`func (o *IngestSyncRequest) SetFilesNil(b bool)`

 SetFilesNil sets the value for Files to be an explicit nil

### UnsetFiles
`func (o *IngestSyncRequest) UnsetFiles()`

UnsetFiles ensures that no value is present for Files, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


