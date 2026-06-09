# PlayerScripts

**Superclass:** [Instance](Instance.md)

This file defines `PlayerScripts` as a container for client-side scripts within `Class.Player` objects, which are automatically created when a player joins the game.

## Tags
- NotCreatable
- NotReplicated

## Methods
### `PlayerScripts:ClearComputerCameraMovementModes() -> ()`
- **Summary:** Unregisters all `ComputerCameraMovementMode` enums from the game's settings menu.

### `PlayerScripts:ClearComputerMovementModes() -> ()`
- **Summary:** Unregisters all `ComputerMovementMode` enums from the game's settings menu.

### `PlayerScripts:ClearTouchCameraMovementModes() -> ()`
- **Summary:** Unregisters all `TouchCameraMovementMode` enums from the game's settings menu.

### `PlayerScripts:ClearTouchMovementModes() -> ()`
- **Summary:** Unregisters all `TouchMovementMode` enums from the game's settings menu.

### `PlayerScripts:RegisterComputerCameraMovementMode(cameraMovementMode: ComputerCameraMovementMode) -> ()`
- **Summary:** Registers that a computer camera movement mode is available to be selected from the game menu.

### `PlayerScripts:RegisterComputerMovementMode(movementMode: ComputerMovementMode) -> ()`
- **Summary:** Registers that a computer movement mode is available to be selected from the game menu.

### `PlayerScripts:RegisterTouchCameraMovementMode(cameraMovementMode: TouchCameraMovementMode) -> ()`
- **Summary:** Registers that a touch camera movement mode is available to be selected from the game menu.

### `PlayerScripts:RegisterTouchMovementMode(movementMode: TouchMovementMode) -> ()`
- **Summary:** Registers that a touch movement mode is available to be selected from the game menu.
