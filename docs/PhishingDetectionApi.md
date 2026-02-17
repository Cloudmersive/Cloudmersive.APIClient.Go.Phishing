# \PhishingDetectionApi

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**PhishingDetectEmailAdvancedPost**](PhishingDetectionApi.md#PhishingDetectEmailAdvancedPost) | **Post** /phishing/detect/email/advanced | Perform advanced AI phishing detection and classification against input email.  Analyzes input email as well as embedded URLs with AI deep learning to detect phishing, phishing and other unsafe content.  Uses 25-100 API calls depending on model selected.
[**PhishingDetectFileAdvancedPost**](PhishingDetectionApi.md#PhishingDetectFileAdvancedPost) | **Post** /phishing/detect/file/advanced | Perform advanced AI phishing detection and classification against input text string.  Analyzes input content as well as embedded URLs with AI deep learning to detect phishing, phishing and other unsafe content.  Uses 25-100 API calls depending on model selected.
[**PhishingDetectFilePost**](PhishingDetectionApi.md#PhishingDetectFilePost) | **Post** /phishing/detect/file | Perform AI phishing detection and classification on an input image or document (PDF or DOCX).  Analyzes input content as well as embedded URLs with AI deep learnign to detect phishing and other unsafe content.  Uses 100-125 API calls depending on model selected.
[**PhishingDetectTextStringAdvancedPost**](PhishingDetectionApi.md#PhishingDetectTextStringAdvancedPost) | **Post** /phishing/detect/text-string/advanced | Perform advanced AI phishing detection and classification against input text string.  Analyzes input content as well as embedded URLs with AI deep learnign to detect spam, phishing and other unsafe content.  Uses 25-100 API calls depending on model selected.
[**PhishingDetectUrlAdvancedPost**](PhishingDetectionApi.md#PhishingDetectUrlAdvancedPost) | **Post** /phishing/detect/url/advanced | Perform advanced AI phishing detection and classification against an input URL.  Retrieves the URL content, checks for SSRF threats, and analyzes the page with AI deep learning to detect phishing and other unsafe content.  Uses 100-125 API calls.


# **PhishingDetectEmailAdvancedPost**
> PhishingDetectionEmailAdvancedResponse PhishingDetectEmailAdvancedPost(ctx, optional)
Perform advanced AI phishing detection and classification against input email.  Analyzes input email as well as embedded URLs with AI deep learning to detect phishing, phishing and other unsafe content.  Uses 25-100 API calls depending on model selected.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***PhishingDetectionApiPhishingDetectEmailAdvancedPostOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a PhishingDetectionApiPhishingDetectEmailAdvancedPostOpts struct

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**optional.Interface of AdvancedEmailDetectionRequest**](AdvancedEmailDetectionRequest.md)| Phishing detection request | 

### Return type

[**PhishingDetectionEmailAdvancedResponse**](PhishingDetectionEmailAdvancedResponse.md)

### Authorization

[Apikey](../README.md#Apikey)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **PhishingDetectFileAdvancedPost**
> PhishingDetectionAdvancedResponse PhishingDetectFileAdvancedPost(ctx, optional)
Perform advanced AI phishing detection and classification against input text string.  Analyzes input content as well as embedded URLs with AI deep learning to detect phishing, phishing and other unsafe content.  Uses 25-100 API calls depending on model selected.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***PhishingDetectionApiPhishingDetectFileAdvancedPostOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a PhishingDetectionApiPhishingDetectFileAdvancedPostOpts struct

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | **optional.String**|  | [default to Advanced]
 **customPolicyId** | **optional.String**|  | 
 **inputFile** | **optional.Interface of *os.File**|  | 

### Return type

[**PhishingDetectionAdvancedResponse**](PhishingDetectionAdvancedResponse.md)

### Authorization

[Apikey](../README.md#Apikey)

### HTTP request headers

 - **Content-Type**: multipart/form-data
 - **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **PhishingDetectFilePost**
> PhishingDetectionResponse PhishingDetectFilePost(ctx, optional)
Perform AI phishing detection and classification on an input image or document (PDF or DOCX).  Analyzes input content as well as embedded URLs with AI deep learnign to detect phishing and other unsafe content.  Uses 100-125 API calls depending on model selected.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***PhishingDetectionApiPhishingDetectFilePostOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a PhishingDetectionApiPhishingDetectFilePostOpts struct

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | **optional.String**| Model to use; default setting is Advanced | [default to Advanced]
 **inputFile** | **optional.Interface of *os.File**|  | 

### Return type

[**PhishingDetectionResponse**](PhishingDetectionResponse.md)

### Authorization

[Apikey](../README.md#Apikey)

### HTTP request headers

 - **Content-Type**: multipart/form-data
 - **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **PhishingDetectTextStringAdvancedPost**
> PhishingDetectionAdvancedResponse PhishingDetectTextStringAdvancedPost(ctx, optional)
Perform advanced AI phishing detection and classification against input text string.  Analyzes input content as well as embedded URLs with AI deep learnign to detect spam, phishing and other unsafe content.  Uses 25-100 API calls depending on model selected.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***PhishingDetectionApiPhishingDetectTextStringAdvancedPostOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a PhishingDetectionApiPhishingDetectTextStringAdvancedPostOpts struct

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**optional.Interface of PhishingDetectionAdvancedRequest**](PhishingDetectionAdvancedRequest.md)| Phishing detection request | 

### Return type

[**PhishingDetectionAdvancedResponse**](PhishingDetectionAdvancedResponse.md)

### Authorization

[Apikey](../README.md#Apikey)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **PhishingDetectUrlAdvancedPost**
> PhishingDetectionUrlAdvancedResponse PhishingDetectUrlAdvancedPost(ctx, optional)
Perform advanced AI phishing detection and classification against an input URL.  Retrieves the URL content, checks for SSRF threats, and analyzes the page with AI deep learning to detect phishing and other unsafe content.  Uses 100-125 API calls.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***PhishingDetectionApiPhishingDetectUrlAdvancedPostOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a PhishingDetectionApiPhishingDetectUrlAdvancedPostOpts struct

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**optional.Interface of AdvancedUrlDetectionRequest**](AdvancedUrlDetectionRequest.md)| URL phishing detection request | 

### Return type

[**PhishingDetectionUrlAdvancedResponse**](PhishingDetectionUrlAdvancedResponse.md)

### Authorization

[Apikey](../README.md#Apikey)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

