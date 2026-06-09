# TextChannel

**Superclass:** [Instance](Instance.md)

The `Class.TextChannel` is a class representing a text chat channel, which contains `Class.TextSource` descendants and allows users to send messages to it.

## Properties
### `TextChannel.DirectChatRequester`
- **Type:** `[Player](Player.md)`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The `TextChannel` will only deliver messages to users that can send direct messages to the `DirectChatRequester`.

## Methods
### `TextChannel:AddUserAsync(userId: int64) -> Tuple`
- **Tags:** Yields
- **Summary:** Adds a `Class.TextSource` to the `Class.TextChannel` given userId of a `Class.Player`.

### `TextChannel:DisplaySystemMessage(systemMessage: string, metadata: string) -> [TextChatMessage](TextChatMessage.md)`
- **Summary:** Displays a system message to the user.

### `TextChannel:SendAsync(message: string, metadata: string) -> [TextChatMessage](TextChatMessage.md)`
- **Tags:** Yields
- **Summary:** Sends a `Class.TextChatMessage` to the server.

### `TextChannel:SetDirectChatRequester(requester: [Player](Player.md)) -> ()`
- **Summary:** Sets the `Class.TextChannel.DirectChatRequester|DirectChatRequester` for the `TextChannel`. The `TextChannel` will only deliver messages to users that can send direct messages to the `DirectChatRequester`.

## Events
### `TextChannel.MessageReceived(incomingMessage: [TextChatMessage](TextChatMessage.md))`
- **Summary:** Fires when `Class.TextChannel:DisplaySystemMessage()` is invoked on the client, or when the client receives a valid `Class.TextChannel:SendAsync()` response from the server.
