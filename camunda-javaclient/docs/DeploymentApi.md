# DeploymentApi

All URIs are relative to *http://example.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deploymentByIdGet**](DeploymentApi.md#deploymentByIdGet) | **GET** /deployment/{id} | Deployment051e15ae99b411e792b20242ac110002Get
[**deploymentCreatePost**](DeploymentApi.md#deploymentCreatePost) | **POST** /deployment/create | DeploymentCreatePost
[**deploymentGet**](DeploymentApi.md#deploymentGet) | **GET** /deployment | DeploymentGet
[**processInstanceByIdGet**](DeploymentApi.md#processInstanceByIdGet) | **GET** /process-instance/{id} | ProcessInstance3fde771b9aed11e792b20242ac110002Get
[**processInstanceGet**](DeploymentApi.md#processInstanceGet) | **GET** /process-instance | ProcessInstanceGet


<a name="deploymentByIdGet"></a>
# **deploymentByIdGet**
> deploymentByIdGet(accept, id)

Deployment051e15ae99b411e792b20242ac110002Get

TODO: Add Description

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.DeploymentApi;


DeploymentApi apiInstance = new DeploymentApi();
String accept = "accept_example"; // String | 
String id = "id_example"; // String | 
try {
    apiInstance.deploymentByIdGet(accept, id);
} catch (ApiException e) {
    System.err.println("Exception when calling DeploymentApi#deploymentByIdGet");
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

<a name="deploymentCreatePost"></a>
# **deploymentCreatePost**
> deploymentCreatePost(accept, deploymentName, enableDuplicateFiltering, deployChangedOnly, payTaxesBpmn, smsBodyJs)

DeploymentCreatePost

Create a Camunda Deployment.  Update the Deployment Name and Key/Value of the .bpmn file in the Body.

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.DeploymentApi;


DeploymentApi apiInstance = new DeploymentApi();
String accept = "accept_example"; // String | 
String deploymentName = "deploymentName_example"; // String | 
Boolean enableDuplicateFiltering = true; // Boolean | 
Boolean deployChangedOnly = true; // Boolean | 
String payTaxesBpmn = "payTaxesBpmn_example"; // String | 
String smsBodyJs = "smsBodyJs_example"; // String | 
try {
    apiInstance.deploymentCreatePost(accept, deploymentName, enableDuplicateFiltering, deployChangedOnly, payTaxesBpmn, smsBodyJs);
} catch (ApiException e) {
    System.err.println("Exception when calling DeploymentApi#deploymentCreatePost");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **String**|  |
 **deploymentName** | **String**|  |
 **enableDuplicateFiltering** | **Boolean**|  |
 **deployChangedOnly** | **Boolean**|  |
 **payTaxesBpmn** | **String**|  |
 **smsBodyJs** | **String**|  |

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/x-www-form-urlencoded
 - **Accept**: application/json

<a name="deploymentGet"></a>
# **deploymentGet**
> deploymentGet(accept)

DeploymentGet

TODO: Add Description

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.DeploymentApi;


DeploymentApi apiInstance = new DeploymentApi();
String accept = "accept_example"; // String | 
try {
    apiInstance.deploymentGet(accept);
} catch (ApiException e) {
    System.err.println("Exception when calling DeploymentApi#deploymentGet");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **String**|  |

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="processInstanceByIdGet"></a>
# **processInstanceByIdGet**
> processInstanceByIdGet(accept, id)

ProcessInstance3fde771b9aed11e792b20242ac110002Get

TODO: Add Description

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.DeploymentApi;


DeploymentApi apiInstance = new DeploymentApi();
String accept = "accept_example"; // String | 
String id = "id_example"; // String | 
try {
    apiInstance.processInstanceByIdGet(accept, id);
} catch (ApiException e) {
    System.err.println("Exception when calling DeploymentApi#processInstanceByIdGet");
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

<a name="processInstanceGet"></a>
# **processInstanceGet**
> processInstanceGet(accept)

ProcessInstanceGet

TODO: Add Description

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.DeploymentApi;


DeploymentApi apiInstance = new DeploymentApi();
String accept = "accept_example"; // String | 
try {
    apiInstance.processInstanceGet(accept);
} catch (ApiException e) {
    System.err.println("Exception when calling DeploymentApi#processInstanceGet");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **String**|  |

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

