# Enum.EasingStyle

Enum used with `Datatype.TweenInfo|TweenInfo.new` to control the motion of a `Class.Tween`.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Linear` | 0 |  | Moves at a constant speed. |
| `Sine` | 1 |  | Speed is determined by a sine wave for a gentle easing motion. |
| `Back` | 2 |  | Slightly overshoots the target, then backs into place. |
| `Quad` | 3 |  | Similar to `Sine` but with a slightly sharper curve based on quadratic interpolation. |
| `Quart` | 4 |  | Similar to `Cubic` but with an even sharper curve based on quartic interpolation. |
| `Quint` | 5 |  | Similar to `Quart` but with an even sharper curve based on quintic interpolation. |
| `Bounce` | 6 |  | Bounces backwards multiple times after reaching the target, before eventually settling. |
| `Elastic` | 7 |  | Moves as if attached to a rubber band, overshooting the target several times. |
| `Exponential` | 8 |  | The sharpest curve based on exponential interpolation. |
| `Circular` | 9 |  | Follows a circular arc, such that acceleration is more sudden and deceleration more gradual versus `Quint` or `Exponential`. |
| `Cubic` | 10 |  | Similar to `Quad` but with a slightly sharper curve based on cubic interpolation. |

**Valid values:** `Enum.EasingStyle.Linear`, `Enum.EasingStyle.Sine`, `Enum.EasingStyle.Back`, `Enum.EasingStyle.Quad`, `Enum.EasingStyle.Quart`, `Enum.EasingStyle.Quint`, `Enum.EasingStyle.Bounce`, `Enum.EasingStyle.Elastic`, `Enum.EasingStyle.Exponential`, `Enum.EasingStyle.Circular`, `Enum.EasingStyle.Cubic`
