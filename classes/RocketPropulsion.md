# RocketPropulsion

**Superclass:** [BodyMover](BodyMover.md)

The `RocketPropulsion` class is a `BodyMover` subclass that applies force to an assembly so it follows a target, acting like `Class.BodyPosition` or `Class.BodyGyro`.

## Tags
- Deprecated

## Properties
### `RocketPropulsion.CartoonFactor`
- **Type:** `float`
- **Summary:** Determines the tendency of the assembly to face the `Class.RocketPropulsion.Target|Target`.

### `RocketPropulsion.MaxSpeed`
- **Type:** `float`
- **Summary:** Determines the maximum speed at which the assembly will move toward the `Class.RocketPropulsion.Target|Target`.

### `RocketPropulsion.MaxThrust`
- **Type:** `float`
- **Summary:** Determines the maximum amount of thrust that will be exerted to move the assembly.

### `RocketPropulsion.MaxTorque`
- **Type:** `Vector3`
- **Summary:** Determines the maximum amount of torque that may be exerted to rotate the assembly towards the `Class.RocketPropulsion.Target|Target`.

### `RocketPropulsion.Target`
- **Type:** `[BasePart](BasePart.md)`
- **Summary:** Determines the object towards which the assembly should follow/face.

### `RocketPropulsion.TargetOffset`
- **Type:** `Vector3`
- **Summary:** Determines the world offset from the `Class.RocketPropulsion.Target|Target` toward which the force/torque is exerted.

### `RocketPropulsion.TargetRadius`
- **Type:** `float`
- **Summary:** Determines the maximum distance from the `Class.RocketPropulsion.Target|Target` at which the assembly must be in order for `Class.RocketPropulsion.ReachedTarget|ReachedTarget` to be fired.

### `RocketPropulsion.ThrustD`
- **Type:** `float`
- **Summary:** Determines the dampening applied to the assembly in order to prevent it from overshooting the `Class.RocketPropulsion.Target|Target`.

### `RocketPropulsion.ThrustP`
- **Type:** `float`
- **Summary:** Determines how aggressive of a force is applied in reaching the `Class.RocketPropulsion.Target|Target`.

### `RocketPropulsion.TurnD`
- **Type:** `float`
- **Summary:** Determines the amount of dampening that to use in reaching the `Class.RocketPropulsion.Target|Target`.

### `RocketPropulsion.TurnP`
- **Type:** `float`
- **Summary:** Determines how aggressive of a torque is applied in facing the `Class.RocketPropulsion.Target|Target`.

## Methods
### `RocketPropulsion:Abort() -> ()`
- **Summary:** Causes the assembly to stop moving toward its `Class.RocketPropulsion.Target|Target`.

### `RocketPropulsion:[Fire](Fire.md)() -> ()`
- **Summary:** Causes the assembly to start moving toward its `Class.RocketPropulsion.Target|Target`.

### `RocketPropulsion:fire() -> ()`
- **Tags:** Deprecated

## Events
### `RocketPropulsion.ReachedTarget()`
- **Summary:** Fires when the assembly comes within `Class.RocketPropulsion.TargetRadius|TargetRadius` of the `Class.RocketPropulsion.Target|Target`.
