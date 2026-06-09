# Enum.CameraType

Describes the camera behavior mode if using the default PlayerScripts.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Fixed` | 0 |  | Camera is stationary. |
| `Attach` | 1 |  | Camera moves with the subject at a fixed offset and will rotate as the subject rotates. |
| `Watch` | 2 |  | Camera is stationary but will rotate to keep the subject in the center of the screen. |
| `Track` | 3 |  | Camera moves with the subject but does not rotate automatically. |
| `Follow` | 4 |  | Camera moves with the subject and rotates to keep the subject in the center. |
| `Custom` | 5 |  | Default mode used by Roblox core scripts. |
| `Scriptable` | 6 |  | No default behavior. Used when developers need to script custom behavior. |
| `Orbital` | 7 |  | The camera has a fixed Y position, but can be rotated around the player. |

**Valid values:** `Enum.CameraType.Fixed`, `Enum.CameraType.Attach`, `Enum.CameraType.Watch`, `Enum.CameraType.Track`, `Enum.CameraType.Follow`, `Enum.CameraType.Custom`, `Enum.CameraType.Scriptable`, `Enum.CameraType.Orbital`
