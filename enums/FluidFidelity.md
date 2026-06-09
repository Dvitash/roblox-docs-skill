# Enum.FluidFidelity

Determines the geometric representation used to compute aerodynamic forces.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Automatic` | 0 |  | Let the physics engine select the geometric representation for aerodynamic force and torque calculations. |
| `UseCollisionGeometry` | 1 |  | Use the current collision geometry specified by `Class.TriangleMeshPart.CollisionFidelity` for aerodynamic force and torque calculations . |
| `UsePreciseGeometry` | 2 |  | Force the engine to compute aerodynamic forces and torques using a more precise geometry representation based on the original mesh. This option may increase join and replication time if used on a large scale. |

**Valid values:** `Enum.FluidFidelity.Automatic`, `Enum.FluidFidelity.UseCollisionGeometry`, `Enum.FluidFidelity.UsePreciseGeometry`
