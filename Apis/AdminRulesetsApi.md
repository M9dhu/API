# AdminRulesetsApi

All URIs are relative to *https://localhost:3000/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**addRulesets**](AdminRulesetsApi.md#addRulesets) | **POST** /admin/rulesets | Add a rulesets
[**deleteRuleset**](AdminRulesetsApi.md#deleteRuleset) | **DELETE** /admin/rulesets/${rulesetName} | Delete a ruleset
[**updateRuleset**](AdminRulesetsApi.md#updateRuleset) | **PUT** /admin/rulesets/${rulesetName} | Update a ruleset


<a name="addRulesets"></a>
# **addRulesets**
> addRulesets(addRulesetsRequest)

Add a rulesets

    Add a rulesets

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **addRulesetsRequest** | [**List**](../\Models/RulesetDefinition.md)| Ruleset definitions to add |

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="deleteRuleset"></a>
# **deleteRuleset**
> deleteRuleset(rulesetName)

Delete a ruleset

    Delete a ruleset

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **rulesetName** | **String**| Unique ruleset name | [default to null]

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="updateRuleset"></a>
# **updateRuleset**
> updateRuleset(rulesetName, updateRulesetRequest)

Update a ruleset

    Update a ruleset

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **rulesetName** | **String**| Unique ruleset name | [default to null]
 **updateRulesetRequest** | **Object**| Ruleset definitions to add |

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

