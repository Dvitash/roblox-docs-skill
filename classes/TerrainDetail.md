# TerrainDetail

**Superclass:** [Instance](Instance.md)

TerrainDetail is a class that determines the appearance of terrain faces based on material properties. It inherits from `Class.MaterialVariant` and overrides the terrain appearance for specific faces.

## Properties
### `TerrainDetail.ColorMap`
- **Type:** `ContentId`
- **Summary:** Determines the color of the surface.

### `TerrainDetail.ColorMapContent`
- **Type:** `Content`
- **Summary:** Determines the color of the surface. Only supports asset URIs as textures.

### `TerrainDetail.EmissiveMaskContent`
- **Type:** `Content`
- **Summary:** Determines the emissivity across the surface.

### `TerrainDetail.EmissiveStrength`
- **Type:** `float`
- **Summary:** Determines the strength of emissive contribution.

### `TerrainDetail.EmissiveTint`
- **Type:** `Color3`
- **Summary:** Determines the tinting color for emissive contribution.

### `TerrainDetail.Face`
- **Type:** `TerrainFace`
- **Summary:** The face this TerrainDetail overrides.

### `TerrainDetail.MaterialPattern`
- **Type:** `MaterialPattern`
- **Summary:** Determines texture tiling method.

### `TerrainDetail.MetalnessMap`
- **Type:** `ContentId`
- **Summary:** Determines which parts of the surface are metal and are non-metal.

### `TerrainDetail.MetalnessMapContent`
- **Type:** `Content`
- **Summary:** Determines which parts of the surface are metal and are non-metal. Only supports asset URIs as textures.

### `TerrainDetail.NormalMap`
- **Type:** `ContentId`
- **Summary:** Modifies the lighting of the surface by adding bumps, dents, cracks, and curves without adding more polygons.

### `TerrainDetail.NormalMapContent`
- **Type:** `Content`
- **Summary:** Modifies the lighting of the surface by adding bumps, dents, cracks, and curves without adding more polygons. Only supports asset URIs as textures.

### `TerrainDetail.RoughnessMap`
- **Type:** `ContentId`
- **Summary:** Determines the apparent roughness across the surface.

### `TerrainDetail.RoughnessMapContent`
- **Type:** `Content`
- **Summary:** Determines the apparent roughness across the surface. Only supports asset URIs as textures.

### `TerrainDetail.StudsPerTile`
- **Type:** `float`
- **Summary:** Determines the scale of textures.
