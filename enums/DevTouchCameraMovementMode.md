# Enum.DevTouchCameraMovementMode

Overwrites the camera mode if the player is on a touch device.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `UserChoice` | 0 |  | The camera will move based on the player's settings. |
| `Classic` | 1 |  | Camera tracks the player but will not automatically rotate if the player walks left or right. |
| `Follow` | 2 |  | Camera tracks the player and automatically rotates if the player walks left or right. |
| `Orbital` | 3 |  | The camera has a fixed Y position, but can be rotated around the player. |

**Valid values:** `Enum.DevTouchCameraMovementMode.UserChoice`, `Enum.DevTouchCameraMovementMode.Classic`, `Enum.DevTouchCameraMovementMode.Follow`, `Enum.DevTouchCameraMovementMode.Orbital`
