# SharedTableRegistry

**Superclass:** [Instance](Instance.md)

SharedTableRegistry is a class for managing a global registry of `Datatype.SharedTable` objects, allowing multiple scripts to store and access shared data.

## Tags
- NotCreatable
- Service
- NotReplicated

## Methods
### `SharedTableRegistry:GetSharedTable(name: string) -> SharedTable`
- **Summary:** Gets the registered `Datatype.SharedTable` with the specified name.

### `SharedTableRegistry:SetSharedTable(name: string, st: SharedTable?) -> ()`
- **Summary:** Registers the provided `Datatype.SharedTable` with the specified name.
