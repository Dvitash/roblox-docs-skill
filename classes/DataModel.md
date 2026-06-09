# DataModel

**Superclass:** [ServiceProvider](ServiceProvider.md)

### DataModel **Data Model (Common Name: game)** - **Type:** class - **Memory Category:** Instances - **Description:** The root of Roblox's parent-child hierarchy, which contains fundamental components like `Class.Workspace` and `Class.Lighting`. - **Inherits:** ServiceProvider - **Descendants:** [] - **Tags:** - NotCreatable - ReadOnly - NotReplicated - DeprecationMessage: '' - **Properties:** - name: DataModel.CreatorId - Summary: Describes the ID of the user or group that owns the place. -…

## Tags
- NotCreatable

## Properties
### `DataModel.CreatorId`
- **Type:** `int64`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Describes the ID of the user or group that owns the place.

### `DataModel.CreatorType`
- **Type:** `CreatorType`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Describes the `Enum.CreatorType` of the place, whether the place is owned by a user or a group.

### `DataModel.Environment`
- **Type:** `string`
- **Tags:** ReadOnly, NotReplicated

### `DataModel.GameId`
- **Type:** `int64`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Describes the ID of the experience that the place running on the server belongs to.

### `DataModel.GearGenreSetting`
- **Type:** `GearGenreSetting`
- **Tags:** ReadOnly, NotReplicated, Deprecated
- **Summary:** Not functional. Historically described the gear permissions of the place as set on the Roblox website.

### `DataModel.Genre`
- **Type:** `Genre`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Not functional. Historically described the `Enum.Genre` of the place as set on the Roblox website.

### `DataModel.JobId`
- **Type:** `string`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A unique identifier for the running game server instance.

### `DataModel.lighting`
- **Type:** `[Instance](Instance.md)`
- **Tags:** ReadOnly, NotReplicated, Deprecated
- **Summary:** Refers to the game's `Class.Lighting` service.

### `DataModel.MatchmakingType`
- **Type:** `MatchmakingType`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Represents how players in the server are handled by matchmaking.

### `DataModel.PlaceId`
- **Type:** `int64`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Describes the ID of the place running on the server.

### `DataModel.PlaceVersion`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Describes the version of the place the server is running on.

### `DataModel.PrivateServerId`
- **Type:** `string`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Describes the private server ID of the server, if the server is a private server or a `Class.TeleportService:ReserveServerAsync()|reserved server`.

### `DataModel.PrivateServerOwnerId`
- **Type:** `int64`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Describes the `Class.Player.UserId|UserId` of the `Class.Player` that owns the private server if the server is private.

### `DataModel.RunService`
- **Type:** `[RunService](RunService.md)`
- **Tags:** ReadOnly, NotReplicated

### `DataModel.VIPServerId`
- **Type:** `string`
- **Tags:** Hidden, ReadOnly, NotReplicated, Deprecated
- **Summary:** A string that could identify the current server as a private server.

### `DataModel.VIPServerOwnerId`
- **Type:** `int64`
- **Tags:** Hidden, ReadOnly, NotReplicated, Deprecated
- **Summary:** The `Class.Player.UserId|UserId` of the account who owns the private server.

### `DataModel.Workspace`
- **Type:** `[Workspace](Workspace.md)`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A reference to the `Class.Workspace` service.

### `DataModel.workspace`
- **Type:** `[Workspace](Workspace.md)`
- **Tags:** ReadOnly, NotReplicated, Deprecated

## Methods
### `DataModel:BindToClose(function: Function) -> ()`
- **Summary:** Binds a function to be called before the server shuts down.

### `DataModel:GetJobsInfo() -> Array`
- **Summary:** Returns a table containing basic information about the jobs performed by the task scheduler.

### `DataModel:GetMessage() -> string`
- **Tags:** Deprecated
- **Summary:** **_[OBSOLETE]:_** This function will always return a blank string.

### `DataModel:GetObjects(url: ContentId) -> Instances`
- **Summary:** Returns an array of `Class.Instance|Instances` associated with the given content URL.

### `DataModel:GetRemoteBuildMode() -> boolean`
- **Tags:** Deprecated
- **Summary:** This method is no longer useful and will always return false.

### `DataModel:IsGearTypeAllowed(gearType: GearType) -> boolean`
- **Tags:** Deprecated
- **Summary:** Returns whether gear of the given `Enum.GearType` is permitted to be added to `Class.Player|Players'` `Class.StarterGear|StarterGears`.

### `DataModel:IsLoaded() -> boolean`
- **Summary:** Returns true if the client has finished loading the game for the first time.

### `DataModel:SavePlace(saveFilter: SaveFilter) -> boolean`
- **Tags:** Yields, Deprecated
- **Summary:** Saves the current place.

### `DataModel:SetPlaceId(placeId: int64) -> ()`
- **Summary:** Sets the `Class.DataModel.PlaceId` of the current game instance.

### `DataModel:SetUniverseId(universeId: int64) -> ()`
- **Summary:** Sets the `Class.DataModel.GameId` of the current game instance to the given `universeId`.

## Events
### `DataModel.AllowedGearTypeChanged()`
- **Tags:** Deprecated
- **Summary:** Fires when SetGearSettings is called with a different value for `allowedGenres`.

### `DataModel.GraphicsQualityChangeRequest(betterQuality: boolean)`
- **Summary:** Fires when the user prompts and increase or decrease in graphics quality using the hotkeys.

### `DataModel.ItemChanged(object: [Instance](Instance.md), descriptor: string)`
- **Tags:** Deprecated
- **Summary:** Fires when a property of any object in the `Class.DataModel` is changed.

### `DataModel.Loaded()`
- **Summary:** Fires on the client when the game finishes loading for the first time.

### `DataModel.ServerLifecycleChanged(serverLifecycleChangedEvent: Dictionary)`
