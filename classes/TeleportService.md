# TeleportService

**Superclass:** [Instance](Instance.md)

TeleportService is a class responsible for transporting `Class.Player|Players` between different places and servers, managing the teleportation process and providing UI elements.

## Tags
- NotCreatable
- Service

## Properties
### `TeleportService.CustomizedTeleportUI`
- **Type:** `boolean`
- **Tags:** NotReplicated, Deprecated
- **Summary:** No longer functional.

## Methods
### `TeleportService:GetArrivingTeleportGui() -> [Instance](Instance.md)`
- **Summary:** Returns the _customLoadingScreen_ the `Class.Players.LocalPlayer|LocalPlayer` arrived into the place with.

### `TeleportService:GetLocalPlayerTeleportData() -> Variant`
- **Summary:** Returns the _teleportData_ the `Class.Players.LocalPlayer` arrived into the place with.

### `TeleportService:GetPlayerPlaceInstanceAsync(userId: int64) -> Tuple`
- **Tags:** Yields
- **Summary:** Returns the `Class.DataModel.PlaceId|PlaceId` and `Class.DataModel.JobId|JobId` of the server the user with the given `Class.Player.UserId|UserId` is in provided it is in the same game as the current place.

### `TeleportService:GetTeleportSetting(setting: string) -> Variant`
- **Summary:** Retrieves a teleport setting saved using `Class.TeleportService:SetTeleportSetting()` using the given key.

### `TeleportService:PromptExperienceDetailsAsync(player: [Player](Player.md), universeId: int64) -> PromptExperienceDetailsResult`
- **Tags:** Yields
- **Summary:** Prompts a `Class.Player` with information about the specified experience. The player can choose to teleport to the target experience through the prompt.

### `TeleportService:ReserveServer(placeId: int64) -> Tuple`
- **Tags:** Yields, Deprecated
- **Summary:** Returns an access code that can be used to teleport players to a reserved server, along with the `Class.DataModel.PrivateServerId` for it.

### `TeleportService:ReserveServerAsync(placeId: int64) -> Tuple`
- **Tags:** Yields
- **Summary:** Returns an access code that can be used to teleport players to a reserved server, along with the `Class.DataModel.PrivateServerId` for it.

### `TeleportService:SetTeleportGui(gui: [Instance](Instance.md)) -> ()`
- **Summary:** Sets the custom `Class.ScreenGui|teleport GUI` that will be shown to the local user during teleportation, prior to the teleport being invoked.

### `TeleportService:SetTeleportSetting(setting: string, value: Variant) -> ()`
- **Summary:** Stores a value under a given key that persists across all teleportations in the same game.

### `TeleportService:Teleport(placeId: int64, player: [Instance](Instance.md), teleportData: Variant, customLoadingScreen: [Instance](Instance.md)) -> ()`
- **Summary:** Teleports a `Class.Player` to the place associated with the given `placeId`.

### `TeleportService:TeleportAsync(placeId: int64, players: Instances, teleportOptions: [Instance](Instance.md)) -> [Instance](Instance.md)`
- **Tags:** Yields
- **Summary:** The all-encompassing method to teleport a player or group of players from one server to another.

### `TeleportService:TeleportPartyAsync(placeId: int64, players: Instances, teleportData: Variant, customLoadingScreen: [Instance](Instance.md)) -> string`
- **Tags:** Yields
- **Summary:** Teleports a group of `Class.Player|Players` to the same server of the place with the given `Class.DataModel.PlaceId|PlaceId`, returning the `Class.DataModel.JobId|JobId` of the server instance they were teleported to.

### `TeleportService:TeleportToPlaceInstance(placeId: int64, instanceId: string, player: [Instance](Instance.md), spawnName: string, teleportData: Variant, customLoadingScreen: [Instance](Instance.md)) -> ()`
- **Summary:** Teleports a `Class.Player` to the server instance associated with the given _placeId_ and _instanceId_.

### `TeleportService:TeleportToPrivateServer(placeId: int64, reservedServerAccessCode: string, players: Instances, spawnName: string, teleportData: Variant, customLoadingScreen: [Instance](Instance.md)) -> ()`
- **Summary:** Teleport a group of `Class.Player|Players` to a reserved server created using `Class.TeleportService:ReserveServerAsync()`.

### `TeleportService:TeleportToSpawnByName(placeId: int64, spawnName: string, player: [Instance](Instance.md), teleportData: Variant, customLoadingScreen: [Instance](Instance.md)) -> ()`
- **Summary:** A variant of `Class.TeleportService:Teleport()` that causes the `Class.Player` to spawn at a `Class.SpawnLocation` of the given name at the destination place.

## Events
### `TeleportService.LocalPlayerArrivedFromTeleport(loadingGui: [Instance](Instance.md), dataTable: Variant)`
- **Summary:** Fires when the `Class.Players.LocalPlayer|LocalPlayer` enters the place following a teleport.

### `TeleportService.TeleportInitFailed(player: [Instance](Instance.md), teleportResult: TeleportResult, errorMessage: string, placeId: int64, teleportOptions: [Instance](Instance.md))`
- **Summary:** Fires when a teleport fails to start, leaving the player in their current server.
