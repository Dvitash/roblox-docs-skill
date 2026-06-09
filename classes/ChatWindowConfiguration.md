# ChatWindowConfiguration

**Superclass:** [TextChatConfigurations](TextChatConfigurations.md)

The `ChatWindowConfiguration` class is a configuration class for the default chat window, which is parented to `Class.TextChatService`. It provides read-only properties for screen position and size, and has several read/write properties for font, transparency, and alignment.

## Tags
- NotCreatable

## Properties
### `ChatWindowConfiguration.AbsolutePosition`
- **Type:** `Vector2`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Actual screen position of the default chat window, in pixels.

### `ChatWindowConfiguration.AbsoluteSize`
- **Type:** `Vector2`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Actual screen size of the default chat window, in pixels.

### `ChatWindowConfiguration.BackgroundColor3`
- **Type:** `Color3`
- **Summary:** Background color of the default chat window.

### `ChatWindowConfiguration.BackgroundTransparency`
- **Type:** `double`
- **Summary:** Background transparency of the default chat window.

### `ChatWindowConfiguration.Enabled`
- **Type:** `boolean`
- **Summary:** Whether to show the default chat window.

### `ChatWindowConfiguration.FontFace`
- **Type:** `Datatype.Font`
- **Summary:** Font used to render text in the default chat window.

### `ChatWindowConfiguration.HeightScale`
- **Type:** `float`
- **Summary:** Factor by which the height of the default chat window should be scaled.

### `ChatWindowConfiguration.HorizontalAlignment`
- **Type:** `HorizontalAlignment`
- **Summary:** Horizontal alignment of the chat window.

### `ChatWindowConfiguration.TextColor3`
- **Type:** `Color3`
- **Summary:** Color of the text in default chat window.

### `ChatWindowConfiguration.TextSize`
- **Type:** `int64`
- **Summary:** Size of the text in default chat window.

### `ChatWindowConfiguration.TextStrokeColor3`
- **Type:** `Color3`
- **Summary:** Color of the text stroke for text in default chat window.

### `ChatWindowConfiguration.TextStrokeTransparency`
- **Type:** `double`
- **Summary:** Transparency of the text stroke for text in default chat window.

### `ChatWindowConfiguration.VerticalAlignment`
- **Type:** `VerticalAlignment`
- **Summary:** Vertical alignment of the chat window.

### `ChatWindowConfiguration.WidthScale`
- **Type:** `float`
- **Summary:** Factor by which the width of the default chat window should be scaled.

## Methods
### `ChatWindowConfiguration:DeriveNewMessageProperties() -> [ChatWindowMessageProperties](ChatWindowMessageProperties.md)`
- **Summary:** Creates a new `Class.ChatWindowMessageProperties` instance that can be used to customize the appearance of messages in the chat window.
