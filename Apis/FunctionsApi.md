# FunctionsApi

All URIs are relative to *https://localhost:3000/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**getFunction**](FunctionsApi.md#getFunction) | **GET** /functions/${functionName} | Get a function
[**getFunctions**](FunctionsApi.md#getFunctions) | **GET** /functions | Get the available functions


<a name="getFunction"></a>
# **getFunction**
> Object getFunction(functionName)

Get a function

    Get a function

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **functionName** | **String**| Unique function name | [default to null]

### Return type

[**Object**](../\Models/object.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getFunctions"></a>
# **getFunctions**
> List getFunctions()

Get the available functions

    Get the available functions

### Parameters
This endpoint does not need any parameter.

### Return type

[**List**](../\Models/Function.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

