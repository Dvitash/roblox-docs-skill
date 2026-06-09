# InstanceFileSyncService

**Superclass:** [Instance](Instance.md)

InstanceFileSyncService is a class for interacting with file sync from a plugin, allowing instances to query status and retrieve related instances based on file paths.

## Tags
- NotCreatable
- Service
- NotReplicated

## Methods
### `InstanceFileSyncService:GetAllInstances() -> Instances`
- **Summary:** Returns an array of all instances currently involved in file synchronization.

### `InstanceFileSyncService:GetStatus(instance: [Instance](Instance.md)) -> InstanceFileSyncStatus`
- **Summary:** Returns the synchronization status of a specific instance.

### `InstanceFileSyncService:GetSyncedInstance(filePath: string) -> [Instance](Instance.md)?`
- **Summary:** Returns the instance corresponding to a given file path.

## Events
### `InstanceFileSyncService.StatusChanged(instance: [Instance](Instance.md), status: InstanceFileSyncStatus)`
- **Summary:** Fires when the synchronization status of an instance changes.
