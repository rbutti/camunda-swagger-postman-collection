# ProcessInstanceApi

All URIs are relative to *http://example.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**processInstanceVariablesByIdGet**](ProcessInstanceApi.md#processInstanceVariablesByIdGet) | **GET** /process-instance/{id}/variables | ProcessInstance3fde771b9aed11e792b20242ac110002VariablesGet


<a name="processInstanceVariablesByIdGet"></a>
# **processInstanceVariablesByIdGet**
> processInstanceVariablesByIdGet(accept, id)

ProcessInstance3fde771b9aed11e792b20242ac110002VariablesGet

TODO: Add Description

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.ProcessInstanceApi;


ProcessInstanceApi apiInstance = new ProcessInstanceApi();
String accept = "accept_example"; // String | 
String id = "id_example"; // String | 
try {
    apiInstance.processInstanceVariablesByIdGet(accept, id);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessInstanceApi#processInstanceVariablesByIdGet");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **String**|  |
 **id** | **String**|  |

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

