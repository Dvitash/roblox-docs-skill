# GroundController

**Superclass:** [ControllerBase](ControllerBase.md)

This file contains methods for controlling the ground controller, including acceleration, deceleration, friction, and balancing. These methods are inherited from `ControllerBase` and have specific properties and behaviors based on the character's state and distance to the ground.

## Properties
### `GroundController.AccelerationTime`
- **Type:** `float`
- **Summary:** Estimated time taken to reach the desired speed.

### `GroundController.BalanceMaxTorque`
- **Type:** `float`
- **Summary:** The maximum torque used to keep the `Class.ControllerManager.RootPart` aligned upright.

### `GroundController.BalanceSpeed`
- **Type:** `float`
- **Summary:** The maximum angular speed used to align the `Class.ControllerManager.RootPart` upright.

### `GroundController.DecelerationTime`
- **Type:** `float`
- **Summary:** Estimated time taken to reach a complete stop from full speed.

### `GroundController.Friction`
- **Type:** `float`
- **Summary:** The coefficient of friction of the character on the ground.

### `GroundController.FrictionWeight`
- **Type:** `float`
- **Summary:** Amount the character's friction is weighed against the ground friction.

### `GroundController.GroundOffset`
- **Type:** `float`
- **Summary:** The target distance above the ground to keep the `Class.ControllerManager.RootPart` at.

### `GroundController.TurnSpeedFactor`
- **Type:** `float`
- **Summary:** The value multiplied by the `Class.ControllerManager.BaseTurnSpeed`.
