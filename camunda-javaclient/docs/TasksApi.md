# TasksApi

All URIs are relative to *http://example.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**taskByIdGet**](TasksApi.md#taskByIdGet) | **GET** /task/{id} | Task8f9d8732968d11e7B2330242ac110002Get
[**taskByIdPut**](TasksApi.md#taskByIdPut) | **PUT** /task/{id} | Task8f9d8732968d11e7B2330242ac110002Put
[**taskCompleteByIdPost**](TasksApi.md#taskCompleteByIdPost) | **POST** /task/{id}/complete | TaskD7e3213e968611e7B2330242ac110002CompletePost
[**taskCreatePost**](TasksApi.md#taskCreatePost) | **POST** /task/create | TaskCreatePost
[**taskGet**](TasksApi.md#taskGet) | **GET** /task | TaskGet
[**taskPost**](TasksApi.md#taskPost) | **POST** /task | TaskPost
[**taskVariablesByIdGet**](TasksApi.md#taskVariablesByIdGet) | **GET** /task/{id}/variables | Task3fde9e439aed11e792b20242ac110002VariablesGet


<a name="taskByIdGet"></a>
# **taskByIdGet**
> taskByIdGet(accept, id)

Task8f9d8732968d11e7B2330242ac110002Get

TODO: Add Description

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.TasksApi;


TasksApi apiInstance = new TasksApi();
String accept = "accept_example"; // String | 
String id = "id_example"; // String | 
try {
    apiInstance.taskByIdGet(accept, id);
} catch (ApiException e) {
    System.err.println("Exception when calling TasksApi#taskByIdGet");
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

<a name="taskByIdPut"></a>
# **taskByIdPut**
> taskByIdPut(accept, id, contentType, body)

Task8f9d8732968d11e7B2330242ac110002Put

TODO: Add Description

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.TasksApi;


TasksApi apiInstance = new TasksApi();
String accept = "accept_example"; // String | 
String id = "id_example"; // String | 
String contentType = "contentType_example"; // String | 
Model1task17Bid7Drequest body = new Model1task17Bid7Drequest(); // Model1task17Bid7Drequest | 
try {
    apiInstance.taskByIdPut(accept, id, contentType, body);
} catch (ApiException e) {
    System.err.println("Exception when calling TasksApi#taskByIdPut");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **String**|  |
 **id** | **String**|  |
 **contentType** | **String**|  |
 **body** | [**Model1task17Bid7Drequest**](Model1task17Bid7Drequest.md)|  |

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="taskCompleteByIdPost"></a>
# **taskCompleteByIdPost**
> taskCompleteByIdPost(accept, contentType, body, id)

TaskD7e3213e968611e7B2330242ac110002CompletePost

TODO: Add Description

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.TasksApi;


TasksApi apiInstance = new TasksApi();
String accept = "accept_example"; // String | 
String contentType = "contentType_example"; // String | 
Object body = null; // Object | 
String id = "id_example"; // String | 
try {
    apiInstance.taskCompleteByIdPost(accept, contentType, body, id);
} catch (ApiException e) {
    System.err.println("Exception when calling TasksApi#taskCompleteByIdPost");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **String**|  |
 **contentType** | **String**|  |
 **body** | **Object**|  |
 **id** | **String**|  |

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="taskCreatePost"></a>
# **taskCreatePost**
> taskCreatePost(accept, contentType, body)

TaskCreatePost

TODO: Add Description

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.TasksApi;


TasksApi apiInstance = new TasksApi();
String accept = "accept_example"; // String | 
String contentType = "contentType_example"; // String | 
Model1task1createrequest body = new Model1task1createrequest(); // Model1task1createrequest | 
try {
    apiInstance.taskCreatePost(accept, contentType, body);
} catch (ApiException e) {
    System.err.println("Exception when calling TasksApi#taskCreatePost");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **String**|  |
 **contentType** | **String**|  |
 **body** | [**Model1task1createrequest**](Model1task1createrequest.md)|  |

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="taskGet"></a>
# **taskGet**
> taskGet(accept)

TaskGet

TODO: Add Description

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.TasksApi;


TasksApi apiInstance = new TasksApi();
String accept = "accept_example"; // String | 
try {
    apiInstance.taskGet(accept);
} catch (ApiException e) {
    System.err.println("Exception when calling TasksApi#taskGet");
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

<a name="taskPost"></a>
# **taskPost**
> taskPost(accept, contentType, body)

TaskPost

TODO: Add Description

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.TasksApi;


TasksApi apiInstance = new TasksApi();
String accept = "accept_example"; // String | 
String contentType = "contentType_example"; // String | 
Model1taskrequest body = new Model1taskrequest(); // Model1taskrequest | 
try {
    apiInstance.taskPost(accept, contentType, body);
} catch (ApiException e) {
    System.err.println("Exception when calling TasksApi#taskPost");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **String**|  |
 **contentType** | **String**|  |
 **body** | [**Model1taskrequest**](Model1taskrequest.md)|  |

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="taskVariablesByIdGet"></a>
# **taskVariablesByIdGet**
> taskVariablesByIdGet(deserializeValues, accept, id)

Task3fde9e439aed11e792b20242ac110002VariablesGet

TODO: Add Description

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.TasksApi;


TasksApi apiInstance = new TasksApi();
Boolean deserializeValues = true; // Boolean | 
String accept = "accept_example"; // String | 
String id = "id_example"; // String | 
try {
    apiInstance.taskVariablesByIdGet(deserializeValues, accept, id);
} catch (ApiException e) {
    System.err.println("Exception when calling TasksApi#taskVariablesByIdGet");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **deserializeValues** | **Boolean**|  |
 **accept** | **String**|  |
 **id** | **String**|  |

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

