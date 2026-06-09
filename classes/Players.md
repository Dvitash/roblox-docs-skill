# Players

**Superclass:** [Instance](Instance.md)

The `Class.Players` class contains `Class.Player` objects for connected clients and information about server configuration, including player appearances and avatar thumbnails.

## Tags
- NotCreatable
- Service

## Properties
### `Players.BanningEnabled`
- **Type:** `boolean`
- **Tags:** NotScriptable
- **Summary:** Enables or disables the three `Class.Players` methods (`Class.Players:BanAsync()|BanAsync()`, `Class.Players:UnbanAsync()|UnbanAsync()`, and `Class.Players:GetBanHistoryAsync()|GetBanHistoryAsync()`) that constitute the ban API. This property is not scriptable and can only be modified in Studio.

### `Players.BubbleChat`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Indicates whether or not bubble chat is enabled. It is set with the `Class.Players:SetChatStyle()` method.

### `Players.CharacterAutoLoads`
- **Type:** `boolean`
- **Tags:** NotReplicated
- **Summary:** Indicates whether `Class.Player.Character|characters` will respawn automatically.

### `Players.ClassicChat`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Indicates whether or not classic chat is enabled; set by the `Class.Players:SetChatStyle()` method.

### `Players.LocalPlayer`
- **Type:** `[Player](Player.md)`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The `Class.Player` that the `Class.LocalScript` is running for.

### `Players.localPlayer`
- **Type:** `[Player](Player.md)`
- **Tags:** Hidden, ReadOnly, NotReplicated, Deprecated

### `Players.MaxPlayers`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The maximum number of players that can be in a server.

### `Players.NumPlayers`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated, Deprecated
- **Summary:** Returns the number of people in the server at the current time.

### `Players.numPlayers`
- **Type:** `int`
- **Tags:** Hidden, ReadOnly, NotReplicated, Deprecated
- **Summary:** Returns the number of people in the server at the current time.

### `Players.PreferredPlayers`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The preferred number of players for a server.

### `Players.RespawnTime`
- **Type:** `float`
- **Summary:** Controls the amount of time taken for a players character to respawn.

### `Players.UseStrafingAnimations`
- **Type:** `boolean`
- **Tags:** NotScriptable

## Methods
### `Players:BanAsync(config: Dictionary) -> ()`
- **Tags:** Yields
- **Summary:** Bans users from your experience, with options to specify duration, reason, whether the ban applies to the entire universe or just the current place, and more. This method is enabled and disabled by the `Class.Players.BanningEnabled` property, which you can toggle in Studio.

### `Players:[Chat](Chat.md)(message: string) -> ()`
- **Summary:** Makes the local player chat the given message.

### `Players:CreateHumanoidModelFromDescription(description: [HumanoidDescription](HumanoidDescription.md), rigType: HumanoidRigType, assetTypeVerification: AssetTypeVerification) -> [Model](Model.md)`
- **Tags:** Yields, Deprecated
- **Summary:** Returns a character `Class.Model` equipped with everything specified in the passed in `Class.HumanoidDescription`.

### `Players:CreateHumanoidModelFromDescriptionAsync(description: [HumanoidDescription](HumanoidDescription.md), rigType: HumanoidRigType, assetTypeVerification: AssetTypeVerification) -> [Model](Model.md)`
- **Tags:** Yields
- **Summary:** Returns a character `Class.Model` equipped with everything specified in the passed in `Class.HumanoidDescription`. If `HumanoidDescription.UseAvatarSettings` is set to true, Avatar Settings in the experience will be applied to the returned model.

### `Players:CreateHumanoidModelFromUserId(userId: int64) -> [Model](Model.md)`
- **Tags:** Yields, Deprecated
- **Summary:** Returns a character Model set-up with everything equipped to match the avatar of the user specified by the passed in userId.

### `Players:CreateHumanoidModelFromUserIdAsync(userId: int64) -> [Model](Model.md)`
- **Tags:** Yields
- **Summary:** Returns a character Model set-up with everything equipped to match the avatar of the user specified by the passed in userId.

### `Players:GetBanHistoryAsync(userId: int64) -> [BanHistoryPages](BanHistoryPages.md)`
- **Tags:** Yields
- **Summary:** Retrieves the ban and unban history of any user within the experience's universe. This method is enabled and disabled by the `Class.Players.BanningEnabled` property, which you can toggle in Studio.

### `Players:GetCharacterAppearanceAsync(userId: int64) -> [Model](Model.md)`
- **Tags:** Yields, Deprecated
- **Summary:** Returns a `Class.Model` containing the assets which the player is wearing, excluding gear.

