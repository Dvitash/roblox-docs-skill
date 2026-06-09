# KeyframeSequence

**Superclass:** [AnimationClip](AnimationClip.md)

This class represents a sequence of `Class.Keyframe|Keyframes` for an animation, which determines looping and priority settings.

## Properties
### `KeyframeSequence.AuthoredHipHeight`
- **Type:** `float`
- **Tags:** Hidden
- **Summary:** Contains the hip height of the `Class.Humanoid` of the model that was used to author this `Class.KeyframeSequence`.

## Methods
### `KeyframeSequence:AddKeyframe(keyframe: [Instance](Instance.md)) -> ()`
- **Summary:** Adds a `Class.Keyframe` to the `Class.KeyframeSequence` by parenting it to the `Class.KeyframeSequence`.

### `KeyframeSequence:GetKeyframes() -> List<[Keyframe](Keyframe.md)>`
- **Summary:** Returns an array that contains all `Class.Keyframe|Keyframes` contained in a `Class.KeyframeSequence`.

### `KeyframeSequence:RemoveKeyframe(keyframe: [Instance](Instance.md)) -> ()`
- **Summary:** This method removes a `Class.Keyframe` from the `Class.KeyframeSequence` by setting its parent to `nil`.
