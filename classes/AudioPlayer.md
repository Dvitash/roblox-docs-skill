# AudioPlayer

**Superclass:** [Instance](Instance.md)

This file defines the `Class.AudioPlayer` class, which controls how audio assets are played and is used to manage audio content within a system.

## Properties
### `AudioPlayer.Asset`
- **Type:** `ContentId`
- **Summary:** The asset to be loaded into the `Class.AudioPlayer`.

### `AudioPlayer.AssetId`
- **Type:** `string`
- **Tags:** Hidden, NotReplicated, Deprecated
- **Summary:** The asset to be loaded into the `Class.AudioPlayer`.

### `AudioPlayer.AudioContent`
- **Type:** `Content`
- **Tags:** Hidden
- **Summary:** The audio content to be loaded into the `Class.AudioPlayer`.

### `AudioPlayer.AutoLoad`
- **Type:** `boolean`
- **Summary:** Controls whether `Class.AudioPlayer.Asset|Asset` loads automatically once assigned.

### `AudioPlayer.AutoPlay`
- **Type:** `boolean`
- **Summary:** Denotes whether this `Class.AudioPlayer` starts playing as soon as it spawns in for the first time.

### `AudioPlayer.IsPlaying`
- **Type:** `boolean`
- **Summary:** Denotes whether this `Class.AudioPlayer` is currently playing or planning to play.

### `AudioPlayer.IsReady`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Denotes whether this `Class.AudioPlayer` is loaded, buffered, and ready to play.

### `AudioPlayer.Looping`
- **Type:** `boolean`
- **Summary:** Controls whether this `Class.AudioPlayer` loops.

### `AudioPlayer.LoopRegion`
- **Type:** `NumberRange`
- **Summary:** A range, in seconds, denoting a desired loop start and loop end within the `Class.AudioPlayer.PlaybackRegion|PlaybackRegion` of this `Class.AudioPlayer`.

### `AudioPlayer.PlaybackRegion`
- **Type:** `NumberRange`
- **Summary:** Range in seconds denoting a desired start time (minimum) and stop time (maximum) within the `Class.AudioPlayer.TimeLength|TimeLength`.

### `AudioPlayer.PlaybackSpeed`
- **Type:** `double`
- **Summary:** Controls how quickly the asset will be played, which controls its pitch.

### `AudioPlayer.TimeLength`
- **Type:** `double`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Denotes the length of the loaded asset.

### `AudioPlayer.TimePosition`
- **Type:** `double`
- **Summary:** Tracks the current position of the playhead within the asset.

### `AudioPlayer.Volume`
- **Type:** `float`
- **Summary:** Controls how loudly the asset will be played.

## Methods
### `AudioPlayer:Cancel(actionId: int64?) -> boolean`
- **Summary:** Attempts to cancel a pre-planned future `Play` or `Stop` command.

### `AudioPlayer:GetConnectedWires(pin: string) -> List<[Wire](Wire.md)>`
- **Summary:** Returns an array of `Class.Wire|Wires` that are connected to the specified pin.

### `AudioPlayer:GetInputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.TargetName` to connect to this instance via its `Class.Wire.TargetInstance` property.

### `AudioPlayer:GetOutputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.SourceName` to connect to this instance via its `Class.Wire.SourceInstance` property.

### `AudioPlayer:GetWaveformAsync(timeRange: NumberRange, samples: int) -> Array`
- **Tags:** Yields
- **Summary:** Returns a sampling of the waveform data for the loaded `Class.AudioPlayer.Asset|Asset`.

### `AudioPlayer:Play(atTime: double?) -> int64?`
- **Summary:** Plays the `Class.AudioPlayer` from wherever its `Class.AudioPlayer.TimePosition|TimePosition` is.

### `AudioPlayer:Stop(atTime: double?) -> int64?`
- **Summary:** Stops the `Class.AudioPlayer` wherever its `Class.AudioPlayer.TimePosition|TimePosition` is.

## Events
### `AudioPlayer.Ended()`
- **Summary:** Fires when the `Class.AudioPlayer` has completed playback and stopped.

### `AudioPlayer.Looped()`
- **Summary:** Fires when the `Class.AudioPlayer` loops.

### `AudioPlayer.WiringChanged(connected: boolean, pin: string, wire: [Wire](Wire.md), instance: [Instance](Instance.md))`
- **Summary:** Fires when another instance is connected to or disconnected from the `Class.AudioPlayer` via a `Class.Wire`.
