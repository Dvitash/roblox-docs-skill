# TorsionSpringConstraint

**Superclass:** [Constraint](Constraint.md)

The `TorsionSpringConstraint` is a rotational spring that opposes angular motion between two axes, applying a torque based on an angle and velocity. It includes settings for damping, stiffness, limiting angles, and elasticity.

## Properties
### `TorsionSpringConstraint.Coils`
- **Type:** `float`
- **Summary:** The number of coils visualized for the constraint.

### `TorsionSpringConstraint.CurrentAngle`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The current angle, in degrees, of the limiting cone.

### `TorsionSpringConstraint.Damping`
- **Type:** `float`
- **Summary:** Damping constant for the `Class.TorsionSpringConstraint`. Multiplied to the velocity of the constraint's `Class.Attachment|Attachments` to reduce the spring force applied.

### `TorsionSpringConstraint.LimitEnabled`
- **Type:** `boolean`
- **Tags:** Hidden, Deprecated

### `TorsionSpringConstraint.LimitsEnabled`
- **Type:** `boolean`
- **Summary:** Limits the relative angular motion of the secondary axes of attachments through a cone constraint.

### `TorsionSpringConstraint.MaxAngle`
- **Type:** `float`
- **Summary:** The maximum angle of the constraint's limiting cone.

### `TorsionSpringConstraint.MaxTorque`
- **Type:** `float`
- **Summary:** The maximum allowable torque provided by the torsion spring.

### `TorsionSpringConstraint.Radius`
- **Type:** `float`
- **Summary:** The visualization radius of the spring.

### `TorsionSpringConstraint.Restitution`
- **Type:** `float`
- **Summary:** The restitution coefficient of the cone constraint.

### `TorsionSpringConstraint.Stiffness`
- **Type:** `float`
- **Summary:** The torsional stiffness of the spring.
