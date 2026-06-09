# ScreenGui

**Superclass:** [LayerCollector](LayerCollector.md)

### ScreenGui Class Details - **Class Name:** ScreenGui - **Type:** class - **Memory Category:** Instances - **Summary:** Primary container for 2D `Class.GuiObject` elements on the screen. - **Inherits:** LayerCollector - **Descendants:** GuiMain - **Properties:** - name: ScreenGui.ClipToDeviceSafeArea - Description: Whether to clip contents to the device's safe area. - Value: boolean (default is true). - Description: If `true`, all descendants will be clipped to the device's safe area;…

## Properties
### `ScreenGui.ClipToDeviceSafeArea`
- **Type:** `boolean`
- **Summary:** Whether to clip the contents of this `Class.ScreenGui` to the device's safe area.

### `ScreenGui.DisplayOrder`
- **Type:** `int`
- **Summary:** Controls the Z-index order in which multiple `Class.ScreenGui` containers are drawn.

### `ScreenGui.IgnoreGuiInset`
- **Type:** `boolean`
- **Tags:** NotReplicated
- **Summary:** Determines whether the `Class.ScreenGui` overflows into the range of Roblox's core UI elements.

### `ScreenGui.SafeAreaCompatibility`
- **Type:** `SafeAreaCompatibility`
- **Summary:** Specifies whether automatic UI compatibility transformations are applied to descendant "fullscreen" `Class.GuiObject|GuiObjects` on displays with screen cutouts.

### `ScreenGui.ScreenInsets`
- **Type:** `ScreenInsets`
- **Summary:** Controls the safe area insets that are applied to the contents of the `Class.ScreenGui`.
