# ClimbController

**Superclass:** [ControllerBase](ControllerBase.md)

The `ClimbController` class is a controller for managing the climb speed and balance of the root part, along with methods for controlling acceleration time and force.

## Properties
### `ClimbController.AccelerationTime`
- **Type:** `float`
- **Summary:** The amount of time taken to reach the desired climb velocity from 0.

### `ClimbController.BalanceMaxTorque`
- **Type:** `float`
- **Summary:** The maximum torque used to keep the `Class.ControllerManager.RootPart` aligned upright and aligned to the climbed surface.

### `ClimbController.BalanceSpeed`
- **Type:** `float`
- **Summary:** The maximum angular speed used to align the `Class.ControllerManager.RootPart` upright and with the climbed surface.

### `ClimbController.MoveMaxForce`
- **Type:** `float`
- **Summary:** The maximum force used by the climbing "motor" to move the `Class.ControllerManager.RootPart` or keep it stationary.
