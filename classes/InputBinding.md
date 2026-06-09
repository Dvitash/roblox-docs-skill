# InputBinding

**Superclass:** [Instance](Instance.md)

The `InputBinding` class defines which hardware binding to trigger the `Class.InputAction`, allowing for multiple instances of this binding parented to a single `Class.InputAction`.

## Properties
### `InputBinding.Backward`
- **Type:** `KeyCode`
- **Summary:** Specifies an alternate `Enum.KeyCode` for dispatching directionally "backward" inputs to the parent `Class.InputAction`.

### `InputBinding.ClampMagnitudeToOne`
- **Type:** `boolean`

### `InputBinding.Down`
- **Type:** `KeyCode`
- **Summary:** Specifies an alternate `Enum.KeyCode` for dispatching directionally "down" inputs to the parent `Class.InputAction`.

### `InputBinding.Forward`
- **Type:** `KeyCode`
- **Summary:** Specifies an alternate `Enum.KeyCode` for dispatching directionally "forward" inputs to the parent `Class.InputAction`.

### `InputBinding.KeyCode`
- **Type:** `KeyCode`
- **Summary:** Specifies the `Enum.KeyCode` which triggers the parent `Class.InputAction`.

### `InputBinding.Left`
- **Type:** `KeyCode`
- **Summary:** Specifies an alternate `Enum.KeyCode` for dispatching directionally "left" inputs to the parent `Class.InputAction`.

### `InputBinding.PointerIndex`
- **Type:** `int`

### `InputBinding.PressedThreshold`
- **Type:** `float`
- **Summary:** Numerical value above which to fire an `Class.InputAction` with a `Class.InputAction.Type|Type` of `Enum.InputActionType|Bool`.

### `InputBinding.PrimaryModifier`
- **Type:** `KeyCode`
- **Summary:** Specifies a primary `Enum.KeyCode` that must be pressed for the binding to activate.

### `InputBinding.ReleasedThreshold`
- **Type:** `float`
- **Summary:** Numerical value below which to fire an `Class.InputAction` with a `Class.InputAction.Type|Type` of `Enum.InputActionType|Bool`.

### `InputBinding.ResponseCurve`
- **Type:** `float`
- **Summary:** Numerical value to configure scaling for more precise thumbstick aiming.

### `InputBinding.Right`
- **Type:** `KeyCode`
- **Summary:** Specifies an alternate `Enum.KeyCode` for dispatching directionally "right" inputs to the parent `Class.InputAction`.

### `InputBinding.Scale`
- **Type:** `float`
- **Summary:** Amount by which to linearly scale the values of a directional `Class.InputAction`.

### `InputBinding.SecondaryModifier`
- **Type:** `KeyCode`
- **Summary:** Specifies a secondary `Enum.KeyCode` that must be pressed for the binding to activate.

### `InputBinding.UIButton`
- **Type:** `[GuiButton](GuiButton.md)`
- **Summary:** Connects a `Class.GuiButton` to a boolean action.

### `InputBinding.Up`
- **Type:** `KeyCode`
- **Summary:** Specifies an alternate `Enum.KeyCode` for dispatching directionally "up" inputs to the parent `Class.InputAction`.

### `InputBinding.Vector2Scale`
- **Type:** `Vector2`
- **Summary:** Amount by which to linearly scale the values of a two-directional `Class.InputAction`.

### `InputBinding.Vector3Scale`
- **Type:** `Vector3`
