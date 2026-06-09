# ImageButton

**Superclass:** [GuiButton](GuiButton.md)

This file defines the `ImageButton` class, which acts as a 2D user interface element with an interactive image behavior. It includes various properties for rendering and content, along with specific inheritance and tag information.

## Properties
### `ImageButton.HoverImage`
- **Type:** `ContentId`
- **Summary:** A texture ID that will be used when the `Class.ImageButton` is being hovered.

### `ImageButton.HoverImageContent`
- **Type:** `Content`
- **Summary:** The image content that will be used when the `Class.ImageButton` is being hovered. Only supports asset URIs.

### `ImageButton.Image`
- **Type:** `ContentId`
- **Summary:** The image content displayed by the `Class.ImageButton` element. Reads and writes to `Class.ImageButton.ImageContent|ImageContent`.

### `ImageButton.ImageColor3`
- **Type:** `Color3`
- **Summary:** Determines how a rendered image will be colorized.

### `ImageButton.ImageContent`
- **Type:** `Content`
- **Summary:** The image content displayed by the UI element. Supports asset URIs and `Class.EditableImage` objects.

### `ImageButton.ImageRectOffset`
- **Type:** `Vector2`
- **Summary:** The offset in pixels of the sub-area of an image to be displayed.

### `ImageButton.ImageRectSize`
- **Type:** `Vector2`
- **Summary:** Determines the size in pixels of the sub-area of an image to be displayed.

### `ImageButton.ImageTransparency`
- **Type:** `float`
- **Summary:** Determines the transparency of the rendered image.

### `ImageButton.IsLoaded`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Indicates whether the Image has finished loading from the Roblox website.

### `ImageButton.PressedImage`
- **Type:** `ContentId`
- **Summary:** A texture ID that will be used when an `Class.ImageButton` is being pressed.

### `ImageButton.PressedImageContent`
- **Type:** `Content`
- **Summary:** The image content that will be used when an `Class.ImageButton` is being pressed. Only supports asset URIs.

### `ImageButton.ResampleMode`
- **Type:** `ResamplerMode`
- **Summary:** Selects the image resampling mode for the button.

### `ImageButton.ScaleType`
- **Type:** `ScaleType`
- **Summary:** Determines how an image will scale if displayed in a UI element whose size differs from the source image.

### `ImageButton.SliceCenter`
- **Type:** `Rect`
- **Summary:** Sets the slice boundaries of a 9-sliced image.

### `ImageButton.SliceScale`
- **Type:** `float`
- **Summary:** Scales the 9-slice edges by the specified ratio.

### `ImageButton.TileSize`
- **Type:** `UDim2`
- **Summary:** Sets the tiling scale of the ImageButton.
