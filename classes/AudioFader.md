# AudioFader

**Superclass:** [Instance](Instance.md)

This file defines `AudioFader` class, which controls the volume of audio streams by providing a `GetConnectedWires` method and two `GetInputPins` and `GetOutputPins` methods.

## Properties
### `AudioFader.Bypass`
- **Type:** `boolean`
- **Summary:** Whether audio streams are passed-through unaffected by this effect.

### `AudioFader.Volume`
- **Type:** `float`
- **Summary:** Volume level which is multiplied onto the input stream.

## Methods
### `AudioFader:GetConnectedWires(pin: string) -> List<[Wire](Wire.md)>`
- **Summary:** Returns an array of `Class.Wire|Wires` that are connected to the specified pin.

### `AudioFader:GetInputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.TargetName` to connect to this instance via its `Class.Wire.TargetInstance` property.

### `AudioFader:GetOutputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.SourceName` to connect to this instance via its `Class.Wire.SourceInstance` property.

## Events
### `AudioFader.WiringChanged(connected: boolean, pin: string, wire: [Wire](Wire.md), instance: [Instance](Instance.md))`
- **Summary:** Fires when another instance is connected to or disconnected from the `Class.AudioFader` via a `Class.Wire`.
