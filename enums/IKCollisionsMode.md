# Enum.IKCollisionsMode

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `NoCollisions` | 0 |  | Only the part and any parts directly joined to it via joints/`Class.Constraint\|constraints` be involved in the resolution, everything else in the workspace will be treated as though it doesn't exist. |
| `OtherMechanismsAnchored` | 1 |  | Only the part and any parts directly jointed to it via joints/`Class.Constraint\|constraints` will be moved during resolution, but they will collide with other objects in the workspace. |
| `IncludeContactedMechanisms` | 2 |  | The part, any parts directly joined to it via joints/`Class.Constraint\|constraints`, and any parts which it comes into contact with during the solve will be moved during the resolution. That is, the moved parts will be allowed to "push" other unanchored parts in the workspace out of the way in order to get to the target position. |

**Valid values:** `Enum.IKCollisionsMode.NoCollisions`, `Enum.IKCollisionsMode.OtherMechanismsAnchored`, `Enum.IKCollisionsMode.IncludeContactedMechanisms`
