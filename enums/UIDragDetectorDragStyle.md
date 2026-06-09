# Enum.UIDragDetectorDragStyle

Used with `Class.UIDragDetector` as the paradigm to generate proposed motion, given a stream of input position vectors.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `TranslatePlane` | 0 |  | 2D motion in the plane of the `Class.LayerCollector`. |
| `TranslateLine` | 1 |  | 1D motion along the detector's `Class.UIDragDetector.DragAxis\|DragAxis`. |
| `Rotate` | 2 |  | By default, rotation about the absolute center position of the detector's parent `Class.GuiObject`. If `Class.UIDragDetector.ReferenceUIInstance\|ReferenceUIInstance` is set, rotation happens about that instance's absolute center position. |
| `Scriptable` | 3 |  | Calculates desired motion via a custom function provided through `Class.UIDragDetector:SetDragStyleFunction()\|SetDragStyleFunction()`. |

**Valid values:** `Enum.UIDragDetectorDragStyle.TranslatePlane`, `Enum.UIDragDetectorDragStyle.TranslateLine`, `Enum.UIDragDetectorDragStyle.Rotate`, `Enum.UIDragDetectorDragStyle.Scriptable`
