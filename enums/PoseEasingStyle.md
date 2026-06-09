# Enum.PoseEasingStyle

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Linear` | 0 |  | Poses interpolate linearly between key frames. |
| `Constant` | 1 |  | Poses do not interpolate but snap to the key frame indicated by the `Enum.PoseEasingDirection`. |
| `Elastic` | 2 |  | Pose interpolation will overshoot like it is elastic. |
| `Cubic` | 3 |  | Deprecated - Use `Enum.PoseEasingStyle.CubicV2`. Pose interpolation is a cubic curve between keyframes based on the `Enum.PoseEasingDirection`. |
| `Bounce` | 4 |  | Pose interpolation produces a bounce like effect between key frames. |
| `CubicV2` | 5 |  | Pose interpolation is a cubic curve between keyframes based on `Enum.PoseEasingDirection`. |

**Valid values:** `Enum.PoseEasingStyle.Linear`, `Enum.PoseEasingStyle.Constant`, `Enum.PoseEasingStyle.Elastic`, `Enum.PoseEasingStyle.Cubic`, `Enum.PoseEasingStyle.Bounce`, `Enum.PoseEasingStyle.CubicV2`
