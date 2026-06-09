# Enum.UIFlexMode

Used with `Class.UIFlexItem.FlexMode` to define how the parent `Class.GuiObject` grows or shrinks.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `None` | 0 |  | The parent `Class.GuiObject` is unaffected and neither shrinks nor grows. |
| `Grow` | 1 |  | Sets an effective `1:0` grow‑shrink ratio on the parent `Class.GuiObject`. Objects set to `Grow` never shrink below their basis size, so overflow may occur if the container becomes smaller than the flex line's combined basis size. |
| `Shrink` | 2 |  | Sets an effective `0:1` grow‑shrink ratio on the parent `Class.GuiObject`. Objects set to `Shrink` never grow above their basis size, so underflow may occur if the container becomes larger than the flex line's combined basis size. |
| `Fill` | 3 |  | Sets an effective `1:1` grow‑shrink ratio on the parent `Class.GuiObject`. This setting ensures the flex line always fills the container, even if the container size changes. |
| `Custom` | 4 |  | Enables the `Class.UIFlexItem.GrowRatio\|GrowRatio` and `Class.UIFlexItem.ShrinkRatio\|ShrinkRatio` properties for the `Class.UIFlexItem`, allowing for relative growth or shrinking of the parent `Class.GuiObject` in a ratio compared to other flex objects also under control of a `Class.UIFlexItem`. |

**Valid values:** `Enum.UIFlexMode.None`, `Enum.UIFlexMode.Grow`, `Enum.UIFlexMode.Shrink`, `Enum.UIFlexMode.Fill`, `Enum.UIFlexMode.Custom`
