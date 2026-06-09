# MatchmakingService

**Superclass:** [Instance](Instance.md)

The `MatchmakingService` class manages custom matchmaking data attributes, allowing users to read and write them to a server.

## Tags
- NotCreatable
- Service
- NotReplicated

## Methods
### `MatchmakingService:GetServerAttribute(name: string) -> Tuple`
- **Summary:** Retrieves the value of a specific server attribute.

### `MatchmakingService:InitializeServerAttributesForStudio(serverAttributes: Dictionary) -> Tuple`
- **Summary:** Initiates the server attribute schema and its values to test in Studio.

### `MatchmakingService:SetServerAttribute(name: string, value: Variant) -> Tuple`
- **Summary:** Assigns a value to a specific server attribute.
