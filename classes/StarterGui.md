# StarterGui

**Superclass:** [BasePlayerGui](BasePlayerGui.md)

The `StarterGui` class is a container for `Class.LayerCollector` objects and provides functions to interact with the `Class.CoreGui`.

## Tags
- NotCreatable
- Service

## Properties
### `StarterGui.ProcessUserInput`
- **Type:** `boolean`
- **Tags:** Hidden, NotReplicated
- **Summary:** Allows this service to process input like `Class.PlayerGui` and `Class.CoreGui` do.

### `StarterGui.ResetPlayerGuiOnSpawn`
- **Type:** `boolean`
- **Tags:** Deprecated
- **Summary:** Determines whether each child parented to the StarterGui will be cloned into a player's PlayerGui when that player's character is respawned.

### `StarterGui.RtlTextSupport`
- **Type:** `RtlTextSupport`
- **Tags:** NotScriptable

### `StarterGui.ScreenOrientation`
- **Type:** `ScreenOrientation`
- **Summary:** Sets the default screen orientation mode for users with mobile devices.

### `StarterGui.ShowDevelopmentGui`
- **Type:** `boolean`
- **Summary:** Determines whether the contents of `Class.StarterGui` is visible in Studio.

### `StarterGui.VirtualCursorMode`
- **Type:** `VirtualCursorMode`
- **Tags:** NotScriptable

## Methods
### `StarterGui:GetCore(parameterName: string) -> Variant`
- **Tags:** Yields
- **Summary:** Returns a variable that has been specified by a Roblox core script.

### `StarterGui:GetCoreGuiEnabled(coreGuiType: CoreGuiType) -> boolean`
- **Summary:** Returns whether the given `Enum.CoreGuiType`is enabled, or if it has been disabled using `Class.StarterGui:SetCoreGuiEnabled()`.

### `StarterGui:SetCore(parameterName: string, value: Variant) -> ()`
- **Summary:** Allows you to perform certain interactions with Roblox's core scripts.

### `StarterGui:SetCoreGuiEnabled(coreGuiType: CoreGuiType, enabled: boolean) -> ()`
- **Summary:** Sets whether the `Class.CoreGui` element associated with the given `Enum.CoreGuiType` is enabled or disabled.
