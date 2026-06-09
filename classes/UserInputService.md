# UserInputService

**Superclass:** [Instance](Instance.md)

This file defines `UserInputService` classes for detecting device input types and events, allowing for client-side scripting.

## Tags
- NotCreatable
- Service
- NotReplicated

## Properties
### `UserInputService.AccelerometerEnabled`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Describes whether the user's device has an accelerometer.

### `UserInputService.GamepadEnabled`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Describes whether the user's device has an available gamepad.

### `UserInputService.GyroscopeEnabled`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Describes whether the user's device has a gyroscope.

### `UserInputService.KeyboardEnabled`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Describes whether the user's device has a keyboard available.

### `UserInputService.ModalEnabled`
- **Type:** `boolean`
- **Tags:** Deprecated
- **Summary:** Toggles whether Roblox's mobile controls are hidden on mobile devices.

### `UserInputService.MouseBehavior`
- **Type:** `MouseBehavior`
- **Summary:** Determines whether the user's mouse can be moved freely or is locked.

### `UserInputService.MouseDeltaSensitivity`
- **Type:** `float`
- **Tags:** NotReplicated
- **Summary:** Scales the delta (change) output of the user's `Class.Mouse`.

### `UserInputService.MouseEnabled`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Describes whether the user's device has a mouse available.

### `UserInputService.MouseIcon`
- **Type:** `ContentId`
- **Summary:** The content ID of the image for the user's mouse icon.

### `UserInputService.MouseIconContent`
- **Type:** `Content`
- **Summary:** The content ID of the image for the user's mouse icon. Only supports asset URIs.

### `UserInputService.MouseIconEnabled`
- **Type:** `boolean`
- **Summary:** Determines whether the mouse icon is visible.

### `UserInputService.OnScreenKeyboardPosition`
- **Type:** `Vector2`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Determines the position of the on-screen keyboard.

### `UserInputService.OnScreenKeyboardSize`
- **Type:** `Vector2`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Determines the size of the on-screen keyboard.

### `UserInputService.OnScreenKeyboardVisible`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Describes whether an on-screen keyboard is currently visible on the user's screen.

### `UserInputService.PreferredInput`
- **Type:** `PreferredInput`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Queries the primary input type a player is using, based on anticipated user behavior.

### `UserInputService.TouchEnabled`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Describes whether the user's device has a touch screen available.

### `UserInputService.TouchScreenEnabled`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated

### `UserInputService.UserHeadCFrame`
- **Type:** `CFrame`
- **Tags:** ReadOnly, NotReplicated, Deprecated
- **Summary:** Describes the orientation and position of a user's head, if they are actively using a virtual reality headset.

### `UserInputService.VREnabled`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Indicates whether the user is using a virtual reality headset.

## Methods
### `UserInputService:CreateVirtualInput() -> [Object](Object.md)`
- **Summary:** Creates a `Class.VirtualInput` object for simulating mouse, keyboard, and pointer input.

### `UserInputService:GamepadSupports(gamepadNum: UserInputType, gamepadKeyCode: KeyCode) -> boolean`
- **Summary:** Returns whether the given `Enum.UserInputType` gamepad supports a button corresponding with the given `Enum.KeyCode`.

### `UserInputService:GetConnectedGamepads() -> Array`
- **Summary:** Returns an array of `Enum.UserInputType` gamepads currently connected.

### `UserInputService:GetDeviceAcceleration() -> [InputObject](InputObject.md)`
- **Summary:** Returns an `Class.InputObject` that describes the device's current acceleration.

### `UserInputService:GetDeviceGravity() -> [InputObject](InputObject.md)`
- **Summary:** Returns an `Class.InputObject` describing the device's current gravity vector.

### `UserInputService:GetDeviceRotation() -> Tuple`
- **Summary:** Returns an `Class.InputObject` and a `Datatype.CFrame` describing the device's current rotation vector.

### `UserInputService:GetFocusedTextBox() -> [TextBox](TextBox.md)`
- **Summary:** Returns the `Class.TextBox` the client is currently focused on.

### `UserInputService:GetGamepadConnected(gamepadNum: UserInputType) -> boolean`
- **Summary:** Returns whether a gamepad with the given `Enum.UserInputType` is connected.

### `UserInputService:GetGamepadState(gamepadNum: UserInputType) -> List<[InputObject](InputObject.md)>`
- **Summary:** Returns an array of `Class.InputObject|InputObjects` for all available inputs on the given gamepad, representing each input's last input state.

