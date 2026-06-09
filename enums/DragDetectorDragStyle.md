# Enum.DragDetectorDragStyle

Used with `Class.DragDetector` as the paradigm to generate proposed motion, given a stream of cursor rays.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `TranslateLine` | 0 |  | 1D motion along the detector's `Class.DragDetector.Axis\|Axis`, by default the world **Y** axis. |
| `TranslatePlane` | 1 |  | 2D motion in the plane **perpendicular** to the detector's `Class.DragDetector.Axis\|Axis`, by default the world **XZ** plane. |
| `TranslatePlaneOrLine` | 2 |  | 2D motion in the plane **perpendicular** to the detector's `Class.DragDetector.Axis\|Axis` and, when the modifier is active, 1D motion along the detector's `Class.DragDetector.Axis\|Axis`. |
| `TranslateLineOrPlane` | 3 |  | 1D motion along the detector's `Class.DragDetector.Axis\|Axis` and, when the modifier is active, 2D motion in the plane **perpendicular** to the detector's `Class.DragDetector.Axis\|Axis`. |
| `TranslateViewPlane` | 4 |  | 2D motion in the plane perpendicular to the camera's view. In this mode, the plane is constantly updated, even while dragging, and will always face the camera's current view. |
| `RotateAxis` | 5 |  | Rotation about the detector's `Class.DragDetector.Axis\|Axis`, by default the world **Y** axis. |
| `RotateTrackball` | 6 |  | Trackball rotation, further customized through the `Class.DragDetector.TrackballRadialPullFactor\|TrackballRadialPullFactor` and `Class.DragDetector.TrackballRollFactor\|TrackballRollFactor` properties. |
| `Scriptable` | 7 |  | Calculates desired motion via a custom function provided through `Class.DragDetector:SetDragStyleFunction()\|SetDragStyleFunction()`. |
| `BestForDevice` | 8 |  | **TranslatePlaneOrLine** for mouse and gamepad; **TranslatePlane** for touch; **6DOF** for VR. |

**Valid values:** `Enum.DragDetectorDragStyle.TranslateLine`, `Enum.DragDetectorDragStyle.TranslatePlane`, `Enum.DragDetectorDragStyle.TranslatePlaneOrLine`, `Enum.DragDetectorDragStyle.TranslateLineOrPlane`, `Enum.DragDetectorDragStyle.TranslateViewPlane`, `Enum.DragDetectorDragStyle.RotateAxis`, `Enum.DragDetectorDragStyle.RotateTrackball`, `Enum.DragDetectorDragStyle.Scriptable`, `Enum.DragDetectorDragStyle.BestForDevice`
