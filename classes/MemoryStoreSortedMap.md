# MemoryStoreSortedMap

**Superclass:** [Instance](Instance.md)

MemoryStoreSortedMap is a class that provides access to a sorted map within `Class.MemoryStoreService`, allowing for efficient retrieval and modification of key-value pairs.

## Tags
- NotCreatable
- NotReplicated

## Methods
### `MemoryStoreSortedMap:GetAsync(key: string) -> Tuple`
- **Tags:** Yields
- **Summary:** Retrieves the value and sort key of a key in the sorted map.

### `MemoryStoreSortedMap:GetRangeAsync(direction: SortDirection, count: int, exclusiveLowerBound: Variant, exclusiveUpperBound: Variant) -> Array`
- **Tags:** Yields
- **Summary:** Retrieves items within a sorted range of keys and sort keys.

### `MemoryStoreSortedMap:GetSizeAsync() -> int`
- **Tags:** Yields
- **Summary:** Gets the size of the sorted map.

### `MemoryStoreSortedMap:RemoveAsync(key: string) -> ()`
- **Tags:** Yields
- **Summary:** Removes the provided key from the sorted map.

### `MemoryStoreSortedMap:SetAsync(key: string, value: Variant, expiration: int64, sortKey: Variant) -> boolean`
- **Tags:** Yields
- **Summary:** Sets the value of a key.

### `MemoryStoreSortedMap:UpdateAsync(key: string, transformFunction: Function, expiration: int64) -> Tuple`
- **Tags:** Yields
- **Summary:** Retrieves the value and sort key of a key from a sorted map and updates it with a new value and sort key.
