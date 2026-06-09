# GamePassService

**Superclass:** [Instance](Instance.md)

GamePassService is a class used to manage legacy game passes using Asset IDs, and it should be used with `Class.MarketplaceService` for new work.

## Tags
- NotCreatable
- Service

## Methods
### `GamePassService:PlayerHasPass(player: [Player](Player.md), gamePassId: int64) -> boolean`
- **Tags:** Yields, Deprecated
- **Summary:** Returns `true` if the `Class.Player` has the specified **legacy** game pass. Does not work with new game passes.
