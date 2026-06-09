# AudioGate

**Superclass:** [Instance](Instance.md)

This file defines `Class.AudioGate`, which acts as a noise gate that mutes audio based on a specified volume threshold, and provides methods for controlling gate behavior and accessing its pins.

## Properties
### `AudioGate.Attack`
- **Type:** `float`
- **Summary:** Controls how long it takes for the gate to open when the signal level rises above the `Class.AudioGate.Threshold|Threshold`.

### `AudioGate.Bypass`
- **Type:** `boolean`
- **Summary:** Whether audio streams are passed-through unaffected by this effect.

### `AudioGate.Release`
- **Type:** `float`
- **Summary:** Controls how long it takes for the gate to close when the signal level drops below the `Class.AudioGate.Threshold|Threshold`.

### `AudioGate.Threshold`
- **Type:** `NumberRange`
- **Summary:** The gain value(s) around which the gate opens and closes.

## Methods
### `AudioGate:GetConnectedWires(pin: string) -> List<[Wire](Wire.md)>`
- **Summary:** Returns an array of `Class.Wire|Wires` that are connected to the specified pin.

### `AudioGate:GetInputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.TargetName` to connect to this instance via its `Class.Wire.TargetInstance` property.

### `AudioGate:GetOutputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.SourceName` to connect to this instance via its `Class.Wire.SourceInstance` property.

## Events
### `AudioGate.WiringChanged(connected: boolean, pin: string, wire: [Wire](Wire.md), instance: [Instance](Instance.md))`
- **Summary:** Fires when another instance is connected to or disconnected from the `Class.AudioGate` via a `Class.Wire`.
