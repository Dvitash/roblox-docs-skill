# ChatInputBarConfiguration

**Superclass:** [TextChatConfigurations](TextChatConfigurations.md)

The `ChatInputBarConfiguration` class is a configuration class for the default chat input bar, which is parented to `Class.TextChatService`. It provides read-only properties for screen position and size, and can be set to `true` or `false`.

## Tags
- NotCreatable

## Properties
### `ChatInputBarConfiguration.AbsolutePosition`
- **Type:** `Vector2`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Actual screen position of the default chat input bar in pixels.

### `ChatInputBarConfiguration.AbsoluteSize`
- **Type:** `Vector2`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Actual screen size of the default chat input bar in pixels.

### `ChatInputBarConfiguration.AutocompleteEnabled`
- **Type:** `boolean`
- **Summary:** Whether to enable autocomplete for the chat input bar.

### `ChatInputBarConfiguration.BackgroundColor3`
- **Type:** `Color3`
- **Summary:** Background color of the default chat input bar.

### `ChatInputBarConfiguration.BackgroundTransparency`
- **Type:** `double`
- **Summary:** Background transparency of the default chat input bar.

### `ChatInputBarConfiguration.Enabled`
- **Type:** `boolean`
- **Summary:** Whether to show the default chat input bar.

### `ChatInputBarConfiguration.FontFace`
- **Type:** `Datatype.Font`
- **Summary:** Font used to render text in the default chat input bar.

### `ChatInputBarConfiguration.IsFocused`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Whether the default chat input bar is focused or not.

### `ChatInputBarConfiguration.KeyboardKeyCode`
- **Type:** `KeyCode`
- **Summary:** Additional key users can press to trigger focusing on the default chat input bar.

### `ChatInputBarConfiguration.PlaceholderColor3`
- **Type:** `Color3`
- **Summary:** Color of the text of the placeholder text in the default chat input bar.

### `ChatInputBarConfiguration.TargetTextChannel`
- **Type:** `[TextChannel](TextChannel.md)`
- **Summary:** A reference to the target `Class.TextChannel`.

### `ChatInputBarConfiguration.TextBox`
- **Type:** `[TextBox](TextBox.md)`
- **Summary:** Reference to a designated `Class.TextBox` instance that sends messages on behalf of the user.

### `ChatInputBarConfiguration.TextColor3`
- **Type:** `Color3`
- **Summary:** Color of the text in default chat input bar.

### `ChatInputBarConfiguration.TextSize`
- **Type:** `int64`
- **Summary:** Size of the text in default chat input bar.

### `ChatInputBarConfiguration.TextStrokeColor3`
- **Type:** `Color3`
- **Summary:** Color of the text stroke for text in default chat input bar.

### `ChatInputBarConfiguration.TextStrokeTransparency`
- **Type:** `double`
- **Summary:** Transparency of the text stroke for text in default chat input bar.
