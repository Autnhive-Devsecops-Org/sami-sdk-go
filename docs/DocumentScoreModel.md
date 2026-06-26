# DocumentScoreModel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Index** | **int32** |  | 
**RiskScore** | **float32** |  | 
**IsRemoved** | **bool** |  | 
**Reason** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewDocumentScoreModel

`func NewDocumentScoreModel(index int32, riskScore float32, isRemoved bool, ) *DocumentScoreModel`

NewDocumentScoreModel instantiates a new DocumentScoreModel object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDocumentScoreModelWithDefaults

`func NewDocumentScoreModelWithDefaults() *DocumentScoreModel`

NewDocumentScoreModelWithDefaults instantiates a new DocumentScoreModel object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIndex

`func (o *DocumentScoreModel) GetIndex() int32`

GetIndex returns the Index field if non-nil, zero value otherwise.

### GetIndexOk

`func (o *DocumentScoreModel) GetIndexOk() (*int32, bool)`

GetIndexOk returns a tuple with the Index field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndex

`func (o *DocumentScoreModel) SetIndex(v int32)`

SetIndex sets Index field to given value.


### GetRiskScore

`func (o *DocumentScoreModel) GetRiskScore() float32`

GetRiskScore returns the RiskScore field if non-nil, zero value otherwise.

### GetRiskScoreOk

`func (o *DocumentScoreModel) GetRiskScoreOk() (*float32, bool)`

GetRiskScoreOk returns a tuple with the RiskScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRiskScore

`func (o *DocumentScoreModel) SetRiskScore(v float32)`

SetRiskScore sets RiskScore field to given value.


### GetIsRemoved

`func (o *DocumentScoreModel) GetIsRemoved() bool`

GetIsRemoved returns the IsRemoved field if non-nil, zero value otherwise.

### GetIsRemovedOk

`func (o *DocumentScoreModel) GetIsRemovedOk() (*bool, bool)`

GetIsRemovedOk returns a tuple with the IsRemoved field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsRemoved

`func (o *DocumentScoreModel) SetIsRemoved(v bool)`

SetIsRemoved sets IsRemoved field to given value.


### GetReason

`func (o *DocumentScoreModel) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *DocumentScoreModel) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *DocumentScoreModel) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *DocumentScoreModel) HasReason() bool`

HasReason returns a boolean if a field has been set.

### SetReasonNil

`func (o *DocumentScoreModel) SetReasonNil(b bool)`

 SetReasonNil sets the value for Reason to be an explicit nil

### UnsetReason
`func (o *DocumentScoreModel) UnsetReason()`

UnsetReason ensures that no value is present for Reason, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


