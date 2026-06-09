# WrapTextureTransfer

**Superclass:** [Instance](Instance.md)

WrapTextureTransfer is a class that allows wrapping `Class.Decal` onto `Class.MeshPart` based on the `Class.WrapTarget` cage mesh, which can reuse textures for various MeshParts with different layouts.

## Properties
### `WrapTextureTransfer.ReferenceCageMeshContent`
- **Type:** `Content`
- **Summary:** An optional reference mesh used for pruning and validating the target cage.

### `WrapTextureTransfer.UVMaxBound`
- **Type:** `Vector2`
- **Summary:** Determines the maximum bound of the UV space to include in the transfer.

### `WrapTextureTransfer.UVMinBound`
- **Type:** `Vector2`
- **Summary:** Determines the minimum bound of the UV space to include in the transfer.
