# Motor

**Superclass:** [JointInstance](JointInstance.md)

Moves a movable `Class.JointInstance` between two parts in the Motor class.

## Properties
### `Motor.CurrentAngle`
- **Type:** `float`
- **Tags:** NotReplicated
- **Summary:** Displays the current rotation of the motor in radians.

### `Motor.DesiredAngle`
- **Type:** `float`
- **Summary:** The desired angle to turn the motor to in radians.

### `Motor.MaxVelocity`
- **Type:** `float`
- **Summary:** The maximum velocity the motor can use to reach `Class.Motor.DesiredAngle` measured in radians per physics frame (1/60th of a second).

## Methods
### `Motor:SetDesiredAngle(value: float) -> ()`
- **Summary:** Sets `Class.Motor.DesiredAngle` of the motor.
