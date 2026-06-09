# PluginGui

**Superclass:** [LayerCollector](LayerCollector.md)

PluginGui is an abstract class for GUIs that allow displaying `Class.GuiObject`s in Roblox Studio widgets, with `Class.DockWidgetPluginGui` being the current available type.

## Tags
- NotCreatable
- NotReplicated

## Properties
### `PluginGui.Title`
- **Type:** `string`
- **Summary:** The title that is displayed above the contents of the `Class.PluginGui`.

## Methods
### `PluginGui:BindToClose(function: Function) -> ()`
- **Summary:** Binds a function to the `Class.PluginGui` close button, overriding the default behavior.

### `PluginGui:GetRelativeMousePosition() -> Vector2`
- **Summary:** Returns the position of the mouse relative to the PluginGui.

## Events
### `PluginGui.PluginDragDropped(dragData: Dictionary)`
- **Summary:** Fires when the user releases their mouse when hovering over a PluginGui during a drag operation started by `Class.Plugin:StartDrag()`.

### `PluginGui.PluginDragEntered(dragData: Dictionary)`
- **Summary:** Fires when the user's mouse enters a PluginGui during a drag operation started by `Class.Plugin:StartDrag()`.

### `PluginGui.PluginDragLeft(dragData: Dictionary)`
- **Summary:** Fires when the user's mouse leaves a PluginGui during a drag operation started by `Class.Plugin:StartDrag()`.

### `PluginGui.PluginDragMoved(dragData: Dictionary)`
- **Summary:** Fires when the user's mouse moves within a PluginGui during a drag operation started by `Class.Plugin:StartDrag()`.

### `PluginGui.WindowFocused()`
- **Summary:** Fires when the user begins interacting with the window of the PluginGui.

### `PluginGui.WindowFocusReleased()`
- **Summary:** Fires when the user stops interacting with the window of the PluginGui.
