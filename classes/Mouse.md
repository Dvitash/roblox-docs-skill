# Mouse

**Superclass:** [Instance](Instance.md)

Mouse is superseded by `Class.UserInputService` and `Class.ContextActionService`, which offer more feature-rich alternatives for pointer input.

## Tags
- NotCreatable

## Properties
### `Mouse.Hit`
- **Type:** `CFrame`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The `Datatype.CFrame` of the mouse's position in 3D space.

### `Mouse.hit`
- **Type:** `CFrame`
- **Tags:** Hidden, ReadOnly, NotReplicated, Deprecated

### `Mouse.Icon`
- **Type:** `ContentId`
- **Summary:** The content ID of the image used as the `Class.Mouse` icon.

### `Mouse.IconContent`
- **Type:** `Content`
- **Summary:** The content of the image used as the `Class.Mouse` icon. Only supports asset URIs.

### `Mouse.Origin`
- **Type:** `CFrame`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A `Datatype.CFrame` positioned at the `Class.Workspace.CurrentCamera` and oriented toward the mouse's 3D position.

### `Mouse.Target`
- **Type:** `[BasePart](BasePart.md)`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The object in 3D space the `Class.Mouse|mouse` is pointing to.

### `Mouse.target`
- **Type:** `[BasePart](BasePart.md)`
- **Tags:** ReadOnly, NotReplicated, Deprecated

### `Mouse.TargetFilter`
- **Type:** `[Instance](Instance.md)`
- **Summary:** Determines an object (and its descendants) to be ignored when determining `Class.Mouse.Hit` and `Class.Mouse.Target`.

### `Mouse.TargetSurface`
- **Type:** `NormalId`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Indicates the `Enum.NormalId` of the `Class.BasePart` surface at which the mouse is pointing.

### `Mouse.UnitRay`
- **Type:** `Ray`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A `Datatype.Ray` directed towards the mouse's world position, originating from the `Class.Workspace.CurrentCamera` world position.

### `Mouse.ViewSizeX`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Describes the width of the game window in pixels.

### `Mouse.ViewSizeY`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Describes the height of the game window in pixels.

### `Mouse.X`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Describes the X (horizontal) component of the mouse's position on the screen.

### `Mouse.Y`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Describes the Y (vertical) component of the mouse's screen position.

## Events
### `Mouse.Button1Down()`
- **Summary:** Fires when the left mouse button is pressed.

### `Mouse.Button1Up()`
- **Summary:** Fires when the left mouse button is released.

### `Mouse.Button2Down()`
- **Summary:** Fires when the right mouse button is pressed.

### `Mouse.Button2Up()`
- **Summary:** Fired when the right mouse button is released.

### `Mouse.Idle()`
- **Summary:** Fired during every heartbeat that the mouse isn't being passed to another mouse event.

### `Mouse.KeyDown(key: string)`
- **Tags:** Deprecated
- **Summary:** Fires when a Key is pressed.

### `Mouse.keyDown(key: string)`
- **Tags:** Deprecated

### `Mouse.KeyUp(key: string)`
- **Tags:** Deprecated
- **Summary:** Fires when a Key is released.

### `Mouse.Move()`
- **Summary:** Fired when the mouse is moved.

### `Mouse.WheelBackward()`
- **Summary:** Fires when the mouse wheel is scrolled backwards.

### `Mouse.WheelForward()`
- **Summary:** Fires when the mouse wheel is scrolled forwards.
