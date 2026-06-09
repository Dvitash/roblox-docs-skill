# AudioFilter

**Superclass:** [Instance](Instance.md)

The `AudioFilter` class is a class that adjusts the frequency content of audio streams by controlling properties like `FilterType`, `Gain`, and `Q`.

## Properties
### `AudioFilter.Bypass`
- **Type:** `boolean`
- **Summary:** Whether audio streams are passed-through unaffected by this effect.

### `AudioFilter.FilterType`
- **Type:** `AudioFilterType`
- **Summary:** The curve type of the band represented by the filter.

### `AudioFilter.Frequency`
- **Type:** `float`
- **Summary:** The central frequency that the filter acts around.

### `AudioFilter.Gain`
- **Type:** `float`
- **Summary:** For peaking and shelving filters, controls volume increase or reduction.

### `AudioFilter.Q`
- **Type:** `float`
- **Summary:** For peaking, lowpass, highpass, bandpass, and notch filters, controls the selectiveness or resonance.

## Methods
### `AudioFilter:GetConnectedWires(pin: string) -> List<[Wire](Wire.md)>`
- **Summary:** Returns an array of `Class.Wire|Wires` that are connected to the specified pin.

### `AudioFilter:GetGainAt(frequency: float) -> float`
- **Summary:** Returns the magnitude response of the filter at the given frequency.

### `AudioFilter:GetInputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.TargetName` to connect to this instance via its `Class.Wire.TargetInstance` property.

### `AudioFilter:GetOutputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.SourceName` to connect to this instance via its `Class.Wire.SourceInstance` property.

## Events
### `AudioFilter.WiringChanged(connected: boolean, pin: string, wire: [Wire](Wire.md), instance: [Instance](Instance.md))`
- **Summary:** Fires when another instance is connected to or disconnected from the `Class.AudioFilter` via a `Class.Wire`.
