# DataStore

**Superclass:** [GlobalDataStore](GlobalDataStore.md)

The `DataStore` class provides methods for retrieving version information, listing keys, and enumerating versions across a data store.

## Tags
- NotCreatable
- NotReplicated

## Methods
### `DataStore:GetVersionAsync(key: string, version: string) -> Tuple`
- **Tags:** Yields
- **Summary:** Retrieves the specified key version.

### `DataStore:GetVersionAtTimeAsync(key: string, timestamp: int64) -> Tuple`
- **Tags:** Yields
- **Summary:** Retrieves the key version that was current at a given time.

### `DataStore:ListKeysAsync(prefix: string, pageSize: int, cursor: string, excludeDeleted: boolean) -> [DataStoreKeyPages](DataStoreKeyPages.md)`
- **Tags:** Yields
- **Summary:** Returns a `Class.DataStoreKeyPages` object for enumerating through keys of a data store.

### `DataStore:ListVersionsAsync(key: string, sortDirection: SortDirection, minDate: int64, maxDate: int64, pageSize: int) -> [DataStoreVersionPages](DataStoreVersionPages.md)`
- **Tags:** Yields
- **Summary:** Enumerates all versions of a key.

### `DataStore:RemoveVersionAsync(key: string, version: string) -> ()`
- **Tags:** Yields, Deprecated
- **Summary:** Permanently deletes the specified version of a key.
