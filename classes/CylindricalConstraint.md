# CylindricalConstraint

**Superclass:** [SlidingBallConstraint](SlidingBallConstraint.md)

CylindricalConstraint is a class that constrains attachments along two axes, allowing for relative linear and rotational motion. It can be combined with other constraints like SpringConstraint to build vehicle suspension.

## Properties
### `CylindricalConstraint.AngularActuatorType`
- **Type:** `ActuatorType`
- **Summary:** Type of angular actuator.

### `CylindricalConstraint.AngularLimitsEnabled`
- **Type:** `boolean`
- **Summary:** Enables the angular limits around the rotation axis.

### `CylindricalConstraint.AngularResponsiveness`
- **Type:** `float`
- **Summary:** Specifies the sharpness of the angular servo motor in reaching the `Class.CylindricalConstraint.TargetAngle|TargetAngle`.

### `CylindricalConstraint.AngularRestitution`
- **Type:** `float`
- **Summary:** Restitution of the two limits, or how elastic they are.

### `CylindricalConstraint.AngularSpeed`
- **Type:** `float`
- **Summary:** Target angular speed. This value is unsigned as the servo will always move toward its target. In radians per second.

### `CylindricalConstraint.AngularVelocity`
- **Type:** `float`
- **Summary:** The target angular velocity of the motor in radians per second around the rotation axis.

### `CylindricalConstraint.CurrentAngle`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Signed angle (in degrees) between the reference axis and the secondary axis of `Class.Constraint.Attachment1|Attachment1` around the rotation axis.

### `CylindricalConstraint.InclinationAngle`
- **Type:** `float`
- **Summary:** Direction of the rotation axis as an angle from the **X** axis in the **XY** plane of `Class.Constraint.Attachment0|Attachment0`.

### `CylindricalConstraint.LowerAngle`
- **Type:** `float`
- **Summary:** Lower limit for the angle (in degrees) between the reference axis and the SecondaryAxis of `Class.Constraint.Attachment1|Attachment1` around the rotation axis.

### `CylindricalConstraint.MotorMaxAngularAcceleration`
- **Type:** `float`
- **Summary:** The maximum angular acceleration of the motor in radians per second squared.

### `CylindricalConstraint.MotorMaxTorque`
- **Type:** `float`
- **Summary:** The maximum torque the motor can apply to achieve the target angular velocity.

### `CylindricalConstraint.RotationAxisVisible`
- **Type:** `boolean`
- **Summary:** Enable the visibility of the rotation axis.

### `CylindricalConstraint.ServoMaxTorque`
- **Type:** `float`
- **Summary:** Maximum torque the servo motor can apply.

### `CylindricalConstraint.SoftlockAngularServoUponReachingTarget`
- **Type:** `boolean`
- **Tags:** Deprecated

### `CylindricalConstraint.TargetAngle`
- **Type:** `float`
- **Summary:** Target angle (in degrees) between the reference axis and the secondary axis of `Class.Constraint.Attachment1|Attachment1` around the rotation axis.

### `CylindricalConstraint.UpperAngle`
- **Type:** `float`
- **Summary:** Upper limit for the angle (in degrees) between the reference axis and the secondary axis of `Class.Constraint.Attachment1|Attachment1` around the rotation axis.

### `CylindricalConstraint.WorldRotationAxis`
- **Type:** `Vector3`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The unit vector direction of the rotation axis in world coordinates.
