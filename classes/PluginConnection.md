# PluginConnection

**Superclass:** [Object](Object.md)

PluginConnection encapsulates a connection between a data model and another for plugin communication, allowing multiple plugins to communicate across boundaries.

## Tags
- NotCreatable
- NotReplicated

## Properties
### `PluginConnection.Connected`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Whether this `PluginConnection` object is still connected.

### `PluginConnection.TargetId`
- **Type:** `string`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A unique ID for the target data model.

### `PluginConnection.Type`
- **Type:** `PluginConnectionTargetType`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** This `Enum.PluginConnectionTargetType` describes the relationship of the target data model to the current one.

## Methods
### `PluginConnection:BindToMessage(callback: Function) -> RBXScriptConnection`
- **Summary:** Binds a callback to this `PluginConnection` to receive messages from `SendMessage()`.

### `PluginConnection:SendMessage(message: Variant) -> ()`
- **Summary:** Sends a payload to the remote data model.
