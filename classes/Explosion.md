# Explosion

**Superclass:** [Instance](Instance.md)

Explosion is a class that applies force to `Class.BaseParts` within an explosion's `BlastRadius` and breaks `Class.JointInstances` and `Class.WeldConstraint` between parts, killing `Class.Humanoid` characters protected by `Class.ForceField`.

## Properties
### `Explosion.BlastPressure`
- **Type:** `float`
- **Summary:** Used to determine the amount of force applied to `Class.BasePart|BaseParts` caught in the `Class.Explosion.BlastRadius`.

### `Explosion.BlastRadius`
- **Type:** `float`
- **Summary:** This property determines the radius of the `Class.Explosion`, in studs. This radius determines the area of effect of the explosion, not the size of the explosion's visuals.

### `Explosion.DestroyJointRadiusPercent`
- **Type:** `float`
- **Summary:** Used to set the proportion of the `Class.Explosion.BlastRadius`, between 0 and 1, within which all joints will be destroyed. Anything outside of this range will only have the `Class.Explosion` force applied to it.

### `Explosion.ExplosionType`
- **Type:** `ExplosionType`
- **Summary:** This property determines how the `Class.Explosion` will interact with `Class.Terrain`. Used to set if explosions will cause damage to the terrain or not.

### `Explosion.LocalTransparencyModifier`
- **Type:** `float`
- **Tags:** Hidden, NotReplicated

### `Explosion.Position`
- **Type:** `Vector3`
- **Summary:** This property is the position of the center of the `Class.Explosion`. It is defined in world-space and not influenced by the `Class.Explosion` parent.

### `Explosion.TimeScale`
- **Type:** `float`
- **Summary:** Value between 0 and 1 that controls the speed of the particle effect.

### `Explosion.Visible`
- **Type:** `boolean`
- **Summary:** This property determines whether or not the visual effect of an `Class.Explosion` is shown or not.

## Events
### `Explosion.Hit(part: [BasePart](BasePart.md), distance: float)`
- **Summary:** Fires when the `Class.Explosion` hits a `Class.BasePart` within its `Class.Explosion.BlastRadius`. Returns the part hit along with the distance of the part from `Class.Explosion.Position`.
