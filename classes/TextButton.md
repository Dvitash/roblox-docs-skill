# TextButton

**Superclass:** [GuiButton](GuiButton.md)

The `TextButton` class is a 2D user interface element that displays interactive text, similar to `Class.TextLabel`. It includes methods for disabling text rendering and provides properties for font selection and line height.

## Properties
### `TextButton.ContentText`
- **Type:** `string`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A copy of `Class.TextButton.Text` that contains exactly what is being rendered by the `Class.TextButton`.

### `TextButton.Font`
- **Type:** `Enum.Font`
- **Tags:** Hidden, NotReplicated
- **Summary:** Determines the font used to render text.

### `TextButton.FontFace`
- **Type:** `Datatype.Font`
- **Summary:** Determines the font used to render text.

### `TextButton.FontSize`
- **Type:** `FontSize`
- **Tags:** NotReplicated, Deprecated
- **Summary:** Determines the font size to be used.

### `TextButton.LineHeight`
- **Type:** `float`
- **Summary:** Scales the spacing between lines of text in the `Class.TextButton`.

### `TextButton.LocalizedText`
- **Type:** `string`
- **Tags:** Hidden, ReadOnly, NotReplicated
- **Summary:** Sets whether a `Class.TextButton` should be `Class.GuiBase2d.Localize` or not.

### `TextButton.MaxVisibleGraphemes`
- **Type:** `int`
- **Summary:** The maximum number of graphemes the `Class.TextButton` can show.

### `TextButton.OpenTypeFeatures`
- **Type:** `string`

### `TextButton.OpenTypeFeaturesError`
- **Type:** `string`
- **Tags:** ReadOnly, NotReplicated

### `TextButton.RichText`
- **Type:** `boolean`
- **Summary:** Determines whether the `Class.TextButton` renders its text using rich text formatting.

### `TextButton.Text`
- **Type:** `string`
- **Summary:** Determines the string rendered by the `Class.TextButton`.

### `TextButton.TextBounds`
- **Type:** `Vector2`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Read-only property which reflects the absolute size of rendered text in offsets.

### `TextButton.TextColor`
- **Type:** `BrickColor`
- **Tags:** Hidden, NotReplicated, Deprecated
- **Summary:** Determines the color of text.

### `TextButton.TextColor3`
- **Type:** `Color3`
- **Summary:** Determines the color of rendered text.

### `TextButton.TextDirection`
- **Type:** `TextDirection`
- **Summary:** Direction in which the text is rendered.

### `TextButton.TextFits`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A boolean representation of whether the button's text fits within the size of it.

### `TextButton.TextScaled`
- **Type:** `boolean`
- **Summary:** Changes whether text is resized to fit within the `Class.TextButton`.

### `TextButton.TextSize`
- **Type:** `float`
- **Summary:** Determines the line height of text in offsets.

### `TextButton.TextStrokeColor3`
- **Type:** `Color3`
- **Summary:** Determines the color of the text stroke (outline).

### `TextButton.TextStrokeTransparency`
- **Type:** `float`
- **Summary:** Determines the transparency of the text stroke (outline).

### `TextButton.TextTransparency`
- **Type:** `float`
- **Summary:** Determines the transparency of rendered text.

### `TextButton.TextTruncate`
- **Type:** `TextTruncate`
- **Summary:** Controls the truncation of the text displayed in the `Class.TextButton`.

### `TextButton.TextWrap`
- **Type:** `boolean`
- **Tags:** NotReplicated, Deprecated
- **Summary:** Determines whether or not text should wrap at the edges of the `Class.TextButton` element's space.

### `TextButton.TextWrapped`
- **Type:** `boolean`
- **Summary:** Determines if text wraps to multiple lines within the `Class.TextButton` element's space, truncating excess text.

### `TextButton.TextXAlignment`
- **Type:** `TextXAlignment`
- **Summary:** Determines the horizontal alignment of rendered text.

### `TextButton.TextYAlignment`
- **Type:** `TextYAlignment`
- **Summary:** Determines the vertical alignment of rendered text.
