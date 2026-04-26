# TranslateDictionary200ResponseDefinition

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**word** | Option<**String**> | The word being defined (remains in word_language) | [optional]
**primary_meaning** | Option<[**models::TranslateDictionary200ResponseDefinitionPrimaryMeaning**](TranslateDictionary200ResponseDefinitionPrimaryMeaning.md)> |  | [optional]
**secondary_meanings** | Option<[**Vec<models::TranslateDictionary200ResponseDefinitionSecondaryMeaningsInner>**](TranslateDictionary200ResponseDefinitionSecondaryMeaningsInner.md)> | Secondary or less common meanings | [optional]
**examples** | Option<**Vec<String>**> | Example sentences showing usage (remains in word_language, but includes translations in parentheses when word_language differs from definition_language) | [optional]
**pronunciation** | Option<**String**> | Phonetic pronunciation of the word in its original language (if available) | [optional]
**etymology** | Option<**String**> | Information about word origin (translated to definition_language if available) | [optional]
**notes** | Option<**String**> | Brief usage notes, cultural context, or helpful tips for language learners (translated to definition_language) | [optional]
**temporal_trend** | Option<**TemporalTrend**> | Optional usage trend indicator. Always in English as an enum value. Only provided when trend data is clear and meaningful. (enum: increasing, stable, decreasing) | [optional]
**gender** | Option<**Gender**> | Grammatical gender for nouns in languages that have gender. Always in English as an enum value. Only included for nouns in gendered languages. (enum: masculine, feminine, neuter, common) | [optional]
**plural** | Option<**String**> | Plural form of the word (remains in word_language). Only included for irregular or non-standard plurals. | [optional]
**conjugation_notes** | Option<**String**> | Brief notes about verb conjugation irregularities (remains in word_language). Only included for verbs with notable irregularities. | [optional]
**related_words** | Option<**Vec<String>**> | Related words from the same root or word family (remains in word_language) | [optional]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


