# AudioPitchShifter

**Superclass:** [Instance](Instance.md)

AudioPitchShifter is a class that adjusts the perceived pitch of audio streams by modifying the pitch of the input and output pins. It performs frequency domain modifications and may introduce artifacts, with settings like `Bypass` controlling this effect.

## Properties
### `AudioPitchShifter.Bypass`
- **Type:** `boolean`
- **Summary:** Whether audio streams are passed-through unaffected by this effect.

### `AudioPitchShifter.Pitch`
- **Type:** `float`
- **Summary:** Pitch modification to be multiplied by the pitch of the input stream.

### `AudioPitchShifter.WindowSize`
- **Type:** `AudioWindowSize`
- **Summary:** Controls how much audio will be buffered and shifted at once.

## Methods
### `AudioPitchShifter:GetConnectedWires(pin: string) -> List<[Wire](Wire.md)>`
- **Summary:** Returns an array of `Class.Wire|Wires` that are connected to the specified pin.

### `AudioPitchShifter:GetInputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.TargetName` to connect to this instance via its `Class.Wire.TargetInstance` property.

### `AudioPitchShifter:GetOutputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.SourceName` to connect to this instance via its `Class.Wire.SourceInstance` property.

## Events
### `AudioPitchShifter.WiringChanged(connected: boolean, pin: string, wire: [Wire](Wire.md), instance: [Instance](Instance.md))`
- **Summary:** Fires when another instance is connected to or disconnected from the `Class.AudioPitchShifter` via a `Class.Wire`.
