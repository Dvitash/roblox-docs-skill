# SurfaceAppearance

**Superclass:** [Instance](Instance.md)

The `SurfaceAppearance` class allows developers to override the appearance of a `Class.MeshPart` with advanced graphics options, such as applying Physically-Based Rendering (PBR) texture images or maps.

## Properties
### `SurfaceAppearance.AlphaMode`
- **Type:** `AlphaMode`
- **Summary:** Determines how the alpha channel of the `Class.SurfaceAppearance.ColorMap` is used.

### `SurfaceAppearance.Color`
- **Type:** `Color3`
- **Summary:** Applies a tint to your existing colormap. Set directly with color picker or programmatically with `Datatype.Color3`.

### `SurfaceAppearance.ColorMap`
- **Type:** `ContentId`
- **Summary:** Determines the color and opacity of the surface.

### `SurfaceAppearance.ColorMapContent`
- **Type:** `Content`
- **Tags:** Hidden

### `SurfaceAppearance.EmissiveMaskContent`
- **Type:** `Content`
- **Summary:** Determines the emissivity across the surface.

### `SurfaceAppearance.EmissiveStrength`
- **Type:** `float`
- **Summary:** Determines the strength of emissive contribution.

### `SurfaceAppearance.EmissiveTint`
- **Type:** `Color3`
- **Summary:** Determines the tinting color for emissive contribution.

### `SurfaceAppearance.MetalnessMap`
- **Type:** `ContentId`
- **Summary:** Determines which parts of the surface are metal or non-metal.

### `SurfaceAppearance.MetalnessMapContent`
- **Type:** `Content`
- **Tags:** Hidden

### `SurfaceAppearance.NormalMap`
- **Type:** `ContentId`
- **Summary:** Modifies the lighting of the surface by adding bumps, dents, cracks, and curves.

### `SurfaceAppearance.NormalMapContent`
- **Type:** `Content`
- **Tags:** Hidden

### `SurfaceAppearance.ResampleMode`
- **Type:** `ResamplerMode`

### `SurfaceAppearance.RoughnessMap`
- **Type:** `ContentId`
- **Summary:** Determines the apparent roughness across the surface.

### `SurfaceAppearance.RoughnessMapContent`
- **Type:** `Content`
- **Tags:** Hidden

### `SurfaceAppearance.TexturePack`
- **Type:** `ContentId`
