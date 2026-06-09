# BodyPosition

**Superclass:** [BodyMover](BodyMover.md)

The `BodyPosition` class is a class that applies a force to an assembly to maintain a constant position, controlling dampening, and determining the maximum force applied.

## Tags
- Deprecated

## Properties
### `BodyPosition.D`
- **Type:** `float`
- **Summary:** Determines the amount of dampening to use in reaching the goal `Class.BodyPosition.Position|Position`.

### `BodyPosition.MaxForce`
- **Type:** `Vector3`
- **Summary:** Determines the limit on how much force that may be applied to each axis.

### `BodyPosition.maxForce`
- **Type:** `Vector3`
- **Tags:** NotReplicated, Deprecated

### `BodyPosition.P`
- **Type:** `float`
- **Summary:** Determines how aggressive of a force is applied in reaching the goal position.

### `BodyPosition.Position`
- **Type:** `Vector3`
- **Summary:** Determines the goal position towards which force will be applied.

### `BodyPosition.position`
- **Type:** `Vector3`
- **Tags:** NotReplicated, Deprecated

## Methods
### `BodyPosition:GetLastForce() -> Vector3`
- **Summary:** Returns the last force in the object.

### `BodyPosition:lastForce() -> Vector3`
- **Tags:** Deprecated
- **Summary:** Returns the last force in the object.

## Events
### `BodyPosition.ReachedTarget()`
- **Summary:** Fired when the Parent of the BodyPosition reaches the desired `Class.BodyPosition.Position` (within .1 studs). Once this event fires it will not fire again until `Class.BodyPosition.Position` is updated.
