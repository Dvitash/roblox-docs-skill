# AudioTextToSpeech

**Superclass:** [Instance](Instance.md)

This class is used to play text as speech audio, which controls whether the audio is played immediately or if it loops.

## Properties
### `AudioTextToSpeech.IsLoaded`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Denotes whether the `Class.AudioTextToSpeech` object is loaded, buffered, and ready to play.

### `AudioTextToSpeech.IsPlaying`
- **Type:** `boolean`
- **Summary:** Denotes whether the `Class.AudioTextToSpeech` object is currently playing.

### `AudioTextToSpeech.Looping`
- **Type:** `boolean`
- **Summary:** Controls whether the `Class.AudioTextToSpeech` object loops.

### `AudioTextToSpeech.Pitch`
- **Type:** `float`
- **Summary:** Controls the pitch of the generated speech audio, which will be independent of its speed.

### `AudioTextToSpeech.PlaybackSpeed`
- **Type:** `float`
- **Summary:** Controls how quickly the speech audio will be played, which controls its pitch.

### `AudioTextToSpeech.Speed`
- **Type:** `float`
- **Summary:** Controls the speed of the generated speech audio, which will be independent of its pitch.

### `AudioTextToSpeech.Text`
- **Type:** `string`
- **Summary:** The text to be converted into speech audio by `Class.AudioTextToSpeech`.

### `AudioTextToSpeech.TimeLength`
- **Type:** `double`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Denotes the length of the generated speech audio.

### `AudioTextToSpeech.TimePosition`
- **Type:** `double`
- **Summary:** Tracks the current position of the playhead within the generated speech audio.

### `AudioTextToSpeech.VoiceId`
- **Type:** `string`
- **Summary:** The voice style to be used by `Class.AudioTextToSpeech`.

### `AudioTextToSpeech.Volume`
- **Type:** `float`
- **Summary:** Controls how loudly the generated speech audio will be played.

## Methods
### `AudioTextToSpeech:GetConnectedWires(pin: string) -> List<[Wire](Wire.md)>`
- **Summary:** Returns an array of `Class.Wire|Wires` that are connected to the specified pin.

### `AudioTextToSpeech:GetWaveformAsync(timeRange: NumberRange, samples: int) -> Array`
- **Tags:** Yields
- **Summary:** Returns a sampling of the waveform data for the generated audio.

### `AudioTextToSpeech:LoadAsync() -> AssetFetchStatus`
- **Tags:** Yields
- **Summary:** Generates speech audio.

### `AudioTextToSpeech:Pause() -> ()`
- **Summary:** Pauses the `Class.AudioTextToSpeech` object wherever its `Class.AudioTextToSpeech.TimePosition|TimePosition` is.

### `AudioTextToSpeech:Play() -> ()`
- **Summary:** Plays the `Class.AudioTextToSpeech` from wherever its `Class.AudioTextToSpeech.TimePosition|TimePosition` is.

### `AudioTextToSpeech:Unload() -> ()`
- **Summary:** Unload the generated speech audio.

## Events
### `AudioTextToSpeech.Ended()`
- **Summary:** Fires when the `Class.AudioTextToSpeech` object has completed playback and paused.

### `AudioTextToSpeech.Looped()`
- **Summary:** Fires when the `Class.AudioTextToSpeech` object loops.

### `AudioTextToSpeech.WiringChanged(connected: boolean, pin: string, wire: [Wire](Wire.md), instance: [Instance](Instance.md))`
- **Summary:** Fires when another instance is connected to or disconnected from the `Class.AudioTextToSpeech` via a `Class.Wire`.
