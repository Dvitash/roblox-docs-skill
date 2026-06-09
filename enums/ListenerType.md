# Enum.ListenerType

Defines where and how the listener is positioned when picking up spatial audio.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Camera` | 0 |  | Uses the world CFrame of `workspace.CurrentCamera`. |
| `CFrame` | 1 |  | Uses a specified world CFrame. |
| `ObjectPosition` | 2 |  | Uses the world position of an instance and the rotation of `workspace.CurrentCamera`. |
| `ObjectCFrame` | 3 |  | Uses the world CFrame from an instance. |

**Valid values:** `Enum.ListenerType.Camera`, `Enum.ListenerType.CFrame`, `Enum.ListenerType.ObjectPosition`, `Enum.ListenerType.ObjectCFrame`
