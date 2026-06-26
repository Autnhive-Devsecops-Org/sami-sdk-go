# DefendRequestModel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Query** | **string** | The query string | 
**Documents** | **[]string** | List of retrieved documents | 
**Mode** | Pointer to **string** | Defense mode | [optional] [default to "multihop"]
**TopK** | Pointer to **NullableInt32** | Number of documents to return | [optional] 
**TenantId** | Pointer to **NullableString** | Tenant identifier | [optional] 
**Metadata** | Pointer to **map[string]interface{}** | Additional metadata | [optional] 

## Methods

### NewDefendRequestModel

`func NewDefendRequestModel(query string, documents []string, ) *DefendRequestModel`

NewDefendRequestModel instantiates a new DefendRequestModel object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDefendRequestModelWithDefaults

`func NewDefendRequestModelWithDefaults() *DefendRequestModel`

NewDefendRequestModelWithDefaults instantiates a new DefendRequestModel object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetQuery

`func (o *DefendRequestModel) GetQuery() string`

GetQuery returns the Query field if non-nil, zero value otherwise.

### GetQueryOk

`func (o *DefendRequestModel) GetQueryOk() (*string, bool)`

GetQueryOk returns a tuple with the Query field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuery

`func (o *DefendRequestModel) SetQuery(v string)`

SetQuery sets Query field to given value.


### GetDocuments

`func (o *DefendRequestModel) GetDocuments() []string`

GetDocuments returns the Documents field if non-nil, zero value otherwise.

### GetDocumentsOk

`func (o *DefendRequestModel) GetDocumentsOk() (*[]string, bool)`

GetDocumentsOk returns a tuple with the Documents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocuments

`func (o *DefendRequestModel) SetDocuments(v []string)`

SetDocuments sets Documents field to given value.


### GetMode

`func (o *DefendRequestModel) GetMode() string`

GetMode returns the Mode field if non-nil, zero value otherwise.

### GetModeOk

`func (o *DefendRequestModel) GetModeOk() (*string, bool)`

GetModeOk returns a tuple with the Mode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMode

`func (o *DefendRequestModel) SetMode(v string)`

SetMode sets Mode field to given value.

### HasMode

`func (o *DefendRequestModel) HasMode() bool`

HasMode returns a boolean if a field has been set.

### GetTopK

`func (o *DefendRequestModel) GetTopK() int32`

GetTopK returns the TopK field if non-nil, zero value otherwise.

### GetTopKOk

`func (o *DefendRequestModel) GetTopKOk() (*int32, bool)`

GetTopKOk returns a tuple with the TopK field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopK

`func (o *DefendRequestModel) SetTopK(v int32)`

SetTopK sets TopK field to given value.

### HasTopK

`func (o *DefendRequestModel) HasTopK() bool`

HasTopK returns a boolean if a field has been set.

### SetTopKNil

`func (o *DefendRequestModel) SetTopKNil(b bool)`

 SetTopKNil sets the value for TopK to be an explicit nil

### UnsetTopK
`func (o *DefendRequestModel) UnsetTopK()`

UnsetTopK ensures that no value is present for TopK, not even an explicit nil
### GetTenantId

`func (o *DefendRequestModel) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *DefendRequestModel) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *DefendRequestModel) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.

### HasTenantId

`func (o *DefendRequestModel) HasTenantId() bool`

HasTenantId returns a boolean if a field has been set.

### SetTenantIdNil

`func (o *DefendRequestModel) SetTenantIdNil(b bool)`

 SetTenantIdNil sets the value for TenantId to be an explicit nil

### UnsetTenantId
`func (o *DefendRequestModel) UnsetTenantId()`

UnsetTenantId ensures that no value is present for TenantId, not even an explicit nil
### GetMetadata

`func (o *DefendRequestModel) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *DefendRequestModel) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *DefendRequestModel) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *DefendRequestModel) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *DefendRequestModel) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *DefendRequestModel) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


