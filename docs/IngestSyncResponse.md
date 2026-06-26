# IngestSyncResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SourceAdapter** | **string** |  | 
**SyncedCount** | **int32** |  | 
**Accepted** | **int32** |  | 
**Quarantined** | **int32** |  | 
**Rejected** | **int32** |  | 
**AcceptedDocIds** | **[]string** |  | 
**QuarantinedDocIds** | **[]string** |  | 
**RejectedDocIds** | **[]string** |  | 

## Methods

### NewIngestSyncResponse

`func NewIngestSyncResponse(sourceAdapter string, syncedCount int32, accepted int32, quarantined int32, rejected int32, acceptedDocIds []string, quarantinedDocIds []string, rejectedDocIds []string, ) *IngestSyncResponse`

NewIngestSyncResponse instantiates a new IngestSyncResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIngestSyncResponseWithDefaults

`func NewIngestSyncResponseWithDefaults() *IngestSyncResponse`

NewIngestSyncResponseWithDefaults instantiates a new IngestSyncResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSourceAdapter

`func (o *IngestSyncResponse) GetSourceAdapter() string`

GetSourceAdapter returns the SourceAdapter field if non-nil, zero value otherwise.

### GetSourceAdapterOk

`func (o *IngestSyncResponse) GetSourceAdapterOk() (*string, bool)`

GetSourceAdapterOk returns a tuple with the SourceAdapter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceAdapter

`func (o *IngestSyncResponse) SetSourceAdapter(v string)`

SetSourceAdapter sets SourceAdapter field to given value.


### GetSyncedCount

`func (o *IngestSyncResponse) GetSyncedCount() int32`

GetSyncedCount returns the SyncedCount field if non-nil, zero value otherwise.

### GetSyncedCountOk

`func (o *IngestSyncResponse) GetSyncedCountOk() (*int32, bool)`

GetSyncedCountOk returns a tuple with the SyncedCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSyncedCount

`func (o *IngestSyncResponse) SetSyncedCount(v int32)`

SetSyncedCount sets SyncedCount field to given value.


### GetAccepted

`func (o *IngestSyncResponse) GetAccepted() int32`

GetAccepted returns the Accepted field if non-nil, zero value otherwise.

### GetAcceptedOk

`func (o *IngestSyncResponse) GetAcceptedOk() (*int32, bool)`

GetAcceptedOk returns a tuple with the Accepted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccepted

`func (o *IngestSyncResponse) SetAccepted(v int32)`

SetAccepted sets Accepted field to given value.


### GetQuarantined

`func (o *IngestSyncResponse) GetQuarantined() int32`

GetQuarantined returns the Quarantined field if non-nil, zero value otherwise.

### GetQuarantinedOk

`func (o *IngestSyncResponse) GetQuarantinedOk() (*int32, bool)`

GetQuarantinedOk returns a tuple with the Quarantined field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuarantined

`func (o *IngestSyncResponse) SetQuarantined(v int32)`

SetQuarantined sets Quarantined field to given value.


### GetRejected

`func (o *IngestSyncResponse) GetRejected() int32`

GetRejected returns the Rejected field if non-nil, zero value otherwise.

### GetRejectedOk

`func (o *IngestSyncResponse) GetRejectedOk() (*int32, bool)`

GetRejectedOk returns a tuple with the Rejected field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRejected

`func (o *IngestSyncResponse) SetRejected(v int32)`

SetRejected sets Rejected field to given value.


### GetAcceptedDocIds

`func (o *IngestSyncResponse) GetAcceptedDocIds() []string`

GetAcceptedDocIds returns the AcceptedDocIds field if non-nil, zero value otherwise.

### GetAcceptedDocIdsOk

`func (o *IngestSyncResponse) GetAcceptedDocIdsOk() (*[]string, bool)`

GetAcceptedDocIdsOk returns a tuple with the AcceptedDocIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcceptedDocIds

`func (o *IngestSyncResponse) SetAcceptedDocIds(v []string)`

SetAcceptedDocIds sets AcceptedDocIds field to given value.


### GetQuarantinedDocIds

`func (o *IngestSyncResponse) GetQuarantinedDocIds() []string`

GetQuarantinedDocIds returns the QuarantinedDocIds field if non-nil, zero value otherwise.

### GetQuarantinedDocIdsOk

`func (o *IngestSyncResponse) GetQuarantinedDocIdsOk() (*[]string, bool)`

GetQuarantinedDocIdsOk returns a tuple with the QuarantinedDocIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuarantinedDocIds

`func (o *IngestSyncResponse) SetQuarantinedDocIds(v []string)`

SetQuarantinedDocIds sets QuarantinedDocIds field to given value.


### GetRejectedDocIds

`func (o *IngestSyncResponse) GetRejectedDocIds() []string`

GetRejectedDocIds returns the RejectedDocIds field if non-nil, zero value otherwise.

### GetRejectedDocIdsOk

`func (o *IngestSyncResponse) GetRejectedDocIdsOk() (*[]string, bool)`

GetRejectedDocIdsOk returns a tuple with the RejectedDocIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRejectedDocIds

`func (o *IngestSyncResponse) SetRejectedDocIds(v []string)`

SetRejectedDocIds sets RejectedDocIds field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


