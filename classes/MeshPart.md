# MeshPart

**Superclass:** [TriangleMeshPart](TriangleMeshPart.md)

The `MeshPart` class is a form of `BaseParts` that includes a physically simulated custom mesh, and it is parented to `Class.BaseParts`.

## Properties
### `MeshPart.DoubleSided`
- **Type:** `boolean`
- **Summary:** Determines whether to render both faces of polygons in the mesh.

### `MeshPart.HasJointOffset`
- **Type:** `boolean`
- **Tags:** Hidden, Deprecated

### `MeshPart.HasSkinnedMesh`
- **Type:** `boolean`
- **Tags:** Hidden

### `MeshPart.JointOffset`
- **Type:** `Vector3`
- **Tags:** Hidden, Deprecated

### `MeshPart.MeshContent`
- **Type:** `Content`
- **Summary:** The mesh that is displayed on the `Class.MeshPart`. Supports [asset URIs](../../../projects/assets/index.md#asset-uris) and `Class.EditableMesh` objects.

### `MeshPart.MeshId`
- **Type:** `ContentId`
- **Summary:** The [asset URIs](../../../projects/assets/index.md#asset-uris) of the mesh that is displayed on the `Class.MeshPart`. Reads and writes to `Class.MeshPart.MeshContent|MeshContent`.

### `MeshPart.RenderFidelity`
- **Type:** `RenderFidelity`
- **Tags:** NotReplicated
- **Summary:** The level of detail used to render the `Class.MeshPart`.

### `MeshPart.TextureContent`
- **Type:** `Content`
- **Summary:** The texture applied to the `Class.MeshPart`. Supports [asset URIs](../../../projects/assets/index.md#asset-uris) and `Class.EditableImage` objects.

### `MeshPart.TextureID`
- **Type:** `ContentId`
- **Summary:** The texture applied to the `Class.MeshPart`. Reads and writes to `Class.MeshPart.TextureContent|TextureContent`.

## Methods
### `MeshPart:ApplyMesh(meshPart: [Instance](Instance.md)) -> ()`
- **Summary:** Overwrites the `Class.MeshPart.MeshContent|MeshContent`, `Class.MeshPart.TextureContent|TextureContent`, and collision geometry properties of this `Class.MeshPart` from the given source `meshPart`.
