# Decal

**Superclass:** [FaceInstance](FaceInstance.md)

The `Class.Decal` class is a class for applying an image texture to a face of a parent `Class.BasePart`. It depends on the `Face` property and the size of the decal, determining the tint and opacity of the surface.

## Properties
### `Decal.Color3`
- **Type:** `Color3`
- **Summary:** The `Datatype.Color3` tint of the `Class.Decal`.

### `Decal.ColorMap`
- **Type:** `ContentId`
- **Tags:** NotReplicated
- **Summary:** Content ID that determines the color and opacity of the surface.

### `Decal.ColorMapContent`
- **Type:** `Content`
- **Tags:** NotReplicated
- **Summary:** `Datatype.Content` object that determines the color and opacity of the surface.

### `Decal.LocalTransparencyModifier`
- **Type:** `float`
- **Tags:** Hidden, NotReplicated
- **Summary:** Acts as a multiplier for the decal's `Class.Decal.Transparency|Transparency` property. The effects are only visible to the local player.

### `Decal.MetalnessMap`
- **Type:** `ContentId`
- **Tags:** Hidden

### `Decal.MetalnessMapContent`
- **Type:** `Content`

### `Decal.NormalMap`
- **Type:** `ContentId`
- **Tags:** Hidden

### `Decal.NormalMapContent`
- **Type:** `Content`

### `Decal.Rotation`
- **Type:** `float`

### `Decal.RoughnessMap`
- **Type:** `ContentId`
- **Tags:** Hidden

### `Decal.RoughnessMapContent`
- **Type:** `Content`

### `Decal.Shiny`
- **Type:** `float`
- **Tags:** NotReplicated, Deprecated

### `Decal.Specular`
- **Type:** `float`
- **Tags:** NotReplicated, Deprecated

### `Decal.Texture`
- **Type:** `ContentId`
- **Summary:** The content ID of the image to be applied by the `Class.Decal`.

### `Decal.TextureContent`
- **Type:** `Content`
- **Summary:** The texture content displayed by the `Class.Decal`.

### `Decal.TexturePack`
- **Type:** `ContentId`

### `Decal.Transparency`
- **Type:** `float`
- **Summary:** Determines the transparency of the `Class.Decal`.

### `Decal.UVOffset`
- **Type:** `Vector2`
- **Summary:** Shifts the UV coordinates by adding an offset before texture mapping.

### `Decal.UVScale`
- **Type:** `Vector2`
- **Summary:** Stretches or compresses the UV coordinates by multiplying a scale factor.

### `Decal.ZIndex`
- **Type:** `int`
- **Summary:** Determines the rendering order when multiple decals are assigned the same face.
