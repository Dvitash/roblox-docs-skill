# Enum.AssetTypeVerification

Determines the asset type verification mode.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Default` | 1 |  | Use the default behavior for asset type verification. |
| `ClientOnly` | 2 |  | Only verify asset types on the client. Asset type verification can not be turned off on the client. |
| `Always` | 3 |  | Always verify the asset types to be loaded and disallow loading models. |

**Valid values:** `Enum.AssetTypeVerification.Default`, `Enum.AssetTypeVerification.ClientOnly`, `Enum.AssetTypeVerification.Always`
