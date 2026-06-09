# Enum.PermissionLevelShown

Used to set the highest permission level that APIs have to have in order to be shown in the Object Browser.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Game` | 0 |  | Member must have no security permissions in order to be shown. |
| `RobloxGame` | 1 |  | Member must have security permissions less than or equal to **RobloxPlaceSecurity** to be shown. |
| `RobloxScript` | 2 |  | Member must have security permissions less than or equal to **RobloxScriptSecurity** to be shown. |
| `Studio` | 3 |  | Member must have security permissions less than or equal to **LocalUserSecurity** to be shown. |
| `Roblox` | 4 |  | Member is shown no matter what security it has. |

**Valid values:** `Enum.PermissionLevelShown.Game`, `Enum.PermissionLevelShown.RobloxGame`, `Enum.PermissionLevelShown.RobloxScript`, `Enum.PermissionLevelShown.Studio`, `Enum.PermissionLevelShown.Roblox`
