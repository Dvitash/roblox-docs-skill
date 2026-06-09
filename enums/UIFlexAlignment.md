# Enum.UIFlexAlignment

In a `Class.UIListLayout` flex layout, specifies how to distribute extra space in the parent container.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `None` | 0 |  | No flex behavior; siblings maintain their defined width or height. |
| `Fill` | 1 |  | Siblings resize to fill the entire parent container, overriding their defined width or height. |
| `SpaceAround` | 2 |  | Siblings maintain their defined width or height. Equal spacing is added on both sides of each sibling. |
| `SpaceBetween` | 3 |  | Siblings maintain their defined width or height. Equal spacing is added **between** siblings, but no additional space is added **around** siblings. |
| `SpaceEvenly` | 4 |  | Siblings maintain their defined width or height. Equal spacing is added both **between** and **around** siblings. |

**Valid values:** `Enum.UIFlexAlignment.None`, `Enum.UIFlexAlignment.Fill`, `Enum.UIFlexAlignment.SpaceAround`, `Enum.UIFlexAlignment.SpaceBetween`, `Enum.UIFlexAlignment.SpaceEvenly`
