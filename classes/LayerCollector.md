# LayerCollector

**Superclass:** [GuiBase2d](GuiBase2d.md)

LayerCollector is the base class for 2D UI containers that render `Class.GuiObject` descendants, which can be configured to cache visibility based on specific events or changes.

## Tags
- NotCreatable
- NotBrowsable

## Properties
### `LayerCollector.Enabled`
- **Type:** `boolean`
- **Summary:** Toggles the visibility of this `Class.LayerCollector`.

### `LayerCollector.ResetOnSpawn`
- **Type:** `boolean`
- **Summary:** Determines if the `Class.LayerCollector` resets (deletes itself and re-clones into the player's `Class.PlayerGui`) every time the player's character respawns.

### `LayerCollector.TabKeyboardNavigation`
- **Type:** `boolean`

### `LayerCollector.ZIndexBehavior`
- **Type:** `ZIndexBehavior`
- **Summary:** Controls how `Class.GuiObject.ZIndex` behaves on all descendants of this `Class.LayerCollector`.

## Methods
### `LayerCollector:GetLayoutNodeTree() -> Dictionary`
- **Tags:** Deprecated
