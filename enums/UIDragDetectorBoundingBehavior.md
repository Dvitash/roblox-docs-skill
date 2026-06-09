# Enum.UIDragDetectorBoundingBehavior

Used with `Class.UIDragDetector` to determine bounding behavior of the dragged UI object when `Class.UIDragDetector.BoundingUI` is set.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Automatic` | 0 |  | Mimics **EntireObject** behavior for a UI object that's entirely contained by the `Class.UIDragDetector.BoundingUI\|BoundingUI`, or else **HitPoint** for a UI object that's partially outside the `Class.UIDragDetector.BoundingUI\|BoundingUI`. |
| `EntireObject` | 1 |  | Bounds the entire dragged UI object within the `Class.UIDragDetector.BoundingUI\|BoundingUI`. |
| `HitPoint` | 2 |  | Bounds the dragged UI only by the exact hit/grab point and its respective position after translation/rotation. |

**Valid values:** `Enum.UIDragDetectorBoundingBehavior.Automatic`, `Enum.UIDragDetectorBoundingBehavior.EntireObject`, `Enum.UIDragDetectorBoundingBehavior.HitPoint`