### `UserInputService:GetImageForKeyCode(keyCode: KeyCode) -> ContentId`
- **Summary:** Returns an image for the requested `Enum.KeyCode`.

### `UserInputService:GetKeysPressed() -> List<[InputObject](InputObject.md)>`
- **Summary:** Returns an array of `Class.InputObject|InputObjects` associated with the `Enum.KeyCode|keys` currently being pressed down.

### `UserInputService:GetLastInputType() -> UserInputType`
- **Summary:** Returns the `Enum.UserInputType` associated with the user's most recent input.

### `UserInputService:GetMouseButtonsPressed() -> List<[InputObject](InputObject.md)>`
- **Summary:** Returns an array of `Class.InputObject|InputObjects` associated with the mouse buttons currently being held down.

### `UserInputService:GetMouseDelta() -> Vector2`
- **Summary:** Returns the change, in pixels, of the position of the player's `Class.Mouse` in the last rendered frame. Only works if the mouse is locked.

### `UserInputService:GetMouseLocation() -> Vector2`
- **Summary:** Returns the current screen location of the player's `Class.Mouse` relative to the top-left corner of the screen.

### `UserInputService:GetNavigationGamepads() -> Array`
- **Summary:** Returns an array of gamepads connected and enabled for `Class.GuiObject` navigation in descending order of priority.

### `UserInputService:GetStringForKeyCode(keyCode: KeyCode) -> string`
- **Summary:** Returns a string representing a key the user should press in order to input a given `Enum.KeyCode`.

### `UserInputService:GetSupportedGamepadKeyCodes(gamepadNum: UserInputType) -> Array`
- **Summary:** Returns an array of `Enum.KeyCode|KeyCodes` that the gamepad associated with the given `Enum.UserInputType` supports.

### `UserInputService:GetUserCFrame(type: UserCFrame) -> CFrame`
- **Tags:** Deprecated
- **Summary:** Returns a `Datatype.CFrame` describing the position and orientation of a specified virtual reality device.

### `UserInputService:IsGamepadButtonDown(gamepadNum: UserInputType, gamepadKeyCode: KeyCode) -> boolean`
- **Summary:** Determines whether a particular button is pressed on a gamepad.

### `UserInputService:IsKeyDown(keyCode: KeyCode) -> boolean`
- **Summary:** Returns whether the given `Enum.KeyCode|key` is currently held down.

### `UserInputService:IsMouseButtonPressed(mouseButton: UserInputType) -> boolean`
- **Summary:** Returns whether the given mouse button is currently held down.

### `UserInputService:IsNavigationGamepad(gamepadEnum: UserInputType) -> boolean`
- **Summary:** Returns `true` if the specified gamepad is allowed to control navigation and selection `Class.GuiObject|GuiObjects`.

### `UserInputService:RecenterUserHeadCFrame() -> ()`
- **Summary:** Recenters the `Datatype.CFrame` of the VR headset to the current orientation of the headset worn by the user.

### `UserInputService:SetNavigationGamepad(gamepadEnum: UserInputType, enabled: boolean) -> ()`
- **Summary:** Sets whether or not the specified gamepad can move the `Class.GuiObject` navigator.

## Events
### `UserInputService.DeviceAccelerationChanged(acceleration: [InputObject](InputObject.md))`
- **Summary:** Fires when a user moves a device that has an accelerometer.

### `UserInputService.DeviceGravityChanged(gravity: [InputObject](InputObject.md))`
- **Summary:** Fires when the force of gravity changes on a device that has an enabled accelerometer.

### `UserInputService.DeviceRotationChanged(rotation: [InputObject](InputObject.md), cframe: CFrame)`
- **Summary:** Fires when a user rotates a device that has a gyroscope.

### `UserInputService.GamepadConnected(gamepadNum: UserInputType)`
- **Summary:** Fires when a gamepad is connected to the client.

### `UserInputService.GamepadDisconnected(gamepadNum: UserInputType)`
- **Summary:** Fires when a gamepad is disconnected from the client.

### `UserInputService.InputBegan(input: [InputObject](InputObject.md), gameProcessedEvent: boolean)`
- **Summary:** Fires when a user begins interacting with an input device such as a mouse or gamepad.

### `UserInputService.InputChanged(input: [InputObject](InputObject.md), gameProcessedEvent: boolean)`
- **Summary:** Fires when a user changes how they're interacting with an input device such as a mouse or gamepad.

