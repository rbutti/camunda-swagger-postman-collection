# GroupsApi

All URIs are relative to *http://example.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**groupByIdGet**](GroupsApi.md#groupByIdGet) | **GET** /group/{id} | Group8454c987Cbc54a24Ba1aD420283caabdGet
[**groupCreatePost**](GroupsApi.md#groupCreatePost) | **POST** /group/create | GroupCreatePost
[**groupGet**](GroupsApi.md#groupGet) | **GET** /group | GroupGet


<a name="groupByIdGet"></a>
# **groupByIdGet**
> groupByIdGet(id)

Group8454c987Cbc54a24Ba1aD420283caabdGet

TODO: Add Description

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.GroupsApi;


GroupsApi apiInstance = new GroupsApi();
String id = "id_example"; // String | 
try {
    apiInstance.groupByIdGet(id);
} catch (ApiException e) {
    System.err.println("Exception when calling GroupsApi#groupByIdGet");
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

<a name="groupCreatePost"></a>
# **groupCreatePost**
> groupCreatePost(accept, contentType, body)

GroupCreatePost

TODO: Add Description

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.GroupsApi;


GroupsApi apiInstance = new GroupsApi();
String accept = "accept_example"; // String | 
String contentType = "contentType_example"; // String | 
Model1group1createrequest body = new Model1group1createrequest(); // Model1group1createrequest | 
try {
    apiInstance.groupCreatePost(accept, contentType, body);
} catch (ApiException e) {
    System.err.println("Exception when calling GroupsApi#groupCreatePost");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **String**|  |
 **contentType** | **String**|  |
 **body** | [**Model1group1createrequest**](Model1group1createrequest.md)|  |

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="groupGet"></a>
# **groupGet**
> groupGet()

GroupGet

TODO: Add Description

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.GroupsApi;


GroupsApi apiInstance = new GroupsApi();
try {
    apiInstance.groupGet();
} catch (ApiException e) {
    System.err.println("Exception when calling GroupsApi#groupGet");
    e.printStackTrace();
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

