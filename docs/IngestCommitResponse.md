# IngestCommitResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Accepted** | **int32** |  | 
**Quarantined** | **int32** |  | 
**Rejected** | **int32** |  | 
**AcceptedDocIds** | **[]string** |  | 
**QuarantinedDocIds** | **[]string** |  | 
**RejectedDocIds** | **[]string** |  | 

## Methods

### NewIngestCommitResponse

`func NewIngestCommitResponse(accepted int32, quarantined int32, rejected int32, acceptedDocIds []string, quarantinedDocIds []string, rejectedDocIds []string, ) *IngestCommitResponse`

NewIngestCommitResponse instantiates a new IngestCommitResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIngestCommitResponseWithDefaults

`func NewIngestCommitResponseWithDefaults() *IngestCommitResponse`

NewIngestCommitResponseWithDefaults instantiates a new IngestCommitResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccepted

`func (o *IngestCommitResponse) GetAccepted() int32`

GetAccepted returns the Accepted field if non-nil, zero value otherwise.

### GetAcceptedOk

`func (o *IngestCommitResponse) GetAcceptedOk() (*int32, bool)`

GetAcceptedOk returns a tuple with the Accepted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccepted

`func (o *IngestCommitResponse) SetAccepted(v int32)`

SetAccepted sets Accepted field to given value.


### GetQuarantined

`func (o *IngestCommitResponse) GetQuarantined() int32`

GetQuarantined returns the Quarantined field if non-nil, zero value otherwise.

### GetQuarantinedOk

`func (o *IngestCommitResponse) GetQuarantinedOk() (*int32, bool)`

GetQuarantinedOk returns a tuple with the Quarantined field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuarantined

`func (o *IngestCommitResponse) SetQuarantined(v int32)`

SetQuarantined sets Quarantined field to given value.


### GetRejected

`func (o *IngestCommitResponse) GetRejected() int32`

GetRejected returns the Rejected field if non-nil, zero value otherwise.

### GetRejectedOk

`func (o *IngestCommitResponse) GetRejectedOk() (*int32, bool)`

GetRejectedOk returns a tuple with the Rejected field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRejected

`func (o *IngestCommitResponse) SetRejected(v int32)`

SetRejected sets Rejected field to given value.


### GetAcceptedDocIds

`func (o *IngestCommitResponse) GetAcceptedDocIds() []string`

GetAcceptedDocIds returns the AcceptedDocIds field if non-nil, zero value otherwise.

### GetAcceptedDocIdsOk

`func (o *IngestCommitResponse) GetAcceptedDocIdsOk() (*[]string, bool)`

GetAcceptedDocIdsOk returns a tuple with the AcceptedDocIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcceptedDocIds

`func (o *IngestCommitResponse) SetAcceptedDocIds(v []string)`

SetAcceptedDocIds sets AcceptedDocIds field to given value.


### GetQuarantinedDocIds

`func (o *IngestCommitResponse) GetQuarantinedDocIds() []string`

GetQuarantinedDocIds returns the QuarantinedDocIds field if non-nil, zero value otherwise.

### GetQuarantinedDocIdsOk

`func (o *IngestCommitResponse) GetQuarantinedDocIdsOk() (*[]string, bool)`

GetQuarantinedDocIdsOk returns a tuple with the QuarantinedDocIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuarantinedDocIds

`func (o *IngestCommitResponse) SetQuarantinedDocIds(v []string)`

SetQuarantinedDocIds sets QuarantinedDocIds field to given value.


### GetRejectedDocIds

`func (o *IngestCommitResponse) GetRejectedDocIds() []string`

GetRejectedDocIds returns the RejectedDocIds field if non-nil, zero value otherwise.

### GetRejectedDocIdsOk

`func (o *IngestCommitResponse) GetRejectedDocIdsOk() (*[]string, bool)`

GetRejectedDocIdsOk returns a tuple with the RejectedDocIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRejectedDocIds

`func (o *IngestCommitResponse) SetRejectedDocIds(v []string)`

SetRejectedDocIds sets RejectedDocIds field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


