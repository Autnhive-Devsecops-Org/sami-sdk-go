# DefenseSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Applied** | **bool** |  | 
**Success** | **bool** |  | 
**Error** | **NullableString** |  | 
**RemovedIndices** | **[]int32** |  | 
**RiskScores** | **[]float32** |  | 
**ProcessingTimeMs** | **float32** |  | 

## Methods

### NewDefenseSummary

`func NewDefenseSummary(applied bool, success bool, error_ NullableString, removedIndices []int32, riskScores []float32, processingTimeMs float32, ) *DefenseSummary`

NewDefenseSummary instantiates a new DefenseSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDefenseSummaryWithDefaults

`func NewDefenseSummaryWithDefaults() *DefenseSummary`

NewDefenseSummaryWithDefaults instantiates a new DefenseSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApplied

`func (o *DefenseSummary) GetApplied() bool`

GetApplied returns the Applied field if non-nil, zero value otherwise.

### GetAppliedOk

`func (o *DefenseSummary) GetAppliedOk() (*bool, bool)`

GetAppliedOk returns a tuple with the Applied field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplied

`func (o *DefenseSummary) SetApplied(v bool)`

SetApplied sets Applied field to given value.


### GetSuccess

`func (o *DefenseSummary) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *DefenseSummary) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *DefenseSummary) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetError

`func (o *DefenseSummary) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *DefenseSummary) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *DefenseSummary) SetError(v string)`

SetError sets Error field to given value.


### SetErrorNil

`func (o *DefenseSummary) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *DefenseSummary) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetRemovedIndices

`func (o *DefenseSummary) GetRemovedIndices() []int32`

GetRemovedIndices returns the RemovedIndices field if non-nil, zero value otherwise.

### GetRemovedIndicesOk

`func (o *DefenseSummary) GetRemovedIndicesOk() (*[]int32, bool)`

GetRemovedIndicesOk returns a tuple with the RemovedIndices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemovedIndices

`func (o *DefenseSummary) SetRemovedIndices(v []int32)`

SetRemovedIndices sets RemovedIndices field to given value.


### GetRiskScores

`func (o *DefenseSummary) GetRiskScores() []float32`

GetRiskScores returns the RiskScores field if non-nil, zero value otherwise.

### GetRiskScoresOk

`func (o *DefenseSummary) GetRiskScoresOk() (*[]float32, bool)`

GetRiskScoresOk returns a tuple with the RiskScores field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRiskScores

`func (o *DefenseSummary) SetRiskScores(v []float32)`

SetRiskScores sets RiskScores field to given value.


### GetProcessingTimeMs

`func (o *DefenseSummary) GetProcessingTimeMs() float32`

GetProcessingTimeMs returns the ProcessingTimeMs field if non-nil, zero value otherwise.

### GetProcessingTimeMsOk

`func (o *DefenseSummary) GetProcessingTimeMsOk() (*float32, bool)`

GetProcessingTimeMsOk returns a tuple with the ProcessingTimeMs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessingTimeMs

`func (o *DefenseSummary) SetProcessingTimeMs(v float32)`

SetProcessingTimeMs sets ProcessingTimeMs field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


