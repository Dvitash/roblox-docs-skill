# RodConstraint

**Superclass:** [Constraint](Constraint.md)

The `RodConstraint` class manages separating attachments, allowing for rotation limits and provides methods to set limits on attachment angles.

## Properties
### `RodConstraint.CurrentDistance`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The current distance between the constraint's `Class.Attachment|Attachments`.

### `RodConstraint.Length`
- **Type:** `float`
- **Summary:** The distance apart at which the constraint attempts to keep its `Class.Attachment|Attachments`.

### `RodConstraint.LimitAngle0`
- **Type:** `float`
- **Summary:** The maximum angle between the rod and `Class.Constraint.Attachment0|Attachment0` when `Class.RodConstraint.LimitsEnabled|LimitsEnabled` is true.

### `RodConstraint.LimitAngle1`
- **Type:** `float`
- **Summary:** The maximum angle between the rod and `Class.Constraint.Attachment1|Attachment1` when `Class.RodConstraint.LimitsEnabled|LimitsEnabled` is true.

### `RodConstraint.LimitsEnabled`
- **Type:** `boolean`
- **Summary:** Determines whether `Class.RodConstraint.LimitAngle0|LimitAngle0` and `Class.RodConstraint.LimitAngle1|LimitAngle1` control the angles between the rod and the respective attachments.

### `RodConstraint.Thickness`
- **Type:** `float`
- **Summary:** The visualized thickness of the `Class.RodConstraint`.
