# Enum.UIDragDetectorResponseStyle

Describes how the clicked `Class.GuiObject` will be treated once the desired motion has been calculated.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Offset` | 0 |  | Move by the `Datatype.UDim.Offset\|Offset` values of the detector's parent's `Class.GuiObject.Position` value. |
| `Scale` | 1 |  | Move by the `Datatype.UDim.Scale\|Scale` values of the detector's parent's `Class.GuiObject.Position` value. |
| `CustomOffset` | 2 |  | The UI element will not move at all, but the `Datatype.UDim.Offset\|Offset` values of the detector's `Class.UIDragDetector.DragUDim2\|DragUDim2` will still be updated and the detector's events will still fire, allowing you to respond to drag manipulation however you'd like. |
| `CustomScale` | 3 |  | The UI element will not move at all, but the `Datatype.UDim.Scale\|Scale` values of the detector's `Class.UIDragDetector.DragUDim2\|DragUDim2` will still be updated and the detector's events will still fire, allowing you to respond to drag manipulation however you'd like. |

**Valid values:** `Enum.UIDragDetectorResponseStyle.Offset`, `Enum.UIDragDetectorResponseStyle.Scale`, `Enum.UIDragDetectorResponseStyle.CustomOffset`, `Enum.UIDragDetectorResponseStyle.CustomScale`
