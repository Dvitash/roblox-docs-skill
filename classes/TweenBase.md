# TweenBase

**Superclass:** [Instance](Instance.md)

TweenBase is an abstract base class for in-between interpolation handlers, which inherit from Class.Tween. It provides methods to pause and resume playback, and handles state transitions between states like `Playing` and `Delayed`.

## Tags
- NotCreatable
- NotBrowsable

## Properties
### `TweenBase.PlaybackState`
- **Type:** `PlaybackState`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Read-only property that shows the current state for the `Class.Tween` animation.

## Methods
### `TweenBase:Cancel() -> ()`
- **Summary:** Halts playback and resets the tween variables. If you then call `Class.TweenBase:Play()`, the properties of the tween resume interpolating towards their destination, but take the full length of the animation to do so.

### `TweenBase:Pause() -> ()`
- **Summary:** Halts playback of the tween. Doesn't reset its progress variables, meaning that if you call `Class.TweenBase:Play()`, the tween resumes playback from the moment it was paused.

### `TweenBase:Play() -> ()`
- **Summary:** Starts playback of a tween. Note that if playback has already started, calling `Play()` has no effect unless the tween has finished or is stopped (either by `Class.TweenBase:Cancel()` or `Class.TweenBase:Pause()`).

## Events
### `TweenBase.Completed(playbackState: PlaybackState)`
- **Summary:** Fires when the tween finishes playing or when stopped with `Class.TweenBase:Cancel()`.
