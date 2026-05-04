# SearchResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**url** | **String** | The location of the result. This is the direct URL to the resource that matches the query | 
**title** | **String** | This is the title of the resource. For HTML documents, it reflects `<title>`. For videos, it is the name that would be displayed on the video site. | 
**snippet** | Option<**String**> | A short summary of the contents of the resource | [optional]
**time** | Option<**String**> | The date when the resource was created or last updated. | [optional]
**image** | Option<[**models::SearchResultImage**](SearchResultImage.md)> |  | [optional]
**props** | Option<**std::collections::HashMap<String, serde_json::Value>**> | Holds arbitrary result metadata | [optional]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


