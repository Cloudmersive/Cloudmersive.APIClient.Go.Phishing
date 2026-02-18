# PhishingDetectionAdvancedRequest

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**InputString** | **string** | Input text string to detect phishing against | [optional] [default to null]
**TextType** | **string** | Optional: Type of text being analyzed. Must be one of: \&quot;TextMessage\&quot;, \&quot;UserMessage\&quot;, \&quot;SalesLead\&quot;, \&quot;EmailMessage\&quot;, \&quot;SupportCase\&quot;, \&quot;AppMessage\&quot;, \&quot;Other\&quot;. | [optional] [default to null]
**Model** | **string** | Optional: Specify which AI model to use.  Possible choices are Normal and Advanced.  Default is Advanced. | [optional] [default to null]
**AllowUnsolicitedSales** | **bool** | Optional: True if unsolicited sales should be allowed, false otherwise. Defaults to true. | [optional] [default to null]
**AllowPromotionalContent** | **bool** | Optional: True if promotional content should be allowed, false otherwise. Defaults to true. | [optional] [default to null]
**AllowWebUrls** | **bool** | Optional: True if web URLs should be allowed in the input text, false otherwise. Defaults to true. When false, input containing URLs (including homoglyph URLs and spaced-out URLs) will be flagged as not clean. | [optional] [default to null]
**AllowPhoneNumbers** | **bool** | Optional: True if phone numbers should be allowed in the input text, false otherwise. Defaults to true. When false, input containing phone numbers (including homoglyph digits and spaced-out or spelled-out workarounds) will be flagged as not clean. | [optional] [default to null]
**AllowEmailAddresses** | **bool** | Optional: True if email addresses should be allowed in the input text, false otherwise. Defaults to true. When false, input containing email addresses (including homoglyph characters and obfuscated workarounds like \&quot;danny at somedomaine [DOT] com\&quot;) will be flagged as not clean. | [optional] [default to null]
**ProvideUrlAnalysis** | **bool** | Optional: True to perform deep URL analysis on any URLs detected in the text. When enabled, if the initial AI scan detects URLs, a second AI call enumerates them and each URL is individually analyzed for phishing. Defaults to true. | [optional] [default to null]
**CustomPolicyID** | **string** | Apply a Custom Policy for Phishing Enforcement by providing the ID; to create a Custom Policy,  navigate to the Cloudmersive Management Portal and select Custom Policies.  Requires Managed Instance or Private Cloud | [optional] [default to null]
**ProvideAnalysisRationale** | **bool** | Optional: Set to true to include an analysis rationale in the response explaining why the content was or was not flagged.  Default is true. | [optional] [default to null]
**FromName** | **string** | Optional: Name of the sender | [optional] [default to null]
**ToName** | **string** | Optional: Name of the recipient | [optional] [default to null]
**FromPhoneNumber** | **string** | Optional: Phone number of the sender | [optional] [default to null]
**ToPhoneNumber** | **string** | Optional: Phone number of the recipient | [optional] [default to null]
**FromEmailAddress** | **string** | Optional: Email address of the sender | [optional] [default to null]
**ToEmailAddress** | **string** | Optional: Email address of the recipient | [optional] [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


