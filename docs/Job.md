# Job

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**SignedUrl** | **string** |  | 
**FileName** | **string** |  | 
**PolicyPacks** | **[]string** |  | 
**FileSize** | Pointer to **NullableInt32** |  | [optional] 
**EnhancedPrivacyMode** | Pointer to **bool** |  | [optional] [default to false]

## Methods

### NewJob

`func NewJob(id string, signedUrl string, fileName string, policyPacks []string, ) *Job`

NewJob instantiates a new Job object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJobWithDefaults

`func NewJobWithDefaults() *Job`

NewJobWithDefaults instantiates a new Job object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Job) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Job) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Job) SetId(v string)`

SetId sets Id field to given value.


### GetSignedUrl

`func (o *Job) GetSignedUrl() string`

GetSignedUrl returns the SignedUrl field if non-nil, zero value otherwise.

### GetSignedUrlOk

`func (o *Job) GetSignedUrlOk() (*string, bool)`

GetSignedUrlOk returns a tuple with the SignedUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSignedUrl

`func (o *Job) SetSignedUrl(v string)`

SetSignedUrl sets SignedUrl field to given value.


### GetFileName

`func (o *Job) GetFileName() string`

GetFileName returns the FileName field if non-nil, zero value otherwise.

### GetFileNameOk

`func (o *Job) GetFileNameOk() (*string, bool)`

GetFileNameOk returns a tuple with the FileName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileName

`func (o *Job) SetFileName(v string)`

SetFileName sets FileName field to given value.


### GetPolicyPacks

`func (o *Job) GetPolicyPacks() []string`

GetPolicyPacks returns the PolicyPacks field if non-nil, zero value otherwise.

### GetPolicyPacksOk

`func (o *Job) GetPolicyPacksOk() (*[]string, bool)`

GetPolicyPacksOk returns a tuple with the PolicyPacks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicyPacks

`func (o *Job) SetPolicyPacks(v []string)`

SetPolicyPacks sets PolicyPacks field to given value.


### GetFileSize

`func (o *Job) GetFileSize() int32`

GetFileSize returns the FileSize field if non-nil, zero value otherwise.

### GetFileSizeOk

`func (o *Job) GetFileSizeOk() (*int32, bool)`

GetFileSizeOk returns a tuple with the FileSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileSize

`func (o *Job) SetFileSize(v int32)`

SetFileSize sets FileSize field to given value.

### HasFileSize

`func (o *Job) HasFileSize() bool`

HasFileSize returns a boolean if a field has been set.

### SetFileSizeNil

`func (o *Job) SetFileSizeNil(b bool)`

 SetFileSizeNil sets the value for FileSize to be an explicit nil

### UnsetFileSize
`func (o *Job) UnsetFileSize()`

UnsetFileSize ensures that no value is present for FileSize, not even an explicit nil
### GetEnhancedPrivacyMode

`func (o *Job) GetEnhancedPrivacyMode() bool`

GetEnhancedPrivacyMode returns the EnhancedPrivacyMode field if non-nil, zero value otherwise.

### GetEnhancedPrivacyModeOk

`func (o *Job) GetEnhancedPrivacyModeOk() (*bool, bool)`

GetEnhancedPrivacyModeOk returns a tuple with the EnhancedPrivacyMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnhancedPrivacyMode

`func (o *Job) SetEnhancedPrivacyMode(v bool)`

SetEnhancedPrivacyMode sets EnhancedPrivacyMode field to given value.

### HasEnhancedPrivacyMode

`func (o *Job) HasEnhancedPrivacyMode() bool`

HasEnhancedPrivacyMode returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


