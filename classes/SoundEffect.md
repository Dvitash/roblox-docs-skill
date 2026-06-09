# SoundEffect

**Superclass:** [Instance](Instance.md)

SoundEffect is the base class for all sound effects, which are derived from it by parenting them to `Class.Sound` or `Class.SoundGroup`. It supports toggling and determines the order in which effects are applied.

## Tags
- NotCreatable

## Properties
### `SoundEffect.Enabled`
- **Type:** `boolean`
- **Summary:** Toggles the effect on and off.

### `SoundEffect.Priority`
- **Type:** `int`
- **Summary:** Determines the order the effect will be applied in relation to other effects.
