# UIGridStyleLayout

**Superclass:** [UILayout](UILayout.md)

The `UIGridStyleLayout` class defines base classes for grid style UI layouts, including `UILayout`, `UIPageLayout`, and `UITableLayout`. It provides methods for setting `AbsoluteContentSize` and `FillDirection` to control the layout of elements within a grid.

## Tags
- NotCreatable
- NotBrowsable

## Properties
### `UIGridStyleLayout.AbsoluteContentSize`
- **Type:** `Vector2`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The absolute size of space being taken up by the grid layout.

### `UIGridStyleLayout.FillDirection`
- **Type:** `FillDirection`
- **Summary:** Determines the axis in which UI objects are laid out.

### `UIGridStyleLayout.HorizontalAlignment`
- **Type:** `HorizontalAlignment`
- **Summary:** Determines the horizontal alignment of UI elements within the parent element.

### `UIGridStyleLayout.SortOrder`
- **Type:** `SortOrder`
- **Summary:** Determines the order in which child UI objects are placed in a layout.

### `UIGridStyleLayout.VerticalAlignment`
- **Type:** `VerticalAlignment`
- **Summary:** Determines the vertical alignment of UI elements within the parent element.

## Methods
### `UIGridStyleLayout:ApplyLayout() -> ()`
- **Tags:** Deprecated
- **Summary:** Force re-layout of sibling UI elements.

### `UIGridStyleLayout:SetCustomSortFunction(function: Function) -> ()`
- **Tags:** Deprecated
- **Summary:** Sets the function used to determine the order of elements when SortOrder is set to Custom.
