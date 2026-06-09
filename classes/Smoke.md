# Smoke

**Superclass:** [Instance](Instance.md)

The `Class.Smoke` class is a particle emitter with a smoke aesthetic, which emits particles when parented to `Class.BasePart` or `Class.Attachment`. It has specific rules for rendering and handling particles, including how they are spawned and how they interact with the parent object.

## Properties
### `Smoke.Color`
- **Type:** `Color3`
- **Summary:** Determines the color of the smoke particles.

### `Smoke.Enabled`
- **Type:** `boolean`
- **Summary:** Determines whether smoke particles emit.

### `Smoke.LocalTransparencyModifier`
- **Type:** `float`
- **Tags:** Hidden, NotReplicated

### `Smoke.Opacity`
- **Type:** `float`
- **Tags:** NotReplicated
- **Summary:** Determines how opaque smoke particles render.

### `Smoke.RiseVelocity`
- **Type:** `float`
- **Tags:** NotReplicated
- **Summary:** Determines the velocity of the smoke particles.

### `Smoke.Size`
- **Type:** `float`
- **Tags:** NotReplicated
- **Summary:** Determines the size of newly emit smoke particles.

### `Smoke.TimeScale`
- **Type:** `float`
- **Summary:** Value between 0-1 that controls the speed of the particle effect.
