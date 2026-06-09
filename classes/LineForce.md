# LineForce

**Superclass:** [Constraint](Constraint.md)

The `LineForce` class is a constraint that applies a force along the line connecting two `Class.Attachment` objects, allowing for reaction forces between attachments.

## Properties
### `LineForce.ApplyAtCenterOfMass`
- **Type:** `boolean`
- **Summary:** Whether force is applied at the center of mass of the parent assembly.

### `LineForce.InverseSquareLaw`
- **Type:** `boolean`
- **Summary:** When `true`, the force magnitude is multiplied by the inverse square of the distance.

### `LineForce.Magnitude`
- **Type:** `float`
- **Summary:** The magnitude of the force.

### `LineForce.MaxForce`
- **Type:** `float`
- **Summary:** Maximum absolute force that can be applied.

### `LineForce.ReactionForceEnabled`
- **Type:** `boolean`
- **Summary:** Enables an equal and opposite reaction force on the parent of `Class.Constraint.Attachment1|Attachment1`.
