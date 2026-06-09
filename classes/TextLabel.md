# TextLabel

**Superclass:** [GuiLabel](GuiLabel.md)

The `TextLabel` class is a 2D user interface element that displays non-interactive text, and it provides various properties for controlling its rendering, including text scaling, wrapping, and alignment.

## Properties
### `TextLabel.ContentText`
- **Type:** `string`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A copy of `Class.TextLabel.Text` that contains exactly what is being rendered by the `Class.TextLabel`.

### `TextLabel.Font`
- **Type:** `Enum.Font`
- **Tags:** Hidden, NotReplicated
- **Summary:** Determines the font used to render text.

### `TextLabel.FontFace`
- **Type:** `Datatype.Font`
- **Summary:** Determines the font used to render text.

### `TextLabel.FontSize`
- **Type:** `FontSize`
- **Tags:** NotReplicated, Deprecated
- **Summary:** Determines the font size to be used.

### `TextLabel.LineHeight`
- **Type:** `float`
- **Summary:** Scales the spacing between lines of text in the `Class.TextLabel`.

### `TextLabel.LocalizedText`
- **Type:** `string`
- **Tags:** Hidden, ReadOnly, NotReplicated
- **Summary:** Sets whether a `Class.TextLabel` should be `Class.GuiBase2d.Localize` or not.

### `TextLabel.MaxVisibleGraphemes`
- **Type:** `int`
- **Summary:** The maximum number of graphemes the `Class.TextLabel` can show.

### `TextLabel.OpenTypeFeatures`
- **Type:** `string`

### `TextLabel.OpenTypeFeaturesError`
- **Type:** `string`
- **Tags:** ReadOnly, NotReplicated

### `TextLabel.RichText`
- **Type:** `boolean`
- **Summary:** Determines whether the `Class.TextLabel` renders its text using rich text formatting.

### `TextLabel.Text`
- **Type:** `string`
- **Summary:** Determines the string rendered by the `Class.TextLabel`.

### `TextLabel.TextBounds`
- **Type:** `Vector2`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Read-only property which reflects the absolute size of rendered text in offsets.

### `TextLabel.TextColor`
- **Type:** `BrickColor`
- **Tags:** Hidden, NotReplicated, Deprecated
- **Summary:** Determines the color of text.

### `TextLabel.TextColor3`
- **Type:** `Color3`
- **Summary:** Determines the color of rendered text.

### `TextLabel.TextDirection`
- **Type:** `TextDirection`
- **Summary:** Direction in which the text is rendered.

### `TextLabel.TextFits`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A boolean representation of whether the label's text fits within the size of it.

### `TextLabel.TextScaled`
- **Type:** `boolean`
- **Summary:** Changes whether text is resized to fit within the `Class.TextLabel`.

### `TextLabel.TextSize`
- **Type:** `float`
- **Summary:** Determines the line height of text in offsets.

### `TextLabel.TextStrokeColor3`
- **Type:** `Color3`
- **Summary:** Determines the color of the text stroke (outline).

### `TextLabel.TextStrokeTransparency`
- **Type:** `float`
- **Summary:** Determines the transparency of the text stroke (outline).

### `TextLabel.TextTransparency`
- **Type:** `float`
- **Summary:** Determines the transparency of rendered text.

### `TextLabel.TextTruncate`
- **Type:** `TextTruncate`
- **Summary:** Controls the truncation of the text displayed in the `Class.TextLabel`.

### `TextLabel.TextWrap`
- **Type:** `boolean`
- **Tags:** NotReplicated, Deprecated
- **Summary:** Determines whether or not text should wrap at the edges of the `Class.TextLabel` element's space.

### `TextLabel.TextWrapped`
- **Type:** `boolean`
- **Summary:** Determines if text wraps to multiple lines within the `Class.TextLabel` element's space, truncating excess text.

### `TextLabel.TextXAlignment`
- **Type:** `TextXAlignment`
- **Summary:** Determines the horizontal alignment of rendered text.

### `TextLabel.TextYAlignment`
- **Type:** `TextYAlignment`
- **Summary:** Determines the vertical alignment of rendered text.
