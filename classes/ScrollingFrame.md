# ScrollingFrame

**Superclass:** [GuiObject](GuiObject.md)

### ScrollingFrame Class - The `ScrollingFrame` class is a special `Class.Frame` type with built-in scrolling interactivity and customization options. - It is defined in the `GuiObject` class. ### Properties - **ScrollingFrame.AbsoluteCanvasSize** - Represents the size of the area scrollable within the frame, in offsets. - Sets the maximum scrollable size or the size of the children if `AutomaticCanvasSize` is set to `Enum.AutomaticSize.None`. - **ScrollingFrame.AbsoluteWindowSize** -…

## Properties
### `ScrollingFrame.AbsoluteCanvasSize`
- **Type:** `Vector2`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The size of the area that is scrollable, in offsets.

### `ScrollingFrame.AbsoluteWindowSize`
- **Type:** `Vector2`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The size of the frame, in offsets, without the scroll bars.

### `ScrollingFrame.AutomaticCanvasSize`
- **Type:** `AutomaticSize`
- **Summary:** Determines whether `Class.ScrollingFrame.CanvasSize` is resized based on child content.

### `ScrollingFrame.BottomImage`
- **Type:** `ContentId`
- **Summary:** Image that displays on the bottom of a vertical scroll bar, or the right of a horizontal scroll bar (rotated 90&deg; counterclockwise for a horizontal scroll bar).

### `ScrollingFrame.BottomImageContent`
- **Type:** `Content`
- **Summary:** Image that displays on the bottom of a vertical scroll bar, or the right of a horizontal scroll bar (rotated 90&deg; counterclockwise for a horizontal scroll bar). Only supports asset URIs as textures.

### `ScrollingFrame.CanvasPosition`
- **Type:** `Vector2`
- **Summary:** Reflects the **current** positional offset of the canvas within the frame, in pixels, and sets the position of scroll bars accordingly.

### `ScrollingFrame.CanvasSize`
- **Type:** `UDim2`
- **Summary:** Determines the size of the scrollable area.

### `ScrollingFrame.ElasticBehavior`
- **Type:** `ElasticBehavior`
- **Summary:** Determines if and when elastic scrolling is allowed on touch‑enabled devices.

### `ScrollingFrame.HorizontalScrollBarInset`
- **Type:** `ScrollBarInset`
- **Summary:** Indicates whether `Class.ScrollingFrame.CanvasSize|CanvasSize` is inset by `Class.ScrollingFrame.ScrollBarThickness|ScrollBarThickness` on the horizontal axis.

### `ScrollingFrame.MidImage`
- **Type:** `ContentId`
- **Summary:** Image which spans the area between `Class.ScrollingFrame.TopImage|TopImage` and `Class.ScrollingFrame.BottomImage|BottomImage` (rotated 90&deg; counterclockwise for a horizontal scroll bar).

### `ScrollingFrame.MidImageContent`
- **Type:** `Content`
- **Summary:** Image which spans the area between `Class.ScrollingFrame.TopImageContent|TopImageContent` and `Class.ScrollingFrame.BottomImageContent|BottomImageContent` (rotated 90&deg; counterclockwise for a horizontal scroll bar). Only supports asset URIs as textures.

### `ScrollingFrame.ScrollBarImageColor3`
- **Type:** `Color3`
- **Summary:** Determines how the rendered scroll bar images are colorized.

### `ScrollingFrame.ScrollBarImageTransparency`
- **Type:** `float`
- **Summary:** Determines the opacity of the scroll bar images.

### `ScrollingFrame.ScrollBarThickness`
- **Type:** `int`
- **Summary:** Thickness of the scroll bar in pixels; applies to both horizontal and vertical scroll bars.

### `ScrollingFrame.ScrollingDirection`
- **Type:** `ScrollingDirection`
- **Summary:** Determines the direction(s) in which scrolling is allowed.

### `ScrollingFrame.ScrollingEnabled`
- **Type:** `boolean`
- **Summary:** Determines whether scrolling is allowed on the frame.

### `ScrollingFrame.TopImage`
- **Type:** `ContentId`
- **Summary:** Image which displays on the top of a vertical scroll bar, or the left of a horizontal scroll bar (rotated 90&deg; counterclockwise for a horizontal scroll bar).

### `ScrollingFrame.TopImageContent`
- **Type:** `Content`

### `ScrollingFrame.VerticalScrollBarInset`
- **Type:** `ScrollBarInset`
- **Summary:** Indicates whether `Class.ScrollingFrame.CanvasSize|CanvasSize` is inset by `Class.ScrollingFrame.ScrollBarThickness|ScrollBarThickness` on the vertical axis.

### `ScrollingFrame.VerticalScrollBarPosition`
- **Type:** `VerticalScrollBarPosition`
- **Summary:** Indicates whether the vertical scroll bar is positioned to the left or right of the canvas.

## Methods
### `ScrollingFrame:GetScrollVelocity() -> Vector2`
- **Summary:** Returns a `Datatype.Vector2` representing the current inertial scroll velocity after the user stops their input.

### `ScrollingFrame:ResetScrollVelocity() -> ()`
- **Summary:** Resets the inertial scroll velocity of the `ScrollingFrame` to `0` on both axes.
