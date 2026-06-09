# AnimationClip

**Superclass:** [Instance](Instance.md)

This file defines `Class.AnimationClip` as a class representing all types of animation data that the Roblox animation system can consume, providing methods for looping and priority management.

## Tags
- NotCreatable

## Properties
### `AnimationClip.Length`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Returns the length (in seconds) of this `Class.AnimationClip`. This will return `0` until the animation has fully loaded and thus may not be immediately available.

### `AnimationClip.Loop`
- **Type:** `boolean`
- **Summary:** Determines whether the animation stored in this `Class.AnimationClip` is intended to loop.

### `AnimationClip.Priority`
- **Type:** `AnimationPriority`
- **Summary:** Determines which clip takes priority when multiple animations are playing simultaneously.
