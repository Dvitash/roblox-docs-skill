# Enum.AudioApiRollout

Used to determine whether voice chat is represented and controlled by `Class.AudioDeviceInput` objects.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Disabled` | 0 |  | Voice chat will use an internal voice chat implementation that is automatic and hidden. |
| `Automatic` | 1 |  | Currently means the same thing as `Disabled`, but will be updated to mean `Enabled` in the future. |
| `Enabled` | 2 |  | Voice chat can be customized or controlled via `Class.AudioDeviceInput\|AudioDeviceInputs`. |

**Valid values:** `Enum.AudioApiRollout.Disabled`, `Enum.AudioApiRollout.Automatic`, `Enum.AudioApiRollout.Enabled`
