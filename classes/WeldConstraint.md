# WeldConstraint

**Superclass:** [Instance](Instance.md)

The `WeldConstraint` class is used to connect two `Class.BasePart` objects so that their relative positions and orientations remain constant, even if the parts are not touching.

## Properties
### `WeldConstraint.Active`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Indicates if the WeldConstraint is currently active in the world.

### `WeldConstraint.Enabled`
- **Type:** `boolean`
- **Tags:** NotReplicated
- **Summary:** Toggles the constraint on and off.

### `WeldConstraint.Part0`
- **Type:** `[BasePart](BasePart.md)`
- **Tags:** NotReplicated
- **Summary:** The first part connected by the constraint.

### `WeldConstraint.Part1`
- **Type:** `[BasePart](BasePart.md)`
- **Tags:** NotReplicated
- **Summary:** The second part connected by the constraint.
