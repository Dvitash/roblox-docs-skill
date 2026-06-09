# ArcHandles

**Superclass:** [HandlesBase](HandlesBase.md)

The `ArcHandles` class is a method that places 3D arc handles around any 3D object, requiring the `Class.PartAdornment.Adornee` object to be parented to a player's `Class.PlayerGui` or `Class.CoreGui`.

## Properties
### `ArcHandles.Axes`
- **Type:** `Axes`
- **Summary:** Sets the current Axes ArcHandles will show.

## Events
### `ArcHandles.MouseButton1Down(axis: Axis)`
- **Summary:** Fired when the left mouse button goes down on one of the GUI handles.

### `ArcHandles.MouseButton1Up(axis: Axis)`
- **Summary:** Fired when the left mouse button is released on one of the GUI handles.

### `ArcHandles.MouseDrag(axis: Axis, relativeAngle: float, deltaRadius: float)`
- **Summary:** Fired when the mouse moves while the MouseButton1Down event has fired, but the left mouse button has not been released yet.

### `ArcHandles.MouseEnter(axis: Axis)`
- **Summary:** Fired when a mouse "enters" the GUI handle.

### `ArcHandles.MouseLeave(axis: Axis)`
- **Summary:** Fired when the mouse leaves the GUI handle.
