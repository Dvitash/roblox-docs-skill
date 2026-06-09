# BubbleChatConfiguration

**Superclass:** [TextChatConfigurations](TextChatConfigurations.md)

This file defines `BubbleChatConfiguration` classes that allow for customization of text chat bubbles by providing methods for setting `AdorneeName`, `BackgroundColor3`, `BackgroundTransparency`, and `BubbleDuration`.

## Tags
- NotCreatable

## Properties
### `BubbleChatConfiguration.AdorneeName`
- **Type:** `string`
- **Summary:** Body part or `Class.Attachment` that bubbles will attach to.

### `BubbleChatConfiguration.BackgroundColor3`
- **Type:** `Color3`
- **Summary:** Background color of bubbles.

### `BubbleChatConfiguration.BackgroundTransparency`
- **Type:** `double`
- **Summary:** Determines the background transparency of the default bubble chat as a number between 0 and 1.

### `BubbleChatConfiguration.BubbleDuration`
- **Type:** `float`
- **Summary:** Time before a bubble fades out, in seconds.

### `BubbleChatConfiguration.BubblesSpacing`
- **Type:** `float`
- **Summary:** Vertical space between stacked bubbles, in pixels.

### `BubbleChatConfiguration.Enabled`
- **Type:** `boolean`
- **Summary:** Whether text chat bubbles are enabled.

### `BubbleChatConfiguration.Font`
- **Type:** `Enum.Font`
- **Tags:** Hidden
- **Summary:** `Datatype.Font` of the bubble text.

### `BubbleChatConfiguration.FontFace`
- **Type:** `Datatype.Font`
- **Summary:** `Datatype.Font` of the bubble text.

### `BubbleChatConfiguration.LocalPlayerStudsOffset`
- **Type:** `Vector3`
- **Summary:** Offset of bubbles from their adornee, in studs.

### `BubbleChatConfiguration.MaxBubbles`
- **Type:** `float`
- **Summary:** Maximum number of text chat bubbles shown per user.

### `BubbleChatConfiguration.MaxDistance`
- **Type:** `float`
- **Summary:** Maximum distance from the camera that bubbles are shown.

### `BubbleChatConfiguration.MinimizeDistance`
- **Type:** `float`
- **Summary:** Distance from the camera when bubbles turn into a single bubble with an ellipsis to indicate chatter.

### `BubbleChatConfiguration.TailVisible`
- **Type:** `boolean`
- **Summary:** Determines if the tail at the bottom of the text chat bubbles is visible.

### `BubbleChatConfiguration.TextColor3`
- **Type:** `Color3`
- **Summary:** Color of bubble text.

### `BubbleChatConfiguration.TextSize`
- **Type:** `int64`
- **Summary:** Size of bubble text.

### `BubbleChatConfiguration.VerticalStudsOffset`
- **Type:** `float`
- **Summary:** Extra space between bubbles and their adornee, in studs.
