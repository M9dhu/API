# AdminLoggingApi

All URIs are relative to *https://localhost:3000/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**getLogging**](AdminLoggingApi.md#getLogging) | **GET** /admin/logging | get logging
[**updateLogging**](AdminLoggingApi.md#updateLogging) | **PUT** /admin/logging | Update logging


<a name="getLogging"></a>
# **getLogging**
> Object getLogging()

get logging

    get logging

### Parameters
This endpoint does not need any parameter.

### Return type

[**Object**](../\Models/object.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

<a name="updateLogging"></a>
# **updateLogging**
> updateLogging(updateLoggingRequest)

Update logging

    Update logging

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **updateLoggingRequest** | **Object**| Logging criteria |

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

