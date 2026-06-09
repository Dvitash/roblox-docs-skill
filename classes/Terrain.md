# Terrain

**Superclass:** [BasePart](BasePart.md)

The `Terrain` class is used to create dynamically morphable environments by defining how geometry and material occupy cells, allowing for grid constraints that simulate no grid constraint.

## Tags
- NotCreatable

## Properties
### `Terrain.Decoration`
- **Type:** `boolean`
- **Tags:** NotScriptable
- **Summary:** Enables or disables terrain decoration.

### `Terrain.GrassLength`
- **Type:** `float`
- **Tags:** NotScriptable
- **Summary:** Specifies the length of animated grass.

### `Terrain.IsSmooth`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated, Deprecated
- **Summary:** Returns `true` if the game is using the smooth terrain system.

### `Terrain.MaterialColors`
- **Type:** `BinaryString`
- **Tags:** NotScriptable
- **Summary:** Represents the editor for the **Material Color** feature and cannot be edited by scripts.

### `Terrain.MaxExtents`
- **Type:** `Region3int16`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Displays the boundaries of the largest possible editable region.

### `Terrain.WaterColor`
- **Type:** `Color3`
- **Summary:** The tint of `Terrain` water.

### `Terrain.WaterReflectance`
- **Type:** `float`
- **Summary:** Controls how opaque `Terrain` water reflections are.

### `Terrain.WaterTransparency`
- **Type:** `float`
- **Summary:** The transparency of `Terrain` water.

### `Terrain.WaterWaveSize`
- **Type:** `float`
- **Summary:** Sets the maximum height of `Terrain` water waves in studs.

### `Terrain.WaterWaveSpeed`
- **Type:** `float`
- **Summary:** Sets how many times `Terrain` water waves will move up and down per minute.

## Methods
### `Terrain:AutowedgeCell(x: int, y: int, z: int) -> boolean`
- **Tags:** Deprecated
- **Summary:** Obsolete function which no longer does anything.

### `Terrain:AutowedgeCells(region: Region3int16) -> ()`
- **Tags:** Deprecated
- **Summary:** Obsolete function which no longer does anything.

### `Terrain:CellCenterToWorld(x: int, y: int, z: int) -> Vector3`
- **Summary:** Returns the world position of the center of the terrain cell.

### `Terrain:CellCornerToWorld(x: int, y: int, z: int) -> Vector3`
- **Summary:** Returns the position of the lower-left-forward corner of the grid cell.

### `Terrain:Clear() -> ()`
- **Summary:** Clears all terrain.

### `Terrain:ConvertToSmooth() -> ()`
- **Tags:** Deprecated
- **Summary:** Transforms the legacy terrain engine into the new terrain engine.

### `Terrain:CopyRegion(region: Region3int16) -> [TerrainRegion](TerrainRegion.md)`
- **Summary:** Stores a chunk of terrain into a `Class.TerrainRegion` object so it can be loaded back later.

### `Terrain:CountCells() -> int`
- **Summary:** Returns the number of non-empty cells in the terrain.

### `Terrain:FillBall(center: Vector3, radius: float, material: Material) -> ()`
- **Summary:** Fills a ball of smooth terrain in a given space.

### `Terrain:FillBlock(cframe: CFrame, size: Vector3, material: Material) -> ()`
- **Summary:** Fills a block of smooth terrain with a given location, rotation, size, and material.

### `Terrain:FillCylinder(cframe: CFrame, height: float, radius: float, material: Material) -> ()`
- **Summary:** Fills a cylinder of smooth terrain in a given space.

### `Terrain:FillRegion(region: Region3, resolution: float, material: Material) -> ()`
- **Summary:** Fills a `Datatype.Region3` space with smooth terrain.

### `Terrain:FillWedge(cframe: CFrame, size: Vector3, material: Material) -> ()`
- **Summary:** Fills a wedge-shaped volume of terrain with the given `Enum.Material`.

### `Terrain:GetCell(x: int, y: int, z: int) -> Tuple`
- **Tags:** Deprecated
- **Summary:** Returns the closest cell material from the legacy terrain engine that matches the smooth terrain voxel specified.

### `Terrain:GetMaterialColor(material: Material) -> Color3`
- **Summary:** Returns current terrain material color for specified terrain material.

### `Terrain:GetWaterCell(x: int, y: int, z: int) -> Tuple`
- **Tags:** Deprecated
- **Summary:** Returns `true` if the cell is a water cell.

### `Terrain:PasteRegion(region: [TerrainRegion](TerrainRegion.md), corner: Vector3int16, pasteEmptyCells: boolean) -> ()`
- **Summary:** Applies a chunk of terrain to the `Terrain` object.

### `Terrain:ReadVoxelChannels(region: Region3, resolution: float, channelIds: Array) -> Dictionary`
- **Tags:** CustomLuaState
- **Summary:** Returns a region of terrain voxel data in table format based on the channel names.

### `Terrain:ReadVoxels(region: Region3, resolution: float) -> Tuple`
- **Tags:** CustomLuaState
- **Summary:** Returns a certain region of smooth terrain in table format.

### `Terrain:ReplaceMaterial(region: Region3, resolution: float, sourceMaterial: Material, targetMaterial: Material) -> ()`
- **Summary:** Replaces the terrain of a material within a region with another material.

### `Terrain:SetCell(x: int, y: int, z: int, material: CellMaterial, block: CellBlock, orientation: CellOrientation) -> ()`
- **Tags:** Deprecated
- **Summary:** Sets the occupancy and material of a specific terrain voxel.

### `Terrain:SetCells(region: Region3int16, material: CellMaterial, block: CellBlock, orientation: CellOrientation) -> ()`
- **Tags:** Deprecated
- **Summary:** Sets the occupancy and material of all terrain voxels in a specific region.

### `Terrain:SetMaterialColor(material: Material, value: Color3) -> ()`
- **Summary:** Sets current terrain material color for specified terrain material.

### `Terrain:SetWaterCell(x: int, y: int, z: int, force: WaterForce, direction: WaterDirection) -> ()`
- **Tags:** Deprecated
- **Summary:** Sets the specified terrain voxel's material to water and sets its occupancy to `1`.

### `Terrain:WorldToCell(position: Vector3) -> Vector3`
- **Summary:** Returns the grid cell location that contains the position point.

### `Terrain:WorldToCellPreferEmpty(position: Vector3) -> Vector3`
- **Summary:** Returns the grid cell location that contains the position point, preferring empty grid cells when position is on a grid edge.

### `Terrain:WorldToCellPreferSolid(position: Vector3) -> Vector3`
- **Summary:** Returns the grid cell location that contains the point position, preferring non-empty grid cells when position is on a grid edge.

### `Terrain:WriteVoxelChannels(region: Region3, resolution: float, channels: Dictionary) -> ()`
- **Tags:** CustomLuaState
- **Summary:** Sets a region of terrain using a dictionary of voxel channel data.

### `Terrain:WriteVoxels(region: Region3, resolution: float, materials: Array, occupancy: Array) -> ()`
- **Tags:** CustomLuaState
- **Summary:** Sets a certain region of smooth terrain using table format.
