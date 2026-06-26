# DefendResponseModel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**CleanDocuments** | **[]string** |  | 
**KeptIndices** | **[]int32** |  | 
**RemovedIndices** | **[]int32** |  | 
**DocumentScores** | [**[]DocumentScoreModel**](DocumentScoreModel.md) |  | 
**Stats** | **map[string]interface{}** |  | 
**RequestId** | Pointer to **NullableString** |  | [optional] 
**ProcessingTimeMs** | **float32** |  | 
**Error** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewDefendResponseModel

`func NewDefendResponseModel(success bool, cleanDocuments []string, keptIndices []int32, removedIndices []int32, documentScores []DocumentScoreModel, stats map[string]interface{}, processingTimeMs float32, ) *DefendResponseModel`

NewDefendResponseModel instantiates a new DefendResponseModel object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDefendResponseModelWithDefaults

`func NewDefendResponseModelWithDefaults() *DefendResponseModel`

NewDefendResponseModelWithDefaults instantiates a new DefendResponseModel object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *DefendResponseModel) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *DefendResponseModel) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *DefendResponseModel) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetCleanDocuments

`func (o *DefendResponseModel) GetCleanDocuments() []string`

GetCleanDocuments returns the CleanDocuments field if non-nil, zero value otherwise.

### GetCleanDocumentsOk

`func (o *DefendResponseModel) GetCleanDocumentsOk() (*[]string, bool)`

GetCleanDocumentsOk returns a tuple with the CleanDocuments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCleanDocuments

`func (o *DefendResponseModel) SetCleanDocuments(v []string)`

SetCleanDocuments sets CleanDocuments field to given value.


### GetKeptIndices

`func (o *DefendResponseModel) GetKeptIndices() []int32`

GetKeptIndices returns the KeptIndices field if non-nil, zero value otherwise.

### GetKeptIndicesOk

`func (o *DefendResponseModel) GetKeptIndicesOk() (*[]int32, bool)`

GetKeptIndicesOk returns a tuple with the KeptIndices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeptIndices

`func (o *DefendResponseModel) SetKeptIndices(v []int32)`

SetKeptIndices sets KeptIndices field to given value.


### GetRemovedIndices

`func (o *DefendResponseModel) GetRemovedIndices() []int32`

GetRemovedIndices returns the RemovedIndices field if non-nil, zero value otherwise.

### GetRemovedIndicesOk

`func (o *DefendResponseModel) GetRemovedIndicesOk() (*[]int32, bool)`

GetRemovedIndicesOk returns a tuple with the RemovedIndices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemovedIndices

`func (o *DefendResponseModel) SetRemovedIndices(v []int32)`

SetRemovedIndices sets RemovedIndices field to given value.


### GetDocumentScores

`func (o *DefendResponseModel) GetDocumentScores() []DocumentScoreModel`

GetDocumentScores returns the DocumentScores field if non-nil, zero value otherwise.

### GetDocumentScoresOk

`func (o *DefendResponseModel) GetDocumentScoresOk() (*[]DocumentScoreModel, bool)`

GetDocumentScoresOk returns a tuple with the DocumentScores field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocumentScores

`func (o *DefendResponseModel) SetDocumentScores(v []DocumentScoreModel)`

SetDocumentScores sets DocumentScores field to given value.


### GetStats

`func (o *DefendResponseModel) GetStats() map[string]interface{}`

GetStats returns the Stats field if non-nil, zero value otherwise.

### GetStatsOk

`func (o *DefendResponseModel) GetStatsOk() (*map[string]interface{}, bool)`

GetStatsOk returns a tuple with the Stats field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStats

`func (o *DefendResponseModel) SetStats(v map[string]interface{})`

SetStats sets Stats field to given value.


### GetRequestId

`func (o *DefendResponseModel) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *DefendResponseModel) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *DefendResponseModel) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *DefendResponseModel) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.

### SetRequestIdNil

`func (o *DefendResponseModel) SetRequestIdNil(b bool)`

 SetRequestIdNil sets the value for RequestId to be an explicit nil

### UnsetRequestId
`func (o *DefendResponseModel) UnsetRequestId()`

UnsetRequestId ensures that no value is present for RequestId, not even an explicit nil
### GetProcessingTimeMs

`func (o *DefendResponseModel) GetProcessingTimeMs() float32`

GetProcessingTimeMs returns the ProcessingTimeMs field if non-nil, zero value otherwise.

### GetProcessingTimeMsOk

`func (o *DefendResponseModel) GetProcessingTimeMsOk() (*float32, bool)`

GetProcessingTimeMsOk returns a tuple with the ProcessingTimeMs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessingTimeMs

`func (o *DefendResponseModel) SetProcessingTimeMs(v float32)`

SetProcessingTimeMs sets ProcessingTimeMs field to given value.


### GetError

`func (o *DefendResponseModel) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *DefendResponseModel) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *DefendResponseModel) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *DefendResponseModel) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *DefendResponseModel) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *DefendResponseModel) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


