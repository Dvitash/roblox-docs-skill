# AudioEcho

**Superclass:** [Instance](Instance.md)

Overlays in `AudioEcho` allow for delayed copies of audio streams, and these effects are controlled by properties like `AudioEcho.Bypass` and `AudioEcho.DryLevel`.

## Properties
### `AudioEcho.Bypass`
- **Type:** `boolean`
- **Summary:** Whether audio streams are passed-through unaffected by this effect.

### `AudioEcho.DelayTime`
- **Type:** `float`
- **Summary:** The amount of time between echoes.

### `AudioEcho.DryLevel`
- **Type:** `float`
- **Summary:** Gain level determining how loud the original, unaltered audio stream will be.

### `AudioEcho.Feedback`
- **Type:** `float`
- **Summary:** How slowly echoes fade away.

### `AudioEcho.RampTime`
- **Type:** `float`
- **Summary:** The time taken to interpolate between `Class.AudioEcho.DelayTime|DelayTime` values.

### `AudioEcho.WetLevel`
- **Type:** `float`
- **Summary:** Gain level determining how loud the echoed stream will be.

## Methods
### `AudioEcho:GetConnectedWires(pin: string) -> List<[Wire](Wire.md)>`
- **Summary:** Returns an array of `Class.Wire|Wires` that are connected to the specified pin.

### `AudioEcho:GetInputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.TargetName` to connect to this instance via its `Class.Wire.TargetInstance` property.

### `AudioEcho:GetOutputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.SourceName` to connect to this instance via its `Class.Wire.SourceInstance` property.

## Events
### `AudioEcho.WiringChanged(connected: boolean, pin: string, wire: [Wire](Wire.md), instance: [Instance](Instance.md))`
- **Summary:** Fires when another instance is connected to or disconnected from the `Class.AudioEcho` via a `Class.Wire`.
