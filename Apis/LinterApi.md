# LinterApi

All URIs are relative to *https://localhost:3000/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**runLint**](LinterApi.md#runLint) | **POST** /linter | Lint the specification


<a name="runLint"></a>
# **runLint**
> List runLint(lintRequest)

Lint the specification

    Runs the linter for the provided specification and returns the results

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **lintRequest** | [**LintRequest**](../\Models/LintRequest.md)| Request data to be linted |

### Return type

[**List**](../\Models/LintResponse.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

