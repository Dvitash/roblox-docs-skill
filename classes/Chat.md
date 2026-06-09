# Chat

**Superclass:** [Instance](Instance.md)

The `Chat` class is responsible for running the legacy chat system, which includes code for running the `Class.Chat` script and inserting default objects like `Class.Script|Scripts` and `Class.ModuleScript|ModuleScripts`.

## Tags
- NotCreatable
- Service
- NotReplicated

## Properties
### `Chat.BubbleChatEnabled`
- **Type:** `boolean`
- **Summary:** Determines whether player's chat messages will appear above their in-game avatar.

### `Chat.LoadDefaultChat`
- **Type:** `boolean`
- **Summary:** Toggles whether the default chat framework should be automatically loaded when the game runs.

## Methods
### `Chat:CanUserChatAsync(userId: int64) -> boolean`
- **Tags:** Yields
- **Summary:** Will return false if the player with the specified `Class.Player.UserId` is not allowed to chat because of their account settings.

### `Chat:CanUsersChatAsync(userIdFrom: int64, userIdTo: int64) -> boolean`
- **Tags:** Yields
- **Summary:** Will return false if the two users cannot communicate because their account settings do not allow it.

### `Chat:[Chat](Chat.md)(partOrCharacter: [Instance](Instance.md), message: string, color: ChatColor) -> ()`
- **Summary:** Fires the `Class.Chat.Chatted` event with the parameters specified in this method.

### `Chat:FilterStringAsync(stringToFilter: string, playerFrom: [Player](Player.md), playerTo: [Player](Player.md)) -> string`
- **Tags:** Yields
- **Summary:** Filters a string sent from a player to another player using filtering that is appropriate to the players' account settings.

### `Chat:FilterStringForBroadcast(stringToFilter: string, playerFrom: [Player](Player.md)) -> string`
- **Tags:** Yields
- **Summary:** Filters a string sent from a player meant for broadcast to no particular target. More restrictive than `Class.Chat:FilterStringAsync()`.

### `Chat:FilterStringForPlayerAsync(stringToFilter: string, playerToFilterFor: [Player](Player.md)) -> string`
- **Tags:** Yields, Deprecated
- **Summary:** Filters a string appropriate to the given player's age settings, so they see what is appropriate to them.

### `Chat:InvokeChatCallback(callbackType: ChatCallbackType, callbackArguments: Tuple) -> Tuple`
- **Summary:** Invoke a chat callback function registered by `Class.Chat:RegisterChatCallback()|RegisterChatCallback`. Used by the Luau Chat System.

### `Chat:RegisterChatCallback(callbackType: ChatCallbackType, callbackFunction: Function) -> ()`
- **Summary:** Register a function to be called upon the invocation of some chat system event (`Class.Chat:InvokeChatCallback()|InvokeChatCallback`).

### `Chat:SetBubbleChatSettings(settings: Variant) -> ()`
- **Summary:** Customizes various settings of the in-game bubble chat.

## Events
### `Chat.Chatted(part: [Instance](Instance.md), message: string, color: ChatColor)`
- **Summary:** Fires when `Class.Chat:Chat()` is called.
