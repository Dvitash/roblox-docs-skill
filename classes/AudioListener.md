# AudioListener

**Superclass:** [Instance](Instance.md)

This file defines `Class.AudioListener` as a class for recording audio from surrounding objects, which controls various simulation properties and audio attenuation curves.

## Properties
### `AudioListener.AcousticSimulationEnabled`
- **Type:** `boolean`
- **Summary:** Determines whether acoustic simulation should be used for this `Class.AudioListener`.

### `AudioListener.AngleAttenuation`
- **Type:** `Flyweight`
- **Summary:** Represents how the perceived volume of the emitted sound changes based on the angle between a `Class.AudioEmitter` and the `Datatype.CFrame.LookVector|LookVector` associated with the `Class.AudioListener`.

### `AudioListener.AudioInteractionGroup`
- **Type:** `string`
- **Summary:** Controls which `Class.AudioEmitter|AudioEmitters` are audible to this `Class.AudioListener`.

### `AudioListener.DistanceAttenuation`
- **Type:** `Flyweight`
- **Summary:** Represents how the perceived volume of emitted sounds change as the distance between `Class.AudioEmitter|AudioEmitters` and the `Class.AudioListener` increases.

### `AudioListener.SimulationFidelity`
- **Type:** `AudioSimulationFidelity`
- **Tags:** Deprecated
- **Summary:** Controls how detailed the audio simulation should be for this `Class.AudioListener`.

## Methods
### `AudioListener:GetAngleAttenuation() -> Dictionary`
- **Tags:** CustomLuaState
- **Summary:** Gets the angle attenuation curve that the `Class.AudioListener` is using, or an empty table if it's using the default curve.

### `AudioListener:GetAudibilityFor(emitter: [AudioEmitter](AudioEmitter.md)) -> float`
- **Summary:** Calculates how audible an `Class.AudioEmitter` is for this listener

### `AudioListener:GetConnectedWires(pin: string) -> List<[Wire](Wire.md)>`
- **Summary:** Returns an array of `Class.Wire|Wires` that are connected to the specified pin.

### `AudioListener:GetDistanceAttenuation() -> Dictionary`
- **Tags:** CustomLuaState
- **Summary:** Gets the distance attenuation curve that the `Class.AudioListener` is using, or an empty table if it's using the default curve.

### `AudioListener:GetInputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.TargetName` to connect to this instance via its `Class.Wire.TargetInstance` property.

### `AudioListener:GetInteractingEmitters() -> List<[AudioEmitter](AudioEmitter.md)>`
- **Summary:** Lists all `Class.AudioEmitter|AudioEmitters` that this listener is capable of hearing.

### `AudioListener:GetOutputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.SourceName` to connect to this instance via its `Class.Wire.SourceInstance` property.

### `AudioListener:SetAngleAttenuation(curve: Dictionary) -> ()`
- **Tags:** CustomLuaState
- **Summary:** Sets the angle attenuation curve that the `Class.AudioListener` should use, or uses a constant curve of volume `1` if none is provided.

### `AudioListener:SetDistanceAttenuation(curve: Dictionary) -> ()`
- **Tags:** CustomLuaState
- **Summary:** Sets the distance attenuation curve that the `Class.AudioListener` should use, or uses an inverse rolloff curve if none is provided.

## Events
### `AudioListener.WiringChanged(connected: boolean, pin: string, wire: [Wire](Wire.md), instance: [Instance](Instance.md))`
- **Summary:** Fires when another instance is connected to or disconnected from the `Class.AudioListener` via a `Class.Wire`.
