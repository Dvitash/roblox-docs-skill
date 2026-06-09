# NetworkSettings

**Superclass:** [Instance](Instance.md)

NetworkSettings class provides methods to debug networked engine behaviors in Roblox Studio settings. It allows users to set properties like `InboundNetworkJitterMs` and `InboundNetworkLossPercent` to manage latency and packet drop probability on server-to-client connections.

## Tags
- NotCreatable
- Service
- NotReplicated
- NotBrowsable

## Properties
### `NetworkSettings.EmulatedTotalMemoryInMB`
- **Type:** `int`
- **Tags:** Hidden, NotReplicated

### `NetworkSettings.FreeMemoryMBytes`
- **Type:** `float`
- **Tags:** Hidden, ReadOnly, NotReplicated
- **Summary:** Describes how much free memory is available, in MiBs.

### `NetworkSettings.HttpProxyEnabled`
- **Type:** `boolean`

### `NetworkSettings.HttpProxyURL`
- **Type:** `string`

### `NetworkSettings.InboundNetworkJitterMs`
- **Type:** `float`
- **Tags:** NotReplicated
- **Summary:** Adds jitter to playtest connections in the server-to-client direction.

### `NetworkSettings.InboundNetworkLossPercent`
- **Type:** `float`
- **Tags:** NotReplicated
- **Summary:** Sets the probability that packets on playtest connections from server to client are dropped.

### `NetworkSettings.InboundNetworkMinDelayMs`
- **Type:** `float`
- **Tags:** NotReplicated
- **Summary:** Adds latency to playtest connections in the server-to-client direction.

### `NetworkSettings.IncomingReplicationLag`
- **Type:** `double`
- **Summary:** Simulates additional network latency in the network receiving path.

### `NetworkSettings.OutboundNetworkJitterMs`
- **Type:** `float`
- **Tags:** NotReplicated
- **Summary:** Adds jitter to playtest connections in the client-to-server direction.

### `NetworkSettings.OutboundNetworkLossPercent`
- **Type:** `float`
- **Tags:** NotReplicated
- **Summary:** Sets the probability that packets on playtest connections from client to server are dropped.

### `NetworkSettings.OutboundNetworkMinDelayMs`
- **Type:** `float`
- **Tags:** NotReplicated
- **Summary:** Adds latency to playtest connections in the client-to-server direction.

### `NetworkSettings.PrintJoinSizeBreakdown`
- **Type:** `boolean`
- **Summary:** Prints diagnostic information about data sent on connect.

### `NetworkSettings.PrintPhysicsErrors`
- **Type:** `boolean`
- **Summary:** Whether debug messages will be printed to the output pertaining to physics replication errors.

### `NetworkSettings.PrintStreamInstanceQuota`
- **Type:** `boolean`
- **Summary:** Whether debug information is printed to the output regarding the replication of instances when `Class.Workspace.StreamingEnabled` is set to `true`.

### `NetworkSettings.RandomizeJoinInstanceOrder`
- **Type:** `boolean`
- **Summary:** Special facility to help catch bugs related to how your experience loads.

### `NetworkSettings.RenderStreamedRegions`
- **Type:** `boolean`
- **Summary:** Whether regions of space that are being streamed to the client will be outlined in red.

### `NetworkSettings.ShowActiveAnimationAsset`
- **Type:** `boolean`
- **Summary:** Whether a label will be shown above each player character's head, showing the current animation being played.