### `Players:GetCharacterAppearanceInfoAsync(userId: int64) -> Dictionary`
- **Tags:** Yields
- **Summary:** Returns information about the character appearance of a given user.

### `Players:GetFriendsAsync(userId: int64) -> [FriendPages](FriendPages.md)`
- **Tags:** Yields
- **Summary:** Returns a `Class.FriendPages` object which contains information for all of the given player's friends.

### `Players:GetHumanoidDescriptionFromOutfitId(outfitId: int64) -> [HumanoidDescription](HumanoidDescription.md)`
- **Tags:** Yields, Deprecated
- **Summary:** Returns the HumanoidDescription for a specified outfit, which will be set with the parts/colors/Animations etc of the outfit.

### `Players:GetHumanoidDescriptionFromOutfitIdAsync(outfitId: int64) -> [HumanoidDescription](HumanoidDescription.md)`
- **Tags:** Yields
- **Summary:** Returns the HumanoidDescription for a specified outfit, which will be set with the parts/colors/Animations etc of the outfit.

### `Players:GetHumanoidDescriptionFromUserId(userId: int64) -> [HumanoidDescription](HumanoidDescription.md)`
- **Tags:** Yields, Deprecated
- **Summary:** Returns a HumanoidDescription which specifies everything equipped for the avatar of the user specified by the passed in userId.

### `Players:GetHumanoidDescriptionFromUserIdAsync(userId: int64) -> [HumanoidDescription](HumanoidDescription.md)`
- **Tags:** Yields
- **Summary:** Returns a HumanoidDescription which specifies everything equipped for the avatar of the user specified by the passed in userId.

### `Players:GetNameFromUserIdAsync(userId: int64) -> string`
- **Tags:** Yields
- **Summary:** Sends a query to the Roblox website for the username of an account with a given `Class.Player.UserId|UserId`.

### `Players:GetPlayerByUserId(userId: int64) -> [Player](Player.md)`
- **Summary:** Returns the `Class.Player` with the given `Class.Player.UserId|UserId` if they are in-experience.

### `Players:GetPlayerFromCharacter(character: [Model](Model.md)) -> [Player](Player.md)`
- **Summary:** Returns the `Class.Player` whose `Class.Player.Character` matches the given instance, or `nil` if one cannot be found.

### `Players:GetPlayers() -> List<[Player](Player.md)>`
- **Summary:** Returns a table of all presently connected `Class.Player` objects.

### `Players:getPlayers() -> List<[Player](Player.md)>`
- **Tags:** Deprecated

### `Players:GetUserIdFromNameAsync(userName: string) -> int64`
- **Tags:** Yields
- **Summary:** Sends a query to the Roblox website for the `Class.Player.UserId|userId` of an account with a given username.

### `Players:GetUserThumbnailAsync(userId: int64, thumbnailType: ThumbnailType, thumbnailSize: ThumbnailSize) -> Tuple`
- **Tags:** Yields
- **Summary:** Returns the content URL of a player thumbnail given the size and type, as well as a boolean describing if the image is ready to use.

### `Players:playerFromCharacter(character: [Model](Model.md)) -> [Player](Player.md)`
- **Tags:** Deprecated

### `Players:players() -> List<[Player](Player.md)>`
- **Tags:** Deprecated
- **Summary:** Returns a list of players in an experience.

### `Players:SetChatStyle(style: ChatStyle) -> ()`
- **Summary:** Sets whether BubbleChat and ClassicChat are being used, and tells TeamChat and `Class.Chat` what to do.

### `Players:TeamChat(message: string) -> ()`
- **Summary:** Makes the local player chat the given message, which will only be viewable by users on the same team.

### `Players:UnbanAsync(config: Dictionary) -> ()`
- **Tags:** Yields
- **Summary:** Unbans players banned from `Class.Players:BanAsync()` or the User Restrictions Open Cloud API. This method is enabled and disabled by the `Class.Players.BanningEnabled` property, which you can toggle in Studio.

## Events
### `Players.PlayerAdded(player: [Player](Player.md))`
- **Summary:** Fires when a player enters the experience.

### `Players.PlayerMembershipChanged(player: [Player](Player.md))`
- **Summary:** Fires when the experience server recognizes that a player's membership has changed.

### `Players.PlayerRemoving(player: [Player](Player.md), reason: PlayerExitReason)`
- **Summary:** Fires when a player is about to leave the experience.

### `Players.UserSubscriptionStatusChanged(user: [Player](Player.md), subscriptionId: string)`
- **Summary:** Fires when the experience server recognizes that the user's status for a certain subscription has changed.
