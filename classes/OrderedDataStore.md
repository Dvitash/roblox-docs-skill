# OrderedDataStore

**Superclass:** [GlobalDataStore](GlobalDataStore.md)

OrderedDataStore is a class that allows for ordered data store entries, which are integers. It provides methods to sort and access data in sorted order, though it lacks versioning or metadata support.

## Tags
- NotCreatable
- NotReplicated

## Methods
### `OrderedDataStore:GetSortedAsync(ascending: boolean, pagesize: int, minValue: Variant, maxValue: Variant) -> [DataStorePages](DataStorePages.md)`
- **Tags:** Yields
- **Summary:** Returns a `Class.DataStorePages` object.
