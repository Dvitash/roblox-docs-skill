# AudioEmitter

**Superclass:** [Instance](Instance.md)

This file defines `AudioEmitter` class, which controls how audio streams are emitted and received within a game environment.

## Properties
### `AudioEmitter.AcousticSimulationEnabled`
- **Type:** `boolean`
- **Summary:** Determines whether acoustic simulation should be used for this `Class.AudioEmitter`.

### `AudioEmitter.AngleAttenuation`
- **Type:** `Flyweight`
- **Summary:** Represents how the perceived volume of the emitted sound changes based on the angle between a `Class.AudioListener` and the `Datatype.CFrame.LookVector|LookVector` associated with the `Class.AudioEmitter`.

### `AudioEmitter.AudioInteractionGroup`
- **Type:** `string`
- **Summary:** Controls which `Class.AudioListener|AudioListeners` are capable of hearing this `Class.AudioEmitter`.

### `AudioEmitter.DistanceAttenuation`
- **Type:** `Flyweight`
- **Summary:** Represents how the perceived volume of the emitted sound changes as the distance between a `Class.AudioListener` and the `Class.AudioEmitter` increases.

### `AudioEmitter.SimulationFidelity`
- **Type:** `AudioSimulationFidelity`
- **Tags:** Deprecated
- **Summary:** Controls how detailed the audio simulation should be for this `Class.AudioEmitter`.

## Methods
### `AudioEmitter:GetAngleAttenuation() -> Dictionary`
- **Tags:** CustomLuaState
- **Summary:** Gets the angle attenuation curve that the `Class.AudioEmitter` is using, or an empty table if it's using the default curve.

### `AudioEmitter:GetAudibilityFor(listener: [AudioListener](AudioListener.md)) -> float`
- **Summary:** Calculates how audible this emitter is for a particular `Class.AudioListener`.

### `AudioEmitter:GetConnectedWires(pin: string) -> List<[Wire](Wire.md)>`
- **Summary:** Returns an array of `Class.Wire|Wires` that are connected to the specified pin.

### `AudioEmitter:GetDistanceAttenuation() -> Dictionary`
- **Tags:** CustomLuaState
- **Summary:** Gets the distance attenuation curve that the `Class.AudioEmitter` is using, or an empty table if it's using the default curve.

### `AudioEmitter:GetInputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.TargetName` to connect to this instance via its `Class.Wire.TargetInstance` property.

### `AudioEmitter:GetInteractingListeners() -> List<[AudioListener](AudioListener.md)>`
- **Summary:** Lists all `Class.AudioListener|AudioListeners` that are capable of hearing this emitter.

### `AudioEmitter:GetOutputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.SourceName` to connect to this instance via its `Class.Wire.SourceInstance` property.

### `AudioEmitter:SetAngleAttenuation(curve: Dictionary) -> ()`
- **Tags:** CustomLuaState
- **Summary:** Sets the angle attenuation curve that the `Class.AudioEmitter` should use, or uses a constant curve of volume `1` if none is provided.

### `AudioEmitter:SetDistanceAttenuation(curve: Dictionary) -> ()`
- **Tags:** CustomLuaState
- **Summary:** Sets the distance attenuation curve that the `Class.AudioEmitter` should use, or uses an inverse rolloff curve if none is provided.

## Events
### `AudioEmitter.WiringChanged(connected: boolean, pin: string, wire: [Wire](Wire.md), instance: [Instance](Instance.md))`
- **Summary:** Fires when another instance is connected to or disconnected from the `Class.AudioEmitter` via a `Class.Wire`.
