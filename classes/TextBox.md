# TextBox

**Superclass:** [GuiObject](GuiObject.md)

The `TextBox` class is a 2D user interface element that allows players to provide text input, with options for focus state changes and basic text editing.

## Properties
### `TextBox.ClearTextOnFocus`
- **Type:** `boolean`
- **Summary:** Determines whether clicking on the `TextBox` will clear its `Class.TextBox.Text` property.

### `TextBox.ContentText`
- **Type:** `string`
- **Tags:** ReadOnly, NotReplicated

### `TextBox.CursorPosition`
- **Type:** `int`
- **Summary:** Determines the offset of the text cursor in bytes, or `-1` if there is no cursor.

### `TextBox.Font`
- **Type:** `Enum.Font`
- **Tags:** Hidden, NotReplicated
- **Summary:** Determines the font used to render text.

### `TextBox.FontFace`
- **Type:** `Datatype.Font`
- **Summary:** Determines the font face used to render text.

### `TextBox.FontSize`
- **Type:** `FontSize`
- **Tags:** NotReplicated, Deprecated
- **Summary:** Determines the font size of a `TextBox` object.

### `TextBox.LineHeight`
- **Type:** `float`
- **Summary:** Scales the spacing between lines of text in the `TextBox`.

### `TextBox.MaxVisibleGraphemes`
- **Type:** `int`
- **Summary:** The maximum number of graphemes the `TextBox` can show.

### `TextBox.MultiLine`
- **Type:** `boolean`
- **Summary:** When set to `true`, text inside a `TextBox` is able to move onto multiple lines.

### `TextBox.OpenTypeFeatures`
- **Type:** `string`

### `TextBox.OpenTypeFeaturesError`
- **Type:** `string`
- **Tags:** ReadOnly, NotReplicated

### `TextBox.PlaceholderColor3`
- **Type:** `Color3`
- **Summary:** Sets the text color that gets used when no text has been entered into the `TextBox`.

### `TextBox.PlaceholderText`
- **Type:** `string`
- **Summary:** Sets the text that gets displayed when no text has been entered into the `TextBox`.

### `TextBox.RichText`
- **Type:** `boolean`
- **Summary:** Determines whether the `TextBox` renders the `Class.TextBox.Text|Text` string using rich text formatting.

### `TextBox.SelectionStart`
- **Type:** `int`
- **Summary:** Determines the starting position of a text selection.

### `TextBox.ShowNativeInput`
- **Type:** `boolean`
- **Summary:** If set to `true`, input native to the platform is used instead of Roblox's built-in keyboard.

### `TextBox.Text`
- **Type:** `string`
- **Summary:** Determines the string rendered by the `TextBox` element.

### `TextBox.TextBounds`
- **Type:** `Vector2`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The size of a `TextBox` element's text in offsets.

### `TextBox.TextColor`
- **Type:** `BrickColor`
- **Tags:** Hidden, NotReplicated, Deprecated

### `TextBox.TextColor3`
- **Type:** `Color3`
- **Summary:** Determines the color of non-placeholder rendered text.

### `TextBox.TextDirection`
- **Type:** `TextDirection`

### `TextBox.TextEditable`
- **Type:** `boolean`
- **Summary:** Determines whether the player can change the `Class.TextBox.Text|Text`.

### `TextBox.TextFits`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Whether the text fits within the constraints of the `TextBox`.

### `TextBox.TextScaled`
- **Type:** `boolean`
- **Summary:** Changes whether text is resized to fit within the `TextBox`.

### `TextBox.TextSize`
- **Type:** `float`
- **Summary:** Determine the line height of text in offsets.

### `TextBox.TextStrokeColor3`
- **Type:** `Color3`
- **Summary:** Determines the color of the text stroke (outline).

### `TextBox.TextStrokeTransparency`
- **Type:** `float`
- **Summary:** Determines the transparency of the text stroke (outline).

### `TextBox.TextTransparency`
- **Type:** `float`
- **Summary:** Determines the transparency of the rendered text.

### `TextBox.TextTruncate`
- **Type:** `TextTruncate`
- **Summary:** Controls the truncation of the text displayed in the `TextBox`.

### `TextBox.TextWrap`
- **Type:** `boolean`
- **Tags:** NotReplicated, Deprecated

### `TextBox.TextWrapped`
- **Type:** `boolean`
- **Summary:** Determines if text wraps to multiple lines within the `TextBox` element space, truncating excess text.

### `TextBox.TextXAlignment`
- **Type:** `TextXAlignment`
- **Summary:** Determines the horizontal alignment of the rendered text.

### `TextBox.TextYAlignment`
- **Type:** `TextYAlignment`
- **Summary:** Determines the vertical alignment of the rendered text.

## Methods
### `TextBox:CaptureFocus() -> ()`
- **Summary:** Forces the client to focus on the `TextBox`.

### `TextBox:IsFocused() -> boolean`
- **Summary:** Returns `true` if the `TextBox` is focused or `false` if it is not.

### `TextBox:ReleaseFocus(submitted: boolean) -> ()`
- **Summary:** Forces the client to unfocus the TextBox.

## Events
### `TextBox.Focused()`
- **Summary:** Fires when the `TextBox` gains focus.

### `TextBox.FocusLost(enterPressed: boolean, inputThatCausedFocusLoss: [InputObject](InputObject.md))`
- **Summary:** Fires when the `TextBox` loses its focus.

### `TextBox.ReturnPressedFromOnScreenKeyboard()`
- **Summary:** Fires when the `TextBox` is focused and the player presses the on-screen keyboard's return/enter button.
