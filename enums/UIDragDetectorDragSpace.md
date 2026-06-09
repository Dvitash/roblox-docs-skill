# Enum.UIDragDetectorDragSpace

Used with `Class.DragDetector` to set the paradigm which defines the space of inputs/outputs from a custom drag function.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Parent` | 0 |  | Designates the input and return values' space as the local space of the detector's parent `Class.GuiObject`. |
| `LayerCollector` | 1 |  | Designates the input and return values' space as that of the `Class.LayerCollector`. |
| `Reference` | 2 |  | Designates the input and return values' space as that of the `Class.UIDragDetector.ReferenceUIInstance\|ReferenceUIInstance`. For `Class.UIDragDetector.DragRelativity\|DragRelativity` and `Class.UIDragDetector.DragUDim2\|DragUDim2` purposes, the `(0, 0)` origin is the absolute center position of the `Class.UIDragDetector.ReferenceUIInstance\|ReferenceUIInstance`. If `Class.UIDragDetector.ReferenceUIInstance\|ReferenceUIInstance` is not `nil`, this will behave the same as **Parent**. |

**Valid values:** `Enum.UIDragDetectorDragSpace.Parent`, `Enum.UIDragDetectorDragSpace.LayerCollector`, `Enum.UIDragDetectorDragSpace.Reference`
