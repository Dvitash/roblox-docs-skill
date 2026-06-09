# TextChatMessage

**Superclass:** [Instance](Instance.md)

This file defines a `TextChatMessage` class, which represents a text chat message, and provides methods for manipulating its properties and displaying custom messages to the user.

## Tags
- NotCreatable

## Properties
### `TextChatMessage.BubbleChatMessageProperties`
- **Type:** `[BubbleChatMessageProperties](BubbleChatMessageProperties.md)`

### `TextChatMessage.ChatWindowMessageProperties`
- **Type:** `[ChatWindowMessageProperties](ChatWindowMessageProperties.md)`

### `TextChatMessage.MessageId`
- **Type:** `string`
- **Summary:** A unique identifier for the `Class.TextChatMessage`.

### `TextChatMessage.Metadata`
- **Type:** `string`
- **Summary:** A general purpose field for storing miscellaneous data about the `Class.TextChatMessage`.

### `TextChatMessage.PrefixText`
- **Type:** `string`
- **Summary:** A prefix to add to a user's message.

### `TextChatMessage.Status`
- **Type:** `TextChatMessageStatus`
- **Summary:** Indicates the status of the `Class.TextChatMessage`.

### `TextChatMessage.Text`
- **Type:** `string`
- **Summary:** The filtered text message for the user.

### `TextChatMessage.TextChannel`
- **Type:** `[TextChannel](TextChannel.md)`
- **Summary:** A reference to the origin `Class.TextChannel`.

### `TextChatMessage.TextSource`
- **Type:** `[TextSource](TextSource.md)`
- **Summary:** A reference to the origin `Class.TextSource`.

### `TextChatMessage.Timestamp`
- **Type:** `DateTime`
- **Summary:** A timestamp of when the message was originally sent.

### `TextChatMessage.Translation`
- **Type:** `string`
- **Summary:** Translated and filtered text message.
