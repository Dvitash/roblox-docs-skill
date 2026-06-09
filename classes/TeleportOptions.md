# TeleportOptions

**Superclass:** [Instance](Instance.md)

TeleportOptions is an optional class in `Class.TeleportService` that allows developers to pass arguments to the `TeleportAsync()` function, which determines how players are teleported between servers.

## Properties
### `TeleportOptions.ReservedServerAccessCode`
- **Type:** `string`
- **Summary:** The reserved server access code that indicates the reserved server that the teleport should be to.

### `TeleportOptions.ServerInstanceId`
- **Type:** `string`
- **Summary:** The `Class.DataModel.JobId` of the server instance to teleport to.

### `TeleportOptions.ShouldReserveServer`
- **Type:** `boolean`
- **Summary:** A flag to indicate if a reserved server should be allocated and the players should then be teleported to this allocation.

## Methods
### `TeleportOptions:GetTeleportData() -> Variant`
- **Summary:** Returns the teleport data stored in the `Class.TeleportOptions` instance by `Class.TeleportOptions:SetTeleportData()`.

### `TeleportOptions:SetTeleportData(teleportData: Variant) -> ()`
- **Summary:** Setter function for data to be passed to the destination place.
