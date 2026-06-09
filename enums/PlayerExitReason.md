# Enum.PlayerExitReason

An enum that specifies the reason for **Players.PlayerRemoving** signal.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Unknown` | 0 |  | Catch-all for all other disconnect reasons. |
| `PlatformKick` | 1 |  | User was kicked by Roblox systems, such as being blocked while in a Private Server. |
| `CreatorKick` | 2 |  | Creator called **Player:Kick()** |

**Valid values:** `Enum.PlayerExitReason.Unknown`, `Enum.PlayerExitReason.PlatformKick`, `Enum.PlayerExitReason.CreatorKick`
