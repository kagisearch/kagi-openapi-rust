# SearchRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**query** | **String** | Search query to run. | 
**workflow** | Option<**Workflow**> | Type of results to return. (enum: search, images, videos, news, podcasts) | [optional][default to Search]
**format** | Option<**Format**> | **(EXPERIMENTAL)** Format to serialize the API response as. The exact contents and structure of markdown output is still being worked on - please send your feedback! (enum: json, markdown) | [optional][default to Json]
**lens_id** | Option<**String**> | Lens to apply to the search. Can be a built-in lens's identifier or a lens ID as shown on https://kagi.com/settings/lenses when a lens is set to be shareable. Can be just the ID portion of the URL (`https://kagi.com/lenses/ID`) or the full URL. | [optional]
**lens** | Option<[**models::SearchRequestLens**](SearchRequestLens.md)> |  | [optional]
**timeout** | Option<**f64**> | Number of seconds to allow for collecting search results. Lower values will return results more quickly, but may be lower quality or inconsistent between calls. If omitted, will use the latest recommended value by Kagi. | [optional]
**page** | Option<**i32**> | Page number for paginated results. Must be between 1 and 10. | [optional]
**limit** | Option<**i32**> | Maximum number of results to return. Must be between 1 and 1024. | [optional]
**filters** | Option<[**models::SearchRequestFilters**](SearchRequestFilters.md)> |  | [optional]
**extract** | Option<[**models::SearchRequestExtract**](SearchRequestExtract.md)> |  | [optional]
**safe_search** | Option<**bool**> | Whether safe search is enabled, omitting potentially NSFW content. | [optional][default to true]
**personalizations** | Option<[**models::SearchRequestPersonalizations**](SearchRequestPersonalizations.md)> |  | [optional]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


