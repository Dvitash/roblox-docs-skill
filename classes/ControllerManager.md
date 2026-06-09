# ControllerManager

**Superclass:** [Instance](Instance.md)

The `ControllerManager` class manages simulated motion control for `Class.ControllerManager.RootPart`. It allows users to build physics-based character controllers by setting the `ControllerManager` instance.

## Properties
### `ControllerManager.ActiveController`
- **Type:** `[ControllerBase](ControllerBase.md)`
- **Summary:** The `Class.ControllerBase` that is set to be activated on the character.

### `ControllerManager.BaseMoveSpeed`
- **Type:** `float`
- **Summary:** The base linear movement speed used by all controllers.

### `ControllerManager.BaseTurnSpeed`
- **Type:** `float`
- **Summary:** The base angular turning speed used by all controllers.

### `ControllerManager.ClimbSensor`
- **Type:** `[ControllerSensor](ControllerSensor.md)`
- **Summary:** A reference to the sensor data used while a `Class.ClimbController` is active.

### `ControllerManager.FacingDirection`
- **Type:** `Vector3`
- **Summary:** The unit vector describing the desired direction to face.

### `ControllerManager.GroundSensor`
- **Type:** `[ControllerSensor](ControllerSensor.md)`
- **Summary:** A reference to the sensor data used while a `Class.GroundController` is active.

### `ControllerManager.MovingDirection`
- **Type:** `Vector3`
- **Summary:** The vector describing the desired direction to move in.

### `ControllerManager.RootPart`
- **Type:** `[BasePart](BasePart.md)`
- **Summary:** The `Class.BasePart` where the controller's forces and torques are applied.

### `ControllerManager.UpDirection`
- **Type:** `Vector3`
