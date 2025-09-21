# PhishingDetectionEmailAdvancedResponse

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CleanResult** | **bool** | True if the result is not phishing (clean), and false otherwise | [optional] [default to null]
**PhishingRiskLevel** | **float64** | Overall phishing risk level between 0.0 and 1.0 | [optional] [default to null]
**SpamRiskLevel** | **float64** | Overall phishing spam level between 0.0 and 1.0 | [optional] [default to null]
**ContainsLowReputationSender** | **bool** | True if the input email is from a low reputation sender | [optional] [default to null]
**ContainsPhishing** | **bool** | True if the input email contains phishing threat risks, false otherwise | [optional] [default to null]
**ContainsSpam** | **bool** | True if the email contains phishing threat risks, false otherwise | [optional] [default to null]
**ContainsUnsolicitedSales** | **bool** | True if the input email contains unsolicited sales, false otherwise | [optional] [default to null]
**ContainsPromotionalContent** | **bool** | True if the input email contains promotional content, false otherwise | [optional] [default to null]
**ContainsPhishingAttempt** | **bool** | True if the input email contains a phishing attempt, false otherwise | [optional] [default to null]
**AnalysisRationale** | **string** | Rationale for why the conclusion was formed | [optional] [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


