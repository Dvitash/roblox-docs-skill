# Enum.PackagePermission

Indicates the current user's or group roleset's permission to the package.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `None` | 0 |  | Permission data is not available for the current user or group roleset. |
| `NoAccess` | 1 |  | The current user or group roleset doesn't have access. |
| `Revoked` | 2 |  | The current user's or group roleset's permission is revoked. |
| `UseView` | 3 |  | The current user or group roleset can download a copy of the package from Roblox. |
| `Edit` | 4 |  | The current user or group roleset can download a copy of the package from Roblox and publish package changes to Roblox. |
| `Own` | 5 |  | The current user or group roleset can download a copy of the page from Roblox, publish package changes to Roblox, and manage who has access to the package. |

**Valid values:** `Enum.PackagePermission.None`, `Enum.PackagePermission.NoAccess`, `Enum.PackagePermission.Revoked`, `Enum.PackagePermission.UseView`, `Enum.PackagePermission.Edit`, `Enum.PackagePermission.Own`
