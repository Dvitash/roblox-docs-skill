# Enum.TeleportState

Determines the current teleportation state of a player.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `RequestedFromServer` | 0 |  | The server has requested that the client teleport. |
| `Started` | 1 |  | The client has started attempting to teleport. |
| `WaitingForServer` | 2 |  | The client is waiting for the server to respond to the teleport request. |
| `Failed` | 3 |  | The teleport failed. |
| `InProgress` | 4 |  | The teleport is currently in progress. The player usually disconnects and teleports to the destination after this. |

**Valid values:** `Enum.TeleportState.RequestedFromServer`, `Enum.TeleportState.Started`, `Enum.TeleportState.WaitingForServer`, `Enum.TeleportState.Failed`, `Enum.TeleportState.InProgress`
