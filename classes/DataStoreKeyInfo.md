# DataStoreKeyInfo

**Superclass:** [Instance](Instance.md)

An object representing a specific version of a key, which is returned by various methods for tracking and managing data stores.

## Tags
- NotCreatable
- NotReplicated

## Properties
### `DataStoreKeyInfo.CreatedTime`
- **Type:** `int64`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The date and time the object was created.

### `DataStoreKeyInfo.UpdatedTime`
- **Type:** `int64`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The date and time the object was last updated.

### `DataStoreKeyInfo.Version`
- **Type:** `string`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Uniquely identifies the version of the object.

## Methods
### `DataStoreKeyInfo:GetMetadata() -> Dictionary`
- **Summary:** Returns the metadata associated with the object.

### `DataStoreKeyInfo:GetUserIds() -> Array`
- **Summary:** An array of `Class.Player.UserId|UserIds` tagged with a key.
