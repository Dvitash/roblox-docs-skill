# Enum.CollisionFidelity

Determines behavior of the collision hitbox for `Class.MeshPart` and `Class.PartOperation` instances.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Default` | 0 |  | Collision model uses a voxel-based convex-hull decomposition that is relatively fast but may not be highly accurate, especially for holes, doorways, and cavities in general. |
| `Hull` | 1 |  | Collision model uses the convex hull of the visual mesh. |
| `Box` | 2 |  | Collision model uses a bounding box that encompasses the visual mesh. |
| `PreciseConvexDecomposition` | 3 |  | Collison model uses a convex-hull decomposition of the visual mesh which is computed by a variation of an algorithm called HACD. This option is the most accurate representation of collision geometry for complex objects with built-in tolerances to reduce the total number of convex-hulls by compromising on accuracy when justified. |

**Valid values:** `Enum.CollisionFidelity.Default`, `Enum.CollisionFidelity.Hull`, `Enum.CollisionFidelity.Box`, `Enum.CollisionFidelity.PreciseConvexDecomposition`
