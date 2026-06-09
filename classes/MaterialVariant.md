# MaterialVariant

**Superclass:** [Instance](Instance.md)

MaterialVariant is a class that allows users to define the appearance of materials in an experience. It can expand material variety by setting properties like `name` and `AlphaMode`.

## Properties
### `MaterialVariant.AlphaMode`
- **Type:** `AlphaMode`
- **Tags:** NotBrowsable
- **Summary:** Determines how the alpha channel of the `Class.MaterialVariant.ColorMap` is used.

### `MaterialVariant.BaseMaterial`
- **Type:** `Material`
- **Summary:** Category Material this variant belongs to.

### `MaterialVariant.ColorMap`
- **Type:** `ContentId`
- **Summary:** Determines the color of the surface.

### `MaterialVariant.ColorMapContent`
- **Type:** `Content`
- **Summary:** Determines the color of the surface. Only supports asset URIs as textures.

### `MaterialVariant.CustomPhysicalProperties`
- **Type:** `PhysicalProperties`

### `MaterialVariant.EmissiveMaskContent`
- **Type:** `Content`
- **Summary:** Determines the emissivity across the surface.

### `MaterialVariant.EmissiveStrength`
- **Type:** `float`
- **Summary:** Determines the strength of emissive contribution.

### `MaterialVariant.EmissiveTint`
- **Type:** `Color3`
- **Summary:** Determines the tinting color for emissive contribution.

### `MaterialVariant.MaterialPattern`
- **Type:** `MaterialPattern`
- **Summary:** Determines texture tiling method.

### `MaterialVariant.MetalnessMap`
- **Type:** `ContentId`
- **Summary:** Determines which parts of the surface are metal and are non-metal.

### `MaterialVariant.MetalnessMapContent`
- **Type:** `Content`
- **Summary:** Determines which parts of the surface are metal and are non-metal. Only supports asset URIs as textures.

### `MaterialVariant.NormalMap`
- **Type:** `ContentId`
- **Summary:** Modifies the lighting of the surface by adding bumps, dents, cracks, and curves without adding more polygons.

### `MaterialVariant.NormalMapContent`
- **Type:** `Content`
- **Summary:** Modifies the lighting of the surface by adding bumps, dents, cracks, and curves without adding more polygons. Only supports asset URIs as textures.

### `MaterialVariant.RoughnessMap`
- **Type:** `ContentId`
- **Summary:** Determines the apparent roughness across the surface.

### `MaterialVariant.RoughnessMapContent`
- **Type:** `Content`
- **Summary:** Determines the apparent roughness across the surface. Only supports asset URIs as textures.

### `MaterialVariant.StudsPerTile`
- **Type:** `float`
- **Summary:** Determines the scale of textures.
