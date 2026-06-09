# BillboardGui

**Superclass:** [LayerCollector](LayerCollector.md)

The `BillboardGui` class is a container for UI objects in 3D space that always face the camera, and it has specific properties that affect how interactive elements interact with the view.

## Properties
### `BillboardGui.Active`
- **Type:** `boolean`
- **Summary:** Controls whether the descendants will receive input events.

### `BillboardGui.Adornee`
- **Type:** `[Instance](Instance.md)`
- **Summary:** Sets the target part or attachment that the `Class.BillboardGui` is positioned relative to.

### `BillboardGui.AlwaysOnTop`
- **Type:** `boolean`
- **Summary:** Determines whether the `Class.BillboardGui` will always be rendered on top of other 3D objects.

### `BillboardGui.Brightness`
- **Type:** `float`
- **Summary:** Determines the factor by which the `Class.BillboardGui` container's light is scaled when `Class.BillboardGui.LightInfluence|LightInfluence` is `0`.

### `BillboardGui.ClipsDescendants`
- **Type:** `boolean`
- **Summary:** Whether portions of `Class.GuiObject|GuiObjects` that fall outside of the `Class.BillboardGui` canvas borders will be drawn.

### `BillboardGui.CurrentDistance`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The current distance in studs that the `Class.BillboardGui` is from the player's camera.

### `BillboardGui.DistanceLowerLimit`
- **Type:** `float`
- **Tags:** Deprecated
- **Summary:** Determines the distance in studs at which the `Class.BillboardGui` will stop scaling larger in size.

### `BillboardGui.DistanceStep`
- **Type:** `float`
- **Tags:** NotReplicated
- **Summary:** Determines the size `Class.BillboardGui.CurrentDistance|CurrentDistance` increments and decrements in studs as the player's camera moves closer and further from the `Class.BillboardGui`.

### `BillboardGui.DistanceUpperLimit`
- **Type:** `float`
- **Tags:** Deprecated
- **Summary:** Determines the distance in studs at which the `Class.BillboardGui` will stop scaling smaller in size.

### `BillboardGui.ExtentsOffset`
- **Type:** `Vector3`
- **Summary:** Determines how the `Class.BillboardGui` is offset from its `Class.BillboardGui.Adornee|Adornee`, relative to the `Class.Camera` orientation, in units half the dimensions of the model's `Class.Camera`-aligned bounding box.

### `BillboardGui.ExtentsOffsetWorldSpace`
- **Type:** `Vector3`
- **Summary:** Determines how the `Class.BillboardGui` is offset from its `Class.BillboardGui.Adornee|Adornee`, relative to the global axes, in units half the dimensions of the model's axis-aligned bounding box.

### `BillboardGui.LightInfluence`
- **Type:** `float`
- **Summary:** Controls how much the `Class.BillboardGui` is influenced by environmental lighting.

### `BillboardGui.MaxDistance`
- **Type:** `float`
- **Summary:** Controls how far away the `Class.BillboardGui` can be displayed before it stops rendering.

### `BillboardGui.PlayerToHideFrom`
- **Type:** `[Instance](Instance.md)`
- **Summary:** Used by scripts to hide the `Class.BillboardGui` from a specific player.

### `BillboardGui.Size`
- **Type:** `UDim2`
- **Summary:** Controls the size that the `Class.BillboardGui` will have on screen.

### `BillboardGui.SizeOffset`
- **Type:** `Vector2`
- **Summary:** A 2D offset in size-relative units that acts like an anchor point.

### `BillboardGui.StudsOffset`
- **Type:** `Vector3`
- **Summary:** Determines how the `Class.BillboardGui` is offset from its `Class.BillboardGui.Adornee|Adornee` in studs, relative to the `Class.Camera` orientation.

### `BillboardGui.StudsOffsetWorldSpace`
- **Type:** `Vector3`
- **Summary:** Determines how the `Class.BillboardGui` is offset from its `Class.BillboardGui.Adornee|Adornee` in studs, relative to the global axes.
