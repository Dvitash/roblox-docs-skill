# Enum.AlignType

An enum that specifies how the constraint will attempt to align the body associated with the constraint.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Parallel` | 0 | Deprecated |  |
| `Perpendicular` | 1 | Deprecated |  |
| `PrimaryAxisParallel` | 2 |  | Aligns the primary axis to be parallel to the axis given by `Class.Constraint.Attachment1`. |
| `PrimaryAxisPerpendicular` | 3 |  | Aligns the primary axis to be perpendicular to the axis given by `Class.Constraint.Attachment1`. |
| `PrimaryAxisLookAt` | 4 |  | Aligns the primary axis to look at the point given by `Class.Constraint.Attachment1` or the `Class.AlignOrientation.LookAtPosition`. |
| `AllAxes` | 5 |  | Aligns all of the axes of `Class.Constraint.Attachment0` to the axes given by `Class.Constraint.Attachment1` or to the target orientation provided by `Class.AlignOrientation.PrimaryAxis` and `Class.AlignOrientation.SecondaryAxis`. |

**Valid values:** `Enum.AlignType.Parallel`, `Enum.AlignType.Perpendicular`, `Enum.AlignType.PrimaryAxisParallel`, `Enum.AlignType.PrimaryAxisPerpendicular`, `Enum.AlignType.PrimaryAxisLookAt`, `Enum.AlignType.AllAxes`
