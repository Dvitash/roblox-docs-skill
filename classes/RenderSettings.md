# RenderSettings

**Superclass:** [Instance](Instance.md)

The `RenderSettings` class is a singleton class in Roblox Studio settings that allows developers to debug components of Roblox's graphics engine. It provides various options for managing scene updates and quality levels.

## Tags
- NotCreatable
- Service
- NotReplicated
- NotBrowsable

## Properties
### `RenderSettings.AutoFRMLevel`
- **Type:** `int`
- **Summary:** Sets the starting quality level of the framerate manager.

### `RenderSettings.EagerBulkExecution`
- **Type:** `boolean`
- **Summary:** Whether all scene updates will be given an unlimited budget, regardless of how computationally expensive it may be.

### `RenderSettings.EditQualityLevel`
- **Type:** `QualityLevel`
- **Summary:** Sets the graphics quality level in Roblox Studio.

### `RenderSettings.Enable VR Mode`
- **Type:** `boolean`

### `RenderSettings.EnableFRM`
- **Type:** `boolean`
- **Tags:** Hidden, NotReplicated
- **Summary:** Toggles the enabled state of the framerate manager.

### `RenderSettings.ExportMergeByMaterial`
- **Type:** `boolean`
- **Summary:** Sets whether materials should be generated per part, or per unique appearance in Roblox's exporter.

### `RenderSettings.FrameRateManager`
- **Type:** `FramerateManagerMode`
- **Summary:** Specifies the behavior of the framerate manager.

### `RenderSettings.GraphicsMode`
- **Type:** `GraphicsMode`
- **Summary:** The graphics API that Roblox will use on startup.

### `RenderSettings.MeshCacheSize`
- **Type:** `int`
- **Summary:** The size in bytes of the mesh cache.

### `RenderSettings.MeshPartDetailLevel`
- **Type:** `MeshPartDetailLevel`
- **Summary:** Studio only. Used to visually verify the quality of `Class.MeshPart|MeshParts` at lower level of detail at close range.

### `RenderSettings.QualityLevel`
- **Type:** `QualityLevel`
- **Summary:** Controls the quality level in Roblox Studio.

### `RenderSettings.ReloadAssets`
- **Type:** `boolean`
- **Summary:** Whether Roblox Studio will automatically reload changes that are made to files in Roblox's `content` folder.

### `RenderSettings.RenderCSGTrianglesDebug`
- **Type:** `boolean`
- **Summary:** Whether a wireframe of polygons will be shown on all `Class.PartOperation` objects.

### `RenderSettings.ShowBoundingBoxes`
- **Type:** `boolean`
- **Summary:** Whether bounding boxes are rendered around each individual rendered entity in the scene.

### `RenderSettings.ViewMode`
- **Type:** `ViewMode`

## Methods
### `RenderSettings:GetMaxQualityLevel() -> int`
- **Summary:** Returns the maximum quality level.
