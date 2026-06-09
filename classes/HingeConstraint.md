# HingeConstraint

**Superclass:** [Constraint](Constraint.md)

### HingeConstraint Constraints - **Functionality:** Constrains attachments to rotate about a single axis, constraining them so that they occupy the same position and their `X` axes point in the same direction. - **Constraints:** - **HingeConstraint:** Allows two `Class.Attachment|Attachments` to rotate about one axis, constraining them so that they both occupy the same position and their `X` axes point in the same direction. - **HingeConstraint.ActuatorType:** Determines whether rotation is…

## Properties
### `HingeConstraint.ActuatorType`
- **Type:** `ActuatorType`
- **Summary:** Sets whether the rotation of the `Class.HingeConstraint` is actuated and, if so, what kind of actuation it uses.

### `HingeConstraint.AngularResponsiveness`
- **Type:** `float`
- **Summary:** Specifies the sharpness of the servo motor in reaching the `Class.HingeConstraint.TargetAngle|TargetAngle`.

### `HingeConstraint.AngularSpeed`
- **Type:** `float`
- **Summary:** The desired angular speed a `Class.HingeConstraint` with `Class.HingeConstraint.ActuatorType|ActuatorType` set to `Enum.ActuatorType|Servo` will attempt to maintain while rotating towards its `Class.HingeConstraint.TargetAngle|TargetAngle`. Measured in radians/second.

### `HingeConstraint.AngularVelocity`
- **Type:** `float`
- **Summary:** The angular velocity a `Class.HingeConstraint` with `Class.HingeConstraint.ActuatorType|ActuatorType` set to `Enum.ActuatorType|Motor` will attempt to achieve. Measured in radians/second.

### `HingeConstraint.CurrentAngle`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The current angle of the `Class.HingeConstraint`.

### `HingeConstraint.LimitsEnabled`
- **Type:** `boolean`
- **Summary:** Sets whether the `Class.HingeConstraint` will limit the range of rotation.

### `HingeConstraint.LowerAngle`
- **Type:** `float`
- **Summary:** The minimum rotation angle the `Class.HingeConstraint` will allow if `Class.HingeConstraint.LimitsEnabled|LimitsEnabled` is true.

### `HingeConstraint.MotorMaxAcceleration`
- **Type:** `float`
- **Summary:** The maximum angular acceleration a `Class.HingeConstraint` with `Class.HingeConstraint.ActuatorType|ActuatorType` set to `Enum.ActuatorType|Motor` can apply to achieve its `Class.HingeConstraint.AngularVelocity|AngularVelocity`. Measured in radians/second&sup2;.

### `HingeConstraint.MotorMaxTorque`
- **Type:** `float`
- **Summary:** The maximum torque a `Class.HingeConstraint` with `Class.HingeConstraint.ActuatorType|ActuatorType` set to `Enum.ActuatorType|Motor` can apply when trying to reach its desired `Class.HingeConstraint.AngularVelocity|AngularVelocity`.

### `HingeConstraint.Radius`
- **Type:** `float`
- **Summary:** The visualized radius of the `Class.HingeConstraint`.

### `HingeConstraint.Restitution`
- **Type:** `float`
- **Summary:** How elastic `Class.Attachment` connected by a `Class.HingeConstraint` will be when they reach the end of the range when `Class.HingeConstraint.LimitsEnabled|LimitsEnabled` is true. Constrained between 0 and 1.

### `HingeConstraint.ServoMaxTorque`
- **Type:** `float`
- **Summary:** The maximum torque a `Class.HingeConstraint` with `Class.HingeConstraint.ActuatorType|ActuatorType` set to `Enum.ActuatorType|Servo` can apply when trying to reach its desired `Class.HingeConstraint.TargetAngle|TargetAngle`.

### `HingeConstraint.SoftlockServoUponReachingTarget`
- **Type:** `boolean`
- **Tags:** Deprecated

### `HingeConstraint.TargetAngle`
- **Type:** `float`
- **Summary:** The target angle a `Class.HingeConstraint` will attempt to rotate to if its `Class.HingeConstraint.ActuatorType|ActuatorType` is set to `Enum.ActuatorType|Servo`. Measured in degrees.

### `HingeConstraint.UpperAngle`
- **Type:** `float`
- **Summary:** The maximum rotation angle the `Class.HingeConstraint` will allow if `Class.HingeConstraint.LimitsEnabled|LimitsEnabled` is true.
