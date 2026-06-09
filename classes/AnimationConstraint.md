# AnimationConstraint

**Superclass:** [Constraint](Constraint.md)

AnimationConstraint is a class used to align `Class.BaseParts` with an animateable kinematic or joint, enforcing a specific offset based on the `Transform` property.

## Properties
### `AnimationConstraint.IsKinematic`
- **Type:** `boolean`
- **Summary:** Toggles whether the constraint is kinematic or physically simulated.

### `AnimationConstraint.MaxForce`
- **Type:** `float`
- **Summary:** Maximum force magnitude the constraint can apply to achieve its goal.

### `AnimationConstraint.MaxTorque`
- **Type:** `float`
- **Summary:** Maximum torque the constraint can apply to reach its goal.

### `AnimationConstraint.Transform`
- **Type:** `CFrame`
- **Summary:** Describes the current animation offset of the constraint joint.
