# AudioEqualizer

**Superclass:** [Instance](Instance.md)

The `AudioEqualizer` class is a class that adjusts audio frequency content, offering three gain bands and allowing for crossover points between them.

## Properties
### `AudioEqualizer.Bypass`
- **Type:** `boolean`
- **Summary:** Whether audio streams are passed-through unaffected by this effect.

### `AudioEqualizer.HighGain`
- **Type:** `float`
- **Summary:** Gain value to be applied to the frequency content of the highest band in the equalizer.

### `AudioEqualizer.LowGain`
- **Type:** `float`
- **Summary:** Gain value to be applied to the frequency content of the lowest band in the equalizer.

### `AudioEqualizer.MidGain`
- **Type:** `float`
- **Summary:** Gain value to be applied to the frequency content of the middle band in the equalizer.

### `AudioEqualizer.MidRange`
- **Type:** `NumberRange`
- **Summary:** The frequency range of the band influenced by `Class.AudioEqualizer.MidGain|MidGain`.

## Methods
### `AudioEqualizer:GetConnectedWires(pin: string) -> List<[Wire](Wire.md)>`
- **Summary:** Returns an array of `Class.Wire|Wires` that are connected to the specified pin.

### `AudioEqualizer:GetInputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.TargetName` to connect to this instance via its `Class.Wire.TargetInstance` property.

### `AudioEqualizer:GetOutputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.SourceName` to connect to this instance via its `Class.Wire.SourceInstance` property.

## Events
### `AudioEqualizer.WiringChanged(connected: boolean, pin: string, wire: [Wire](Wire.md), instance: [Instance](Instance.md))`
- **Summary:** Fires when another instance is connected to or disconnected from the `Class.AudioEqualizer` via a `Class.Wire`.
