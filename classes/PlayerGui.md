# PlayerGui

**Superclass:** [BasePlayerGui](BasePlayerGui.md)

The `PlayerGui` class is a container for holding objects that create the player's UI, allowing for controlling the visibility and behavior of game elements.

## Tags
- NotCreatable
- PlayerReplicated

## Properties
### `PlayerGui.CurrentScreenOrientation`
- **Type:** `ScreenOrientation`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Describes the player's current screen orientation.

### `PlayerGui.ScreenOrientation`
- **Type:** `ScreenOrientation`
- **Summary:** Sets the preferred screen orientation mode for this player, if on a mobile device.

### `PlayerGui.SelectionImageObject`
- **Type:** `[GuiObject](GuiObject.md)`
- **Summary:** Overrides the default selection adornment used for gamepads.

## Methods
### `PlayerGui:GetTopbarTransparency() -> float`
- **Tags:** Deprecated
- **Summary:** Returns the transparency of the Topbar.

### `PlayerGui:SetTopbarTransparency(transparency: float) -> ()`
- **Tags:** Deprecated
- **Summary:** Sets the transparency of the top bar.

## Events
### `PlayerGui.TopbarTransparencyChangedSignal(transparency: float)`
- **Tags:** Deprecated
- **Summary:** Fires when the transparency of the Topbar CoreGui changes.
