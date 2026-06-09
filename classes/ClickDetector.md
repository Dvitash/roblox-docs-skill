# ClickDetector

**Superclass:** [Instance](Instance.md)

ClickDetector is an object that receives pointer input from `Class.BasePart` or `Class.Model` objects, allowing scripts to interact with the detector when parented to these objects.

## Properties
### `ClickDetector.CursorIcon`
- **Type:** `ContentId`
- **Summary:** Sets the cursor icon to display when the mouse is hovered over the parent of this `Class.ClickDetector` or `Class.DragDetector`.

### `ClickDetector.CursorIconContent`
- **Type:** `Content`
- **Summary:** Sets the cursor icon to display when the mouse is hovered over the parent of this `Class.ClickDetector` or `Class.DragDetector`. Only supports asset URIs.

### `ClickDetector.MaxActivationDistance`
- **Type:** `float`
- **Summary:** Maximum distance between a character and the `Class.ClickDetector` or `Class.DragDetector` for the player to be able to interact with it.

## Events
### `ClickDetector.MouseClick(playerWhoClicked: [Player](Player.md))`
- **Summary:** Fires when a player interacts with the parent of a `Class.ClickDetector` or `Class.DragDetector`.

### `ClickDetector.mouseClick(playerWhoClicked: [Player](Player.md))`
- **Tags:** Deprecated

### `ClickDetector.MouseHoverEnter(playerWhoHovered: [Player](Player.md))`
- **Summary:** Fires when the parent of a `Class.ClickDetector` or `Class.DragDetector` is hovered over by a player.

### `ClickDetector.MouseHoverLeave(playerWhoHovered: [Player](Player.md))`
- **Summary:** Fires when a player's cursor hovers off the parent of a `Class.ClickDetector` or `Class.DragDetector`.

### `ClickDetector.RightMouseClick(playerWhoClicked: [Player](Player.md))`
- **Summary:** Fires when a player right clicks their mouse cursor on a `Class.ClickDetector` or `Class.DragDetector`.