### `UserInputService.InputEnded(input: [InputObject](InputObject.md), gameProcessedEvent: boolean)`
- **Summary:** Fires when a user stops interacting with an input device such as a mouse or gamepad.

### `UserInputService.JumpRequest()`
- **Summary:** Fires whenever the client makes a request for their character to jump.

### `UserInputService.LastInputTypeChanged(lastInputType: UserInputType)`
- **Summary:** Fires whenever the client's `Enum.UserInputType` is changed.

### `UserInputService.PointerAction(wheel: float, pan: Vector2, pinch: float, gameProcessedEvent: boolean)`
- **Summary:** Fires when the user performs a specific pointer action.

### `UserInputService.TextBoxFocused(textboxFocused: [TextBox](TextBox.md))`
- **Summary:** Fires when the client focuses on a `Class.TextBox`.

### `UserInputService.TextBoxFocusReleased(textboxReleased: [TextBox](TextBox.md))`
- **Summary:** Fires when the client loses focus on a `Class.TextBox`.

### `UserInputService.TouchDrag(dragDirection: SwipeDirection, numberOfTouches: int, gameProcessedEvent: boolean)`
- **Summary:** Fires when the user drags on the screen of a `Class.UserInputService.TouchEnabled|TouchEnabled` device.

### `UserInputService.TouchEnded(touch: [InputObject](InputObject.md), gameProcessedEvent: boolean)`
- **Summary:** Fires when a user releases their finger from the screen of a `Class.UserInputService.TouchEnabled|TouchEnabled` device.

### `UserInputService.TouchLongPress(touchPositions: Array, state: UserInputState, gameProcessedEvent: boolean)`
- **Summary:** Fires when a user holds at least one finger for a short amount of time on the screen of a `Class.UserInputService.TouchEnabled|TouchEnabled` device.

### `UserInputService.TouchMoved(touch: [InputObject](InputObject.md), gameProcessedEvent: boolean)`
- **Summary:** Fires when a user moves their finger on the screen of a `Class.UserInputService.TouchEnabled|TouchEnabled` device.

### `UserInputService.TouchPan(touchPositions: Array, totalTranslation: Vector2, velocity: Vector2, state: UserInputState, gameProcessedEvent: boolean)`
- **Summary:** Fires when the user drags at least one finger on the screen of a `Class.UserInputService.TouchEnabled|TouchEnabled` device.

### `UserInputService.TouchPinch(touchPositions: Array, scale: float, velocity: float, state: UserInputState, gameProcessedEvent: boolean)`
- **Summary:** Fires when a user performs a pinch gesture on the screen of a `Class.UserInputService.TouchEnabled|TouchEnabled` device.

### `UserInputService.TouchRotate(touchPositions: Array, rotation: float, velocity: float, state: UserInputState, gameProcessedEvent: boolean)`
- **Summary:** Fires when a user rotates two fingers on the screen of a `Class.UserInputService.TouchEnabled|TouchEnabled` device.

### `UserInputService.TouchStarted(touch: [InputObject](InputObject.md), gameProcessedEvent: boolean)`
- **Summary:** Fires when a user places their finger on the screen of a `Class.UserInputService.TouchEnabled|TouchEnabled` device.

### `UserInputService.TouchSwipe(swipeDirection: SwipeDirection, numberOfTouches: int, gameProcessedEvent: boolean)`
- **Summary:** Fires on a `Class.UserInputService.TouchEnabled|TouchEnabled` device when a user places their finger(s) down on the screen, pans across the screen, and lifts their finger(s) off with a certain speed of movement.

### `UserInputService.TouchTap(touchPositions: Array, gameProcessedEvent: boolean)`
- **Summary:** Fires when a user taps their finger on the screen of a `Class.UserInputService.TouchEnabled|TouchEnabled` device.

### `UserInputService.TouchTapInWorld(position: Vector2, processedByUI: boolean)`
- **Summary:** Fires when a user taps their finger on the screen of a `Class.UserInputService.TouchEnabled|TouchEnabled` device and the tap location is in the 3D world.

### `UserInputService.UserCFrameChanged(type: UserCFrame, value: CFrame)`
- **Tags:** Deprecated
- **Summary:** Fires when the `Datatype.CFrame` of a specified Virtual Reality device changes.

### `UserInputService.WindowFocused()`
- **Summary:** Fires when the window of the Roblox client gains focus on the user's screen.

### `UserInputService.WindowFocusReleased()`
- **Summary:** Fires when the window of the Roblox client loses focus on the user's screen.
