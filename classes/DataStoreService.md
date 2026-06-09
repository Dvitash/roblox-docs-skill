# DataStoreService

**Superclass:** [Instance](Instance.md)

This file defines `DataStoreService` classes that provide methods to access persistent data storage across game places, including `Class.DataStore` and `Class.OrderedDataStore`.

## Tags
- NotCreatable
- Service
- NotReplicated

## Methods
### `DataStoreService:GetDataStore(name: string, scope: string, options: [Instance](Instance.md)) -> [DataStore](DataStore.md)`
- **Summary:** Creates a `Class.DataStore` instance with the provided name and scope.

### `DataStoreService:GetGlobalDataStore() -> [DataStore](DataStore.md)`
- **Summary:** Returns the default data store.

### `DataStoreService:GetOrderedDataStore(name: string, scope: string) -> [OrderedDataStore](OrderedDataStore.md)`
- **Summary:** Get an `Class.OrderedDataStore` given a name and optional scope.

### `DataStoreService:GetRequestBudgetForRequestType(requestType: DataStoreRequestType) -> int`
- **Summary:** Returns the number of requests that can be made by the given request type.

### `DataStoreService:ListDataStoresAsync(prefix: string, pageSize: int, cursor: string) -> [DataStoreListingPages](DataStoreListingPages.md)`
- **Tags:** Yields
- **Summary:** Returns a `Class.DataStoreListingPages` object for enumerating through all of the experience's data stores.

### `DataStoreService:SetRateLimitForRequestType(requestType: DataStoreRequestType, baseLimit: int, perPlayerLimit: int) -> ()`
- **Summary:** Sets the rate limit for a given request type per minute.
