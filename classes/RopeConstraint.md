# RopeConstraint

**Superclass:** [Constraint](Constraint.md)

RopeConstraint is a class in Roblox Units that simulates rope dynamics to prevent two attachments from separating beyond a defined length. It can be powered as a motorized winch or controlled via physics settings.

## Properties
### `RopeConstraint.CurrentDistance`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The current distance between the constraint's `Class.Attachment|Attachments`.

### `RopeConstraint.Length`
- **Type:** `float`
- **Summary:** The maximum distance apart the two `Class.Attachment|Attachments` can be.

### `RopeConstraint.Restitution`
- **Type:** `float`
- **Summary:** Elasticity of the `Class.Attachment|Attachments` connected by the constraint when reaching the maximum defined `Class.RopeConstraint.Length|Length`. Constrained between 0 and 1.

### `RopeConstraint.Thickness`
- **Type:** `float`
- **Summary:** The visualized thickness of the `Class.RopeConstraint`.

### `RopeConstraint.WinchEnabled`
- **Type:** `boolean`
- **Summary:** Enables the winch motor.

### `RopeConstraint.WinchForce`
- **Type:** `float`
- **Summary:** The maximum force that the winch motor can apply.

### `RopeConstraint.WinchResponsiveness`
- **Type:** `float`
- **Summary:** The sharpness of the winch motor in reaching the `Class.RopeConstraint.WinchTarget|WinchTarget`.

### `RopeConstraint.WinchSpeed`
- **Type:** `float`
- **Summary:** A positive desired velocity at which the winch motor changes the rope length.

### `RopeConstraint.WinchTarget`
- **Type:** `float`
- **Summary:** The target length for the winch motor.
