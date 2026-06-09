# AudioTremolo

**Superclass:** [Instance](Instance.md)

The `AudioTremolo` class is a method that creates a trembling effect on a sound by varying the volume up and down, utilizing two pins (`Input` and `Output`).

## Properties
### `AudioTremolo.Bypass`
- **Type:** `boolean`
- **Summary:** Whether audio streams are passed-through unaffected by this effect.

### `AudioTremolo.Depth`
- **Type:** `float`
- **Summary:** Controls how much the volume will raise and lower.

### `AudioTremolo.Duty`
- **Type:** `float`
- **Summary:** Controls how long the effect will be active during one volume oscillation.

### `AudioTremolo.Frequency`
- **Type:** `float`
- **Summary:** Sets how often the effect will oscillate the volume.

### `AudioTremolo.Shape`
- **Type:** `float`
- **Summary:** Controls the shape of the low frequency oscillations.

### `AudioTremolo.Skew`
- **Type:** `float`
- **Summary:** Time-skews the low frequency oscillations cycle.

### `AudioTremolo.Square`
- **Type:** `float`
- **Summary:** Flatness of the low frequency oscillations shape.

## Methods
### `AudioTremolo:GetConnectedWires(pin: string) -> List<[Wire](Wire.md)>`
- **Summary:** Returns an array of `Class.Wire|Wires` that are connected to the specified pin.

### `AudioTremolo:GetInputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.TargetName` to connect to this instance via its `Class.Wire.TargetInstance` property.

### `AudioTremolo:GetOutputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.SourceName` to connect to this instance via its `Class.Wire.SourceInstance` property.

## Events
### `AudioTremolo.WiringChanged(connected: boolean, pin: string, wire: [Wire](Wire.md), instance: [Instance](Instance.md))`
- **Summary:** Fires when another instance is connected to or disconnected from the `Class.AudioTremolo` via a `Class.Wire`.
