# Constraint

**Superclass:** [Instance](Instance.md)

The `Constraint` class is the base class for constraint-based objects, and it contains various attachment and kinematic constraints.

## Tags
- NotCreatable

## Properties
### `Constraint.Active`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Indicates if the constraint is currently active in the world.

### `Constraint.Attachment0`
- **Type:** `[Attachment](Attachment.md)`
- **Summary:** The `Class.Attachment` that is connected to `Class.Constraint.Attachment1`.

### `Constraint.Attachment1`
- **Type:** `[Attachment](Attachment.md)`
- **Summary:** The `Class.Attachment` that is connected to `Class.Constraint.Attachment0`.

### `Constraint.Color`
- **Type:** `BrickColor`
- **Summary:** The color of the constraint.

### `Constraint.Enabled`
- **Type:** `boolean`
- **Summary:** Toggles whether or not the constraint is enabled.

### `Constraint.Visible`
- **Type:** `boolean`
- **Summary:** Toggles the constraint's visibility.

## Methods
### `Constraint:GetDebugAppliedForce(bodyId: int) -> Vector3`
- **Tags:** Deprecated

### `Constraint:GetDebugAppliedTorque(bodyId: int) -> Vector3`
- **Tags:** Deprecated
