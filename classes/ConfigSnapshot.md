# ConfigSnapshot

**Superclass:** [Object](Object.md)

This file defines `ConfigSnapshot` as a class for capturing configuration values at a specific version, allowing for targeted experimentation and error handling.

## Tags
- NotCreatable
- NotReplicated

## Properties
### `ConfigSnapshot.Error`
- **Type:** `ConfigSnapshotErrorState`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Populated if snapshot was in an error state.

### `ConfigSnapshot.Outdated`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** If true, indicates the snapshot is outdated and can be refreshed to newer values.

## Methods
### `ConfigSnapshot:GetValue(key: string) -> Variant`
- **Summary:** Returns the value for the given key.

### `ConfigSnapshot:GetValueChangedSignal(key: string) -> RBXScriptSignal`
- **Summary:** Returns a signal that fires when the value for the given key changes due to a refresh.

### `ConfigSnapshot:Refresh() -> ()`
- **Summary:** Refreshes the snapshot to the latest configuration values.

## Events
### `ConfigSnapshot.UpdateAvailable()`
- **Summary:** Fires when a newer version of the configuration is available.
