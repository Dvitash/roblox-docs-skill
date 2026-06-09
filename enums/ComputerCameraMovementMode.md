# Enum.ComputerCameraMovementMode

The camera movement mode currently in-use by the client.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Default` | 0 |  | The default camera movement mode is classic. |
| `Classic` | 1 |  | Camera tracks the player but will not automatically rotate if the player walks left or right. |
| `Follow` | 2 |  | Camera tracks the player and automatically rotates if the player walks left or right. |
| `Orbital` | 3 |  | The camera has a fixed Y position, but can be rotated around the player. |
| `CameraToggle` | 4 |  | The camera toggles between locked and free rotation with the right mouse button. |

**Valid values:** `Enum.ComputerCameraMovementMode.Default`, `Enum.ComputerCameraMovementMode.Classic`, `Enum.ComputerCameraMovementMode.Follow`, `Enum.ComputerCameraMovementMode.Orbital`, `Enum.ComputerCameraMovementMode.CameraToggle`
