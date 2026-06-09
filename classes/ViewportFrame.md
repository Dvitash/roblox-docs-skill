# ViewportFrame

**Superclass:** [GuiObject](GuiObject.md)

ViewportFrame is a `Class.GuiObject` that renders 3D objects within its bounds, offering features like lighting and cubemap use. It supports specific material effects, nested objects, and allows for custom lighting based on environment settings.

## Properties
### `ViewportFrame.Ambient`
- **Type:** `Color3`
- **Summary:** The lighting hue applied to the area within the `ViewportFrame`.

### `ViewportFrame.CurrentCamera`
- **Type:** `[Camera](Camera.md)`
- **Tags:** NotReplicated
- **Summary:** `Class.Camera` that is used to render children objects.

### `ViewportFrame.ImageColor3`
- **Type:** `Color3`
- **Summary:** Determines how the rendered viewport image will be colorized.

### `ViewportFrame.ImageTransparency`
- **Type:** `float`
- **Summary:** Determines the transparency of the rendered viewport image.

### `ViewportFrame.LightColor`
- **Type:** `Color3`
- **Summary:** The color of the emitted light.

### `ViewportFrame.LightDirection`
- **Type:** `Vector3`
- **Summary:** A `Datatype.Vector3` representing the direction of the light source.
