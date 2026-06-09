# VirtualInput

**Superclass:** [Object](Object.md)

The `VirtualInput` class simulates mouse, keyboard, and pointer input as if it were real player input, designed for testing only and should not be used for automation.

## Tags
- NotCreatable
- NotReplicated

## Methods
### `VirtualInput:SendKey(isPressed: boolean, keyCode: KeyCode, isRepeatedKey: boolean) -> ()`
- **Summary:** Injects a keyboard key press or release event.

### `VirtualInput:SendMouseButton(position: Vector2, button: UserInputType, isDown: boolean, repeatCount: int) -> ()`
- **Summary:** Injects a mouse button press or release event at the specified screen position.

### `VirtualInput:SendMouseDelta(positionDelta: Vector2) -> ()`
- **Summary:** Injects a relative mouse movement event. Only works while the player's cursor is locked.

### `VirtualInput:SendMousePosition(position: Vector2) -> ()`
- **Summary:** Moves the virtual mouse cursor to the specified absolute screen position.

### `VirtualInput:SendPointerAction(position: Vector2, pointerAction: Dictionary) -> ()`
- **Summary:** Injects a scroll wheel, trackpad pan, or pinch gesture event at the specified screen position.

### `VirtualInput:SendTextInput(text: string) -> ()`
- **Summary:** Injects a text input event as if the specified string was typed on a keyboard.
