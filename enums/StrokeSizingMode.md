# Enum.StrokeSizingMode

Used by `Class.UIStroke.StrokeSizingMode` to determine whether the stroke's `Class.UIStroke.Thickness|Thickness` will be measured in pixels or be relative to the parent.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `FixedSize` | 0 |  | `Class.UIStroke.Thickness\|Thickness` is measured in pixels. |
| `ScaledSize` | 1 |  | `Class.UIStroke.Thickness\|Thickness` is relative to minimum parent width or height. If stroke is on text, thickness is relative to font size. |

**Valid values:** `Enum.StrokeSizingMode.FixedSize`, `Enum.StrokeSizingMode.ScaledSize`
