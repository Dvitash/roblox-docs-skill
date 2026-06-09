# GamepadService

**Superclass:** [Instance](Instance.md)

The GamepadService is a class responsible for handling gamepad input from controllers like Xbox One and PlayStation DualShock. It manages the virtual cursor state and provides methods to enable or disable it.

## Tags
- NotCreatable
- Service
- NotReplicated

## Properties
### `GamepadService.GamepadCursorEnabled`
- **Type:** `boolean`
- **Summary:** The state of the gamepad virtual cursor.

## Methods
### `GamepadService:DisableGamepadCursor() -> ()`
- **Summary:** Disables the gamepad cursor, if currently enabled.

### `GamepadService:EnableGamepadCursor(guiObject: [Instance](Instance.md)) -> ()`
- **Summary:** Enables the gamepad cursor or updates its position.
