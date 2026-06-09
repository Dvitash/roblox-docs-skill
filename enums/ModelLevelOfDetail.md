# Enum.ModelLevelOfDetail

Controls the level of detail for `Class.Model|Models` in experiences with instance streaming enabled.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Automatic` | 0 |  | Default behavior, currently equivalent to **Disabled**. |
| `StreamingMesh` | 1 |  | A lower resolution "imposter" mesh (colored, coarse mesh that wraps around all child parts of the model) renders outside the streaming radius. |
| `Disabled` | 2 |  | A lower resolution mesh will not be displayed. |
| `SLIM` | 4 |  | A Scalable Lightweight Interactive Model, or SLIM, model (a composite of all child parts of the model) renders at progressively lower resolutions at distances based on the streaming radius. Greatly improves visual quality over `StreamingMesh`. |

**Valid values:** `Enum.ModelLevelOfDetail.Automatic`, `Enum.ModelLevelOfDetail.StreamingMesh`, `Enum.ModelLevelOfDetail.Disabled`, `Enum.ModelLevelOfDetail.SLIM`
