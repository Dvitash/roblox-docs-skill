# GuiButton

**Superclass:** [GuiObject](GuiObject.md)

The `GuiButton` class is an abstract base class for interactive 2D user interface elements, providing basic properties and a multi-platform event system.

## Tags
- NotCreatable
- NotBrowsable

## Properties
### `GuiButton.AutoButtonColor`
- **Type:** `boolean`
- **Summary:** Determines whether the button automatically changes color when the mouse hovers over or clicks on it.

### `GuiButton.HoverHapticEffect`
- **Type:** `[HapticEffect](HapticEffect.md)`
- **Summary:** A `Class.HapticEffect` instance that will play when the `Class.GuiButton` is being hovered.

### `GuiButton.Modal`
- **Type:** `boolean`
- **Summary:** If `true` while the GUI element is visible, the mouse will not be locked unless the right mouse button is down.

### `GuiButton.PressHapticEffect`
- **Type:** `[HapticEffect](HapticEffect.md)`
- **Summary:** A `Class.HapticEffect` instance that will play when the `Class.GuiButton` is being pressed.

### `GuiButton.Selected`
- **Type:** `boolean`
- **Summary:** A boolean property which indicates whether the object has been selected.

### `GuiButton.Style`
- **Type:** `ButtonStyle`
- **Summary:** Sets the style of the `Class.GuiButton` based on a list of pre-determined styles.

## Events
### `GuiButton.Activated(inputObject: [InputObject](InputObject.md), clickCount: int)`
- **Summary:** Fires when the button is activated.

### `GuiButton.MouseButton1Click()`
- **Summary:** Fires when the user's mouse fully left clicks the `Class.GuiButton`.

### `GuiButton.MouseButton1Down(x: int, y: int)`
- **Summary:** Fires when the user presses their left mouse button down on the `Class.GuiButton`.

### `GuiButton.MouseButton1Up(x: int, y: int)`
- **Summary:** Fires when the user releases their left mouse button off of the `Class.GuiButton`.

### `GuiButton.MouseButton2Click()`
- **Summary:** Fires when the user's mouse fully right clicks the `Class.GuiButton`.

### `GuiButton.MouseButton2Down(x: int, y: int)`
- **Summary:** Fires when the user presses their right mouse button down on the `Class.GuiButton`.

### `GuiButton.MouseButton2Up(x: int, y: int)`
- **Summary:** Fires when the user releases their right mouse button off of the `Class.GuiButton`.
