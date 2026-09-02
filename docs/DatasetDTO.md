# DatasetDTO


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **number** |  | [optional] [default to undefined]
**name** | **string** |  | [default to undefined]
**owningTeam** | **string** |  | [default to undefined]
**sourceSystem** | **string** |  | [default to undefined]
**tags** | **Array&lt;string&gt;** |  | [default to undefined]
**sensitivity** | [**DatasetSensitivity**](DatasetSensitivity.md) |  | [default to undefined]
**retentionDays** | **number** |  | [default to undefined]
**refreshIntervalHours** | **number** |  | [default to undefined]
**schemaFields** | [**Array&lt;FieldDTO&gt;**](FieldDTO.md) |  | [default to undefined]
**updatedAt** | **string** |  | [optional] [default to undefined]

## Example

```typescript
import { DatasetDTO } from '@javazone-2026/catalog-client';

const instance: DatasetDTO = {
    id,
    name,
    owningTeam,
    sourceSystem,
    tags,
    sensitivity,
    retentionDays,
    refreshIntervalHours,
    schemaFields,
    updatedAt,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
