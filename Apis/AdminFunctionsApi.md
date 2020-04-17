# AdminFunctionsApi

All URIs are relative to *https://localhost:3000/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**addFunctions**](AdminFunctionsApi.md#addFunctions) | **POST** /admin/functions | Add functions
[**deleteFunction**](AdminFunctionsApi.md#deleteFunction) | **DELETE** /admin/functions/${functionName} | Delete a function
[**updateFunction**](AdminFunctionsApi.md#updateFunction) | **PUT** /admin/functions/${functionName} | Update a function


<a name="addFunctions"></a>
# **addFunctions**
> addFunctions(addFunctionsRequest)

Add functions

    Add functions

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **addFunctionsRequest** | [**List**](../\Models/FunctionDefinition.md)| Function definitions to add |

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="deleteFunction"></a>
# **deleteFunction**
> deleteFunction(functionName)

Delete a function

    Delete a function

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **functionName** | **String**| Unique function name | [default to null]

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="updateFunction"></a>
# **updateFunction**
> updateFunction(functionName, updateFunctionRequest)

Update a function

    Update a function

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **functionName** | **String**| Unique function name | [default to null]
 **updateFunctionRequest** | **Object**| Function definitions to add |

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

