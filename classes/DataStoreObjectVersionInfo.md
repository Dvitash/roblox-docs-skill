# DataStoreObjectVersionInfo

**Superclass:** [Instance](Instance.md)

An instance of `DataStoreObjectVersionInfo` is used to uniquely identify a particular version of a key, including the creation time and deletion status.

## Tags
- NotCreatable
- NotReplicated

## Properties
### `DataStoreObjectVersionInfo.CreatedTime`
- **Type:** `int64`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Indicates when the version was created in milliseconds since epoch.

### `DataStoreObjectVersionInfo.IsDeleted`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Whether the version has been marked as deleted.

### `DataStoreObjectVersionInfo.Version`
- **Type:** `string`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Uniquely identifies a particular version of the key.
