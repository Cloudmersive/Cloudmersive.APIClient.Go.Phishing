# PhishingDetectionAdvancedResponse

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CleanResult** | **bool** | True if the result is not phishing (clean), and false otherwise | [optional] [default to null]
**ContainsPhishing** | **bool** | True if the input text contains a phishing attempt, false otherwise | [optional] [default to null]
**ContainsUnsolicitedSales** | **bool** | True if the input text contains unsolicited sales, false otherwise | [optional] [default to null]
**ContainsPromotionalContent** | **bool** | True if the input text contains promotional content, false otherwise | [optional] [default to null]
**ContainsWebUrls** | **bool** | True if the input text contains web URLs, including homoglyph URLs and spaced-out URL workarounds | [optional] [default to null]
**ContainsPhoneNumbers** | **bool** | True if the input text contains phone numbers, including homoglyph digits and spaced-out or spelled-out workarounds | [optional] [default to null]
**ContainsEmailAddresses** | **bool** | True if the input text contains email addresses, including homoglyph characters and obfuscated workarounds | [optional] [default to null]
**ConfidenceLevel** | **float64** | Confidence level between 0.0 and 1.0 where values over 0.9 indicate high confidence | [optional] [default to null]
**AnalysisRationale** | **string** | Rationale for why the conclusion was formed | [optional] [default to null]
**UnsafeUrls** | [**[]UnsafeUrlResult**](UnsafeUrlResult.md) | URLs detected in the input text that were analyzed and found to be unsafe. Only populated when ProvideUrlAnalysis is true and URLs are detected. | [optional] [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


