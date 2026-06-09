# HandleAdornment

**Superclass:** [PVAdornment](PVAdornment.md)

HandleAdornment is an abstract class inherited by 3D handle adornments, which allows for input events and behavior based on camera distance.

## Tags
- NotCreatable

## Properties
### `HandleAdornment.AdornCullingMode`
- **Type:** `AdornCullingMode`
- **Summary:** Determines whether to automatically cull the adornment.

### `HandleAdornment.AlwaysOnTop`
- **Type:** `boolean`
- **Summary:** Forces this adornment to render on top of all 3D objects in the workspace.

### `HandleAdornment.CFrame`
- **Type:** `CFrame`
- **Summary:** The position and rotation of the object relative to its `Class.PVAdornment.Adornee`.

### `HandleAdornment.SizeRelativeOffset`
- **Type:** `Vector3`
- **Summary:** The positional offset of the adornment based on the adornee's `Class.BasePart.Size`.

### `HandleAdornment.ZIndex`
- **Type:** `int`
- **Summary:** Determines the draw order of this `Class.HandleAdornment` when `Class.HandleAdornment.AlwaysOnTop|AlwaysOnTop` is `true`.

## Events
### `HandleAdornment.MouseButton1Down()`
- **Summary:** Fires when a player presses down on their left mouse button while hovering over the adornment.

### `HandleAdornment.MouseButton1Up()`
- **Summary:** Fires when a player releases their left mouse button while hovering over the adornment.

### `HandleAdornment.MouseEnter()`
- **Summary:** Fires when a player moves their mouse over the adornment.

### `HandleAdornment.MouseLeave()`
- **Summary:** Fires when a player moves their mouse out of the adornment.
