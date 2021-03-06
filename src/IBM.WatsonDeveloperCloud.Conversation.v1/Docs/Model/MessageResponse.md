# .IBM.WatsonDeveloperCloud.Conversation.v1.Model.MessageResponse
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Input** | [**MessageInput**](MessageInput.md) | The user input from the request. | [optional] 
**Intents** | [**List<RuntimeIntent>**](RuntimeIntent.md) | An array of intents recognized in the user input, sorted in descending order of confidence. | [optional] 
**Entities** | [**List<RuntimeEntity>**](RuntimeEntity.md) | An array of entities identified in the user input. | [optional] 
**AlternateIntents** | **bool?** | Whether to return more than one intent. `true` indicates that all matching intents are returned. | [optional] [default to false]
**Context** | [**RuntimeContext**](RuntimeContext.md) | State information for the conversation. | [optional] 
**Output** | [**RuntimeOutput**](RuntimeOutput.md) | Output from the dialog, including the response to the user, the nodes that were triggered, and log messages. | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

