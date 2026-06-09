# AudioChorus

**Superclass:** [Instance](Instance.md)

This class controls how audio streams are processed, allowing for varying levels of volume and modulating pitch based on the input stream.

## Properties
### `AudioChorus.Bypass`
- **Type:** `boolean`
- **Summary:** Whether audio streams are passed-through unaffected by this effect.

### `AudioChorus.Depth`
- **Type:** `float`
- **Summary:** Controls the maximum delay time of the copied streams in the chorus effect.

### `AudioChorus.Mix`
- **Type:** `float`
- **Summary:** Controls the balance of plain input stream to modified output stream.

### `AudioChorus.Rate`
- **Type:** `float`
- **Summary:** Controls the rate of pitch modulations.

## Methods
### `AudioChorus:GetConnectedWires(pin: string) -> List<[Wire](Wire.md)>`
- **Summary:** Returns an array of `Class.Wire|Wires` that are connected to the specified pin.

### `AudioChorus:GetInputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.TargetName` to connect to this instance via its `Class.Wire.TargetInstance` property.

### `AudioChorus:GetOutputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.SourceName` to connect to this instance via its `Class.Wire.SourceInstance` property.

## Events
### `AudioChorus.WiringChanged(connected: boolean, pin: string, wire: [Wire](Wire.md), instance: [Instance](Instance.md))`
- **Summary:** Fires when another instance is connected to or disconnected from the `Class.AudioChorus` via a `Class.Wire`.
