# Enum.InputActionType

This enum is used by `Class.InputAction.Type` to determine which input data type the `Class.InputAction` will receive.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Bool` | 0 |  | The `Class.InputAction` will receive boolean values from button inputs, for example `true`/`false` on press/release from inputs such as `Enum.KeyCode.ButtonA` or `Enum.KeyCode.E`. This setting also exposes the `Class.InputBinding.UIButton\|UIButton` property on child `Class.InputBinding\|InputBindings`, allowing you to easily hook up press or release of a `Class.GuiButton` for the action. |
| `Direction1D` | 1 |  | The `Class.InputAction` will receive numerical values, generally from analog gamepad triggers such as `Enum.KeyCode.ButtonL2` or `Enum.KeyCode.ButtonR2`. This setting also exposes the `Class.InputBinding.Up\|Up` and `Class.InputBinding.Down\|Down` properties on child `Class.InputBinding\|InputBindings`, allowing for boolean inputs or "1D" inputs as composite directions for the action. |
| `Direction2D` | 2 |  | The `Class.InputAction` will receive `Datatype.Vector2` values, generally from thumbstick inputs such as `Enum.KeyCode.Thumbstick1` and `Enum.KeyCode.Thumbstick2`. This setting also exposes the `Class.InputBinding.Up\|Up`, `Class.InputBinding.Down\|Down`, `Class.InputBinding.Left\|Left`, and `Class.InputBinding.Right\|Right` properties on child `Class.InputBinding\|InputBindings`, allowing for "2D" inputs as composite directions for the action. |
| `Direction3D` | 3 |  | The `Class.InputAction` will receive `Datatype.Vector3` values from inputs assigned to the `Class.InputBinding.Up\|Up`, `Class.InputBinding.Down\|Down`, `Class.InputBinding.Left\|Left`, `Class.InputBinding.Right\|Right`, `Class.InputBinding.Forward\|Forward`, and/or `Class.InputBinding.Backward\|Backward` properties on child `Class.InputBinding\|InputBindings`, allowing for "3D" inputs as composite directions for the action. |
| `ViewportPosition` | 4 |  | The `Class.InputAction` will receive `Datatype.Vector2` values representing the absolute pixel (**X**, **Y**) coordinates of a pointer input in the viewport. |

**Valid values:** `Enum.InputActionType.Bool`, `Enum.InputActionType.Direction1D`, `Enum.InputActionType.Direction2D`, `Enum.InputActionType.Direction3D`, `Enum.InputActionType.ViewportPosition`
