# \ExtractApi

All URIs are relative to *https://kagi.com/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**extract_content**](ExtractApi.md#extract_content) | **POST** /extract | Extract page content as markdown from URLs



## extract_content

> models::ExtractResponse extract_content(extract_request)
Extract page content as markdown from URLs

Extracts markdown content from up to 10 HTTP(s) URLs. Each URL is processed and the extracted content is returned in the response. 

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**extract_request** | [**ExtractRequest**](ExtractRequest.md) |  | [required] |

### Return type

[**models::ExtractResponse**](extractResponse.md)

### Authorization

[kagi](../README.md#kagi)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json, text/markdown

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

