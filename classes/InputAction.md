# InputAction

**Superclass:** [Instance](Instance.md)

InputAction is a class used to define gameplay actions that are mapped to hardware inputs using `Class.InputBinding`. It handles checking for ancestors and registering itself to the appropriate context.

## Properties
### `InputAction.BoolState`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated, NotScriptable
- **Summary:** Non-scriptable read-only property useful for debugging `Enum.InputActionType|Bool` input actions.

### `InputAction.Direction1DState`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated, NotScriptable
- **Summary:** Non-scriptable read-only property useful for debugging `Enum.InputActionType|Direction1D` input actions.

### `InputAction.Direction2DState`
- **Type:** `Vector2`
- **Tags:** ReadOnly, NotReplicated, NotScriptable
- **Summary:** Non-scriptable read-only property useful for debugging `Enum.InputActionType|Direction2D` input actions.

### `InputAction.Direction3DState`
- **Type:** `Vector3`
- **Tags:** ReadOnly, NotReplicated, NotScriptable
- **Summary:** Non-scriptable read-only property useful for debugging `Enum.InputActionType|Direction3D` input actions.

### `InputAction.Enabled`
- **Type:** `boolean`
- **Summary:** Determines if the `InputAction` is enabled or not.

### `InputAction.Type`
- **Type:** `InputActionType`
- **Summary:** Specifies what type of input value the action is expecting.

### `InputAction.ViewportPositionState`
- **Type:** `Vector2`
- **Tags:** ReadOnly, NotReplicated, NotScriptable
- **Summary:** Non-scriptable read-only property useful for debugging `Enum.InputActionType|ViewportPosition` input actions.

## Methods
### `InputAction:[Fire](Fire.md)(state: Variant) -> ()`
- **Summary:** Updates the `InputAction` to the given state and fires the appropriate signals.

### `InputAction:GetState() -> Variant`
- **Summary:** Returns the current state of the `Class.InputAction`.

## Events
### `InputAction.Pressed()`
- **Summary:** Fires only when the `Class.InputAction.Type` is set to `Enum.InputActionType|Bool` on a state transition from `false` to `true`.

### `InputAction.Released()`
- **Summary:** Fires only when the `Class.InputAction.Type` is set to `Enum.InputActionType|Bool` on a state transition from `true` to `false`.

### `InputAction.StateChanged(value: Variant)`
- **Summary:** Fires for all `Enum.InputActionType` types whenever the state changes, except if the state attempts to transition to the same state.
