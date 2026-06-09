# ImageLabel

**Superclass:** [GuiLabel](GuiLabel.md)

The `ImageLabel` class is a 2D user interface element that displays a single, non-interactive image. It supports manipulating the image's color and transparency via properties like `ImageColor3` and `ImageTransparency`.

## Properties
### `ImageLabel.Image`
- **Type:** `ContentId`
- **Summary:** The image content displayed by the UI element. Reads and writes to `Class.ImageLabel.ImageContent|ImageContent`.

### `ImageLabel.ImageColor3`
- **Type:** `Color3`
- **Summary:** Determines how a rendered image will be colorized.

### `ImageLabel.ImageContent`
- **Type:** `Content`
- **Summary:** The image content displayed by the UI element. Supports [asset URIs](../../../projects/assets/index.md#asset-uris) and `Class.EditableImage` objects.

### `ImageLabel.ImageRectOffset`
- **Type:** `Vector2`
- **Summary:** The offset in pixels of the sub-area of an image to be displayed.

### `ImageLabel.ImageRectSize`
- **Type:** `Vector2`
- **Summary:** Determines the size in pixels of the sub-area of an image to be displayed.

### `ImageLabel.ImageTransparency`
- **Type:** `float`
- **Summary:** Determines the transparency of the rendered image.

### `ImageLabel.IsLoaded`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Indicates whether the image has finished loading from Roblox.

### `ImageLabel.ResampleMode`
- **Type:** `ResamplerMode`
- **Summary:** Selects the image resampling mode for the label.

### `ImageLabel.ScaleType`
- **Type:** `ScaleType`
- **Summary:** Determines how an image will scale if displayed in a UI element whose size differs from the source image.

### `ImageLabel.SliceCenter`
- **Type:** `Rect`
- **Summary:** Sets the slice boundaries of a 9-sliced image.

### `ImageLabel.SliceScale`
- **Type:** `float`
- **Summary:** Scales the 9-slice edges by the specified ratio.

### `ImageLabel.TileSize`
- **Type:** `UDim2`
- **Summary:** Sets the tiling size of the `Class.ImageLabel`.
