# SlidingBallConstraint

**Superclass:** [Constraint](Constraint.md)

The `SlidingBallConstraint` class defines a base class for constraints that allow attachments to slide along an axis but not rotate, including `Class.PrismaticConstraint` and `Class.CylindricalConstraint`.

## Tags
- NotCreatable

## Properties
### `SlidingBallConstraint.ActuatorType`
- **Type:** `ActuatorType`
- **Summary:** Sets whether the translation of the `Class.SlidingBallConstraint` is actuated and, if so, what kind of actuation.

### `SlidingBallConstraint.CurrentPosition`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The current offset between the constraint's `Class.Attachment|Attachments`.

### `SlidingBallConstraint.LimitsEnabled`
- **Type:** `boolean`
- **Summary:** Sets whether the `Class.SlidingBallConstraint` will limit the range of translation.

### `SlidingBallConstraint.LinearResponsiveness`
- **Type:** `float`
- **Summary:** Specifies the "sharpness" of the linear servo motor in reaching the `Class.SlidingBallConstraint.TargetPosition|TargetPosition`.

### `SlidingBallConstraint.LowerLimit`
- **Type:** `float`
- **Summary:** The lower positional limit along the **X** axis of `Class.Constraint.Attachment0|Attachment0` if `Class.SlidingBallConstraint.LimitsEnabled|LimitsEnabled` is true.

### `SlidingBallConstraint.MotorMaxAcceleration`
- **Type:** `float`
- **Summary:** The constraint's maximum acceleration when `Class.SlidingBallConstraint.ActuatorType|ActuatorType` is set to `Enum.ActuatorType|Motor` as the constraint attempts to reach its desired `Class.SlidingBallConstraint.Velocity|Velocity`.

### `SlidingBallConstraint.MotorMaxForce`
- **Type:** `float`
- **Summary:** The constraint's maximum force when `Class.SlidingBallConstraint.ActuatorType|ActuatorType` is set to `Enum.ActuatorType|Motor`, as the constraint attempts to reach its desired `Class.SlidingBallConstraint.Velocity|Velocity`.

### `SlidingBallConstraint.Restitution`
- **Type:** `float`
- **Summary:** The elasticity of the constraint's `Class.Attachment|Attachments` when they reach the end of the range specified by `Class.SlidingBallConstraint.UpperLimit|UpperLimit` and `Class.SlidingBallConstraint.LowerLimit|LowerLimit`, assuming `Class.SlidingBallConstraint.LimitsEnabled|LimitsEnabled` is set to true.

### `SlidingBallConstraint.ServoMaxForce`
- **Type:** `float`
- **Summary:** The constraint's maximum force when `Class.SlidingBallConstraint.ActuatorType|ActuatorType` is set to `Enum.ActuatorType|Servo`, as the constraint attempts to reach its desired `Class.SlidingBallConstraint.Speed|Speed`.

### `SlidingBallConstraint.Size`
- **Type:** `float`
- **Summary:** The constraint's visualized size.

### `SlidingBallConstraint.SoftlockServoUponReachingTarget`
- **Type:** `boolean`
- **Tags:** Deprecated

### `SlidingBallConstraint.Speed`
- **Type:** `float`
- **Summary:** The constraint's desired speed when `Class.SlidingBallConstraint.ActuatorType|ActuatorType` is set to `Enum.ActuatorType|Servo`, as the constraint translates towards its `Class.SlidingBallConstraint.TargetPosition|TargetPosition`. Measured in studs per second.

### `SlidingBallConstraint.TargetPosition`
- **Type:** `float`
- **Summary:** The constraint's attempted target position when `Class.SlidingBallConstraint.ActuatorType|ActuatorType` is set to `Enum.ActuatorType|Servo`. Measured in studs.

### `SlidingBallConstraint.UpperLimit`
- **Type:** `float`
- **Summary:** The upper positional limit along the **X** axis of `Class.Constraint.Attachment0|Attachment0` if `Class.SlidingBallConstraint.LimitsEnabled|LimitsEnabled` is true.

### `SlidingBallConstraint.Velocity`
- **Type:** `float`
- **Summary:** The constraint's attempted velocity when `Class.SlidingBallConstraint.ActuatorType|ActuatorType` is set to `Enum.ActuatorType|Motor`. Measured in studs per second.
