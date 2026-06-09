# AudioChannelSplitter

**Superclass:** [Instance](Instance.md)

Splits an audio stream into component channels to allow for independent processing of each channel.

## Properties
### `AudioChannelSplitter.Layout`
- **Type:** `AudioChannelLayout`
- **Summary:** Controls the input channel layout to be split from.

## Methods
### `AudioChannelSplitter:GetConnectedWires(pin: string) -> List<[Wire](Wire.md)>`
- **Summary:** Returns an array of `Class.Wire|Wires` that are connected to the specified pin.

### `AudioChannelSplitter:GetInputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.TargetName` to connect to this instance via its `Class.Wire.TargetInstance` property.

### `AudioChannelSplitter:GetOutputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.SourceName` to connect to this instance via its `Class.Wire.SourceInstance` property.

## Events
### `AudioChannelSplitter.WiringChanged(connected: boolean, pin: string, wire: [Wire](Wire.md), instance: [Instance](Instance.md))`
- **Summary:** Fires when another instance is connected to or disconnected from the `Class.AudioChannelSplitter` via a `Class.Wire`.
