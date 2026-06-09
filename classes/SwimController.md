# SwimController

**Superclass:** [ControllerBase](ControllerBase.md)

SwimController is a class representing the controller for controlling the swim speed and pitch. It contains methods for determining maximum torque, pitch speed, and roll speed, along with associated safety and simulation considerations.

## Properties
### `SwimController.PitchMaxTorque`
- **Type:** `float`
- **Summary:** The maximum torque used to rotate to the desired pitch.

### `SwimController.PitchSpeedFactor`
- **Type:** `float`
- **Summary:** Multiplied by `Class.ControllerManager.BaseTurnSpeed` to determine the maximum angular velocity for pitch.

### `SwimController.RollMaxTorque`
- **Type:** `float`
- **Summary:** The maximum torque applied to rotate to the desired roll.

### `SwimController.RollSpeedFactor`
- **Type:** `float`
- **Summary:** Multiplied by `Class.ControllerManager.BaseTurnSpeed` to determine the maximum angular velocity for roll.
