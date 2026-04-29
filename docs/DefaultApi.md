# citysim_slurm.DefaultApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**cancel_cancel_job_id_get**](DefaultApi.md#cancel_cancel_job_id_get) | **GET** /cancel/{job_id} | Cancel
[**create_create_name_get**](DefaultApi.md#create_create_name_get) | **GET** /create/{name} | Create
[**delete_delete_name_get**](DefaultApi.md#delete_delete_name_get) | **GET** /delete/{name} | Delete
[**run_run_name_get**](DefaultApi.md#run_run_name_get) | **GET** /run/{name} | Run
[**status_status_job_id_get**](DefaultApi.md#status_status_job_id_get) | **GET** /status/{job_id} | Status
[**version_health_get**](DefaultApi.md#version_health_get) | **GET** /health | Version


# **cancel_cancel_job_id_get**
> CitySimSlurmMessage cancel_cancel_job_id_get(job_id)

Cancel

### Example


```python
import citysim_slurm
from citysim_slurm.models.city_sim_slurm_message import CitySimSlurmMessage
from citysim_slurm.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost
# See configuration.py for a list of all supported configuration parameters.
configuration = citysim_slurm.Configuration(
    host = "http://localhost"
)


# Enter a context with an instance of the API client
async with citysim_slurm.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = citysim_slurm.DefaultApi(api_client)
    job_id = 56 # int | 

    try:
        # Cancel
        api_response = await api_instance.cancel_cancel_job_id_get(job_id)
        print("The response of DefaultApi->cancel_cancel_job_id_get:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->cancel_cancel_job_id_get: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **job_id** | **int**|  | 

### Return type

[**CitySimSlurmMessage**](CitySimSlurmMessage.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **create_create_name_get**
> CitySimSlurmMessage create_create_name_get(name)

Create

### Example


```python
import citysim_slurm
from citysim_slurm.models.city_sim_slurm_message import CitySimSlurmMessage
from citysim_slurm.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost
# See configuration.py for a list of all supported configuration parameters.
configuration = citysim_slurm.Configuration(
    host = "http://localhost"
)


# Enter a context with an instance of the API client
async with citysim_slurm.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = citysim_slurm.DefaultApi(api_client)
    name = 'name_example' # str | 

    try:
        # Create
        api_response = await api_instance.create_create_name_get(name)
        print("The response of DefaultApi->create_create_name_get:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->create_create_name_get: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **str**|  | 

### Return type

[**CitySimSlurmMessage**](CitySimSlurmMessage.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **delete_delete_name_get**
> CitySimSlurmMessage delete_delete_name_get(name)

Delete

### Example


```python
import citysim_slurm
from citysim_slurm.models.city_sim_slurm_message import CitySimSlurmMessage
from citysim_slurm.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost
# See configuration.py for a list of all supported configuration parameters.
configuration = citysim_slurm.Configuration(
    host = "http://localhost"
)


# Enter a context with an instance of the API client
async with citysim_slurm.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = citysim_slurm.DefaultApi(api_client)
    name = 'name_example' # str | 

    try:
        # Delete
        api_response = await api_instance.delete_delete_name_get(name)
        print("The response of DefaultApi->delete_delete_name_get:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->delete_delete_name_get: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **str**|  | 

### Return type

[**CitySimSlurmMessage**](CitySimSlurmMessage.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **run_run_name_get**
> CitySimSlurmMessage run_run_name_get(name)

Run

### Example


```python
import citysim_slurm
from citysim_slurm.models.city_sim_slurm_message import CitySimSlurmMessage
from citysim_slurm.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost
# See configuration.py for a list of all supported configuration parameters.
configuration = citysim_slurm.Configuration(
    host = "http://localhost"
)


# Enter a context with an instance of the API client
async with citysim_slurm.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = citysim_slurm.DefaultApi(api_client)
    name = 'name_example' # str | 

    try:
        # Run
        api_response = await api_instance.run_run_name_get(name)
        print("The response of DefaultApi->run_run_name_get:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->run_run_name_get: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **str**|  | 

### Return type

[**CitySimSlurmMessage**](CitySimSlurmMessage.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **status_status_job_id_get**
> CitySimSlurmMessage status_status_job_id_get(job_id)

Status

### Example


```python
import citysim_slurm
from citysim_slurm.models.city_sim_slurm_message import CitySimSlurmMessage
from citysim_slurm.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost
# See configuration.py for a list of all supported configuration parameters.
configuration = citysim_slurm.Configuration(
    host = "http://localhost"
)


# Enter a context with an instance of the API client
async with citysim_slurm.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = citysim_slurm.DefaultApi(api_client)
    job_id = 56 # int | 

    try:
        # Status
        api_response = await api_instance.status_status_job_id_get(job_id)
        print("The response of DefaultApi->status_status_job_id_get:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->status_status_job_id_get: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **job_id** | **int**|  | 

### Return type

[**CitySimSlurmMessage**](CitySimSlurmMessage.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **version_health_get**
> str version_health_get()

Version

### Example


```python
import citysim_slurm
from citysim_slurm.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost
# See configuration.py for a list of all supported configuration parameters.
configuration = citysim_slurm.Configuration(
    host = "http://localhost"
)


# Enter a context with an instance of the API client
async with citysim_slurm.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = citysim_slurm.DefaultApi(api_client)

    try:
        # Version
        api_response = await api_instance.version_health_get()
        print("The response of DefaultApi->version_health_get:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->version_health_get: %s\n" % e)
```



### Parameters

This endpoint does not need any parameter.

### Return type

**str**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

