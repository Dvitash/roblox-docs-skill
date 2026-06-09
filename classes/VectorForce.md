# VectorForce

**Superclass:** [Constraint](Constraint.md)

The `VectorForce` class is a constraint that applies constant force to an assembly based on the direction and strength of the force relative to an attachment or world coordinate system.

## Properties
### `VectorForce.ApplyAtCenterOfMass`
- **Type:** `boolean`
- **Summary:** Whether force is applied at the center of mass of the parent assembly.

### `VectorForce.Force`
- **Type:** `Vector3`
- **Summary:** The strength and direction of the force.

### `VectorForce.RelativeTo`
- **Type:** `ActuatorRelativeTo`
- **Summary:** The `Datatype.CFrame` in which the force is expressed.
