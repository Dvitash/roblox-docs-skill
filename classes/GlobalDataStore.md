# GlobalDataStore

**Superclass:** [Instance](Instance.md)

The `GlobalDataStore` class exposes methods to access and modify data stores, including `get_a_key()` and `set_a_key()`, which manage versioning and metadata for ordered data stores.

## Tags
- NotCreatable
- NotReplicated

## Methods
### `GlobalDataStore:GetAsync(key: string, options: [DataStoreGetOptions](DataStoreGetOptions.md)) -> Tuple`
- **Tags:** Yields
- **Summary:** Returns the value of a key in a specified data store and a `Class.DataStoreKeyInfo` instance.

### `GlobalDataStore:IncrementAsync(key: string, delta: int, userIds: Array, options: [DataStoreIncrementOptions](DataStoreIncrementOptions.md)) -> Variant`
- **Tags:** Yields
- **Summary:** Increments the value of a key by the provided amount (both must be integers).

### `GlobalDataStore:OnUpdate(key: string, callback: Function) -> RBXScriptConnection`
- **Tags:** Deprecated
- **Summary:** Sets a callback function to be executed any time the value associated with a key is changed.

### `GlobalDataStore:RemoveAsync(key: string) -> Tuple`
- **Tags:** Yields
- **Summary:** Removes the specified key while also retaining an accessible version.

### `GlobalDataStore:SetAsync(key: string, value: Variant, userIds: Array, options: [DataStoreSetOptions](DataStoreSetOptions.md)) -> Variant`
- **Tags:** Yields
- **Summary:** Sets the value of the data store for the given key.

### `GlobalDataStore:UpdateAsync(key: string, transformFunction: Function) -> Tuple`
- **Tags:** Yields
- **Summary:** Updates a key's value with a new value from the specified callback function.
