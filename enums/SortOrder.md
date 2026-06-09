# Enum.SortOrder

Used by `Class.UIGridStyleLayout.SortOrder` to order the elements in the layout.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Name` | 0 |  | Elements are ordered by their `Class.Instance.Name` in alphanumeric order. |
| `Custom` | 1 | Deprecated | Elements are ordered by the function passed to `Class.UIGridStyleLayout:SetCustomSortFunction()`. |
| `LayoutOrder` | 2 |  | Elements are ordered by `Class.GuiObject.LayoutOrder` in ascending order; for example `0` will be placed before `1`. |

**Valid values:** `Enum.SortOrder.Name`, `Enum.SortOrder.Custom`, `Enum.SortOrder.LayoutOrder`
