# AdvancedEmailDetectionRequest

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FromEmailAddress** | **string** | Email address of the sender | [optional] [default to null]
**ToEmailAddress** | **string** | Email address of the recipient | [optional] [default to null]
**Subject** | **string** | Subject of the email | [optional] [default to null]
**HtmlBody** | **string** | Body of the email in HTML, or text | [optional] [default to null]
**AllowLowReputationSenders** | **bool** | Allow email from low reputation senders and domains | [optional] [default to null]
**AllowSanctioned** | **bool** | True to allow sanctioned countries and certain known sanctioned entities, false otherwise (default) | [optional] [default to null]
**InputEmailFile** | **string** |  | [optional] [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


