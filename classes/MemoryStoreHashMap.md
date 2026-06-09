# MemoryStoreHashMap

**Superclass:** [Instance](Instance.md)

MemoryStoreHashMap is a class in `Class.MemoryStoreService` that provides access to a hash map, allowing users to retrieve values or enumerate items.

## Tags
- NotCreatable
- NotReplicated

## Methods
### `MemoryStoreHashMap:GetAsync(key: string) -> Variant`
- **Tags:** Yields
- **Summary:** Retrieves the value of a key in the hash map.

### `MemoryStoreHashMap:ListItemsAsync(count: int) -> [MemoryStoreHashMapPages](MemoryStoreHashMapPages.md)`
- **Tags:** Yields
- **Summary:** Returns a `Class.MemoryStoreHashMapPages` object for enumerating through items in the hash map.

### `MemoryStoreHashMap:RemoveAsync(key: string) -> ()`
- **Tags:** Yields
- **Summary:** Removes an item from the hash map.

### `MemoryStoreHashMap:SetAsync(key: string, value: Variant, expiration: int64) -> boolean`
- **Tags:** Yields
- **Summary:** Sets the value of a key in the hash map.

### `MemoryStoreHashMap:UpdateAsync(key: string, transformFunction: Function, expiration: int64) -> Variant`
- **Tags:** Yields
- **Summary:** Retrieves the value of a key from a hash map and lets you update it to a new value.
