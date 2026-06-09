# Attachment

**Superclass:** [Instance](Instance.md)

This file defines `Attachment` objects, which define a point and orientation relative to an ancestor (`Class.PVInstance`, `Class.Bone`, etc.).

## Properties
### `Attachment.Axis`
- **Type:** `Vector3`
- **Tags:** NotReplicated
- **Summary:** Direction of the **X** axis of the attachment, represented as a unit `Datatype.Vector3`.

### `Attachment.CFrame`
- **Type:** `CFrame`
- **Summary:** `Datatype.CFrame` offset of the attachment.

### `Attachment.Orientation`
- **Type:** `Vector3`
- **Tags:** Hidden, NotReplicated
- **Summary:** Orientation of the attachment relative to the orientation of its parent.

### `Attachment.Position`
- **Type:** `Vector3`
- **Tags:** Hidden, NotReplicated
- **Summary:** Positional offset of the attachment, relative to the position and orientation of its parent.

### `Attachment.Rotation`
- **Type:** `Vector3`
- **Tags:** Hidden, NotReplicated, Deprecated
- **Summary:** Rotation of the attachment relative to the rotation of its parent.

### `Attachment.SecondaryAxis`
- **Type:** `Vector3`
- **Tags:** NotReplicated
- **Summary:** Direction of the **Y** axis of the attachment, represented as a unit `Datatype.Vector3`.

### `Attachment.Visible`
- **Type:** `boolean`
- **Summary:** Toggles the in-experience visibility of the attachment.

### `Attachment.WorldAxis`
- **Type:** `Vector3`
- **Tags:** NotReplicated
- **Summary:** Direction of the **X** axis of the attachment relative to the world, represented as a unit `Datatype.Vector3` with a length of 1.

### `Attachment.WorldCFrame`
- **Type:** `CFrame`
- **Tags:** NotReplicated
- **Summary:** The exact `Datatype.CFrame` of the attachment in world space coordinates.

### `Attachment.WorldOrientation`
- **Type:** `Vector3`
- **Tags:** Hidden, NotReplicated
- **Summary:** Orientation of the attachment relative to the world rather than its own parent.

### `Attachment.WorldPosition`
- **Type:** `Vector3`
- **Tags:** Hidden, NotReplicated
- **Summary:** Position of the attachment relative to the world rather than its own parent.

### `Attachment.WorldRotation`
- **Type:** `Vector3`
- **Tags:** Hidden, ReadOnly, NotReplicated, Deprecated
- **Summary:** Rotation of the attachment relative to the world rather than its own parent.

### `Attachment.WorldSecondaryAxis`
- **Type:** `Vector3`
- **Tags:** NotReplicated
- **Summary:** Direction of the **Y** axis of the attachment relative to the world, represented as a unit `Datatype.Vector3` with a length of 1.

## Methods
### `Attachment:GetAxis() -> Vector3`
- **Tags:** Deprecated
- **Summary:** Returns the value of the attachment's `Class.Attachment.Axis|Axis`.

### `Attachment:GetConstraints() -> List<[Constraint](Constraint.md)>`
- **Summary:** Returns a list of `Class.Constraint|Constraints` connected to the attachment.

### `Attachment:GetSecondaryAxis() -> Vector3`
- **Tags:** Deprecated
- **Summary:** Returns the value of the attachment's `Class.Attachment.SecondaryAxis|SecondaryAxis`.

### `Attachment:SetAxis(axis: Vector3) -> ()`
- **Tags:** Deprecated
- **Summary:** Sets the value of the attachment's `Class.Attachment.Axis|Axis`.

### `Attachment:SetSecondaryAxis(axis: Vector3) -> ()`
- **Tags:** Deprecated
- **Summary:** Sets the value of the attachment's `Class.Attachment.SecondaryAxis|SecondaryAxis`.
