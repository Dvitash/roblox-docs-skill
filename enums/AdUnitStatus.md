# Enum.AdUnitStatus

Exposes the status of an immersive ad.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Inactive` | 0 |  | The ad unit isn't currently serving an ad and it may be configured incorrectly. An `Class.AdGui` with this status will display its fallback image. |
| `Active` | 1 |  | The ad unit is currently serving an ad. Players will observe sponsored content in an `Class.AdGui` and an `Class.AdPortal` will teleport users that walk through. |

**Valid values:** `Enum.AdUnitStatus.Inactive`, `Enum.AdUnitStatus.Active`
