# WireframeHandleAdornment

**Superclass:** [HandleAdornment](HandleAdornment.md)

The `WireframeHandleAdornment` class is a class that allows rendering wireframe adornments onto `Class.BasePart` or `Class.Workspace` objects, and provides methods for adding lines, paths, and text to the adornment.

## Properties
### `WireframeHandleAdornment.Scale`
- **Type:** `Vector3`
- **Summary:** The **XYZ** scale of the wireframe adornment.

### `WireframeHandleAdornment.Thickness`
- **Type:** `float`
- **Summary:** Thickness of the wireframe adornment's lines in pixels.

## Methods
### `WireframeHandleAdornment:AddLine(from: Vector3, to: Vector3) -> ()`
- **Summary:** Adds a line to the wireframe adornment from a starting point to an ending point relative to the center of the `Class.WireframeHandleAdornment.Adornee|Adornee`.

### `WireframeHandleAdornment:AddLines(points: Array) -> ()`
- **Summary:** Adds one or more lines to the wireframe adornment using an array.

### `WireframeHandleAdornment:AddPath(points: Array, loop: boolean) -> ()`
- **Summary:** Adds multiple line segments to the wireframe adornment in a sequence from point to point.

### `WireframeHandleAdornment:AddText(point: Vector3, text: string, size: int) -> ()`
- **Summary:** Adds a text label to the wireframe adornment.

### `WireframeHandleAdornment:Clear() -> ()`
- **Summary:** Instantly clears all lines and text in the wireframe adornment.
