# PhishingDetectionAdvancedRequest

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**InputString** | **string** | Input text string to detect phishing against | [optional] [default to null]
**Model** | **string** | Optional: Specify which AI model to use.  Possible choices are Normal and Advanced.  Default is Advanced. | [optional] [default to null]
**CustomPolicyID** | **string** | Apply a Custom Policy for Phishing Enforcement by providing the ID; to create a Custom Policy,  navigate to the Cloudmersive Management Portal and select Custom Policies.  Requires Managed Instance or Private Cloud | [optional] [default to null]
**ProvideAnalysisRationale** | **bool** | Optional: Set to true to include an analysis rationale in the response explaining why the content was or was not flagged.  Default is true. | [optional] [default to null]
**TextType** | **string** | Optional: Type of text being analyzed. Must be one of: \&quot;Text Message\&quot;, \&quot;User Message\&quot;, \&quot;Sales Lead\&quot;, \&quot;Email Message\&quot;, \&quot;Support Case\&quot;, \&quot;Other\&quot;. | [optional] [default to null]
**FromName** | **string** | Optional: Name of the sender | [optional] [default to null]
**ToName** | **string** | Optional: Name of the recipient | [optional] [default to null]
**FromPhoneNumber** | **string** | Optional: Phone number of the sender | [optional] [default to null]
**ToPhoneNumber** | **string** | Optional: Phone number of the recipient | [optional] [default to null]
**FromEmailAddress** | **string** | Optional: Email address of the sender | [optional] [default to null]
**ToEmailAddress** | **string** | Optional: Email address of the recipient | [optional] [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


