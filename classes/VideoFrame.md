# VideoFrame

**Superclass:** [GuiObject](GuiObject.md)

The `VideoFrame` class is a GUI object that renders a rectangle with a moving video image, and it can be configured to emit sound from a specific part of the base part.

## Properties
### `VideoFrame.IsLoaded`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Indicates when the `Class.VideoFrame.Video` has loaded from Roblox servers and is ready to play.

### `VideoFrame.Looped`
- **Type:** `boolean`
- **Summary:** Sets whether or not the `Class.VideoFrame.Video` repeats once it has finished when it is playing.

### `VideoFrame.MaximumResolution`
- **Type:** `VideoSampleSize`

### `VideoFrame.Playing`
- **Type:** `boolean`
- **Tags:** NotReplicated
- **Summary:** Indicates whether the `Class.VideoFrame.Video` is currently playing. It can be set to start or pause playback.

### `VideoFrame.Resolution`
- **Type:** `Vector2`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Gets the original source resolution of the `Class.VideoFrame.Video` file.

### `VideoFrame.RollOffMaxDistance`
- **Type:** `float`

### `VideoFrame.RollOffMinDistance`
- **Type:** `float`

### `VideoFrame.RollOffMode`
- **Type:** `RollOffMode`

### `VideoFrame.TimeLength`
- **Type:** `double`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Indicates the length of the `Class.VideoFrame.Video` in seconds.

### `VideoFrame.TimePosition`
- **Type:** `double`
- **Tags:** NotReplicated
- **Summary:** Indicates the progress in seconds of the `Class.VideoFrame.Video`.

### `VideoFrame.Video`
- **Type:** `ContentId`
- **Summary:** The content ID of the video file a `Class.VideoFrame` object is associated with.

### `VideoFrame.VideoContent`
- **Type:** `Content`

### `VideoFrame.Volume`
- **Type:** `float`
- **Summary:** Indicates how loud the `Class.VideoFrame.Video` is currently playing back.

## Methods
### `VideoFrame:Pause() -> ()`
- **Summary:** Sets `Class.VideoFrame.Playing` to `false`, pausing playback if the `Class.VideoFrame.Video` is playing.

### `VideoFrame:Play() -> ()`
- **Summary:** Sets `Class.VideoFrame.Playing` to `true`, playing the `Class.VideoFrame.Video` from the current `Class.VideoFrame.TimePosition`.

## Events
### `VideoFrame.DidLoop(video: string)`
- **Summary:** Fires whenever the `Class.VideoFrame.Video` loops.

### `VideoFrame.Ended(video: string)`
- **Summary:** Fires when the `Class.VideoFrame.Video` has completed playback and stopped.

### `VideoFrame.Loaded(video: string)`
- **Summary:** Fires when the `Class.VideoFrame.Video` is loaded.

### `VideoFrame.Paused(video: string)`
- **Summary:** This event fires whenever the `Class.VideoFrame.Video` is paused using `Class.VideoFrame:Pause()` or by setting `Class.VideoFrame.Playing` to false.

### `VideoFrame.Played(video: string)`
- **Summary:** Fires whenever the `Class.VideoFrame.Video` is played using the `Class.VideoFrame:Play()` function or by setting `Class.VideoFrame.Playing` to true.
