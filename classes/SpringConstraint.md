# SpringConstraint

**Superclass:** [Constraint](Constraint.md)

Simulates spring and damper behavior between two attachments using a `SpringConstraint`.

## Properties
### `SpringConstraint.Coils`
- **Type:** `float`
- **Summary:** The number of coils visualized on the `Class.SpringConstraint`.

### `SpringConstraint.CurrentLength`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The current distance between the constraint's `Class.Attachment|Attachments`.

### `SpringConstraint.Damping`
- **Type:** `float`
- **Summary:** Damping constant for the `Class.SpringConstraint`. Multiplied to the velocity of the constraint's `Class.Attachment|Attachments` to reduce the spring force applied.

### `SpringConstraint.FreeLength`
- **Type:** `float`
- **Summary:** Natural resting length of the spring.

### `SpringConstraint.LimitsEnabled`
- **Type:** `boolean`
- **Summary:** Sets whether the `Class.SpringConstraint` enforces a minimum and maximum length.

### `SpringConstraint.MaxForce`
- **Type:** `float`
- **Summary:** The maximum force the `Class.SpringConstraint` can apply on its `Class.Attachment|Attachments`.

### `SpringConstraint.MaxLength`
- **Type:** `float`
- **Summary:** The maximum separation the SpringConstraint will allow if `Class.SpringConstraint.LimitsEnabled|LimitsEnabled` is true.

### `SpringConstraint.MinLength`
- **Type:** `float`
- **Summary:** The minimum separation the SpringConstraint will allow if `Class.SpringConstraint.LimitsEnabled|LimitsEnabled` is true.

### `SpringConstraint.Radius`
- **Type:** `float`
- **Summary:** The visualized radius of the spring's coils.

### `SpringConstraint.Stiffness`
- **Type:** `float`
- **Summary:** The strength of the spring. The higher this value the more force will be applied when the attachments are separated a different length than the `Class.SpringConstraint.FreeLength|FreeLength`.

### `SpringConstraint.Thickness`
- **Type:** `float`
- **Summary:** The visualized thickness of the spring's coils.
