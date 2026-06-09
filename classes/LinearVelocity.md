# LinearVelocity

**Superclass:** [Constraint](Constraint.md)

- **LinearVelocity Constraints**

## Properties
### `LinearVelocity.ForceLimitMode`
- **Type:** `ForceLimitMode`
- **Summary:** Determines how the constraint force will be limited.

### `LinearVelocity.ForceLimitsEnabled`
- **Type:** `boolean`
- **Summary:** Determines if the constraint force will be limited or if the physics solver can apply an unlimited force to achieve the target velocity.

### `LinearVelocity.LineDirection`
- **Type:** `Vector3`
- **Summary:** The normalized `Datatype.Vector3` direction for constraining the velocity along a line.

### `LinearVelocity.LineVelocity`
- **Type:** `float`
- **Summary:** Float value of the velocity when `Class.LinearVelocity.VelocityConstraintMode|VelocityConstraintMode` is set to `Enum.VelocityConstraintMode|Line`.

### `LinearVelocity.MaxAxesForce`
- **Type:** `Vector3`
- **Summary:** Maximum force along each axis that the constraint can apply to achieve the vector velocity. Only used if `Class.LinearVelocity.ForceLimitsEnabled|ForceLimitsEnabled` is `true`, `Class.LinearVelocity.ForceLimitMode|ForceLimitMode` is `Enum.ForceLimitMode|PerAxis`, and `Class.LinearVelocity.VelocityConstraintMode|VelocityConstraintMode` is `Enum.VelocityConstraintMode|Vector`.

### `LinearVelocity.MaxForce`
- **Type:** `float`
- **Summary:** Maximum magnitude of the force vector the constraint can apply.

### `LinearVelocity.MaxPlanarAxesForce`
- **Type:** `Vector2`
- **Summary:** Maximum force along each axis that the constraint can apply to achieve the plane velocity. Only used if `Class.LinearVelocity.ForceLimitsEnabled|ForceLimitsEnabled` is `true`, `Class.LinearVelocity.ForceLimitMode|ForceLimitMode` is `Enum.ForceLimitMode|PerAxis`, and `Class.LinearVelocity.VelocityConstraintMode|VelocityConstraintMode` is `Enum.VelocityConstraintMode|Plane`.

### `LinearVelocity.PlaneVelocity`
- **Type:** `Vector2`
- **Summary:** `Datatype.Vector2` value of the velocity in each tangent direction of the plane.

### `LinearVelocity.PrimaryTangentAxis`
- **Type:** `Vector3`
- **Summary:** The primary axis in the plane, when `Class.LinearVelocity.VelocityConstraintMode|VelocityConstraintMode` is set to `Enum.VelocityConstraintMode|Plane`.

### `LinearVelocity.ReactionForceEnabled`
- **Type:** `boolean`

### `LinearVelocity.RelativeTo`
- **Type:** `ActuatorRelativeTo`
- **Summary:** Sets the `Enum.ActuatorRelativeTo` property for the constraint.

### `LinearVelocity.SecondaryTangentAxis`
- **Type:** `Vector3`
- **Summary:** The secondary axis in the plane, when `Class.LinearVelocity.VelocityConstraintMode|VelocityConstraintMode` is set to `Enum.VelocityConstraintMode|Plane`.

### `LinearVelocity.VectorVelocity`
- **Type:** `Vector3`
- **Summary:** `Datatype.Vector3` velocity value when `Class.LinearVelocity.VelocityConstraintMode|VelocityConstraintMode` is set to `Enum.VelocityConstraintMode|Vector`.

### `LinearVelocity.VelocityConstraintMode`
- **Type:** `VelocityConstraintMode`
- **Summary:** The mode of the constraint.
