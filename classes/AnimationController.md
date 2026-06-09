# AnimationController

**Superclass:** [Instance](Instance.md)

This file defines the `AnimationController` class, which allows loading and applying animations to a character or model, and provides methods for controlling animation playback.

## Methods
### `AnimationController:GetPlayingAnimationTracks() -> Array`
- **Tags:** Deprecated
- **Summary:** Returns an array of all `Class.AnimationTrack|AnimationTracks` that are currently being played by the `Class.AnimationController`.

### `AnimationController:LoadAnimation(animation: [Animation](Animation.md)) -> [AnimationTrack](AnimationTrack.md)`
- **Tags:** Deprecated
- **Summary:** Loads an `Class.Animation` onto an `Class.AnimationController`, returning an `Class.AnimationTrack` that can be used for playback.

## Events
### `AnimationController.AnimationPlayed(animationTrack: [AnimationTrack](AnimationTrack.md))`
- **Tags:** Deprecated
- **Summary:** Fires whenever the `Class.AnimationController` begins playing an animation. It returns the `Class.AnimationTrack` playing.
