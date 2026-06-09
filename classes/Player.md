# Player

**Superclass:** [Instance](Instance.md)

The `Player` class represents a currently connected client in the experience, and it is managed by the `Class.Players` service.

## Properties
### `Player.AccountAge`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Describes the player's account age in days.

### `Player.AutoJumpEnabled`
- **Type:** `boolean`
- **Summary:** Determines whether the character of a player using a mobile device will automatically jump upon hitting an obstacle.

### `Player.CameraMaxZoomDistance`
- **Type:** `float`
- **Summary:** The maximum distance the player's camera is allowed to zoom out.

### `Player.CameraMinZoomDistance`
- **Type:** `float`
- **Summary:** The minimum distance the player's camera is allowed to zoom in.

### `Player.CameraMode`
- **Type:** `CameraMode`
- **Summary:** Changes the camera's mode to either first or third person.

### `Player.CanLoadCharacterAppearance`
- **Type:** `boolean`
- **Summary:** Determines whether the character's appearance will be loaded when the player spawns. If `false`, the player will spawn with a default appearance.

### `Player.Character`
- **Type:** `[Model](Model.md)`
- **Summary:** A `Class.Model` controlled by the player that contains a `Class.Humanoid`, body parts, scripts, and other objects.

### `Player.CharacterAppearance`
- **Type:** `string`
- **Tags:** NotBrowsable, Deprecated
- **Summary:** The URL of the asset containing the character's appearance, clothing, and gear.

### `Player.CharacterAppearanceId`
- **Type:** `int64`
- **Summary:** Determines the user ID of the account whose character appearance is used for a player's `Class.Player.Character|Character`.

### `Player.DataComplexity`
- **Type:** `int`
- **Tags:** Hidden, ReadOnly, NotReplicated, Deprecated
- **Summary:** The total amount of data currently being stored in the player's cache on the current place.

### `Player.DataReady`
- **Type:** `boolean`
- **Tags:** Hidden, ReadOnly, NotReplicated, Deprecated
- **Summary:** Indicates when the player's data is available to load.

### `Player.DevCameraOcclusionMode`
- **Type:** `DevCameraOcclusionMode`
- **Summary:** Sets how the default camera handles objects between the camera and the player.

### `Player.DevComputerCameraMode`
- **Type:** `DevComputerCameraMovementMode`
- **Summary:** Determines player's camera movement mode when using a device with a mouse and keyboard.

### `Player.DevComputerMovementMode`
- **Type:** `DevComputerMovementMode`
- **Summary:** Determines player's character movement mode when using a device with a mouse and keyboard.

### `Player.DevEnableMouseLock`
- **Type:** `boolean`
- **Summary:** Determines if the player can toggle mouse lock.

### `Player.DevTouchCameraMode`
- **Type:** `DevTouchCameraMovementMode`
- **Summary:** Determines player's camera movement mode when using a touch-enabled device.

### `Player.DevTouchMovementMode`
- **Type:** `DevTouchMovementMode`
- **Summary:** Determines player's character movement mode when using a touch-enabled device.

### `Player.DisplayName`
- **Type:** `string`
- **Summary:** The display name of the authenticated user associated with the `Class.Player`.

### `Player.FollowUserId`
- **Type:** `int64`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Describes the user ID of the player who was followed into an experience by a player.

### `Player.GameplayPaused`
- **Type:** `boolean`
- **Tags:** Hidden
- **Summary:** Whether player client-side gameplay is currently paused.

### `Player.HasRobloxSubscription`
- **Type:** `boolean`
- **Summary:** Indicates whether the player has an active Roblox subscription.

### `Player.HasVerifiedBadge`
- **Type:** `boolean`
- **Summary:** Indicates if a player has a **Verified** badge.

### `Player.HealthDisplayDistance`
- **Type:** `float`
- **Summary:** Sets the distance at which this player will see other players' health bars.

### `Player.InputLatency`
- **Type:** `int`

### `Player.LocaleId`
- **Type:** `string`
- **Tags:** Hidden, ReadOnly, NotReplicated
- **Summary:** This property shows the locale ID that the local player has set for their Roblox account.

### `Player.MembershipType`
- **Type:** `MembershipType`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Describes the account's membership type.

### `Player.NameDisplayDistance`
- **Type:** `float`
- **Summary:** Sets the distance at which this player will see other players' names.

### `Player.Neutral`
- **Type:** `boolean`
- **Summary:** Determines whether the player is on a specific team.

### `Player.PartyId`
- **Type:** `string`
- **Tags:** Hidden, NotReplicated
- **Summary:** A unique identifier of the party a `Class.Player` belongs to.

### `Player.ReplicationFocus`
- **Type:** `[Instance](Instance.md)`
- **Summary:** Sets the part to focus replication around.

### `Player.RespawnLocation`
- **Type:** `[SpawnLocation](SpawnLocation.md)`
- **Summary:** If set, the player will respawn at the given `Class.SpawnLocation`.

### `Player.StepIdOffset`
- **Type:** `int`

