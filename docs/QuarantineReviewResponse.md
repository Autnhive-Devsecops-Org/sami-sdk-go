# QuarantineReviewResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DocId** | **string** |  | 
**PreviousStatus** | **string** |  | 
**NewStatus** | **string** |  | 
**Indexed** | Pointer to **bool** |  | [optional] [default to false]
**IndexError** | Pointer to **NullableString** |  | [optional] 
**Review** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewQuarantineReviewResponse

`func NewQuarantineReviewResponse(docId string, previousStatus string, newStatus string, ) *QuarantineReviewResponse`

NewQuarantineReviewResponse instantiates a new QuarantineReviewResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQuarantineReviewResponseWithDefaults

`func NewQuarantineReviewResponseWithDefaults() *QuarantineReviewResponse`

NewQuarantineReviewResponseWithDefaults instantiates a new QuarantineReviewResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDocId

`func (o *QuarantineReviewResponse) GetDocId() string`

GetDocId returns the DocId field if non-nil, zero value otherwise.

### GetDocIdOk

`func (o *QuarantineReviewResponse) GetDocIdOk() (*string, bool)`

GetDocIdOk returns a tuple with the DocId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocId

`func (o *QuarantineReviewResponse) SetDocId(v string)`

SetDocId sets DocId field to given value.


### GetPreviousStatus

`func (o *QuarantineReviewResponse) GetPreviousStatus() string`

GetPreviousStatus returns the PreviousStatus field if non-nil, zero value otherwise.

### GetPreviousStatusOk

`func (o *QuarantineReviewResponse) GetPreviousStatusOk() (*string, bool)`

GetPreviousStatusOk returns a tuple with the PreviousStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviousStatus

`func (o *QuarantineReviewResponse) SetPreviousStatus(v string)`

SetPreviousStatus sets PreviousStatus field to given value.


### GetNewStatus

`func (o *QuarantineReviewResponse) GetNewStatus() string`

GetNewStatus returns the NewStatus field if non-nil, zero value otherwise.

### GetNewStatusOk

`func (o *QuarantineReviewResponse) GetNewStatusOk() (*string, bool)`

GetNewStatusOk returns a tuple with the NewStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewStatus

`func (o *QuarantineReviewResponse) SetNewStatus(v string)`

SetNewStatus sets NewStatus field to given value.


### GetIndexed

`func (o *QuarantineReviewResponse) GetIndexed() bool`

GetIndexed returns the Indexed field if non-nil, zero value otherwise.

### GetIndexedOk

`func (o *QuarantineReviewResponse) GetIndexedOk() (*bool, bool)`

GetIndexedOk returns a tuple with the Indexed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndexed

`func (o *QuarantineReviewResponse) SetIndexed(v bool)`

SetIndexed sets Indexed field to given value.

### HasIndexed

`func (o *QuarantineReviewResponse) HasIndexed() bool`

HasIndexed returns a boolean if a field has been set.

### GetIndexError

`func (o *QuarantineReviewResponse) GetIndexError() string`

GetIndexError returns the IndexError field if non-nil, zero value otherwise.

### GetIndexErrorOk

`func (o *QuarantineReviewResponse) GetIndexErrorOk() (*string, bool)`

GetIndexErrorOk returns a tuple with the IndexError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndexError

`func (o *QuarantineReviewResponse) SetIndexError(v string)`

SetIndexError sets IndexError field to given value.

### HasIndexError

`func (o *QuarantineReviewResponse) HasIndexError() bool`

HasIndexError returns a boolean if a field has been set.

### SetIndexErrorNil

`func (o *QuarantineReviewResponse) SetIndexErrorNil(b bool)`

 SetIndexErrorNil sets the value for IndexError to be an explicit nil

### UnsetIndexError
`func (o *QuarantineReviewResponse) UnsetIndexError()`

UnsetIndexError ensures that no value is present for IndexError, not even an explicit nil
### GetReview

`func (o *QuarantineReviewResponse) GetReview() map[string]interface{}`

GetReview returns the Review field if non-nil, zero value otherwise.

### GetReviewOk

`func (o *QuarantineReviewResponse) GetReviewOk() (*map[string]interface{}, bool)`

GetReviewOk returns a tuple with the Review field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReview

`func (o *QuarantineReviewResponse) SetReview(v map[string]interface{})`

SetReview sets Review field to given value.

### HasReview

`func (o *QuarantineReviewResponse) HasReview() bool`

HasReview returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


