# PluginConnectionService

**Superclass:** [Instance](Instance.md)

This file describes the `PluginConnectionService` class, which is used by plugins to communicate with other instances within their data models.

## Tags
- NotCreatable
- Service
- NotReplicated

## Methods
### `PluginConnectionService:CanHaveConnectionType(type: PluginConnectionTargetType) -> boolean`
- **Summary:** Checks if the current data model context can ever have connections of a given type.

### `PluginConnectionService:GetPluginConnectionsOfType(type: PluginConnectionTargetType) -> Array`
- **Summary:** Returns a list of currently connected `Class.PluginConnection` objects with the given connection type.

## Events
### `PluginConnectionService.Connected(conn: [PluginConnection](PluginConnection.md))`
- **Summary:** Fires just after a new `Class.PluginConnection` successfully connects.
