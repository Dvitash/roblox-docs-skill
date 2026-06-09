# AudioReverb

**Superclass:** [Instance](Instance.md)

This class is a `AudioReverb` class that models reverberation by controlling the frequency and time of sound decay. It allows for controlling the "Bypass" setting to determine if audio is passed through unaffected.

## Properties
### `AudioReverb.Bypass`
- **Type:** `boolean`
- **Summary:** Whether audio streams are passed-through unaffected by this effect.

### `AudioReverb.DecayRatio`
- **Type:** `float`
- **Summary:** Controls how quickly high frequency sound decays compared to the overall reverb.

### `AudioReverb.DecayTime`
- **Type:** `float`
- **Summary:** Controls how long it takes for the reverb to dissipate.

### `AudioReverb.Density`
- **Type:** `float`
- **Summary:** Controls how many reflections are generated.

### `AudioReverb.Diffusion`
- **Type:** `float`
- **Summary:** Controls how smooth and reflective the simulated surfaces are.

### `AudioReverb.DryLevel`
- **Type:** `float`
- **Summary:** Gain level determining how loud the original, unaltered audio stream will be.

### `AudioReverb.EarlyDelayTime`
- **Type:** `float`
- **Summary:** Controls the amount of time before reverberation begins .

### `AudioReverb.HighCutFrequency`
- **Type:** `float`
- **Summary:** Frequency above which sound is filtered out of the reverb.

### `AudioReverb.LateDelayTime`
- **Type:** `float`
- **Summary:** Time, following early delays, before diffuse reverberations begin.

### `AudioReverb.LowShelfFrequency`
- **Type:** `float`
- **Summary:** Frequency below which audio can be boosted or reduced in the reverb.

### `AudioReverb.LowShelfGain`
- **Type:** `float`
- **Summary:** Controls the presence of low frequency content in the reverb.

### `AudioReverb.ReferenceFrequency`
- **Type:** `float`
- **Summary:** Frequency that separates low frequency decay speeds from high frequency decay speeds.

### `AudioReverb.WetLevel`
- **Type:** `float`
- **Summary:** Gain level determining how loud the reverberated stream will be.

## Methods
### `AudioReverb:GetConnectedWires(pin: string) -> List<[Wire](Wire.md)>`
- **Summary:** Returns an array of `Class.Wire|Wires` that are connected to the specified pin.

### `AudioReverb:GetInputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.TargetName` to connect to this instance via its `Class.Wire.TargetInstance` property.

### `AudioReverb:GetOutputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.SourceName` to connect to this instance via its `Class.Wire.SourceInstance` property.

## Events
### `AudioReverb.WiringChanged(connected: boolean, pin: string, wire: [Wire](Wire.md), instance: [Instance](Instance.md))`
- **Summary:** Fires when another instance is connected to or disconnected from the `Class.AudioReverb` via a `Class.Wire`.
