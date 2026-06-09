# AudioDeviceOutput

**Superclass:** [Instance](Instance.md)

AudioDeviceOutput is a class for accepting audio streams to be rendered to hardware devices like speakers or headphones. It provides an input pin for wired streams and outputs a list of `Class.Wire|Wires` to connect to the device.

## Properties
### `AudioDeviceOutput.Player`
- **Type:** `[Player](Player.md)`
- **Summary:** A `Class.Player` who is intended to hear the connected audio streams.

## Methods
### `AudioDeviceOutput:GetConnectedWires(pin: string) -> List<[Wire](Wire.md)>`
- **Summary:** Returns an array of `Class.Wire|Wires` that are connected to the specified pin.

### `AudioDeviceOutput:GetInputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.TargetName` to connect to this instance via its `Class.Wire.TargetInstance` property.

### `AudioDeviceOutput:GetOutputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.SourceName` to connect to this instance via its `Class.Wire.SourceInstance` property.

## Events
### `AudioDeviceOutput.WiringChanged(connected: boolean, pin: string, wire: [Wire](Wire.md), instance: [Instance](Instance.md))`
- **Summary:** Fires when another instance is connected to or disconnected from the `Class.AudioDeviceOutput` via a `Class.Wire`.
