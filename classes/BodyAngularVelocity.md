# BodyAngularVelocity

**Superclass:** [BodyMover](BodyMover.md)

Applies a torque to maintain a constant angular velocity, which is the rotational counterpart of `Class.BodyVelocity`.

## Tags
- Deprecated

## Properties
### `BodyAngularVelocity.AngularVelocity`
- **Type:** `Vector3`
- **Summary:** Determines the axis of rotation (direction) and the rotational velocity (magnitude) in radians/s.

### `BodyAngularVelocity.angularvelocity`
- **Type:** `Vector3`
- **Tags:** NotReplicated, Deprecated

### `BodyAngularVelocity.MaxTorque`
- **Type:** `Vector3`
- **Summary:** Determines the limit of torque that may be exerted on each world axis.

### `BodyAngularVelocity.maxTorque`
- **Type:** `Vector3`
- **Tags:** NotReplicated, Deprecated
- **Summary:** Determines how much force can be applied to each axis.

### `BodyAngularVelocity.P`
- **Type:** `float`
- **Summary:** Determines how aggressive of a torque is applied in reaching the goal angular velocity.
