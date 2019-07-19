# ProcessDefinitionApi

All URIs are relative to *http://example.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**processDefinitionByIdDelete**](ProcessDefinitionApi.md#processDefinitionByIdDelete) | **DELETE** /process-definition/{id} | ProcessDefinitionPayTaxes1608cd76b9e4e11e7B8b70242ac110002Delete
[**processDefinitionByIdGet**](ProcessDefinitionApi.md#processDefinitionByIdGet) | **GET** /process-definition/{id} | ProcessDefinitionPayTaxes50520118099b411e792b20242ac110002StatisticsGet
[**processDefinitionDiagramByIdGet**](ProcessDefinitionApi.md#processDefinitionDiagramByIdGet) | **GET** /process-definition/{id}/diagram | ProcessDefinitionPayTaxes50520118099b411e792b20242ac110002DiagramGet
[**processDefinitionGet**](ProcessDefinitionApi.md#processDefinitionGet) | **GET** /process-definition | ProcessDefinitionGet
[**processDefinitionKeyStartByKeyPost**](ProcessDefinitionApi.md#processDefinitionKeyStartByKeyPost) | **POST** /process-definition/key/{key}/start | ProcessDefinitionKeyPayTaxesStartPost
[**processDefinitionKeyStartFormByKeyGet**](ProcessDefinitionApi.md#processDefinitionKeyStartFormByKeyGet) | **GET** /process-definition/key/{key}/startForm | ProcessDefinitionKeyPayTaxesStartFormGet
[**processDefinitionKeyXmlByKeyGet**](ProcessDefinitionApi.md#processDefinitionKeyXmlByKeyGet) | **GET** /process-definition/key/{key}/xml | ProcessDefinitionKeyPayTaxesXmlGet
[**processDefinitionStartFormByIdGet**](ProcessDefinitionApi.md#processDefinitionStartFormByIdGet) | **GET** /process-definition/{id}/startForm | ProcessDefinitionPayTaxes50520118099b411e792b20242ac110002StartFormGet
[**processDefinitionStatisticsByIdGet**](ProcessDefinitionApi.md#processDefinitionStatisticsByIdGet) | **GET** /process-definition/{id}/statistics | ProcessDefinitionPayTaxes50520118099b411e792b20242ac110002StatisticsGet


<a name="processDefinitionByIdDelete"></a>
# **processDefinitionByIdDelete**
> processDefinitionByIdDelete(accept, id)

ProcessDefinitionPayTaxes1608cd76b9e4e11e7B8b70242ac110002Delete

TODO: Add Description

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.ProcessDefinitionApi;


ProcessDefinitionApi apiInstance = new ProcessDefinitionApi();
String accept = "accept_example"; // String | 
String id = "id_example"; // String | 
try {
    apiInstance.processDefinitionByIdDelete(accept, id);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessDefinitionApi#processDefinitionByIdDelete");
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

<a name="processDefinitionByIdGet"></a>
# **processDefinitionByIdGet**
> processDefinitionByIdGet(accept, id)

ProcessDefinitionPayTaxes50520118099b411e792b20242ac110002StatisticsGet

TODO: Add Description

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.ProcessDefinitionApi;


ProcessDefinitionApi apiInstance = new ProcessDefinitionApi();
String accept = "accept_example"; // String | 
String id = "id_example"; // String | 
try {
    apiInstance.processDefinitionByIdGet(accept, id);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessDefinitionApi#processDefinitionByIdGet");
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

<a name="processDefinitionDiagramByIdGet"></a>
# **processDefinitionDiagramByIdGet**
> processDefinitionDiagramByIdGet(id)

ProcessDefinitionPayTaxes50520118099b411e792b20242ac110002DiagramGet

TODO: Add Description

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.ProcessDefinitionApi;


ProcessDefinitionApi apiInstance = new ProcessDefinitionApi();
String id = "id_example"; // String | 
try {
    apiInstance.processDefinitionDiagramByIdGet(id);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessDefinitionApi#processDefinitionDiagramByIdGet");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  |

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="processDefinitionGet"></a>
# **processDefinitionGet**
> processDefinitionGet(accept)

ProcessDefinitionGet

TODO: Add Description

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.ProcessDefinitionApi;


ProcessDefinitionApi apiInstance = new ProcessDefinitionApi();
String accept = "accept_example"; // String | 
try {
    apiInstance.processDefinitionGet(accept);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessDefinitionApi#processDefinitionGet");
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

<a name="processDefinitionKeyStartByKeyPost"></a>
# **processDefinitionKeyStartByKeyPost**
> processDefinitionKeyStartByKeyPost(accept, contentType, key, body)

ProcessDefinitionKeyPayTaxesStartPost

TODO: Add Description

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.ProcessDefinitionApi;


ProcessDefinitionApi apiInstance = new ProcessDefinitionApi();
String accept = "accept_example"; // String | 
String contentType = "contentType_example"; // String | 
String key = "key_example"; // String | 
Model1processDefinition1key17Bkey7D1startRequest body = new Model1processDefinition1key17Bkey7D1startRequest(); // Model1processDefinition1key17Bkey7D1startRequest | 
try {
    apiInstance.processDefinitionKeyStartByKeyPost(accept, contentType, key, body);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessDefinitionApi#processDefinitionKeyStartByKeyPost");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **String**|  |
 **contentType** | **String**|  |
 **key** | **String**|  |
 **body** | [**Model1processDefinition1key17Bkey7D1startRequest**](Model1processDefinition1key17Bkey7D1startRequest.md)|  |

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="processDefinitionKeyStartFormByKeyGet"></a>
# **processDefinitionKeyStartFormByKeyGet**
> processDefinitionKeyStartFormByKeyGet(key)

ProcessDefinitionKeyPayTaxesStartFormGet

TODO: Add Description

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.ProcessDefinitionApi;


ProcessDefinitionApi apiInstance = new ProcessDefinitionApi();
String key = "key_example"; // String | 
try {
    apiInstance.processDefinitionKeyStartFormByKeyGet(key);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessDefinitionApi#processDefinitionKeyStartFormByKeyGet");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **key** | **String**|  |

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="processDefinitionKeyXmlByKeyGet"></a>
# **processDefinitionKeyXmlByKeyGet**
> processDefinitionKeyXmlByKeyGet(key)

ProcessDefinitionKeyPayTaxesXmlGet

TODO: Add Description

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.ProcessDefinitionApi;


ProcessDefinitionApi apiInstance = new ProcessDefinitionApi();
String key = "key_example"; // String | 
try {
    apiInstance.processDefinitionKeyXmlByKeyGet(key);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessDefinitionApi#processDefinitionKeyXmlByKeyGet");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **key** | **String**|  |

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="processDefinitionStartFormByIdGet"></a>
# **processDefinitionStartFormByIdGet**
> processDefinitionStartFormByIdGet(accept, id)

ProcessDefinitionPayTaxes50520118099b411e792b20242ac110002StartFormGet

TODO: Add Description

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.ProcessDefinitionApi;


ProcessDefinitionApi apiInstance = new ProcessDefinitionApi();
String accept = "accept_example"; // String | 
String id = "id_example"; // String | 
try {
    apiInstance.processDefinitionStartFormByIdGet(accept, id);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessDefinitionApi#processDefinitionStartFormByIdGet");
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

<a name="processDefinitionStatisticsByIdGet"></a>
# **processDefinitionStatisticsByIdGet**
> processDefinitionStatisticsByIdGet(accept, id)

ProcessDefinitionPayTaxes50520118099b411e792b20242ac110002StatisticsGet

TODO: Add Description

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.ProcessDefinitionApi;


ProcessDefinitionApi apiInstance = new ProcessDefinitionApi();
String accept = "accept_example"; // String | 
String id = "id_example"; // String | 
try {
    apiInstance.processDefinitionStatisticsByIdGet(accept, id);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessDefinitionApi#processDefinitionStatisticsByIdGet");
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

