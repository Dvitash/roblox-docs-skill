# UIStroke

**Superclass:** [UIComponent](UIComponent.md)

The `UIStroke` class is a method that applies an outline to text or a UI border, and it includes various properties and methods for adjusting stroke parameters, specifying placement, adding gradient elements, and controlling visibility.

## Properties
### `UIStroke.ApplyStrokeMode`
- **Type:** `ApplyStrokeMode`
- **Summary:** Determines whether to apply the stroke to the object's border instead of the text itself.

### `UIStroke.BorderOffset`
- **Type:** `UDim`
- **Summary:** Specifies an additional offset to the stroke's position, relative to the parent's minimum height or width.

### `UIStroke.BorderStrokePosition`
- **Type:** `BorderStrokePosition`
- **Summary:** Determines the stroke's position on its parent's border.

### `UIStroke.Color`
- **Type:** `Color3`
- **Summary:** Determines the stroke color.

### `UIStroke.Enabled`
- **Type:** `boolean`
- **Summary:** Determines whether the stroke in visible.

### `UIStroke.LineJoinMode`
- **Type:** `LineJoinMode`
- **Summary:** Determines how corners are interpreted.

### `UIStroke.StrokeSizingMode`
- **Type:** `StrokeSizingMode`
- **Summary:** Determines whether the stroke's `Class.UIStroke.Thickness|Thickness` will be measured in pixels or be relative to the parent.

### `UIStroke.Thickness`
- **Type:** `float`
- **Summary:** Determines the stroke's thickness.

### `UIStroke.Transparency`
- **Type:** `float`
- **Summary:** Sets the stroke opacity independently of the parent object's `Class.GuiObject.BackgroundTransparency|BackgroundTransparency` or `Class.TextLabel.TextTransparency|TextTransparency`.

### `UIStroke.ZIndex`
- **Type:** `int`
- **Summary:** Determines the order in which the stroke renders relative to sibling `Class.UIStroke` instances.
