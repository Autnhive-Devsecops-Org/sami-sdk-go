# ChatCompletionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Messages** | [**[]ChatMessage**](ChatMessage.md) | List of messages comprising the conversation. | 
**AI_KEY** | Pointer to **NullableString** | Optional explicit OpenAI API key. | [optional] 
**AI_URL** | Pointer to **NullableString** | Optional custom provider base URL. | [optional] 
**AI_PROVIDER** | Pointer to **NullableString** | Optional provider routing string. | [optional] 

## Methods

### NewChatCompletionRequest

`func NewChatCompletionRequest(messages []ChatMessage, ) *ChatCompletionRequest`

NewChatCompletionRequest instantiates a new ChatCompletionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChatCompletionRequestWithDefaults

`func NewChatCompletionRequestWithDefaults() *ChatCompletionRequest`

NewChatCompletionRequestWithDefaults instantiates a new ChatCompletionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessages

`func (o *ChatCompletionRequest) GetMessages() []ChatMessage`

GetMessages returns the Messages field if non-nil, zero value otherwise.

### GetMessagesOk

`func (o *ChatCompletionRequest) GetMessagesOk() (*[]ChatMessage, bool)`

GetMessagesOk returns a tuple with the Messages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessages

`func (o *ChatCompletionRequest) SetMessages(v []ChatMessage)`

SetMessages sets Messages field to given value.


### GetAI_KEY

`func (o *ChatCompletionRequest) GetAI_KEY() string`

GetAI_KEY returns the AI_KEY field if non-nil, zero value otherwise.

### GetAI_KEYOk

`func (o *ChatCompletionRequest) GetAI_KEYOk() (*string, bool)`

GetAI_KEYOk returns a tuple with the AI_KEY field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAI_KEY

`func (o *ChatCompletionRequest) SetAI_KEY(v string)`

SetAI_KEY sets AI_KEY field to given value.

### HasAI_KEY

`func (o *ChatCompletionRequest) HasAI_KEY() bool`

HasAI_KEY returns a boolean if a field has been set.

### SetAI_KEYNil

`func (o *ChatCompletionRequest) SetAI_KEYNil(b bool)`

 SetAI_KEYNil sets the value for AI_KEY to be an explicit nil

### UnsetAI_KEY
`func (o *ChatCompletionRequest) UnsetAI_KEY()`

UnsetAI_KEY ensures that no value is present for AI_KEY, not even an explicit nil
### GetAI_URL

`func (o *ChatCompletionRequest) GetAI_URL() string`

GetAI_URL returns the AI_URL field if non-nil, zero value otherwise.

### GetAI_URLOk

`func (o *ChatCompletionRequest) GetAI_URLOk() (*string, bool)`

GetAI_URLOk returns a tuple with the AI_URL field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAI_URL

`func (o *ChatCompletionRequest) SetAI_URL(v string)`

SetAI_URL sets AI_URL field to given value.

### HasAI_URL

`func (o *ChatCompletionRequest) HasAI_URL() bool`

HasAI_URL returns a boolean if a field has been set.

### SetAI_URLNil

`func (o *ChatCompletionRequest) SetAI_URLNil(b bool)`

 SetAI_URLNil sets the value for AI_URL to be an explicit nil

### UnsetAI_URL
`func (o *ChatCompletionRequest) UnsetAI_URL()`

UnsetAI_URL ensures that no value is present for AI_URL, not even an explicit nil
### GetAI_PROVIDER

`func (o *ChatCompletionRequest) GetAI_PROVIDER() string`

GetAI_PROVIDER returns the AI_PROVIDER field if non-nil, zero value otherwise.

### GetAI_PROVIDEROk

`func (o *ChatCompletionRequest) GetAI_PROVIDEROk() (*string, bool)`

GetAI_PROVIDEROk returns a tuple with the AI_PROVIDER field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAI_PROVIDER

`func (o *ChatCompletionRequest) SetAI_PROVIDER(v string)`

SetAI_PROVIDER sets AI_PROVIDER field to given value.

### HasAI_PROVIDER

`func (o *ChatCompletionRequest) HasAI_PROVIDER() bool`

HasAI_PROVIDER returns a boolean if a field has been set.

### SetAI_PROVIDERNil

`func (o *ChatCompletionRequest) SetAI_PROVIDERNil(b bool)`

 SetAI_PROVIDERNil sets the value for AI_PROVIDER to be an explicit nil

### UnsetAI_PROVIDER
`func (o *ChatCompletionRequest) UnsetAI_PROVIDER()`

UnsetAI_PROVIDER ensures that no value is present for AI_PROVIDER, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


