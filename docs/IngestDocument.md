# IngestDocument

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DocId** | Pointer to **NullableString** | Optional document identifier | [optional] 
**Text** | **string** | Document text/content | 
**Metadata** | Pointer to **map[string]interface{}** | Document metadata, including source_type | [optional] 

## Methods

### NewIngestDocument

`func NewIngestDocument(text string, ) *IngestDocument`

NewIngestDocument instantiates a new IngestDocument object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIngestDocumentWithDefaults

`func NewIngestDocumentWithDefaults() *IngestDocument`

NewIngestDocumentWithDefaults instantiates a new IngestDocument object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDocId

`func (o *IngestDocument) GetDocId() string`

GetDocId returns the DocId field if non-nil, zero value otherwise.

### GetDocIdOk

`func (o *IngestDocument) GetDocIdOk() (*string, bool)`

GetDocIdOk returns a tuple with the DocId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocId

`func (o *IngestDocument) SetDocId(v string)`

SetDocId sets DocId field to given value.

### HasDocId

`func (o *IngestDocument) HasDocId() bool`

HasDocId returns a boolean if a field has been set.

### SetDocIdNil

`func (o *IngestDocument) SetDocIdNil(b bool)`

 SetDocIdNil sets the value for DocId to be an explicit nil

### UnsetDocId
`func (o *IngestDocument) UnsetDocId()`

UnsetDocId ensures that no value is present for DocId, not even an explicit nil
### GetText

`func (o *IngestDocument) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *IngestDocument) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *IngestDocument) SetText(v string)`

SetText sets Text field to given value.


### GetMetadata

`func (o *IngestDocument) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *IngestDocument) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *IngestDocument) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *IngestDocument) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


