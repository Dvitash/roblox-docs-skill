# Enum.SurfaceConstraint

This item is deprecated and is replaced by the `Enum.SurfaceType` enum.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `None` | 0 |  | No surface constraint. |
| `Hinge` | 1 |  | Makes the side appear with a yellow hinge. Any part connected to this hinge will stick to the side and rotate using physics. |
| `SteppingMotor` | 2 |  | Functions identically to a motor. It may have functioned differently in the past, but that functionality no longer seems to exist. |
| `Motor` | 3 |  | Acts the same as a Hinge, but has a grey ring around it and automatically rotates any part connected to it. |

**Valid values:** `Enum.SurfaceConstraint.None`, `Enum.SurfaceConstraint.Hinge`, `Enum.SurfaceConstraint.SteppingMotor`, `Enum.SurfaceConstraint.Motor`
