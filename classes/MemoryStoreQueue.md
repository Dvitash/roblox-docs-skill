# MemoryStoreQueue

**Superclass:** [Instance](Instance.md)

MemoryStoreQueue is a class for managing queues within the MemoryStore system, which provides temporary storage for arbitrary items.

## Tags
- NotCreatable
- NotReplicated

## Methods
### `MemoryStoreQueue:AddAsync(value: Variant, expiration: int64, priority: double) -> ()`
- **Tags:** Yields
- **Summary:** Adds an item to the queue.

### `MemoryStoreQueue:GetSizeAsync(excludeInvisible: boolean) -> int`
- **Tags:** Yields
- **Summary:** Gets the size of the queue.

### `MemoryStoreQueue:ReadAsync(count: int, allOrNothing: boolean, waitTimeout: double) -> Tuple`
- **Tags:** Yields
- **Summary:** Reads one or more items from the queue.

### `MemoryStoreQueue:RemoveAsync(id: string) -> ()`
- **Tags:** Yields
- **Summary:** Removes an item or items previously read from the queue.
