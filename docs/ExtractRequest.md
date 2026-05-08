# ExtractRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**pages** | [**Vec<models::PageInput>**](PageInput.md) | Array of pages to extract content from. Must contain 1-10 URLs. Each URL must be a valid HTTPS URL.  | 
**timeout** | Option<**f32**> | Optional timeout in seconds for the extraction operation | [optional]
**format** | Option<**Format**> | **(EXPERIMENTAL)** Format to serialize the API response as. The exact contents and structure of markdown output is still being worked on - please send your feedback! (enum: json, markdown) | [optional][default to Json]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


