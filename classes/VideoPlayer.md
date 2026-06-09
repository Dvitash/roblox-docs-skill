# VideoPlayer

**Superclass:** [Instance](Instance.md)

The `VideoPlayer` class is a container for playing video assets, allowing connections to `Class.VideoDisplay` and `Class.Audio` instances. It supports loading `VideoContent` in Studio Edit mode and controlling playback speed.

## Tags
- NotBrowsable

## Properties
### `VideoPlayer.AutoLoadInStudio`
- **Type:** `boolean`
- **Tags:** NotReplicated, NotScriptable
- **Summary:** Loads the `Class.VideoPlayer.VideoContent|VideoContent` while in Studio Edit mode.

### `VideoPlayer.AutoPlayInStudio`
- **Type:** `boolean`
- **Tags:** NotReplicated, NotScriptable
- **Summary:** Plays the `Class.VideoPlayer.VideoContent|VideoContent` while in Studio Edit mode.

### `VideoPlayer.IsLoaded`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Indicates when the `Class.VideoPlayer.VideoContent|VideoContent` has loaded and is ready to play.

### `VideoPlayer.IsPlaying`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Denotes whether this `Class.VideoPlayer` is currently playing.

### `VideoPlayer.Looping`
- **Type:** `boolean`
- **Summary:** Controls whether this `Class.VideoPlayer` loops.

### `VideoPlayer.MaximumResolution`
- **Type:** `VideoSampleSize`

### `VideoPlayer.PlaybackSpeed`
- **Type:** `float`
- **Summary:** Controls the speed at which the video is played.

### `VideoPlayer.Resolution`
- **Type:** `Vector2`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Gets the original source resolution of the `Class.VideoPlayer.VideoContent|VideoContent` file.

### `VideoPlayer.TimeLength`
- **Type:** `double`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Indicates the length of the `Class.VideoPlayer.VideoContent|VideoContent` in seconds.

### `VideoPlayer.TimePosition`
- **Type:** `double`
- **Summary:** Indicates the progress in seconds of the `Class.VideoPlayer.VideoContent|VideoContent`.

### `VideoPlayer.VideoContent`
- **Type:** `Content`
- **Summary:** The asset to be loaded into the `Class.VideoPlayer`.

### `VideoPlayer.Volume`
- **Type:** `float`
- **Summary:** Controls how loudly the audio track will be played.

## Methods
### `VideoPlayer:GetConnectedWires(pin: string) -> List<[Wire](Wire.md)>`
- **Summary:** Returns an array of `Class.Wire|Wires` that are connected to the specified pin.

### `VideoPlayer:GetInputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.TargetName` to connect to this instance via its `Class.Wire.TargetInstance` property.

### `VideoPlayer:GetOutputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.SourceName` to connect to this instance via its `Class.Wire.SourceInstance` property.

### `VideoPlayer:LoadAsync() -> AssetFetchStatus`
- **Tags:** Yields
- **Summary:** Loads the `Class.VideoPlayer.VideoContent|VideoContent` before it is played.

### `VideoPlayer:Pause() -> ()`
- **Summary:** Pauses the `Class.VideoPlayer` wherever its `Class.VideoPlayer.TimePosition|TimePosition` is.

### `VideoPlayer:Play() -> ()`
- **Summary:** Plays the `Class.VideoPlayer` from wherever its `Class.VideoPlayer.TimePosition|TimePosition` is.

### `VideoPlayer:Unload() -> ()`
- **Summary:** Unloads the `Class.VideoPlayer.VideoContent` to save resources.

## Events
### `VideoPlayer.DidEnd()`
- **Summary:** Fires when the `Class.VideoPlayer.VideoContent|VideoContent` has completed playback and stopped.

### `VideoPlayer.DidLoop()`
- **Summary:** Fires when the `Class.VideoPlayer.VideoContent|VideoContent` loops.

### `VideoPlayer.PlayFailed(error: AssetFetchStatus)`

### `VideoPlayer.WiringChanged(connected: boolean, pin: string, wire: [Wire](Wire.md), instance: [Instance](Instance.md))`
- **Summary:** Fires when another instance is connected to or disconnected from the `Class.VideoPlayer` via a `Class.Wire`.
