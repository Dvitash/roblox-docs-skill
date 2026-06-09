# AnimationTrack

**Superclass:** [Instance](Instance.md)

This file defines `AnimationTrack` as a class that controls the playback of an animation on an `Class.Animator`. It provides methods for controlling playback speed, looping, and setting priority based on animation priorities.

## Tags
- NotCreatable

## Properties
### `AnimationTrack.Animation`
- **Type:** `[Animation](Animation.md)`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The `Class.Animation` object that was used to create this `Class.AnimationTrack`.

### `AnimationTrack.IsPlaying`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A read-only property that returns true when the `Class.AnimationTrack` is playing.

### `AnimationTrack.Length`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A read-only property that returns the length (in seconds) of an `Class.AnimationTrack`. This will return `0` until the animation has fully loaded and thus may not be immediately available.

### `AnimationTrack.Looped`
- **Type:** `boolean`
- **Summary:** Sets whether the animation will repeat after finishing. If it is changed while playing the result will take effect after the animation finishes.

### `AnimationTrack.Priority`
- **Type:** `AnimationPriority`
- **Summary:** Sets the priority of an `Class.AnimationTrack`. Depending on what this is set to, playing multiple animations at once will look to this property to figure out which `Class.Keyframe` `Class.Pose|Poses` should be played over one another.

### `AnimationTrack.Speed`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Read-only property that gives the current playback speed of the `Class.AnimationTrack`.

### `AnimationTrack.TimePosition`
- **Type:** `float`
- **Tags:** NotReplicated
- **Summary:** Returns the position in time in seconds that an `Class.AnimationTrack` is through playing its source animation. Can be set to make the track jump to a specific moment in the animation.

### `AnimationTrack.WeightCurrent`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Read-only property that gives the current weight of the `Class.AnimationTrack`.

### `AnimationTrack.WeightTarget`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Read-only property that gives the current weight of the `Class.AnimationTrack`.

## Methods
### `AnimationTrack:AdjustSpeed(speed: float) -> ()`
- **Tags:** CustomLuaState
- **Summary:** Changes the `Class.AnimationTrack.Speed` of an animation. A positive value for speed plays the animation forward, a negative one plays it backwards, and `0` pauses it.

### `AnimationTrack:AdjustWeight(weight: float, fadeTime: float) -> ()`
- **Tags:** CustomLuaState
- **Summary:** Changes the weight of an animation, with the optional `fadeTime` parameter determining how long it takes for `Class.AnimationTrack.WeightCurrent` to reach `Class.AnimationTrack.WeightTarget`.

### `AnimationTrack:GetMarkerReachedSignal(name: string) -> RBXScriptSignal`
- **Summary:** Returns an `Datatype.RBXScriptSignal` (event) that fires when a specified `Class.KeyframeMarker` has been hit in an `Class.Animation|animation`.

### `AnimationTrack:GetParameter(key: string) -> Variant`

### `AnimationTrack:GetParameterDefaults() -> Dictionary`

### `AnimationTrack:GetTargetInstance(name: string) -> [Instance](Instance.md)?`

### `AnimationTrack:GetTargetNames() -> Array`

### `AnimationTrack:GetTimeOfKeyframe(keyframeName: string) -> double`
- **Summary:** Returns the time position of the first `Class.Keyframe` of the given name in an `Class.AnimationTrack`.

### `AnimationTrack:Play(fadeTime: float, weight: float, speed: float) -> ()`
- **Tags:** CustomLuaState
- **Summary:** Plays the `Class.AnimationTrack`. Once called an `Class.AnimationTrack` will play with the specified `fadeTime`, weight and speed.

### `AnimationTrack:SetParameter(key: string, value: Variant) -> ()`

### `AnimationTrack:SetTargetInstance(name: string, target: [Instance](Instance.md)?) -> ()`

### `AnimationTrack:Stop(fadeTime: float) -> ()`
- **Tags:** CustomLuaState
- **Summary:** Stops the `Class.AnimationTrack`.

## Events
### `AnimationTrack.DidLoop()`
- **Summary:** Fires when an `Class.AnimationTrack` loops on the next update following the end of the previous animation loop.

### `AnimationTrack.Ended()`
- **Summary:** Fires when the `Class.AnimationTrack` is completely done moving anything in the world.

### `AnimationTrack.KeyframeReached(keyframeName: string)`
- **Summary:** Fires every time playback of an `Class.AnimationTrack` reaches a `Class.Keyframe` that does not have the default name of `Keyframe`.

### `AnimationTrack.Stopped()`
- **Summary:** Fires when the `Class.AnimationTrack` finishes playing. The AnimationTrack might still animate the subject while the animation "fades out". To catch when the AnimationTrack is completely done moving anything in the world, use the `Class.AnimationTrack.Ended` event.
