# AudioLimiter

**Superclass:** [Instance](Instance.md)

AudioLimiter is a class that limits the volume of audio streams, allowing for a single input pin and output pin to manage this effect.

## Properties
### `AudioLimiter.Bypass`
- **Type:** `boolean`
- **Summary:** Whether audio streams are passed-through unaffected by this effect.

### `AudioLimiter.MaxLevel`
- **Type:** `float`
- **Summary:** The maximum volume tolerated.

### `AudioLimiter.Release`
- **Type:** `float`
- **Summary:** The amount of time it takes for previously limited streams to return to their normal volume.

## Methods
### `AudioLimiter:GetConnectedWires(pin: string) -> List<[Wire](Wire.md)>`
- **Summary:** Returns an array of `Class.Wire|Wires` that are connected to the specified pin.

### `AudioLimiter:GetInputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.TargetName` to connect to this instance via its `Class.Wire.TargetInstance` property.

### `AudioLimiter:GetOutputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.SourceName` to connect to this instance via its `Class.Wire.SourceInstance` property.

## Events
### `AudioLimiter.WiringChanged(connected: boolean, pin: string, wire: [Wire](Wire.md), instance: [Instance](Instance.md))`
- **Summary:** Fires when another instance is connected to or disconnected from the `Class.AudioLimiter` via a `Class.Wire`.
