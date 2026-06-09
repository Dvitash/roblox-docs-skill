# Enum.VelocityConstraintMode

The velocity constraint mode property controls how the linear velocity of the attachment(s) is constrained.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Line` | 0 |  | The velocity component in the direction of the line is constrained to the specified value. The line direction is based on the `Class.LinearVelocity.RelativeTo\|RelativeTo` property: - `Enum.ActuatorRelativeTo\|Attachment0` - The line direction is the primary axis of `Class.Constraint.Attachment0\|Attachment0`. - `Enum.ActuatorRelativeTo\|Attachment1` - The line direction is the primary axis of `Class.Constraint.Attachment1\|Attachment1`. - `Enum.ActuatorRelativeTo\|World` - The line direction must be specified. |
| `Plane` | 1 |  | The velocity components in the plane are constrained to the specified values. The plane tangents are based on the `Class.LinearVelocity.RelativeTo\|RelativeTo` property: - `Enum.ActuatorRelativeTo\|Attachment0` - The plane tangents are the two axes of `Class.Constraint.Attachment0\|Attachment0`. - `Enum.ActuatorRelativeTo\|Attachment1` - The plane tangents are the two axes of `Class.Constraint.Attachment1\|Attachment1`. - `Enum.ActuatorRelativeTo\|World` - The two plane tangents must be specified |
| `Vector` | 2 |  | The velocity components must be equal to the vector components specified. The coordinate system of the vector is based on the `Class.LinearVelocity.RelativeTo\|RelativeTo` property: - `Enum.ActuatorRelativeTo\|Attachment0` - The vector components are in the coordinate system defined by the axes of `Class.Constraint.Attachment0\|Attachment0`. - `Enum.ActuatorRelativeTo\|Attachment1` - The vector components are in the coordinate system defined by the axes of `Class.Constraint.Attachment1\|Attachment1`. - `Enum.ActuatorRelativeTo\|World` - The coordinate system is in the world and the vector components must be specified. |

**Valid values:** `Enum.VelocityConstraintMode.Line`, `Enum.VelocityConstraintMode.Plane`, `Enum.VelocityConstraintMode.Vector`
