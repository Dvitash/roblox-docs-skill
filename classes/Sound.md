# Sound

**Superclass:** [Instance](Instance.md)

The `Class.Sound` class is a container for emitting sound from `Class.BasePart` or `Class.Attachment` positions, and it can be attached to play the sound at a constant volume throughout the object's position.

## Properties
### `Sound.AcousticSimulationEnabled`
- **Type:** `boolean`

### `Sound.AudioContent`
- **Type:** `Content`
- **Tags:** Hidden
- **Summary:** A reference to an audio asset.

### `Sound.EmitterSize`
- **Type:** `float`
- **Tags:** Deprecated
- **Summary:** The minimum distance, in studs, at which a 3D `Class.Sound` (direct child of a `Class.BasePart` or `Class.Attachment`) will begin to attenuate (decrease in volume).

### `Sound.IsLoaded`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** This property is `true` when the `Class.Sound` has loaded from Roblox servers and is ready to play.

### `Sound.IsPaused`
- **Type:** `boolean`
- **Tags:** Hidden, ReadOnly, NotReplicated
- **Summary:** Read-only property which returns `true` when the `Class.Sound` is not playing.

### `Sound.IsPlaying`
- **Type:** `boolean`
- **Tags:** Hidden, ReadOnly, NotReplicated
- **Summary:** Read-only property which returns `true` when the `Class.Sound` is playing.

### `Sound.isPlaying`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated, Deprecated

### `Sound.Looped`
- **Type:** `boolean`
- **Summary:** Sets whether or not the `Class.Sound` repeats once it has finished playing.

### `Sound.LoopRegion`
- **Type:** `NumberRange`
- **Summary:** A range denoting a desired loop start and loop end within the `Class.Sound.PlaybackRegion|PlaybackRegion`, in seconds.

### `Sound.MaxDistance`
- **Type:** `float`
- **Tags:** Deprecated
- **Summary:** The maximum distance, in studs, a client's listener can be from the `Class.Sound|Sound\s` origin and still hear it. Only applies to Sounds parented to a `Class.Part` or `Class.Attachment` (3D sounds).

### `Sound.MinDistance`
- **Type:** `float`
- **Tags:** Deprecated
- **Summary:** The minimum distance at which a 3D `Class.Sound` (direct child of a `Class.BasePart` or `Class.Attachment`) will begin to attenuate. Effectively, the emitter size.

### `Sound.Pitch`
- **Type:** `float`
- **Tags:** Deprecated
- **Summary:** Sets how high pitched and fast a `Class.Sound` is when it is played. The greater the integer, the higher and faster the `Class.Sound` is.

### `Sound.PlaybackLoudness`
- **Type:** `double`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A number between `0` and `1000` indicating how loud the `Class.Sound` is currently playing back.

### `Sound.PlaybackRegion`
- **Type:** `NumberRange`
- **Summary:** A range denoting a desired start and stop time within the `Class.Sound.TimeLength|TimeLength`, in seconds.

### `Sound.PlaybackRegionsEnabled`
- **Type:** `boolean`
- **Summary:** If `true`, this property gives your `Class.Sound` access to the `Class.Sound.PlaybackRegion|PlaybackRegion` and `Class.Sound.LoopRegion|LoopRegion` properties which can more-accurately control its playback.

### `Sound.PlaybackSpeed`
- **Type:** `float`
- **Tags:** NotReplicated
- **Summary:** Determines the speed at which a `Class.Sound` will play, with higher values causing the sound to play faster and at a higher pitch.

### `Sound.Playing`
- **Type:** `boolean`
- **Tags:** NotReplicated
- **Summary:** Indicates whether the `Class.Sound` is currently playing.

### `Sound.PlayOnRemove`
- **Type:** `boolean`
- **Summary:** When `true`, the `Class.Sound` will play when it is removed from the experience.

### `Sound.RollOffMaxDistance`
- **Type:** `float`
- **Summary:** The maximum distance, in studs, a client's listener can be from the sound's origin and still hear it. Only applies to `Class.Sound|Sounds` parented to a `Class.BasePart` or `Class.Attachment`.

### `Sound.RollOffMinDistance`
- **Type:** `float`
- **Summary:** The minimum distance, in studs, at which a `Class.Sound` which is parented to a `Class.BasePart` or `Class.Attachment` will begin to attenuate (decrease in volume).

### `Sound.RollOffMode`
- **Type:** `RollOffMode`
- **Summary:** Controls how the volume of a `Class.Sound` which is parented to a `Class.BasePart` or `Class.Attachment` attenuates (fades out) as the distance between the listener and parent changes.

### `Sound.SoundGroup`
- **Type:** `[SoundGroup](SoundGroup.md)`
- **Summary:** The `Class.SoundGroup` that is linked to this `Class.Sound`.

### `Sound.SoundId`
- **Type:** `ContentId`
- **Summary:** Content ID of the sound file to associate with the `Class.Sound`.

### `Sound.TimeLength`
- **Type:** `double`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The length of the `Class.Sound` in seconds.

### `Sound.TimePosition`
- **Type:** `double`
- **Tags:** NotReplicated
- **Summary:** Progress of the `Class.Sound` in seconds. Can be changed to move the playback position of the `Class.Sound` both before and during playback.

### `Sound.Volume`
- **Type:** `float`
- **Summary:** The volume of the `Class.Sound`.

## Methods
### `Sound:Pause() -> ()`
- **Summary:** Pauses playback of the `Class.Sound` if it is playing.

### `Sound:pause() -> ()`
- **Tags:** Deprecated

### `Sound:Play() -> ()`
- **Summary:** Plays the `Class.Sound`.

### `Sound:play() -> ()`
- **Tags:** Deprecated

### `Sound:Resume() -> ()`
- **Summary:** Resumes the `Class.Sound`.

### `Sound:Stop() -> ()`
- **Summary:** Stops the `Class.Sound`.

### `Sound:stop() -> ()`
- **Tags:** Deprecated

## Events
### `Sound.DidLoop(soundId: string, numOfTimesLooped: int)`
- **Summary:** Fires whenever the `Class.Sound` loops.

### `Sound.Ended(soundId: string)`
- **Summary:** Fires when the `Class.Sound` has completed playback and stopped.

### `Sound.Loaded(soundId: string)`
- **Summary:** Fires when the `Class.Sound` is loaded.

### `Sound.Paused(soundId: string)`
- **Summary:** Fires whenever the `Class.Sound` is paused using `Class.Sound:Pause()|Pause()`.

### `Sound.Played(soundId: string)`
- **Summary:** Fires whenever the `Class.Sound` is played using `Class.Sound:Play()|Play()`.

### `Sound.Resumed(soundId: string)`
- **Summary:** Fires when the `Class.Sound` is resumed using `Class.Sound:Resume()|Resume()`.

### `Sound.Stopped(soundId: string)`
- **Summary:** Fires when the `Class.Sound` is stopped through using `Class.Sound:Stop()|Stop()`.
