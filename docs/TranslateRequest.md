# TranslateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**text** | [**models::TranslateRequestText**](TranslateRequestText.md) |  | 
**source_lang** | Option<**String**> | Source language code (ISO-639) or \"auto\" for automatic detection | [optional][default to auto]
**target_lang** | Option<**String**> | Target language code (ISO-639) | [optional][default to en]
**from** | Option<**String**> | Legacy parameter for source language (use source_lang instead) | [optional]
**to** | Option<**String**> | Legacy parameter for target language (use target_lang instead) | [optional]
**context** | Option<**String**> | Additional context to improve translation accuracy | [optional]
**preserve_formatting** | Option<**bool**> | Whether to preserve original text formatting | [optional][default to false]
**formality** | Option<**Formality**> | Level of formality in translation. All formality levels are supported for all language pairs. 'prefer_more' is same as 'more', and 'prefer_less' is same as 'less' (included for backwards compatibility). (enum: default, more, less, prefer_more, prefer_less) | [optional][default to Default]
**speaker_gender** | Option<**SpeakerGender**> | Gender of the speaker for languages with gender-specific expressions (enum: unknown, feminine, masculine, neutral) | [optional][default to Unknown]
**addressee_gender** | Option<**AddresseeGender**> | Gender of the addressee for languages with gender-specific expressions (enum: unknown, feminine, masculine, neutral) | [optional][default to Unknown]
**translation_style** | Option<**TranslationStyle**> | Style of translation (natural for fluency, literal for exactness) (enum: natural, literal) | [optional][default to Natural]
**predicted_language** | Option<**String**> | Pre-detected source language (if available) | [optional]
**prediction** | Option<**String**> | Pre-generated translation (if available) | [optional]
**stream** | Option<**bool**> | Whether to stream the response as Server-Sent Events | [optional][default to false]
**dictionary_language** | Option<**String**> | Language code for dictionary definitions (if not provided, the source language will be used) | [optional]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


