# ParticleEmitter

**Superclass:** [Instance](Instance.md)

The `ParticleEmitter` class is a special object that emits customizable 2D particles into the world. It can be parented to `Class.BasePart` or `Class.Attachment` to determine where and how particles are emitted.

## Properties
### `ParticleEmitter.Acceleration`
- **Type:** `Vector3`
- **Summary:** Determines the global-axis acceleration of all active particles, measured in studs per second squared.

### `ParticleEmitter.Brightness`
- **Type:** `float`
- **Summary:** Scales the light emitted from the emitter when `Class.ParticleEmitter.LightInfluence` is 0.

### `ParticleEmitter.Color`
- **Type:** `ColorSequence`
- **Summary:** Determines the color of all active particles over their individual lifetimes.

### `ParticleEmitter.Drag`
- **Type:** `float`
- **Summary:** Determines the rate at which particles will lose half their speed through exponential decay.

### `ParticleEmitter.EmissionDirection`
- **Type:** `NormalId`
- **Summary:** Determines the face of the object that particles emit from.

### `ParticleEmitter.Enabled`
- **Type:** `boolean`
- **Summary:** Determines if particles emit from the emitter.

### `ParticleEmitter.FlipbookBlendFrames`
- **Type:** `boolean`
- **Summary:** Determines whether the flipbook frames are blended between.

### `ParticleEmitter.FlipbookFramerate`
- **Type:** `NumberRange`
- **Summary:** Determines how fast the flipbook texture animates in frames per second.

### `ParticleEmitter.FlipbookIncompatible`
- **Type:** `string`
- **Summary:** The error message to display if the `Class.ParticleEmitter.Texture|Texture` is incompatible for a flipbook.

### `ParticleEmitter.FlipbookLayout`
- **Type:** `ParticleFlipbookLayout`
- **Summary:** Determines the layout of the flipbook texture. Must be None, Grid2x2, Grid4x4, Grid8x8 or Custom.

### `ParticleEmitter.FlipbookMode`
- **Type:** `ParticleFlipbookMode`
- **Summary:** Determines the type of the flipbook animation. Must be Loop, OneShot, PingPong, or Random.

### `ParticleEmitter.FlipbookSizeX`
- **Type:** `int`
- **Summary:** Defines the number of horizontal frames in a custom flipbook layout.

### `ParticleEmitter.FlipbookSizeY`
- **Type:** `int`
- **Summary:** Defines the number of vertical frames in a custom flipbook layout.

### `ParticleEmitter.FlipbookStartRandom`
- **Type:** `boolean`
- **Summary:** Determines whether the animation starts at a random frame chosen per particle instead of always starting at frame zero.

### `ParticleEmitter.Lifetime`
- **Type:** `NumberRange`
- **Summary:** Defines a random range of ages for newly emitted particles.

### `ParticleEmitter.LightEmission`
- **Type:** `float`
- **Summary:** Determines how much particles' colors are blended with the colors behind them.

### `ParticleEmitter.LightInfluence`
- **Type:** `float`
- **Summary:** Determines how much particles are influenced by the environmental light.

### `ParticleEmitter.LocalTransparencyModifier`
- **Type:** `float`
- **Tags:** Hidden, NotReplicated

### `ParticleEmitter.LockedToPart`
- **Type:** `boolean`
- **Summary:** Determines whether the particles rigidly move with the part they're being emitted from.

### `ParticleEmitter.Orientation`
- **Type:** `ParticleOrientation`
- **Summary:** Specifies how to orient particles.

### `ParticleEmitter.Rate`
- **Type:** `float`
- **Summary:** Determines the number of particles emitted per second.

### `ParticleEmitter.Rotation`
- **Type:** `NumberRange`
- **Summary:** Determines the range of rotations in degrees for newly emitted particles.

### `ParticleEmitter.RotSpeed`
- **Type:** `NumberRange`
- **Summary:** Determines the range of angular speeds of emitted particles, measured in degrees per second.

### `ParticleEmitter.Shape`
- **Type:** `ParticleEmitterShape`
- **Summary:** Sets the shape of the emitter to either a box, sphere, cylinder, or disc.

### `ParticleEmitter.ShapeInOut`
- **Type:** `ParticleEmitterShapeInOut`
- **Summary:** Sets whether particles emit outward only, inward only, or in both directions.

### `ParticleEmitter.ShapePartial`
- **Type:** `float`
- **Summary:** Influences particle emission from cylinder, disc, sphere, and box shapes.

### `ParticleEmitter.ShapeStyle`
- **Type:** `ParticleEmitterShapeStyle`
- **Summary:** Sets particle emission to either volumetric or surface-only emission.

### `ParticleEmitter.Size`
- **Type:** `NumberSequence`
- **Summary:** Determines the world size over individual particles' lifetimes.

### `ParticleEmitter.Speed`
- **Type:** `NumberRange`
- **Summary:** Determines a random range of velocities (minimum to maximum) at which new particles will emit, measured in studs per second.

### `ParticleEmitter.SpreadAngle`
- **Type:** `Vector2`
- **Summary:** Determines the angles at which particles may be randomly emit, measured in degrees.

### `ParticleEmitter.Squash`
- **Type:** `NumberSequence`
- **Summary:** Allows for non-uniform scaling of particles, curve-controlled over their lifetime.

### `ParticleEmitter.Texture`
- **Type:** `ContentId`
- **Summary:** Determines the image rendered on particles.

### `ParticleEmitter.TimeScale`
- **Type:** `float`
- **Summary:** Value between 0 and 1 that controls the speed of the particle effect.

### `ParticleEmitter.Transparency`
- **Type:** `NumberSequence`
- **Summary:** Determines the transparency of particles over their individual lifetimes.

### `ParticleEmitter.VelocityInheritance`
- **Type:** `float`
- **Summary:** Determines how much of the parent's velocity is inherited by particles when emitted.

### `ParticleEmitter.VelocitySpread`
- **Type:** `float`
- **Tags:** NotReplicated, Deprecated
- **Summary:** Determines how offset a particle can be fired from the local emitter direction of its parent.

### `ParticleEmitter.WindAffectsDrag`
- **Type:** `boolean`
- **Summary:** Whether emitted particles follow the `Class.Workspace.GlobalWind` vector.

### `ParticleEmitter.ZOffset`
- **Type:** `float`
- **Summary:** Determines the forward-backward render position of particles; used to control what particles render on top/bottom.

## Methods
### `ParticleEmitter:Clear() -> ()`
- **Summary:** Clears all particles that have been emitted.

### `ParticleEmitter:Emit(particleCount: int) -> ()`
- **Summary:** Emits a given number of particles.
