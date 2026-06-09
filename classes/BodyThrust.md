# BodyThrust

**Superclass:** [BodyMover](BodyMover.md)

BodyThrust is a class that applies a constant force to an object at a specific point relative to its assembly. It allows for dynamic application of torque or angular velocity, and is deprecated in favor of `Class.BodyAngularVelocity` and `Class.BodyGyro`.

## Tags
- Deprecated

## Properties
### `BodyThrust.Force`
- **Type:** `Vector3`
- **Summary:** Determines the amount of force exerted on each axis relative to the assembly.

### `BodyThrust.force`
- **Type:** `Vector3`
- **Tags:** NotReplicated, Deprecated

### `BodyThrust.Location`
- **Type:** `Vector3`
- **Summary:** Determines the relative position where the `Class.BodyThrust.Force|Force` is exerted.

### `BodyThrust.location`
- **Type:** `Vector3`
- **Tags:** NotReplicated, Deprecated
