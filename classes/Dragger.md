# Dragger

**Superclass:** [Instance](Instance.md)

Dragger is a helper object used to create tools that can drag parts, and it is deprecated due to compatibility issues with `Class.Workspace.FilteringEnabled`.

## Methods
### `Dragger:AxisRotate(axis: Axis) -> ()`
- **Summary:** Rotates the currently dragged part(s) by 90 degrees on the given axis.

### `Dragger:MouseDown(mousePart: [Instance](Instance.md), pointOnMousePart: Vector3, parts: Instances) -> ()`
- **Summary:** Initializes a dragging action, specifying which parts to use when dragging.

### `Dragger:MouseMove(mouseRay: Ray) -> ()`
- **Summary:** Tries to move the currently dragged part to the point where MouseRay hits another part.

### `Dragger:MouseUp() -> ()`
- **Summary:** Stops the current dragging action (made by `Class.Dragger:MouseDown()`).
