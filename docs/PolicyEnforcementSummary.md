# PolicyEnforcementSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PolicyMode** | **string** |  | 
**Blocked** | **bool** |  | 
**Reason** | **NullableString** |  | 
**RetrieverBackend** | Pointer to **NullableString** |  | [optional] 
**LegacyBackfillRequired** | Pointer to **bool** |  | [optional] [default to true]
**LegacyBackfillCompleted** | Pointer to **bool** |  | [optional] [default to false]
**RiskAcknowledgedAt** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewPolicyEnforcementSummary

`func NewPolicyEnforcementSummary(policyMode string, blocked bool, reason NullableString, ) *PolicyEnforcementSummary`

NewPolicyEnforcementSummary instantiates a new PolicyEnforcementSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPolicyEnforcementSummaryWithDefaults

`func NewPolicyEnforcementSummaryWithDefaults() *PolicyEnforcementSummary`

NewPolicyEnforcementSummaryWithDefaults instantiates a new PolicyEnforcementSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPolicyMode

`func (o *PolicyEnforcementSummary) GetPolicyMode() string`

GetPolicyMode returns the PolicyMode field if non-nil, zero value otherwise.

### GetPolicyModeOk

`func (o *PolicyEnforcementSummary) GetPolicyModeOk() (*string, bool)`

GetPolicyModeOk returns a tuple with the PolicyMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicyMode

`func (o *PolicyEnforcementSummary) SetPolicyMode(v string)`

SetPolicyMode sets PolicyMode field to given value.


### GetBlocked

`func (o *PolicyEnforcementSummary) GetBlocked() bool`

GetBlocked returns the Blocked field if non-nil, zero value otherwise.

### GetBlockedOk

`func (o *PolicyEnforcementSummary) GetBlockedOk() (*bool, bool)`

GetBlockedOk returns a tuple with the Blocked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlocked

`func (o *PolicyEnforcementSummary) SetBlocked(v bool)`

SetBlocked sets Blocked field to given value.


### GetReason

`func (o *PolicyEnforcementSummary) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *PolicyEnforcementSummary) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *PolicyEnforcementSummary) SetReason(v string)`

SetReason sets Reason field to given value.


### SetReasonNil

`func (o *PolicyEnforcementSummary) SetReasonNil(b bool)`

 SetReasonNil sets the value for Reason to be an explicit nil

### UnsetReason
`func (o *PolicyEnforcementSummary) UnsetReason()`

UnsetReason ensures that no value is present for Reason, not even an explicit nil
### GetRetrieverBackend

`func (o *PolicyEnforcementSummary) GetRetrieverBackend() string`

GetRetrieverBackend returns the RetrieverBackend field if non-nil, zero value otherwise.

### GetRetrieverBackendOk

`func (o *PolicyEnforcementSummary) GetRetrieverBackendOk() (*string, bool)`

GetRetrieverBackendOk returns a tuple with the RetrieverBackend field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetrieverBackend

`func (o *PolicyEnforcementSummary) SetRetrieverBackend(v string)`

SetRetrieverBackend sets RetrieverBackend field to given value.

### HasRetrieverBackend

`func (o *PolicyEnforcementSummary) HasRetrieverBackend() bool`

HasRetrieverBackend returns a boolean if a field has been set.

### SetRetrieverBackendNil

`func (o *PolicyEnforcementSummary) SetRetrieverBackendNil(b bool)`

 SetRetrieverBackendNil sets the value for RetrieverBackend to be an explicit nil

### UnsetRetrieverBackend
`func (o *PolicyEnforcementSummary) UnsetRetrieverBackend()`

UnsetRetrieverBackend ensures that no value is present for RetrieverBackend, not even an explicit nil
### GetLegacyBackfillRequired

`func (o *PolicyEnforcementSummary) GetLegacyBackfillRequired() bool`

GetLegacyBackfillRequired returns the LegacyBackfillRequired field if non-nil, zero value otherwise.

### GetLegacyBackfillRequiredOk

`func (o *PolicyEnforcementSummary) GetLegacyBackfillRequiredOk() (*bool, bool)`

GetLegacyBackfillRequiredOk returns a tuple with the LegacyBackfillRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLegacyBackfillRequired

`func (o *PolicyEnforcementSummary) SetLegacyBackfillRequired(v bool)`

SetLegacyBackfillRequired sets LegacyBackfillRequired field to given value.

### HasLegacyBackfillRequired

`func (o *PolicyEnforcementSummary) HasLegacyBackfillRequired() bool`

HasLegacyBackfillRequired returns a boolean if a field has been set.

### GetLegacyBackfillCompleted

`func (o *PolicyEnforcementSummary) GetLegacyBackfillCompleted() bool`

GetLegacyBackfillCompleted returns the LegacyBackfillCompleted field if non-nil, zero value otherwise.

### GetLegacyBackfillCompletedOk

`func (o *PolicyEnforcementSummary) GetLegacyBackfillCompletedOk() (*bool, bool)`

GetLegacyBackfillCompletedOk returns a tuple with the LegacyBackfillCompleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLegacyBackfillCompleted

`func (o *PolicyEnforcementSummary) SetLegacyBackfillCompleted(v bool)`

SetLegacyBackfillCompleted sets LegacyBackfillCompleted field to given value.

### HasLegacyBackfillCompleted

`func (o *PolicyEnforcementSummary) HasLegacyBackfillCompleted() bool`

HasLegacyBackfillCompleted returns a boolean if a field has been set.

### GetRiskAcknowledgedAt

`func (o *PolicyEnforcementSummary) GetRiskAcknowledgedAt() string`

GetRiskAcknowledgedAt returns the RiskAcknowledgedAt field if non-nil, zero value otherwise.

### GetRiskAcknowledgedAtOk

`func (o *PolicyEnforcementSummary) GetRiskAcknowledgedAtOk() (*string, bool)`

GetRiskAcknowledgedAtOk returns a tuple with the RiskAcknowledgedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRiskAcknowledgedAt

`func (o *PolicyEnforcementSummary) SetRiskAcknowledgedAt(v string)`

SetRiskAcknowledgedAt sets RiskAcknowledgedAt field to given value.

### HasRiskAcknowledgedAt

`func (o *PolicyEnforcementSummary) HasRiskAcknowledgedAt() bool`

HasRiskAcknowledgedAt returns a boolean if a field has been set.

### SetRiskAcknowledgedAtNil

`func (o *PolicyEnforcementSummary) SetRiskAcknowledgedAtNil(b bool)`

 SetRiskAcknowledgedAtNil sets the value for RiskAcknowledgedAt to be an explicit nil

### UnsetRiskAcknowledgedAt
`func (o *PolicyEnforcementSummary) UnsetRiskAcknowledgedAt()`

UnsetRiskAcknowledgedAt ensures that no value is present for RiskAcknowledgedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


