# AudioDistortion

**Superclass:** [Instance](Instance.md)

AudioDistortion is a class that modifies audio streams by altering their sound quality, affecting input/output pins, and triggering specific events when connected or disconnected.

## Properties
### `AudioDistortion.Bypass`
- **Type:** `boolean`
- **Summary:** Whether audio streams are passed-through unaffected by this effect.

### `AudioDistortion.Level`
- **Type:** `float`
- **Summary:** Controls how distorted the input stream will become.

## Methods
### `AudioDistortion:GetConnectedWires(pin: string) -> List<[Wire](Wire.md)>`
- **Summary:** Returns an array of `Class.Wire|Wires` that are connected to the specified pin.

### `AudioDistortion:GetInputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.TargetName` to connect to this instance via its `Class.Wire.TargetInstance` property.

### `AudioDistortion:GetOutputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.SourceName` to connect to this instance via its `Class.Wire.SourceInstance` property.

## Events
### `AudioDistortion.WiringChanged(connected: boolean, pin: string, wire: [Wire](Wire.md), instance: [Instance](Instance.md))`
- **Summary:** Fires when another instance is connected to or disconnected from the `Class.AudioDistortion` via a `Class.Wire`.
