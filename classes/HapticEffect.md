# HapticEffect

**Superclass:** [Instance](Instance.md)

Modern controllers and devices include motors for haptic feedback, which can be controlled by adding rumbles or vibrations. Roblox supports haptics for various devices.

## Properties
### `HapticEffect.Looped`
- **Type:** `boolean`
- **Summary:** Whether the haptic effect loops continuously.

### `HapticEffect.Position`
- **Type:** `Vector3`
- **Summary:** Along with `Class.HapticEffect.Radius|Radius`, specifies the impact position relative to the input device and, effectively, how broadly that impact effects nearby motors.

### `HapticEffect.Radius`
- **Type:** `float`
- **Summary:** Along with `Class.HapticEffect.Position|Position`, specifies the impact radius relative to the input device and, effectively, how broadly that impact effects nearby motors.

### `HapticEffect.Type`
- **Type:** `HapticEffectType`
- **Summary:** `Enum.HapticEffectType` describing the haptic type.

## Methods
### `HapticEffect:Play() -> ()`
- **Summary:** Plays the haptic effect.

### `HapticEffect:SetWaveformKeys(keys: Array) -> ()`
- **Summary:** Defines a custom waveform as a table and applies it to the haptic. This method takes in an array of `Datatype.FloatCurveKey` objects.

### `HapticEffect:Stop() -> ()`
- **Summary:** Stops the haptic effect.

## Events
### `HapticEffect.Ended()`
- **Summary:** Fires when the `Class.HapticEffect` has completed playback and stopped.
