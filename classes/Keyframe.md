# Keyframe

**Superclass:** [Instance](Instance.md)

The `Class.Keyframe` class represents a keyframe in an animation, holding `Class.Pose` objects representing the applied poses at a specific time.

## Properties
### `Keyframe.Time`
- **Type:** `float`
- **Summary:** The `Class.Keyframe` time position (in seconds) in an animation. This determines the time at which the `Class.Pose|Poses` inside the keyframe will be shown.

## Methods
### `Keyframe:AddMarker(marker: [Instance](Instance.md)) -> ()`
- **Summary:** Adds a `Class.KeyframeMarker` to the `Class.Keyframe` by parenting it to the keyframe.

### `Keyframe:AddPose(pose: [Instance](Instance.md)) -> ()`
- **Summary:** Adds a `Class.Pose` to the `Class.Keyframe` by parenting it to the keyframe.

### `Keyframe:GetMarkers() -> List<[KeyframeMarker](KeyframeMarker.md)>`
- **Summary:** Returns an array containing all `KeyframeMarkers` that have been added to the `Class.Keyframe`.

### `Keyframe:GetPoses() -> List<[Pose](Pose.md)>`
- **Summary:** Returns an array containing all `Class.Pose|Poses` that have been added to a `Class.Keyframe`.

### `Keyframe:RemoveMarker(marker: [Instance](Instance.md)) -> ()`
- **Summary:** Removes a `Class.KeyframeMarker` from the `Class.Keyframe` by settings its `Class.Instance.Parent` to `nil`.

### `Keyframe:RemovePose(pose: [Instance](Instance.md)) -> ()`
- **Summary:** Removes a `Class.Pose` from the `Class.Keyframe` by setting its `Class.Instance.Parent` to `nil`.
