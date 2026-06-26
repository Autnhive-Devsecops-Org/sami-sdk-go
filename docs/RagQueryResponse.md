# RagQueryResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RequestId** | **string** |  | 
**TenantId** | **NullableString** |  | 
**AppId** | **string** |  | 
**Query** | **string** |  | 
**Answer** | **string** |  | 
**ContextDocs** | **[]string** |  | 
**Defense** | [**DefenseSummary**](DefenseSummary.md) |  | 
**PolicyEnforcement** | [**PolicyEnforcementSummary**](PolicyEnforcementSummary.md) |  | 

## Methods

### NewRagQueryResponse

`func NewRagQueryResponse(requestId string, tenantId NullableString, appId string, query string, answer string, contextDocs []string, defense DefenseSummary, policyEnforcement PolicyEnforcementSummary, ) *RagQueryResponse`

NewRagQueryResponse instantiates a new RagQueryResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRagQueryResponseWithDefaults

`func NewRagQueryResponseWithDefaults() *RagQueryResponse`

NewRagQueryResponseWithDefaults instantiates a new RagQueryResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRequestId

`func (o *RagQueryResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *RagQueryResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *RagQueryResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.


### GetTenantId

`func (o *RagQueryResponse) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *RagQueryResponse) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *RagQueryResponse) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.


### SetTenantIdNil

`func (o *RagQueryResponse) SetTenantIdNil(b bool)`

 SetTenantIdNil sets the value for TenantId to be an explicit nil

### UnsetTenantId
`func (o *RagQueryResponse) UnsetTenantId()`

UnsetTenantId ensures that no value is present for TenantId, not even an explicit nil
### GetAppId

`func (o *RagQueryResponse) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *RagQueryResponse) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *RagQueryResponse) SetAppId(v string)`

SetAppId sets AppId field to given value.


### GetQuery

`func (o *RagQueryResponse) GetQuery() string`

GetQuery returns the Query field if non-nil, zero value otherwise.

### GetQueryOk

`func (o *RagQueryResponse) GetQueryOk() (*string, bool)`

GetQueryOk returns a tuple with the Query field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuery

`func (o *RagQueryResponse) SetQuery(v string)`

SetQuery sets Query field to given value.


### GetAnswer

`func (o *RagQueryResponse) GetAnswer() string`

GetAnswer returns the Answer field if non-nil, zero value otherwise.

### GetAnswerOk

`func (o *RagQueryResponse) GetAnswerOk() (*string, bool)`

GetAnswerOk returns a tuple with the Answer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnswer

`func (o *RagQueryResponse) SetAnswer(v string)`

SetAnswer sets Answer field to given value.


### GetContextDocs

`func (o *RagQueryResponse) GetContextDocs() []string`

GetContextDocs returns the ContextDocs field if non-nil, zero value otherwise.

### GetContextDocsOk

`func (o *RagQueryResponse) GetContextDocsOk() (*[]string, bool)`

GetContextDocsOk returns a tuple with the ContextDocs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContextDocs

`func (o *RagQueryResponse) SetContextDocs(v []string)`

SetContextDocs sets ContextDocs field to given value.


### GetDefense

`func (o *RagQueryResponse) GetDefense() DefenseSummary`

GetDefense returns the Defense field if non-nil, zero value otherwise.

### GetDefenseOk

`func (o *RagQueryResponse) GetDefenseOk() (*DefenseSummary, bool)`

GetDefenseOk returns a tuple with the Defense field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefense

`func (o *RagQueryResponse) SetDefense(v DefenseSummary)`

SetDefense sets Defense field to given value.


### GetPolicyEnforcement

`func (o *RagQueryResponse) GetPolicyEnforcement() PolicyEnforcementSummary`

GetPolicyEnforcement returns the PolicyEnforcement field if non-nil, zero value otherwise.

### GetPolicyEnforcementOk

`func (o *RagQueryResponse) GetPolicyEnforcementOk() (*PolicyEnforcementSummary, bool)`

GetPolicyEnforcementOk returns a tuple with the PolicyEnforcement field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicyEnforcement

`func (o *RagQueryResponse) SetPolicyEnforcement(v PolicyEnforcementSummary)`

SetPolicyEnforcement sets PolicyEnforcement field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


