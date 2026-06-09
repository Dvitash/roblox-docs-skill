# UnreliableRemoteEvent

**Superclass:** [BaseRemoteEvent](BaseRemoteEvent.md)

UnreliableRemoteEvent is a class used for asynchronous, unordered, and unreliable communication between client and server, which does not yield for a response.

## Methods
### `UnreliableRemoteEvent:FireAllClients(arguments: Tuple) -> ()`
- **Summary:** Fires the `Class.UnreliableRemoteEvent.OnClientEvent|OnClientEvent` event for all connected clients. Has a 1000 byte limit to the payload of the event. Events with larger payloads are dropped.

### `UnreliableRemoteEvent:FireClient(player: [Player](Player.md), arguments: Tuple) -> ()`
- **Summary:** Fires the `Class.UnreliableRemoteEvent.OnClientEvent|OnClientEvent` event for a specific client. Has a 1000 byte limit to the payload of the event. Events with larger payloads are dropped.

### `UnreliableRemoteEvent:FireServer(arguments: Tuple) -> ()`
- **Summary:** Fires the `Class.UnreliableRemoteEvent.OnServerEvent|OnServerEvent` event on the server from one connected client. Has a 1000 byte limit to the payload of the event. Events with larger payloads are dropped.

## Events
### `UnreliableRemoteEvent.OnClientEvent(arguments: Tuple)`
- **Summary:** Fires from a `Class.LocalScript` when either `Class.UnreliableRemoteEvent:FireClient()|FireClient()` or `Class.UnreliableRemoteEvent:FireAllClients()|FireAllClients()` is called on the same `Class.UnreliableRemoteEvent` instance from a `Class.Script`, although this firing is not guaranteed even if one of the above methods are called. This can occur due to packet loss or to maintain optimal engine performance.

### `UnreliableRemoteEvent.OnServerEvent(player: [Player](Player.md), arguments: Tuple)`
- **Summary:** Fires from a `Class.Script` when `Class.UnreliableRemoteEvent:FireServer()|FireServer()` is called on the same `Class.UnreliableRemoteEvent` instance from a `Class.LocalScript`, although this firing is not guaranteed even if the above methods is called. This can occur due to packet loss or to maintain optimal engine performance.
