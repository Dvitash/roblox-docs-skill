# ConfigService

**Superclass:** [Instance](Instance.md)

ConfigService is a game service that provides in-experience configuration updates in real time. It allows clients to access `Class.ConfigSnapshot` objects, though they must be accessed only by game servers.

## Tags
- NotCreatable
- Service
- NotReplicated

## Methods
### `ConfigService:ClearTestingValue(key: string) -> ()`
- **Summary:** Clears current testing value for the given key.

### `ConfigService:GetConfigAsync() -> [ConfigSnapshot](ConfigSnapshot.md)`
- **Tags:** Yields
- **Summary:** Retrieves a snapshot of the latest configuration.

### `ConfigService:GetConfigForPlayerAsync(player: [Player](Player.md)) -> [ConfigSnapshot](ConfigSnapshot.md)`
- **Tags:** Yields
- **Summary:** Retrieves a snapshot of the latest configuration for a specific player.

### `ConfigService:SetTestingValue(key: string, value: Variant) -> ()`
- **Summary:** Sets a testing override for the given key.
