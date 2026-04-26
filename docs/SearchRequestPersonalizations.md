# SearchRequestPersonalizations

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**domains** | Option<[**Vec<models::SearchRequestPersonalizationsDomainsInner>**](SearchRequestPersonalizationsDomainsInner.md)> | Domain-level personalization rules (maximum 1000 rules). Each rule can boost or lower the ranking of results from specific domains. | [optional]
**regexes** | Option<[**Vec<models::SearchRequestPersonalizationsRegexesInner>**](SearchRequestPersonalizationsRegexesInner.md)> | Regex-based personalization rules (maximum 1000 rules, max 1000 bytes per pattern). | [optional]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


