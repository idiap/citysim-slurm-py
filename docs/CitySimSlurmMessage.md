# CitySimSlurmMessage


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | [**CitySimSlurmStatus**](CitySimSlurmStatus.md) |  | 
**job_id** | **int** |  | [optional] 
**message** | **str** |  | [optional] 

## Example

```python
from citysim_slurm.models.city_sim_slurm_message import CitySimSlurmMessage

# TODO update the JSON string below
json = "{}"
# create an instance of CitySimSlurmMessage from a JSON string
city_sim_slurm_message_instance = CitySimSlurmMessage.from_json(json)
# print the JSON string representation of the object
print(CitySimSlurmMessage.to_json())

# convert the object into a dict
city_sim_slurm_message_dict = city_sim_slurm_message_instance.to_dict()
# create an instance of CitySimSlurmMessage from a dict
city_sim_slurm_message_from_dict = CitySimSlurmMessage.from_dict(city_sim_slurm_message_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


