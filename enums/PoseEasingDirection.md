# Enum.PoseEasingDirection

Used exclusively by Pose.EasingDirection to specify direction of the EasingStyle curve.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `In` | 0 |  | The EasingStyle curve is reversed, with the easing becoming linear as it approaches the next keyframe. |
| `Out` | 1 |  | EasingStyle curves are applied in the forward direction, from the current keyframe to the next. |
| `InOut` | 2 |  | Two easing curves are applied back-to-back with the linear ends of the curves meeting in the middle. |

**Valid values:** `Enum.PoseEasingDirection.In`, `Enum.PoseEasingDirection.Out`, `Enum.PoseEasingDirection.InOut`
