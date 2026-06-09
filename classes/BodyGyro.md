# BodyGyro

**Superclass:** [BodyMover](BodyMover.md)

Applies a torque to maintain a constant angular displacement or orientation, allowing for the creation of assemblies that point in a specific direction.

## Tags
- Deprecated

## Properties
### `BodyGyro.CFrame`
- **Type:** `CFrame`
- **Summary:** Determines the target orientation (translational component ignored).

### `BodyGyro.cframe`
- **Type:** `CFrame`
- **Tags:** NotReplicated, Deprecated

### `BodyGyro.D`
- **Type:** `float`
- **Summary:** Determines the amount of dampening to use in reaching the goal `Class.BodyGyro.CFrame|CFrame`.

### `BodyGyro.MaxTorque`
- **Type:** `Vector3`
- **Summary:** Determines the limit on how much torque that may be applied to each axis.

### `BodyGyro.maxTorque`
- **Type:** `Vector3`
- **Tags:** NotReplicated, Deprecated

### `BodyGyro.P`
- **Type:** `float`
- **Summary:** Determines how aggressive of a torque is applied in reaching the goal orientation.
