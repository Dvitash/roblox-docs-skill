# AudioCompressor

**Superclass:** [Instance](Instance.md)

The `AudioCompressor` class is a method that adjusts the dynamic range of audio streams by clamping loudness, providing input/sidechain pins, and an output pin for wire management.

## Properties
### `AudioCompressor.Attack`
- **Type:** `float`
- **Summary:** Controls how quickly the compressor will clamp down on volume after it surpasses `Class.AudioCompressor.Threshold|Threshold`.

### `AudioCompressor.Bypass`
- **Type:** `boolean`
- **Summary:** Whether audio streams are passed-through unaffected by this effect.

### `AudioCompressor.MakeupGain`
- **Type:** `float`
- **Summary:** A gain value to be applied after compression.

### `AudioCompressor.Ratio`
- **Type:** `float`
- **Summary:** Ratio of input volume to output volume, to be applied when surpassing `Class.AudioCompressor.Threshold|Threshold`.

### `AudioCompressor.Release`
- **Type:** `float`
- **Summary:** Controls how quickly the compressor will unclamp after the stream volume dips back below `Class.AudioCompressor.Threshold|Threshold`.

### `AudioCompressor.Threshold`
- **Type:** `float`
- **Summary:** Gain value at which the compressor will start to modify the input stream.

## Methods
### `AudioCompressor:GetConnectedWires(pin: string) -> List<[Wire](Wire.md)>`
- **Summary:** Returns an array of `Class.Wire|Wires` that are connected to the specified pin.

### `AudioCompressor:GetInputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.TargetName` to connect to this instance via its `Class.Wire.TargetInstance` property.

### `AudioCompressor:GetOutputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.SourceName` to connect to this instance via its `Class.Wire.SourceInstance` property.

## Events
### `AudioCompressor.WiringChanged(connected: boolean, pin: string, wire: [Wire](Wire.md), instance: [Instance](Instance.md))`
- **Summary:** Fires when another instance is connected to or disconnected from the `Class.AudioCompressor` via a `Class.Wire`.
