# Enum.CloseReason

Specifies the reason for the experience server shutdown.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Unknown` | 0 |  | The server shut down for an unknown reason. |
| `RobloxMaintenance` | 1 |  | The server shut down for maintenance. |
| `DeveloperShutdown` | 2 |  | The experience developer has shut down the server, or functions bound by `Class.DataModel:BindToClose()\|BindToClose()` have been called inside Studio. |
| `DeveloperUpdate` | 3 |  | The experience developer has migrated the server to a new place version. |
| `ServerEmpty` | 4 |  | The last player has left and the experience is empty. |
| `OutOfMemory` | 5 |  | The experience has hit the memory limit for the game server. |

**Valid values:** `Enum.CloseReason.Unknown`, `Enum.CloseReason.RobloxMaintenance`, `Enum.CloseReason.DeveloperShutdown`, `Enum.CloseReason.DeveloperUpdate`, `Enum.CloseReason.ServerEmpty`, `Enum.CloseReason.OutOfMemory`