### `Player.Team`
- **Type:** `[Team](Team.md)`
- **Tags:** NotReplicated
- **Summary:** Determines the `Class.Team` with which the player is associated.

### `Player.TeamColor`
- **Type:** `BrickColor`
- **Summary:** Determines the `Class.Team` with which the player is associated with according to that team's `Class.Team.TeamColor`.

### `Player.ThirdPartyTextChatRestrictionStatus`
- **Type:** `ChatRestrictionStatus`
- **Tags:** ReadOnly, NotReplicated

### `Player.UserId`
- **Type:** `int64`
- **Summary:** A unique identifying integer assigned to all user accounts.

### `Player.userId`
- **Type:** `int64`
- **Tags:** Deprecated

## Methods
### `Player:AddReplicationFocus(part: [BasePart](BasePart.md)) -> ()`
- **Summary:** Adds an additional replication focus for the player.

### `Player:ClearCharacterAppearance() -> ()`
- **Summary:** Removes all accessories and other character appearance objects from a player's `Class.Player.Character|Character`.

### `Player:ClearCachedAvatarAppearance() -> ()`
- **Summary:** Clears the cached avatar appearance for the player, forcing a fresh fetch from the backend on the next respawn.

### `Player:DistanceFromCharacter(point: Vector3) -> float`
- **Summary:** Returns the distance between the character's head and the given `Datatype.Vector3`, or `0` if the player has no character.

### `Player:GetFriendsOnline(maxFriends: int) -> Array`
- **Tags:** Yields, Deprecated
- **Summary:** Returns a dictionary of online friends. Returns the product information of an asset using its asset ID.

### `Player:GetFriendsOnlineAsync(maxFriends: int) -> Array`
- **Tags:** Yields
- **Summary:** Returns a dictionary of online friends.

### `Player:GetFriendsWhoPlayedAsync() -> Array`
- **Tags:** Yields

### `Player:GetJoinData() -> Dictionary`
- **Tags:** CustomLuaState
- **Summary:** Returns a dictionary containing information describing how the player joins the experience.

### `Player:GetMouse() -> [Mouse](Mouse.md)`
- **Summary:** Returns the mouse being used by the client.

### `Player:GetNetworkPing() -> float`
- **Summary:** Returns the round-trip, isolated network latency in seconds.

### `Player:GetRankInGroup(groupId: int64) -> int`
- **Tags:** Yields, Deprecated
- **Summary:** Returns the player's rank in the group as an integer.

### `Player:GetRankInGroupAsync(groupId: int64) -> int`
- **Tags:** Yields, Deprecated
- **Summary:** Returns the player's rank in the group as an integer.

### `Player:GetRoleInGroup(groupId: int64) -> string`
- **Tags:** Yields, Deprecated
- **Summary:** Returns the player's role in the group as a string, or `Guest` if the player isn't part of the group.

### `Player:GetRoleInGroupAsync(groupId: int64) -> string`
- **Tags:** Yields, Deprecated
- **Summary:** Returns the player's role in the group as a string, or `Guest` if the player isn't part of the group.

### `Player:HasAppearanceLoaded() -> boolean`
- **Summary:** Returns whether or not the appearance of the player's character has loaded.

### `Player:IsBestFriendsWith(userId: int64) -> boolean`
- **Tags:** Yields, Deprecated
- **Summary:** Returns whether a player is friends with the specified user.

### `Player:IsFriendsWith(userId: int64) -> boolean`
- **Tags:** Yields, Deprecated
- **Summary:** Checks whether a player is a friend of the user with the given `Class.Player.UserId`.

### `Player:isFriendsWith(userId: int64) -> boolean`
- **Tags:** Yields, Deprecated

### `Player:IsFriendsWithAsync(userId: int64) -> boolean`
- **Tags:** Yields
- **Summary:** Checks whether a player is a friend of the user with the given `Class.Player.UserId`.

### `Player:IsInGroup(groupId: int64) -> boolean`
- **Tags:** Yields, Deprecated
- **Summary:** Checks whether a player is a member of a group with the given ID.

### `Player:IsInGroupAsync(groupId: int64) -> boolean`
- **Tags:** Yields
- **Summary:** Checks whether a player is a member of a group with the given ID.

### `Player:IsVerified() -> boolean`
- **Summary:** Returns whether the player is verified with concrete, real-world signals.

### `Player:Kick(message: string) -> ()`
- **Summary:** Forcibly disconnect a player from the experience, optionally providing a message.

### `Player:LoadBoolean(key: string) -> boolean`
- **Tags:** Deprecated
- **Summary:** Returns a boolean value that was previously saved to the player with `Class.Player:SaveBoolean()` with the same key.

### `Player:loadBoolean(key: string) -> boolean`
- **Tags:** Deprecated

### `Player:LoadCharacter() -> ()`
- **Tags:** Yields, Deprecated
- **Summary:** Creates a new character for the player, removing the old one. Also clears the player's `Class.Backpack` and `Class.PlayerGui`.

