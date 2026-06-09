# AudioChannelMixer

**Superclass:** [Instance](Instance.md)

Combines multiple audio streams into a single, multichannel audio stream.

## Properties
### `AudioChannelMixer.Layout`
- **Type:** `AudioChannelLayout`
- **Summary:** Controls the output channel layout to be mixed to.

## Methods
### `AudioChannelMixer:GetConnectedWires(pin: string) -> List<[Wire](Wire.md)>`
- **Summary:** Returns an array of `Class.Wire|Wires` that are connected to the specified pin.

### `AudioChannelMixer:GetInputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.TargetName` to connect to this instance via its `Class.Wire.TargetInstance` property.

### `AudioChannelMixer:GetOutputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.SourceName` to connect to this instance via its `Class.Wire.SourceInstance` property.

## Events
### `AudioChannelMixer.WiringChanged(connected: boolean, pin: string, wire: [Wire](Wire.md), instance: [Instance](Instance.md))`
- **Summary:** Fires when another instance is connected to or disconnected from the `Class.AudioChannelMixer` via a `Class.Wire`.
