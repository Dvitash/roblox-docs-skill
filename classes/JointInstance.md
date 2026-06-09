# JointInstance

**Superclass:** [Instance](Instance.md)

The `JointInstance` class defines the base class for joints, which handles the connection and behavior between multiple parts.

## Tags
- NotCreatable

## Properties
### `JointInstance.Active`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Determines if the joint is currently active in the world.

### `JointInstance.C0`
- **Type:** `CFrame`
- **Summary:** Determines how the offset point is attached to `Class.JointInstance.Part0`.

### `JointInstance.C1`
- **Type:** `CFrame`
- **Summary:** Subtracted from the `Class.JointInstance.C0|C0` property to create an offset point for `Class.JointInstance.Part1|Part1`.

### `JointInstance.Enabled`
- **Type:** `boolean`
- **Summary:** Sets whether the joint is active or not.

### `JointInstance.Part0`
- **Type:** `[BasePart](BasePart.md)`
- **Summary:** The first `Class.BasePart` that the joint connects.

### `JointInstance.Part1`
- **Type:** `[BasePart](BasePart.md)`
- **Summary:** The second `Class.BasePart` that the joint connects.

### `JointInstance.part1`
- **Type:** `[BasePart](BasePart.md)`
- **Tags:** Hidden, NotReplicated, Deprecated
