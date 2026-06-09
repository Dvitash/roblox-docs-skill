# TerrainRegion

**Superclass:** [Instance](Instance.md)

A `TerrainRegion` is a snapshot of `Class.Terrain` and can be pasted into the Terrain editor using `Class.Terrain:PasteRegion()`.

## Properties
### `TerrainRegion.IsSmooth`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated, Deprecated
- **Summary:** The state of this property shows whether or not this `Class.TerrainRegion` contains _smooth terrain_.

### `TerrainRegion.SizeInCells`
- **Type:** `Vector3`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The size of this TerrainRegion in cells.

## Methods
### `TerrainRegion:ConvertToSmooth() -> ()`
- **Tags:** Deprecated
- **Summary:** Transforms the TerrainRegion so it can be used with smooth terrain.
