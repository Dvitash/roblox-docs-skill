# DataStoreInfo

**Superclass:** [Instance](Instance.md)

DataStoreInfo is a class used to store data store information, including the name and last update time. It is part of the `Class.DataStoreListingPages` object returned by `Class.DataStoreService:ListDataStoresAsync()`.

## Tags
- NotCreatable
- NotReplicated

## Properties
### `DataStoreInfo.CreatedTime`
- **Type:** `int64`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Indicates when the data store was created in milliseconds since epoch.

### `DataStoreInfo.DataStoreName`
- **Type:** `string`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The name of the data store.

### `DataStoreInfo.UpdatedTime`
- **Type:** `int64`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Indicates the last time the data store was updated in milliseconds since epoch.
