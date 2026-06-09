# AlignOrientation

**Superclass:** [Constraint](Constraint.md)

The `AlignOrientation` constraint applies torque to align two or more attachments, affecting their orientation relative to a central axis.

## Properties
### `AlignOrientation.AlignType`
- **Type:** `AlignType`
- **Summary:** The constraint's axis alignment type.

### `AlignOrientation.CFrame`
- **Type:** `CFrame`
- **Summary:** The `Datatype.CFrame` orientation with which the constraint will attempt to match the orientation of `Class.Constraint.Attachment0|Attachment0`.

### `AlignOrientation.LookAtPosition`
- **Type:** `Vector3`
- **Tags:** NotReplicated
- **Summary:** A `Datatype.Vector3` world space location toward which the primary axis will attempt to align.

### `AlignOrientation.MaxAngularVelocity`
- **Type:** `float`
- **Summary:** Maximum angular velocity the constraint can use to reach its goal.

### `AlignOrientation.MaxTorque`
- **Type:** `float`
- **Summary:** Maximum torque the constraint can use to reach its goal.

### `AlignOrientation.Mode`
- **Type:** `OrientationAlignmentMode`
- **Summary:** Whether the constraint uses one or two attachments in calculating its goal.

### `AlignOrientation.PrimaryAxis`
- **Type:** `Vector3`
- **Tags:** NotReplicated
- **Summary:** The direction of the goal's **X** axis, represented as a unit `Datatype.Vector3`.

### `AlignOrientation.PrimaryAxisOnly`
- **Type:** `boolean`
- **Summary:** Determines how the constraint's axes are affected by torque.

### `AlignOrientation.ReactionTorqueEnabled`
- **Type:** `boolean`
- **Summary:** Whether the constraint applies torque only to `Class.Constraint.Attachment0|Attachment0`, or to both attachments in equal and opposite directions.

### `AlignOrientation.Responsiveness`
- **Type:** `float`
- **Summary:** Controls how quickly the constraint reaches its goal. Higher values cause the attachment(s) to align more rapidly.

### `AlignOrientation.RigidityEnabled`
- **Type:** `boolean`
- **Summary:** Whether torque is dependent on other properties, or if the physics solver reacts as quickly as possible to complete the alignment.

### `AlignOrientation.SecondaryAxis`
- **Type:** `Vector3`
- **Tags:** NotReplicated
- **Summary:** The direction of the goal's **Y** axis, represented as a unit `Datatype.Vector3`.
