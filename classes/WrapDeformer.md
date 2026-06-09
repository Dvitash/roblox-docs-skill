# WrapDeformer

**Superclass:** [BaseWrap](BaseWrap.md)

WrapDeformer is a class that allows for the real-time deformation of `Class.MeshPart` geometry by using a low-resolution cage mesh with a `Class.WrapTarget`.

## Methods
### `WrapDeformer:CreateEditableMeshAsync() -> [EditableMesh](EditableMesh.md)`
- **Tags:** Yields
- **Summary:** Returns an `Class.EditableMesh` (currently unskinned) equivalent to the deformed parent mesh.

### `WrapDeformer:GetDeformedCFrameAsync(originalCFrame: CFrame) -> CFrame`
- **Tags:** Yields
- **Summary:** Returns a `Datatype.CFrame` deformed comparably to the `Class.MeshPart`.

### `WrapDeformer:SetCageMeshContent(content: Content, cageOrigin: CFrame?) -> ()`
- **Summary:** Sets the cage mesh used to deform against a sibling `Class.WrapTarget` cage mesh.
