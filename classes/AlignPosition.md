# AlignPosition

**Superclass:** [Constraint](Constraint.md)

The `AlignPosition` constraint applies a force to move attachments together or to move one attachment to a goal position. It is defined by three properties: `name`, `ApplyAtCenterOfMass`, and `ForceLimitMode`.

## Properties
### `AlignPosition.ApplyAtCenterOfMass`
- **Type:** `boolean`
- **Summary:** Whether force is applied to the parent of `Class.Constraint.Attachment0|Attachment0` at that attachment's location, or at the parents' center of mass.

### `AlignPosition.ForceLimitMode`
- **Type:** `ForceLimitMode`
- **Summary:** Determines how the constraint force will be limited. Only used if `Class.AlignPosition.RigidityEnabled|RigidityEnabled` is `false`.

### `AlignPosition.ForceRelativeTo`
- **Type:** `ActuatorRelativeTo`
- **Summary:** Determines the axes that the constraint uses to limit the force. Only applies when `Class.AlignPosition.RigidityEnabled|RigidityEnabled` is `false` and `Class.AlignPosition.ForceLimitMode` is `Enum.ForceLimitMode|PerAxis`. .

### `AlignPosition.MaxAxesForce`
- **Type:** `Vector3`
- **Summary:** Maximum force along each axis that the constraint can apply to achieve its goal.

### `AlignPosition.MaxForce`
- **Type:** `float`
- **Summary:** Maximum force magnitude the constraint can apply to achieve its goal.

### `AlignPosition.MaxVelocity`
- **Type:** `float`
- **Summary:** Maximum speed the attachments can move when converging.

### `AlignPosition.Mode`
- **Type:** `PositionAlignmentMode`
- **Summary:** Whether the constraint uses one or two attachments in calculating its goal.

### `AlignPosition.Position`
- **Type:** `Vector3`
- **Summary:** The position to which the constraint should move its `Class.Constraint.Attachment0|Attachment0`.

### `AlignPosition.ReactionForceEnabled`
- **Type:** `boolean`
- **Summary:** Whether the constraint applies force only to `Class.Constraint.Attachment0|Attachment0`, or to both attachments in equal and opposite directions.

### `AlignPosition.Responsiveness`
- **Type:** `float`
- **Summary:** Controls how quickly the constraint reaches its goal. Higher values cause the attachment(s) to align more rapidly.

### `AlignPosition.RigidityEnabled`
- **Type:** `boolean`
- **Summary:** Whether force is dependent on other properties, or if the physics solver reacts as quickly as possible to complete the alignment.
