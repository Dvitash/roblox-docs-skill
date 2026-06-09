# TriangleMeshPart

**Superclass:** [BasePart](BasePart.md)

TriangleMeshPart is an abstract class that manages physical geometry properties for PartOperations and MeshParts, inheriting from `Class.MeshPart` and `Class.PartOperation`. It provides methods to manage collision fidelity and fluid fidelity.

## Tags
- NotCreatable

## Properties
### `TriangleMeshPart.CollisionFidelity`
- **Type:** `CollisionFidelity`
- **Tags:** NotReplicated
- **Summary:** Determines the level of detail the part's physics will adhere to its mesh.

### `TriangleMeshPart.FluidFidelity`
- **Type:** `FluidFidelity`
- **Tags:** NotReplicated
- **Summary:** Determines the geometric representation used to compute aerodynamic forces and torques.

### `TriangleMeshPart.MeshSize`
- **Type:** `Vector3`
- **Tags:** ReadOnly, NotReplicated
