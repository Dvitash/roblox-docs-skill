# Handles

**Superclass:** [HandlesBase](HandlesBase.md)

Places 3D handles around objects that `Class.Handles.Adornee` is set to.

## Properties
### `Handles.Faces`
- **Type:** `Faces`
- **Summary:** Sets which sides the GUI handles will appear.

### `Handles.Style`
- **Type:** `HandlesStyle`
- **Summary:** Sets the GUI style of the handles.

## Events
### `Handles.MouseButton1Down(face: NormalId)`
- **Summary:** Fired when the left mouse button goes down on one of the GUI handles.

### `Handles.MouseButton1Up(face: NormalId)`
- **Summary:** Fired when the left mouse button is released on one of the GUI handles.

### `Handles.MouseDrag(face: NormalId, distance: float)`
- **Summary:** Fired when the mouse moves while the MouseButton1Down event has fired, but the left mouse button has not been released yet.

### `Handles.MouseEnter(face: NormalId)`
- **Summary:** Fired when a mouse "enters" the GUI handle.

### `Handles.MouseLeave(face: NormalId)`
- **Summary:** Fired when the mouse leaves the GUI handle.
