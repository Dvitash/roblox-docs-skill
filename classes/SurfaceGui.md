# SurfaceGui

**Superclass:** [SurfaceGuiBase](SurfaceGuiBase.md)

The `Class.SurfaceGui` class is a container for rendering GUI objects onto a surface, allowing for basic user interaction and parented UI elements to be visible on the surface.

## Properties
### `SurfaceGui.AlwaysOnTop`
- **Type:** `boolean`
- **Summary:** Determines whether the `Class.SurfaceGui` will always be rendered on top of other 3D objects.

### `SurfaceGui.Brightness`
- **Type:** `float`
- **Summary:** Determines the factor by which the `Class.SurfaceGui` container's light is scaled when `Class.SurfaceGui.LightInfluence|LightInfluence` is `0`.

### `SurfaceGui.CanvasSize`
- **Type:** `Vector2`
- **Summary:** The size of a "virtual screen" in "virtual pixels" which makes `Class.SurfaceGui|SurfaceGuis` pixel-to-pixel compatible with `Class.ScreenGui|ScreenGuis`.

### `SurfaceGui.ClipsDescendants`
- **Type:** `boolean`
- **Summary:** Whether portions of `Class.GuiObject|GuiObjects` that fall outside of the `Class.SurfaceGui` canvas borders will be drawn.

### `SurfaceGui.LightInfluence`
- **Type:** `float`
- **Summary:** Controls how much the `Class.SurfaceGui` is influenced by environmental lighting.

### `SurfaceGui.MaxDistance`
- **Type:** `float`
- **Summary:** Controls how far away the `Class.SurfaceGui` can be displayed before it stops rendering.

### `SurfaceGui.PixelsPerStud`
- **Type:** `float`
- **Summary:** Determines the density of pixels used for each world-space stud to render the contents of the `Class.SurfaceGui`.

### `SurfaceGui.SizingMode`
- **Type:** `SurfaceGuiSizingMode`
- **Summary:** Determines whether the `Class.SurfaceGui` will render at a fixed size or scale with its size in studs.

### `SurfaceGui.ToolPunchThroughDistance`
- **Type:** `float`
- **Summary:** Sets the distance in which left clicking starts acting on the `Class.SurfaceGui` instead of for the held `Class.Tool`.

### `SurfaceGui.ZOffset`
- **Type:** `float`
- **Summary:** Layers this `Class.SurfaceGui` in relation to other `Class.SurfaceGui|SurfaceGuis` on the same face.
