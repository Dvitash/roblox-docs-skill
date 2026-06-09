# AudioAnalyzer

**Superclass:** [Instance](Instance.md)

The `Class.AudioAnalyzer` class provides measurements from audio streams connected via `Class.Wire|Wires`. It filters processing to conserve resources and returns only stable results when used from server scripts.

## Properties
### `AudioAnalyzer.PeakLevel`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The loudest volume observed during the last audio buffer.

### `AudioAnalyzer.RmsLevel`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The root-mean-square average volume observed during the last audio buffer.

### `AudioAnalyzer.SpectrumEnabled`
- **Type:** `boolean`
- **Summary:** Enables usage of `Class.AudioAnalyzer:GetSpectrum|GetSpectrum`.

### `AudioAnalyzer.WindowSize`
- **Type:** `AudioWindowSize`
- **Summary:** Controls the resolution and timeliness of `Class.AudioAnalyzer:GetSpectrum|GetSpectrum`.

## Methods
### `AudioAnalyzer:GetConnectedWires(pin: string) -> List<[Wire](Wire.md)>`
- **Summary:** Returns an array of `Class.Wire|Wires` that are connected to the specified pin.

### `AudioAnalyzer:GetInputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.TargetName` to connect to this instance via its `Class.Wire.TargetInstance` property.

### `AudioAnalyzer:GetOutputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.SourceName` to connect to this instance via its `Class.Wire.SourceInstance` property.

### `AudioAnalyzer:GetSpectrum() -> Array`
- **Tags:** CustomLuaState
- **Summary:** Returns the frequency spectrum of the last audio buffer.

## Events
### `AudioAnalyzer.WiringChanged(connected: boolean, pin: string, wire: [Wire](Wire.md), instance: [Instance](Instance.md))`
- **Summary:** Fires when another instance is connected to or disconnected from the `Class.AudioAnalyzer` via a `Class.Wire`.
