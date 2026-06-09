# VelocityMotor

**Superclass:** [JointInstance](JointInstance.md)

The VelocityMotor is a special joint type that uses `Class.Motor` and `Class.Hole` to establish a connection, requiring specific parent classes and object placement for correct functionality.

## Properties
### `VelocityMotor.CurrentAngle`
- **Type:** `float`
- **Summary:** Displays the angle that the motor is at in radians.

### `VelocityMotor.DesiredAngle`
- **Type:** `float`
- **Summary:** The desired angle to be reached. The motor will attempt to reach this angle.

### `VelocityMotor.Hole`
- **Type:** `[Hole](Hole.md)`
- **Summary:** The `Class.Hole` linked to this VelocityMotor.

### `VelocityMotor.MaxVelocity`
- **Type:** `float`
- **Summary:** The maximum amount of velocity able to be reached.
