# BodyVelocity

**Superclass:** [BodyMover](BodyMover.md)

BodyVelocity is a class that applies a force to an assembly to maintain a constant velocity, controlling the amount of force applied and limiting its magnitude.

## Tags
- Deprecated

## Properties
### `BodyVelocity.MaxForce`
- **Type:** `Vector3`
- **Summary:** Determines the limit on how much force that may be applied to each axis.

### `BodyVelocity.maxForce`
- **Type:** `Vector3`
- **Tags:** NotReplicated, Deprecated

### `BodyVelocity.P`
- **Type:** `float`
- **Summary:** Determines how aggressive of a force is applied in reaching the goal velocity.

### `BodyVelocity.Velocity`
- **Type:** `Vector3`
- **Summary:** Determines the goal velocity.

### `BodyVelocity.velocity`
- **Type:** `Vector3`
- **Tags:** NotReplicated, Deprecated

## Methods
### `BodyVelocity:GetLastForce() -> Vector3`
- **Summary:** Not implemented and will always return the `0` vector.

### `BodyVelocity:lastForce() -> Vector3`
- **Summary:** Returns the last force in the object.
