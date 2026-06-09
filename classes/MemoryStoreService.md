# MemoryStoreService

**Superclass:** [Instance](Instance.md)

MemoryStoreService is a top-level singleton class in RBLox that exposes methods to access specific primitives within the MemoryStore. It is used for data that rapidly changes that other servers can restore, such as leaderboards or matchmaking queues.

## Tags
- Service

## Methods
### `MemoryStoreService:GetHashMap(name: string) -> [MemoryStoreHashMap](MemoryStoreHashMap.md)`
- **Summary:** Returns a `Class.MemoryStoreHashMap` instance for the provided name.

### `MemoryStoreService:GetQueue(name: string, invisibilityTimeout: int) -> [MemoryStoreQueue](MemoryStoreQueue.md)`
- **Summary:** Returns a `Class.MemoryStoreQueue` instance for the provided name.

### `MemoryStoreService:GetSortedMap(name: string) -> [MemoryStoreSortedMap](MemoryStoreSortedMap.md)`
- **Summary:** Returns a `Class.MemoryStoreSortedMap` instance for the provided name.
