# RemoteFunction

**Superclass:** [Instance](Instance.md)

The `Class.RemoteFunction` class allows for synchronous, two-way communication between a client and server by invoking a custom callback function.

## Methods
### `RemoteFunction:InvokeClient(player: [Player](Player.md), arguments: Tuple) -> Tuple`
- **Tags:** Yields
- **Summary:** Invokes the `Class.RemoteFunction` which in turn calls the `Class.RemoteFunction.OnClientInvoke|OnClientInvoke` callback.

### `RemoteFunction:InvokeServer(arguments: Tuple) -> Tuple`
- **Tags:** Yields
- **Summary:** Invokes the `Class.RemoteFunction` which in turn calls the `Class.RemoteFunction.OnServerInvoke|OnServerInvoke` callback.
