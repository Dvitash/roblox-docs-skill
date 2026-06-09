# Enum.SafeAreaCompatibility

Describes how descendants of a `Class.ScreenGui` adapt to screens with cutouts.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `None` | 0 |  | Do not apply compatibility transformations to any descendants of the `Class.ScreenGui`. |
| `FullscreenExtension` | 1 |  | If the total area of any descendant `Class.GuiObject` within the `Class.ScreenGui` (including any applied border or `Class.UIStroke`) covers the device's safe area both horizontally and vertically, its background area will be expanded to cover the fullscreen area. This expansion does **not** affect the size or position of the descendant's **content**, except in the case of `Class.ImageLabel`, `Class.ImageButton`, or `Class.VideoFrame` where the image/video is considered part of the background and will be expanded to fullscreen. Note that this option is intended to automatically improve the appearance of UI that was authored for screens without any cutouts. However, it's recommended that you avoid fullscreen extensions for new work; instead, use the `Class.ScreenGui.ScreenInsets\|ScreenInsets` property to specify which insets should be respected for different `Class.ScreenGui\|ScreenGuis`. |

**Valid values:** `Enum.SafeAreaCompatibility.None`, `Enum.SafeAreaCompatibility.FullscreenExtension`
