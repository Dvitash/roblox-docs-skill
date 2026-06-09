# ServerScriptService

**Superclass:** [Instance](Instance.md)

ServerScriptService is a container service for server-only `Class.Script` objects, which are not replicated to player clients, allowing for secure storage of game logic.

## Tags
- NotCreatable
- Service
- NotReplicated

## Properties
### `ServerScriptService.LoadStringEnabled`
- **Type:** `boolean`
- **Tags:** NotReplicated, NotScriptable
- **Summary:** Toggles whether or not the `loadstring` function can be used by server scripts. Defaults to false.
