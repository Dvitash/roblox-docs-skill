# AudioDeviceInput

**Superclass:** [Instance](Instance.md)

This file defines `AudioDeviceInput`, which controls audio streams from physical devices and provides access to controlling the mute state of the device.

## Properties
### `AudioDeviceInput.AccessType`
- **Type:** `AccessModifierType`
- **Summary:** Determines whether the list of user IDs provided to `Class.AudioDeviceInput.SetUserIdAccessList|SetUserIdAccessList` is treated as an allow-list or deny-list.

### `AudioDeviceInput.Active`
- **Type:** `boolean`
- **Summary:** Controls whether the physical device is actively recording.

### `AudioDeviceInput.IsReady`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Denotes whether this `Class.AudioDeviceInput` is ready to produce sound.

### `AudioDeviceInput.Muted`
- **Type:** `boolean`
- **Summary:** Controls whether this `Class.AudioDeviceInput` is muted.

### `AudioDeviceInput.Player`
- **Type:** `[Player](Player.md)`
- **Summary:** Determines whose device is producing sound.

### `AudioDeviceInput.Volume`
- **Type:** `float`
- **Summary:** Volume level which is multiplied onto the output audio stream.

## Methods
### `AudioDeviceInput:GetConnectedWires(pin: string) -> List<[Wire](Wire.md)>`
- **Summary:** Returns an array of `Class.Wire|Wires` that are connected to the specified pin.

### `AudioDeviceInput:GetInputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.TargetName` to connect to this instance via its `Class.Wire.TargetInstance` property.

### `AudioDeviceInput:GetOutputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.SourceName` to connect to this instance via its `Class.Wire.SourceInstance` property.

### `AudioDeviceInput:GetUserIdAccessList() -> Array`
- **Summary:** Returns a list of user IDs that are either permitted to hear or blocked from hearing this `Class.AudioDeviceInput`.

### `AudioDeviceInput:SetUserIdAccessList(userIds: Array) -> ()`
- **Summary:** Sets a list of user IDs that are either permitted to hear or blocked from hearing this `Class.AudioDeviceInput`.

## Events
### `AudioDeviceInput.WiringChanged(connected: boolean, pin: string, wire: [Wire](Wire.md), instance: [Instance](Instance.md))`
- **Summary:** Fires when another instance is connected to or disconnected from the `Class.AudioDeviceInput` via a `Class.Wire`.
