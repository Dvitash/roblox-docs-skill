# BallSocketConstraint

**Superclass:** [Constraint](Constraint.md)

The `BallSocketConstraint` class enforces that attachments occupy the same position and allows for limited rotation based on attachment limits.

## Properties
### `BallSocketConstraint.LimitsEnabled`
- **Type:** `boolean`
- **Summary:** Sets whether the `BallSocketConstraint` sets a limit on rotation based on `Class.BallSocketConstraint.UpperAngle|UpperAngle`.

### `BallSocketConstraint.MaxFrictionTorque`
- **Type:** `float`
- **Summary:** Sets the maximum frictional torque applied to keep its `Class.Attachment|Attachments` aligned.

### `BallSocketConstraint.Radius`
- **Type:** `float`
- **Summary:** The visualized radius of the `BallSocketConstraint`.

### `BallSocketConstraint.Restitution`
- **Type:** `float`
- **Summary:** How elastic `Class.Attachment|Attachments` connected by a `BallSocketConstraint` will be when they reach the end of the range specified by `Class.BallSocketConstraint.UpperAngle|UpperAngle` when `Class.BallSocketConstraint.LimitsEnabled|LimitsEnabled` is `true`.

### `BallSocketConstraint.TwistLimitsEnabled`
- **Type:** `boolean`
- **Summary:** Sets whether the `BallSocketConstraint` sets a limit on twist rotation based on `Class.BallSocketConstraint.TwistUpperAngle|TwistUpperAngle` and `Class.BallSocketConstraint.TwistLowerAngle|TwistLowerAngle`.

### `BallSocketConstraint.TwistLowerAngle`
- **Type:** `float`
- **Summary:** Sets the lower twist rotation limit of the `BallSocketConstraint`, as long as `Class.BallSocketConstraint.TwistLimitsEnabled|TwistLimitsEnabled` is `true`.

### `BallSocketConstraint.TwistUpperAngle`
- **Type:** `float`
- **Summary:** Sets the upper twist rotation limit of the `BallSocketConstraint`, as long as `Class.BallSocketConstraint.TwistLimitsEnabled|TwistLimitsEnabled` is `true`.

### `BallSocketConstraint.UpperAngle`
- **Type:** `float`
- **Summary:** Sets the upper rotation limit of the `BallSocketConstraint`, as long as `Class.BallSocketConstraint.LimitsEnabled|LimitsEnabled` is `true`.