### `Player:LoadCharacterAppearance(assetInstance: [Instance](Instance.md)) -> ()`
- **Tags:** Deprecated
- **Summary:** Places the given instance either in the player's character, head, or StarterGear based on the instance's class.

### `Player:LoadCharacterAsync() -> ()`
- **Tags:** Yields
- **Summary:** Creates a new character for the player, removing the old one. Also clears the player's `Class.Backpack` and `Class.PlayerGui`.

### `Player:LoadCharacterWithHumanoidDescription(humanoidDescription: [HumanoidDescription](HumanoidDescription.md), assetTypeVerification: AssetTypeVerification) -> ()`
- **Tags:** Yields, Deprecated
- **Summary:** Spawns a player character with everything equipped in the passed in `Class.HumanoidDescription`.

### `Player:LoadCharacterWithHumanoidDescriptionAsync(humanoidDescription: [HumanoidDescription](HumanoidDescription.md), assetTypeVerification: AssetTypeVerification) -> ()`
- **Tags:** Yields
- **Summary:** Spawns a player character with everything equipped in the passed in `Class.HumanoidDescription`.

### `Player:LoadInstance(key: string) -> [Instance](Instance.md)`
- **Tags:** Deprecated
- **Summary:** Returns an instance that was previously saved to the player with `Class.Player:SaveInstance()` with the same key.

### `Player:loadInstance(key: string) -> [Instance](Instance.md)`
- **Tags:** Deprecated

### `Player:LoadNumber(key: string) -> double`
- **Tags:** Deprecated
- **Summary:** Returns a number value that was previously saved to the player.

### `Player:loadNumber(key: string) -> double`
- **Tags:** Deprecated

### `Player:LoadString(key: string) -> string`
- **Tags:** Deprecated
- **Summary:** Returns a string value that was previously saved to the player.

### `Player:loadString(key: string) -> string`
- **Tags:** Deprecated

### `Player:Move(walkDirection: Vector3, relativeToCamera: boolean) -> ()`
- **Summary:** Causes the player's character to walk in the given direction until stopped, or interrupted by the player (by using their controls).

### `Player:RemoveReplicationFocus(part: [BasePart](BasePart.md)) -> ()`
- **Summary:** Removes a previously added replication focus.

### `Player:RequestStreamAroundAsync(position: Vector3, timeOut: double) -> ()`
- **Tags:** Yields
- **Summary:** Requests that the server stream to the player around the specified location.

### `Player:SaveBoolean(key: string, value: boolean) -> ()`
- **Tags:** Deprecated
- **Summary:** Used to save a boolean value that can be loaded again at a later time using `Class.Player:LoadBoolean()`.

### `Player:saveBoolean(key: string, value: boolean) -> ()`
- **Tags:** Deprecated

### `Player:SaveInstance(key: string, value: [Instance](Instance.md)) -> ()`
- **Tags:** Deprecated
- **Summary:** Saves an instance which can be loaded again at a later time.

### `Player:saveInstance(key: string, value: [Instance](Instance.md)) -> ()`
- **Tags:** Deprecated

### `Player:SaveNumber(key: string, value: double) -> ()`
- **Tags:** Deprecated
- **Summary:** Saves a number value that can be loaded again at a later time using.

### `Player:saveNumber(key: string, value: double) -> ()`
- **Tags:** Deprecated

### `Player:SaveString(key: string, value: string) -> ()`
- **Tags:** Deprecated
- **Summary:** Saves a string value that can be loaded again at a later time.

### `Player:saveString(key: string, value: string) -> ()`
- **Tags:** Deprecated

### `Player:SetAccountAge(accountAge: int) -> ()`
- **Summary:** Sets the `Class.Player.AccountAge|AccountAge` of the player.

### `Player:SetSuperSafeChat(value: boolean) -> ()`
- **Summary:** Sets whether or not the player sees filtered chats, rather than normal chats.

### `Player:WaitForDataReady() -> boolean`
- **Tags:** Yields, Deprecated
- **Summary:** Used to pause the script until the player's data is available to manipulate, or until a certain amount of time has elapsed without fetching the player's data.

### `Player:waitForDataReady() -> boolean`
- **Tags:** Yields, Deprecated

## Events
### `Player.CharacterAdded(character: [Model](Model.md))`
- **Summary:** Fires when a player's character spawns or respawns.

### `Player.CharacterAppearanceLoaded(character: [Model](Model.md))`
- **Summary:** Fires when the full appearance of a `Class.Player.Character|Character` has been inserted.

### `Player.CharacterRemoving(character: [Model](Model.md))`
- **Summary:** Fires right before a player's character is removed.

### `Player.Chatted(message: string, recipient: [Player](Player.md))`
- **Summary:** Fires when a player chats in experience using Roblox's provided chat bar.

### `Player.Idled(time: double)`
- **Summary:** This event fires approximately two minutes after the engine classifies the player as idle. Time is the number of seconds that have elapsed since that point.

### `Player.OnTeleport(teleportState: TeleportState, placeId: int64, spawnName: string)`
- **Summary:** Fires when the teleport state of a player changes.
