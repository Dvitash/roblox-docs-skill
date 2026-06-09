# Animator

**Superclass:** [Instance](Instance.md)

The `Animator` class is the main entry point for managing the playback and replication of `Class.Animation` tracks in Roblox.

## Properties
### `Animator.EvaluationThrottled`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated

### `Animator.PreferLodEnabled`
- **Type:** `boolean`

### `Animator.RootMotion`
- **Type:** `CFrame`
- **Tags:** ReadOnly, NotReplicated, NotBrowsable

### `Animator.RootMotionWeight`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated, NotBrowsable

## Methods
### `Animator:ApplyJointVelocities(motors: Variant) -> ()`
- **Summary:** Computes relative velocities between parts and applies them to `Class.Motor6D.Part1`.

### `Animator:GetPlayingAnimationTracks() -> Array`
- **Summary:** Returns the list of currently active `Class.AnimationTrack|AnimationTracks`.

### `Animator:GetTrackByAnimationId(animationId: ContentId) -> [AnimationTrack](AnimationTrack.md)?`
- **Summary:** Returns an existing `Class.AnimationTrack` on this `Class.Animator` that was loaded from an `Class.Animation` with the given animation ID. Unlike `Class.Animator:LoadAnimation()|LoadAnimation()`, this method does not create a new `Class.AnimationTrack` instance.

### `Animator:LoadAnimation(animation: [Animation](Animation.md)) -> [AnimationTrack](AnimationTrack.md)`
- **Summary:** Loads an `Class.Animation` onto an `Animator`, returning an `Class.AnimationTrack`.

### `Animator:RegisterEvaluationParallelCallback(callback: Function) -> ()`

### `Animator:StepAnimations(deltaTime: float) -> ()`
- **Summary:** Increments the `Class.AnimationTrack.TimePosition` of all playing `Class.AnimationTrack|AnimationTracks` that are loaded onto the `Animator`, applying the offsets to the model associated with the `Animator`. For use in the command bar or by plugins only.

## Events
### `Animator.AnimationPlayed(animationTrack: [AnimationTrack](AnimationTrack.md))`
- **Summary:** Fires when the `Animator` starts playing an `Class.AnimationTrack`.
