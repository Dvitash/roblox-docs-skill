# VideoDisplay

**Superclass:** [GuiObject](GuiObject.md)

VideoDisplay is a GUI object that displays video content from a `Class.VideoPlayer` connected via `Class.Wire`. It functions similarly to an ImageLabel but is optimized for video playback.

## Tags
- NotBrowsable

## Properties
### `VideoDisplay.ResampleMode`
- **Type:** `ResamplerMode`
- **Summary:** Selects the texture resampling mode for the `Class.VideoDisplay`.

### `VideoDisplay.ScaleType`
- **Type:** `ScaleType`
- **Summary:** Determines how a video will scale if displayed in a UI element whose aspect ratio differs from the source video.

### `VideoDisplay.TileSize`
- **Type:** `UDim2`

### `VideoDisplay.VideoColor3`
- **Type:** `Color3`
- **Summary:** Determines how a rendered video will be colorized.

### `VideoDisplay.VideoRectOffset`
- **Type:** `Vector2`
- **Summary:** The offset in pixels of the sub-area of a video to be displayed.

### `VideoDisplay.VideoRectSize`
- **Type:** `Vector2`
- **Summary:** Determines the size in pixels of the sub-area of a video to be displayed.

### `VideoDisplay.VideoTransparency`
- **Type:** `float`
- **Summary:** Determines the transparency of the rendered video.

## Methods
### `VideoDisplay:GetConnectedWires(pin: string) -> List<[Wire](Wire.md)>`
- **Summary:** Returns an array of `Class.Wire|Wires` that are connected to the specified pin.

### `VideoDisplay:GetInputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.TargetName` to connect to this instance via its `Class.Wire.TargetInstance` property.

### `VideoDisplay:GetOutputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.SourceName` to connect to this instance via its `Class.Wire.SourceInstance` property.

## Events
### `VideoDisplay.WiringChanged(connected: boolean, pin: string, wire: [Wire](Wire.md), instance: [Instance](Instance.md))`
- **Summary:** Fires when another instance is connected to or disconnected from the `Class.VideoDisplay` via a `Class.Wire`.
