# AirController

**Superclass:** [ControllerBase](ControllerBase.md)

AirController is a class representing an Air Controller, which handles balancing and turning. It includes properties for maximum torque and angular speed, as well as methods for maintaining or applying angular momentum and linear velocity.

## Properties
### `AirController.BalanceMaxTorque`
- **Type:** `float`
- **Summary:** The maximum torque the character can use to remain balanced upright.

### `AirController.BalanceSpeed`
- **Type:** `float`
- **Summary:** The maximum angular speed used to align the character upright.

### `AirController.MaintainAngularMomentum`
- **Type:** `boolean`
- **Summary:** Determines whether angular momentum is preserved when input has stopped.

### `AirController.MaintainLinearMomentum`
- **Type:** `boolean`
- **Summary:** Determines whether linear momentum is preserved when input has stopped.

### `AirController.MoveMaxForce`
- **Type:** `float`
- **Summary:** The maximum force that can be applied on the `Class.ControllerManager.RootPart` for moving in the `Class.ControllerManager.MovingDirection`.

### `AirController.TurnMaxTorque`
- **Type:** `float`
- **Summary:** The maximum torque that can be applied on the `Class.ControllerManager.RootPart` for turning towards the `Class.ControllerManager.FacingDirection`.

### `AirController.TurnSpeedFactor`
- **Type:** `float`
- **Summary:** The value multiplied by the `Class.ControllerManager.BaseTurnSpeed`.
