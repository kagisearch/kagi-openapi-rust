# SearchRequestLens

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**sites_included** | Option<**Vec<String>**> | Search only these domains. | [optional]
**sites_excluded** | Option<**Vec<String>**> | Exclude these domains from the search. | [optional]
**keywords_included** | Option<**Vec<String>**> | Return only results containing these keywords. | [optional]
**keywords_excluded** | Option<**Vec<String>**> | Exclude results containing these keywords. | [optional]
**file_type** | Option<**String**> | A specific file type to search for. (e.g., `pdf`) | [optional]
**time_after** | Option<**chrono::NaiveDate**> | Filters for web pages that have been updated or published *after* the given date. | [optional]
**time_before** | Option<**chrono::NaiveDate**> | Filters for web pages that have been updated or published *before* the given date. | [optional]
**time_relative** | Option<**TimeRelative**> | Filters for web pages that have been updated or published in the given interval, relative to today's date. (enum: day, week, month) | [optional]
**search_region** | Option<**String**> | Requests results localized to a specific region. Can be any valid [ISO-3166-1 Alpha-2 country code](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2#Officially_assigned_code_elements), or the special value `no_region`, that will try to get the most general results possible. | [optional]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


