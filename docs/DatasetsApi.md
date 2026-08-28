# DatasetsApi

All URIs are relative to *http://localhost*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**createDataset**](#createdataset) | **POST** /datasets | |
|[**deleteDataset**](#deletedataset) | **DELETE** /datasets/{id} | |
|[**getDataset**](#getdataset) | **GET** /datasets/{id} | |
|[**listDatasets**](#listdatasets) | **GET** /datasets | |
|[**updateDataset**](#updatedataset) | **PUT** /datasets/{id} | |

# **createDataset**
> DatasetDTO createDataset(datasetDTO)


### Example

```typescript
import {
    DatasetsApi,
    Configuration,
    DatasetDTO
} from '@javazone-2026/catalog-client';

const configuration = new Configuration();
const apiInstance = new DatasetsApi(configuration);

let datasetDTO: DatasetDTO; //

const { status, data } = await apiInstance.createDataset(
    datasetDTO
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **datasetDTO** | **DatasetDTO**|  | |


### Return type

**DatasetDTO**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**201** | createDataset 201 response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteDataset**
> deleteDataset()


### Example

```typescript
import {
    DatasetsApi,
    Configuration
} from '@javazone-2026/catalog-client';

const configuration = new Configuration();
const apiInstance = new DatasetsApi(configuration);

let id: number; // (default to undefined)

const { status, data } = await apiInstance.deleteDataset(
    id
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **id** | [**number**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | deleteDataset 204 response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getDataset**
> DatasetDTO getDataset()


### Example

```typescript
import {
    DatasetsApi,
    Configuration
} from '@javazone-2026/catalog-client';

const configuration = new Configuration();
const apiInstance = new DatasetsApi(configuration);

let id: number; // (default to undefined)

const { status, data } = await apiInstance.getDataset(
    id
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **id** | [**number**] |  | defaults to undefined|


### Return type

**DatasetDTO**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | getDataset 200 response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listDatasets**
> Array<DatasetDTO> listDatasets()


### Example

```typescript
import {
    DatasetsApi,
    Configuration
} from '@javazone-2026/catalog-client';

const configuration = new Configuration();
const apiInstance = new DatasetsApi(configuration);

const { status, data } = await apiInstance.listDatasets();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**Array<DatasetDTO>**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | listDatasets 200 response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateDataset**
> DatasetDTO updateDataset(datasetDTO)


### Example

```typescript
import {
    DatasetsApi,
    Configuration,
    DatasetDTO
} from '@javazone-2026/catalog-client';

const configuration = new Configuration();
const apiInstance = new DatasetsApi(configuration);

let id: number; // (default to undefined)
let datasetDTO: DatasetDTO; //

const { status, data } = await apiInstance.updateDataset(
    id,
    datasetDTO
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **datasetDTO** | **DatasetDTO**|  | |
| **id** | [**number**] |  | defaults to undefined|


### Return type

**DatasetDTO**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | updateDataset 200 response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

