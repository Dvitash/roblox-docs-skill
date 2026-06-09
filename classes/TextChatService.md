# TextChatService

**Superclass:** [Instance](Instance.md)

This class manages in-experience text chat, including handling translations, creating commands, and customizing message interfaces.

## Tags
- NotCreatable
- Service

## Properties
### `TextChatService.ChatTranslationEnabled`
- **Type:** `boolean`
- **Tags:** NotReplicated
- **Summary:** Determines whether a user has chat translation enabled.

### `TextChatService.ChatVersion`
- **Type:** `ChatVersion`
- **Summary:** Determines whether to fully enable `Class.TextChatService` or revert to the legacy chat system.

### `TextChatService.CreateDefaultCommands`
- **Type:** `boolean`
- **Summary:** Determines whether `Class.TextChatService` should create default `Class.TextChatCommand|TextChatCommands`.

### `TextChatService.CreateDefaultTextChannels`
- **Type:** `boolean`
- **Summary:** Determines whether `Class.TextChatService` should create default `Class.TextChannel|TextChannels`.

## Methods
### `TextChatService:CanUserChatAsync(userId: int64) -> boolean`
- **Tags:** Yields
- **Summary:** Determines whether a user has permission to chat in experiences.

### `TextChatService:CanUsersChatAsync(userIdFrom: int64, userIdTo: int64) -> boolean`
- **Tags:** Yields
- **Summary:** Determines whether or not two users can receive messages from each other.

### `TextChatService:CanUsersDirectChatAsync(requesterUserId: int64, userIds: Array) -> Array`
- **Tags:** Yields
- **Summary:** Determines whether a user has permission to chat directly with other users in experiences based on factors such as their parental control settings.

### `TextChatService:DisplayBubble(partOrCharacter: [Instance](Instance.md), message: string) -> ()`
- **Summary:** Displays a chat bubble above the provided part or player character.

### `TextChatService:GetChatGroupsAsync(players: Instances) -> Array`
- **Tags:** Yields
- **Summary:** Returns chat group IDs that indicate which players can synchronously text chat together.

## Events
### `TextChatService.BubbleDisplayed(partOrCharacter: [Instance](Instance.md), textChatMessage: [TextChatMessage](TextChatMessage.md))`
- **Summary:** Fires when `Class.TextChatService:DisplayBubble()` is called.

### `TextChatService.MessageReceived(textChatMessage: [TextChatMessage](TextChatMessage.md))`
- **Summary:** Fires when `Class.TextChannel:DisplaySystemMessage()` is invoked on the client, or when the client receives a valid `Class.TextChannel:SendAsync()` response from the server.

### `TextChatService.SendingMessage(textChatMessage: [TextChatMessage](TextChatMessage.md))`
- **Summary:** Fires when `Class.TextChannel:SendAsync()` is called by the sending client.
