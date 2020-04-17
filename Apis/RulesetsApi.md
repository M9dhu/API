# RulesetsApi

All URIs are relative to *https://localhost:3000/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**getRuleset**](RulesetsApi.md#getRuleset) | **GET** /rulesets/${rulesetName} | Get a ruleset
[**getRulesets**](RulesetsApi.md#getRulesets) | **GET** /rulesets | Get the available rulesets


<a name="getRuleset"></a>
# **getRuleset**
> Object getRuleset(rulesetName)

Get a ruleset

    Get a ruleset

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **rulesetName** | **String**| Unique ruleset name | [default to null]

### Return type

[**Object**](../\Models/object.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getRulesets"></a>
# **getRulesets**
> List getRulesets()

Get the available rulesets

    Get the available runsets

### Parameters
This endpoint does not need any parameter.

### Return type

[**List**](../\Models/Ruleset.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

