# RagQueryRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Query** | **string** | User query | 
**TopK** | Pointer to **int32** | Number of documents to retrieve (mock retriever) | [optional] [default to 10]
**Channel** | Pointer to **NullableString** | Channel identifier (web, api, mobile, etc.) | [optional] 
**RetrieverBackend** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewRagQueryRequest

`func NewRagQueryRequest(query string, ) *RagQueryRequest`

NewRagQueryRequest instantiates a new RagQueryRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRagQueryRequestWithDefaults

`func NewRagQueryRequestWithDefaults() *RagQueryRequest`

NewRagQueryRequestWithDefaults instantiates a new RagQueryRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetQuery

`func (o *RagQueryRequest) GetQuery() string`

GetQuery returns the Query field if non-nil, zero value otherwise.

### GetQueryOk

`func (o *RagQueryRequest) GetQueryOk() (*string, bool)`

GetQueryOk returns a tuple with the Query field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuery

`func (o *RagQueryRequest) SetQuery(v string)`

SetQuery sets Query field to given value.


### GetTopK

`func (o *RagQueryRequest) GetTopK() int32`

GetTopK returns the TopK field if non-nil, zero value otherwise.

### GetTopKOk

`func (o *RagQueryRequest) GetTopKOk() (*int32, bool)`

GetTopKOk returns a tuple with the TopK field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopK

`func (o *RagQueryRequest) SetTopK(v int32)`

SetTopK sets TopK field to given value.

### HasTopK

`func (o *RagQueryRequest) HasTopK() bool`

HasTopK returns a boolean if a field has been set.

### GetChannel

`func (o *RagQueryRequest) GetChannel() string`

GetChannel returns the Channel field if non-nil, zero value otherwise.

### GetChannelOk

`func (o *RagQueryRequest) GetChannelOk() (*string, bool)`

GetChannelOk returns a tuple with the Channel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannel

`func (o *RagQueryRequest) SetChannel(v string)`

SetChannel sets Channel field to given value.

### HasChannel

`func (o *RagQueryRequest) HasChannel() bool`

HasChannel returns a boolean if a field has been set.

### SetChannelNil

`func (o *RagQueryRequest) SetChannelNil(b bool)`

 SetChannelNil sets the value for Channel to be an explicit nil

### UnsetChannel
`func (o *RagQueryRequest) UnsetChannel()`

UnsetChannel ensures that no value is present for Channel, not even an explicit nil
### GetRetrieverBackend

`func (o *RagQueryRequest) GetRetrieverBackend() string`

GetRetrieverBackend returns the RetrieverBackend field if non-nil, zero value otherwise.

### GetRetrieverBackendOk

`func (o *RagQueryRequest) GetRetrieverBackendOk() (*string, bool)`

GetRetrieverBackendOk returns a tuple with the RetrieverBackend field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetrieverBackend

`func (o *RagQueryRequest) SetRetrieverBackend(v string)`

SetRetrieverBackend sets RetrieverBackend field to given value.

### HasRetrieverBackend

`func (o *RagQueryRequest) HasRetrieverBackend() bool`

HasRetrieverBackend returns a boolean if a field has been set.

### SetRetrieverBackendNil

`func (o *RagQueryRequest) SetRetrieverBackendNil(b bool)`

 SetRetrieverBackendNil sets the value for RetrieverBackend to be an explicit nil

### UnsetRetrieverBackend
`func (o *RagQueryRequest) UnsetRetrieverBackend()`

UnsetRetrieverBackend ensures that no value is present for RetrieverBackend, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


