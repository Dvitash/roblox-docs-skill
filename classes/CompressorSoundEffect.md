# CompressorSoundEffect

**Superclass:** [SoundEffect](SoundEffect.md)

Adjusts the dynamic range of audio by compressing or expanding the volume based on a specified threshold.

## Properties
### `CompressorSoundEffect.Attack`
- **Type:** `float`
- **Summary:** The time the effect takes to become active after its `Class.CompressorSoundEffect.Threshold|Threshold` has been reached.

### `CompressorSoundEffect.GainMakeup`
- **Type:** `float`
- **Summary:** The overall amplification applied to the effect's `Class.Sound` or `Class.SoundGroup` after attenuation of sounds above the threshold.

### `CompressorSoundEffect.Ratio`
- **Type:** `float`
- **Summary:** The ratio between the `Class.CompressorSoundEffect.SideChain|SideChain` sound effect, and this sound effect.

### `CompressorSoundEffect.Release`
- **Type:** `float`
- **Summary:** The time the effect takes to become inactive after its sound is below the `Class.CompressorSoundEffect.Threshold|Threshold`.

### `CompressorSoundEffect.SideChain`
- **Type:** `[Instance](Instance.md)`
- **Summary:** Applies a ducking effect to the compressor sound effect. The behavior of the sidechain depends on the `Class.Sound` or `Class.SoundGroup` linked to it.

### `CompressorSoundEffect.Threshold`
- **Type:** `float`
- **Summary:** Volume level at which point the compressor applies its effect.
