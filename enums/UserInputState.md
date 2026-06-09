# Enum.UserInputState

This enum describes the state of an input that is currently or was recently performed.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Begin` | 0 |  | Occurs when an `Class.InputObject` starts to interact with the experience. For example, a mouse button down, a key down, or when the player begins touching the screen. |
| `Change` | 1 |  | Occurs each frame an `Class.InputObject` has already begun interacting with the experience and part of its state is changing. For example, movement of the mouse position, a gamepad thumbstick movement, an analog gamepad trigger button change, or screen touch point change. |
| `End` | 2 |  | Occurs when an `Class.InputObject` finishes interacting with the experience. For example, a mouse button up, a key up, or when the player stops touching the screen. |
| `Cancel` | 3 |  | A special circumstance state that indicates this input is no longer relevant, particularly with `Class.ContextActionService`. For example, binding two action-handling functions will cause the first to `Cancel` if an input was already in-progress when the second was bound. |
| `None` | 4 |  | A state that should never be seen in an experience; essentially just marks the end of the enum. |

**Valid values:** `Enum.UserInputState.Begin`, `Enum.UserInputState.Change`, `Enum.UserInputState.End`, `Enum.UserInputState.Cancel`, `Enum.UserInputState.None`
