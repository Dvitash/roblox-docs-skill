# NetworkClient

**Superclass:** [NetworkPeer](NetworkPeer.md)

This file defines the `NetworkClient` class, which handles connecting a client to a server. It includes methods for successful and failed connections, along with associated code samples.

## Tags
- NotCreatable
- Service
- NotReplicated

## Events
### `NetworkClient.ConnectionAccepted(peer: string, replicator: [Instance](Instance.md))`
- **Summary:** Fired when the client successfully connects to a server. Returns a string showing the server's IP and port, and the client's `Class.ClientReplicator`.

### `NetworkClient.ConnectionFailed(peer: string, code: int)`
- **Summary:** Fired if the client fails to connect to the server.
