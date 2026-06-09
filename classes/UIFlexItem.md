# UIFlexItem

**Superclass:** [UIComponent](UIComponent.md)

UIFlexItem defines flex behavior for a `Class.GuiObject` within a `Class.UIListLayout`, overriding the controlling `Class.UIListLayout` to allow per-object growth or shrinkage.

## Properties
### `UIFlexItem.FlexMode`
- **Type:** `UIFlexMode`
- **Summary:** How the parent `Class.GuiObject` grows or shrinks with available space in the flex layout container.

### `UIFlexItem.GrowRatio`
- **Type:** `float`
- **Summary:** Determines the amount the parent `Class.GuiObject` grows relative to other items in the line. Applies only if `Class.UIFlexItem.FlexMode|FlexMode` is set to `Enum.UIFlexMode.Custom`.

### `UIFlexItem.ItemLineAlignment`
- **Type:** `ItemLineAlignment`
- **Summary:** Cross-axis alignment of the specific parent `Class.GuiObject` within the flex line.

### `UIFlexItem.ShrinkRatio`
- **Type:** `float`
- **Summary:** Determines the amount the parent `Class.GuiObject` shrinks relative to other items in the line. Applies only if `Class.UIFlexItem.FlexMode|FlexMode` is set to `Enum.UIFlexMode.Custom`.
