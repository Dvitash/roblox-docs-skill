# Path2D

**Superclass:** [GuiBase](GuiBase.md)

Path2D is a UI instance used to represent a 2D spline, allowing for editing in the viewport. It stores control points and enables features like curved layouts, animations, and interactive tools.

## Properties
### `Path2D.Closed`
- **Type:** `boolean`
- **Summary:** Connects the first and last control points when enabled.

### `Path2D.Color3`
- **Type:** `Color3`
- **Summary:** Determines the color of the `Class.Path2D`.

### `Path2D.SelectedControlPoint`
- **Type:** `int`
- **Tags:** NotReplicated
- **Summary:** Index of the currently selected `Datatype.Path2DControlPoint`.

### `Path2D.SelectedControlPointData`
- **Type:** `Path2DControlPoint`
- **Tags:** NotReplicated
- **Summary:** `Datatype.Path2DControlPoint` data type representing the currently selected control point.

### `Path2D.Thickness`
- **Type:** `float`
- **Summary:** Determines how thick the `Class.Path2D` path is.

### `Path2D.Visible`
- **Type:** `boolean`
- **Summary:** Determines if the `Class.Path2D` path is rendered or not.

### `Path2D.ZIndex`
- **Type:** `int`
- **Summary:** Determines the order in which a `Class.Path2D` path renders relative to other GUIs.

## Methods
### `Path2D:GetBoundingRect() -> Rect`
- **Summary:** Returns the bounding size for the `Class.Path2D`.

### `Path2D:GetControlPoint(index: int) -> Path2DControlPoint`
- **Summary:** Returns the `Datatype.Path2DControlPoint` for a given index.

### `Path2D:GetControlPoints() -> Array`
- **Summary:** Returns all the `Datatype.Path2DControlPoint|Path2DControlPoints` for the `Class.Path2D`.

### `Path2D:GetLength() -> float`
- **Summary:** Returns the length of the `Class.Path2D`.

### `Path2D:GetMaxControlPoints() -> int`
- **Summary:** Returns the maximum allowed number of control points.

### `Path2D:GetPositionOnCurve(t: float) -> UDim2`
- **Summary:** Returns the position at a given value in parameter space.

### `Path2D:GetPositionOnCurveArcLength(t: float) -> UDim2`
- **Summary:** Returns the position at a given value in arc length space.

### `Path2D:GetTangentOnCurve(t: float) -> Vector2`
- **Summary:** Returns the tangent at a given value in parameter space.

### `Path2D:GetTangentOnCurveArcLength(t: float) -> Vector2`
- **Summary:** Returns the tangent at a given value in arc length space.

### `Path2D:InsertControlPoint(index: int, point: Path2DControlPoint) -> ()`
- **Summary:** Inserts a new control point at a given index.

### `Path2D:RemoveControlPoint(index: int) -> ()`
- **Summary:** Removes a control at the given index.

### `Path2D:SetControlPoints(controlPoints: Array) -> ()`
- **Summary:** Sets all the control points to the specified array, replacing all existing points with new ones.

### `Path2D:UpdateControlPoint(index: int, point: Path2DControlPoint) -> ()`
- **Summary:** Updates a control point at the given index.

## Events
### `Path2D.ControlPointChanged()`
- **Summary:** Fires any time control points change.
