# Enum.ItemLineAlignment

Used for `Class.UIListLayout.ItemLineAlignment` and `Class.UIFlexItem.ItemLineAlignment` in a flex layout to define the cross-directional alignment of siblings or the parent within a line.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Automatic` | 0 |  | Aligns the siblings of the `Class.UIListLayout` or the specific `Class.UIFlexItem` parent to the layout's `Class.UIListLayout.HorizontalAlignment\|HorizontalAlignment` or `Class.UIListLayout.VerticalAlignment\|VerticalAlignment`, depending on its `Class.UIListLayout.FillDirection\|FillDirection`. If `Class.UIListLayout.HorizontalFlex\|HorizontalFlex` or `Class.UIListLayout.VerticalFlex\|VerticalFlex` is enabled for the `Class.UIListLayout` cross‑direction, `Stretch` will be used for that direction. |
| `Start` | 1 |  | Aligns the siblings of the `Class.UIListLayout` or the specific `Class.UIFlexItem` parent to the line's **top** in a horizontal fill or the line's **left** in a vertical fill. |
| `Center` | 2 |  | Aligns the siblings of the `Class.UIListLayout` or the specific `Class.UIFlexItem` parent to the line's **center** in either a horizontal or vertical fill. |
| `End` | 3 |  | Aligns the siblings of the `Class.UIListLayout` or the specific `Class.UIFlexItem` parent to the line's **bottom** in a horizontal fill or the line's **right** in a vertical fill. |
| `Stretch` | 4 |  | Stretches the siblings of the `Class.UIListLayout` or the specific `Class.UIFlexItem` parent to fill the entire cross‑direction of the line in either a horizontal or vertical fill. |

**Valid values:** `Enum.ItemLineAlignment.Automatic`, `Enum.ItemLineAlignment.Start`, `Enum.ItemLineAlignment.Center`, `Enum.ItemLineAlignment.End`, `Enum.ItemLineAlignment.Stretch`
