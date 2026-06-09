# Enum.TeleportResult

Describes the result of a teleport.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Success` | 0 |  | The teleport was successful. |
| `Failure` | 1 |  | The teleport failed for an unknown reason. |
| `GameNotFound` | 2 |  | The game that this player attempted to teleport to could not be found. |
| `GameEnded` | 3 |  | The game that this player attempted to teleport to has ended. |
| `GameFull` | 4 |  | The game that this player attempted to teleport to is full. |
| `Unauthorized` | 5 |  | The player is not authorized to complete this teleport. |
| `Flooded` | 6 |  | Too many teleport requests have been made recently. |
| `IsTeleporting` | 7 |  | The player is currently being teleported. |

**Valid values:** `Enum.TeleportResult.Success`, `Enum.TeleportResult.Failure`, `Enum.TeleportResult.GameNotFound`, `Enum.TeleportResult.GameEnded`, `Enum.TeleportResult.GameFull`, `Enum.TeleportResult.Unauthorized`, `Enum.TeleportResult.Flooded`, `Enum.TeleportResult.IsTeleporting`
