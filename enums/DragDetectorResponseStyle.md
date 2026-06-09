# Enum.DragDetectorResponseStyle

Describes how the clicked object will be treated once the desired motion has been calculated.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Geometric` | 0 |  | For an `Class.BasePart.Anchored\|Anchored` object both inside the running experience and in Studio edit mode, the position/orientation of the object will be updated to exactly reflect the proposed motion. For an unanchored object, behavior is the same as for an anchored object; however, in a running experience, the object will be anchored at the start of the drag and restored to unanchored upon drag release. |
| `Physical` | 1 |  | An `Class.BasePart.Anchored\|Anchored` object will default to **Geometric** behavior as it is not affected by forces. An unanchored object will be moved by constraint forces that attempt to bring it to the desired position and/or orientation given by the proposed motion. |
| `Custom` | 2 |  | The object will not move at all, but `Class.DragDetector.DragFrame\|DragFrame` will still be updated and you can respond to drag manipulation however you'd like. |

**Valid values:** `Enum.DragDetectorResponseStyle.Geometric`, `Enum.DragDetectorResponseStyle.Physical`, `Enum.DragDetectorResponseStyle.Custom`
