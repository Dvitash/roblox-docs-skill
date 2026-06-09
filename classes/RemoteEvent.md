# RemoteEvent

**Superclass:** [BaseRemoteEvent](BaseRemoteEvent.md)

The `Class.RemoteEvent` class is used to facilitate asynchronous, one-way communication between a client and a server, without yielding for a response.

## Methods
### `RemoteEvent:FireAllClients(arguments: Tuple) -> ()`
- **Summary:** Fires the `Class.RemoteEvent.OnClientEvent|OnClientEvent` event for each connected client.

### `RemoteEvent:FireClient(player: [Player](Player.md), arguments: Tuple) -> ()`
- **Summary:** Fires the `Class.RemoteEvent.OnClientEvent|OnClientEvent` event for a specific client.

### `RemoteEvent:FireServer(arguments: Tuple) -> ()`
- **Summary:** Fires the `Class.RemoteEvent.OnServerEvent|OnServerEvent` event on the server from one connected client.

## Events
### `RemoteEvent.OnClientEvent(arguments: Tuple)`
- **Summary:** Fires from a `Class.LocalScript` when either `Class.RemoteEvent:FireClient()|FireClient()` or `Class.RemoteEvent:FireAllClients()|FireAllClients()` is called on the same `Class.RemoteEvent` instance from a `Class.Script`.

### `RemoteEvent.OnServerEvent(player: [Player](Player.md), arguments: Tuple)`
- **Summary:** Fires from a `Class.Script` when `Class.RemoteEvent:FireServer()|FireServer()` is called on the same `Class.RemoteEvent` instance from a `Class.LocalScript`.
