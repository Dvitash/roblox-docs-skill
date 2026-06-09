# AudioFlanger

**Superclass:** [Instance](Instance.md)

The `AudioFlanger` class provides methods to control the pitch modulation of audio streams, including `GetConnectedWires`, `GetInputPins`, and `GetOutputPins`.

## Properties
### `AudioFlanger.Bypass`
- **Type:** `boolean`
- **Summary:** Whether audio streams are passed-through unaffected by this effect.

### `AudioFlanger.Depth`
- **Type:** `float`
- **Summary:** Controls how strong the pitch modulation of the flanger is.

### `AudioFlanger.Mix`
- **Type:** `float`
- **Summary:** Controls the balance of plain input stream to modified output stream.

### `AudioFlanger.Rate`
- **Type:** `float`
- **Summary:** Controls the rate of pitch modulations.

## Methods
### `AudioFlanger:GetConnectedWires(pin: string) -> List<[Wire](Wire.md)>`
- **Summary:** Returns an array of `Class.Wire|Wires` that are connected to the specified pin.

### `AudioFlanger:GetInputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.TargetName` to connect to this instance via its `Class.Wire.TargetInstance` property.

### `AudioFlanger:GetOutputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.SourceName` to connect to this instance via its `Class.Wire.SourceInstance` property.

## Events
### `AudioFlanger.WiringChanged(connected: boolean, pin: string, wire: [Wire](Wire.md), instance: [Instance](Instance.md))`
- **Summary:** Fires when another instance is connected to or disconnected from the `Class.AudioFlanger` via a `Class.Wire`.
