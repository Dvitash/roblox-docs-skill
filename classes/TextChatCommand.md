# TextChatCommand

**Superclass:** [Instance](Instance.md)

TextChatCommand is a class representing a text chat command that allows users to create custom commands for managing text messages.

## Properties
### `TextChatCommand.AutocompleteVisible`
- **Type:** `boolean`

### `TextChatCommand.Enabled`
- **Type:** `boolean`
- **Summary:** Determines whether the `Class.TextChatCommand` is enabled.

### `TextChatCommand.PrimaryAlias`
- **Type:** `string`
- **Summary:** A primary alias used to trigger the `Class.TextChatCommand`.

### `TextChatCommand.SecondaryAlias`
- **Type:** `string`
- **Summary:** A secondary alias used to trigger the `Class.TextChatCommand`.

## Events
### `TextChatCommand.Triggered(originTextSource: [TextSource](TextSource.md), unfilteredText: string)`
- **Summary:** An event that developers can bind to execute commands.
