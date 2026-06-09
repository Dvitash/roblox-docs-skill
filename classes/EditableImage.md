# EditableImage

**Superclass:** [Object](Object.md)

EditableImage is a class for runtime creation and manipulation of images, allowing for the creation of images from existing ones.

## Tags
- NotCreatable

## Properties
### `EditableImage.Size`
- **Type:** `Vector2`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Size of the `EditableImage` in pixels.

## Methods
### `EditableImage:Destroy() -> ()`

### `EditableImage:DrawCircle(center: Vector2, radius: int, color: Color3, transparency: float, combineType: ImageCombineType, antiAliasing: AntiAliasing) -> ()`
- **Summary:** Draws a circle at the specified point.

### `EditableImage:DrawImage(position: Vector2, image: [EditableImage](EditableImage.md), combineType: ImageCombineType) -> ()`
- **Summary:** Draws another `EditableImage` into this `EditableImage` at the given position.

### `EditableImage:DrawImageProjected(mesh: [EditableMesh](EditableMesh.md), projection: Dictionary, brushConfig: Dictionary) -> ()`
- **Summary:** Projects another `EditableImage` into an `Class.EditableMesh` and stores the result on this `EditableImage`.

### `EditableImage:DrawImageTransformed(position: Vector2, scale: Vector2, rotation: float, image: [EditableImage](EditableImage.md), options: Dictionary?) -> ()`
- **Summary:** Draws an image into this `EditableImage` with transformations including scaling and rotation, placing it at the specified position.

### `EditableImage:DrawLine(p1: Vector2, p2: Vector2, color: Color3, transparency: float, combineType: ImageCombineType, antiAliasing: AntiAliasing) -> ()`
- **Summary:** Draws a line between two provided points.

### `EditableImage:DrawRectangle(position: Vector2, size: Vector2, color: Color3, transparency: float, combineType: ImageCombineType) -> ()`
- **Summary:** Draws a rectangle of the given size at the given top-left position.

### `EditableImage:ReadPixelsBuffer(position: Vector2, size: Vector2) -> buffer`
- **Tags:** CustomLuaState
- **Summary:** Reads a rectangular region of pixels into a buffer.

### `EditableImage:WritePixelsBuffer(position: Vector2, size: Vector2, buffer: buffer) -> ()`
- **Tags:** CustomLuaState
- **Summary:** Writes a rectangular region of pixels into the image.
