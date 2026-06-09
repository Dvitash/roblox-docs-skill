# SoundService

**Superclass:** [Instance](Instance.md)

The `SoundService` class determines various aspects of how audio engine behavior is managed, including global acoustic simulation and advanced audio system instance behavior.

## Tags
- NotCreatable
- Service

## Properties
### `SoundService.AcousticSimulationEnabled`
- **Type:** `boolean`
- **Summary:** Determines whether acoustic simulation is enabled globally in the advanced audio system.

### `SoundService.AmbientReverb`
- **Type:** `ReverbType`
- **Summary:** The ambient sound environment preset applied to all `Class.Sound|Sounds`.

### `SoundService.CharacterSoundsUseNewApi`
- **Type:** `RolloutState`
- **Summary:** Determines whether the default character sounds will use instances in the advanced audio system vs. `Class.Sound|Sounds`.

### `SoundService.DefaultListenerLocation`
- **Type:** `ListenerLocation`
- **Summary:** Determines where (if anywhere) to place an `Class.AudioListener` by default.

### `SoundService.DistanceFactor`
- **Type:** `float`
- **Summary:** The number of studs to be considered a meter by `Class.SoundService` when simulating the Doppler effect for `Class.Sound|Sounds`.

### `SoundService.DopplerScale`
- **Type:** `float`
- **Summary:** Degree to which the pitch of a `Class.Sound` varies due to the Doppler effect.

### `SoundService.RespectFilteringEnabled`
- **Type:** `boolean`
- **Summary:** Sets whether `Class.Sound` playback from a client will replicate to the server.

### `SoundService.RolloffScale`
- **Type:** `float`
- **Summary:** Determines how fast the volume of a `Class.Sound` attenuates beyond its `Class.Sound.RollOffMinDistance`.

### `SoundService.VolumetricAudio`
- **Type:** `VolumetricAudio`
- **Tags:** NotScriptable
- **Summary:** Determines whether certain spatialized `Class.Sound|Sounds` emit volumetrically, throughout the space of their parent object.

## Methods
### `SoundService:GetListener() -> Tuple`
- **Summary:** Returns the current listener type used by `Class.Sound|Sounds`, as well as what that listener is currently set to.

### `SoundService:GetMixerTime() -> double`
- **Summary:** Returns the number of seconds since the audio engine began mixing.

### `SoundService:OpenAttenuationCurveEditor(selectedCurveObjects: Instances) -> ()`
- **Summary:** Opens the attenuation curve editor in Studio for the provided `Class.AudioEmitter` or `Class.AudioListener` instances.

### `SoundService:OpenDirectionalCurveEditor(selectedCurveObjects: Instances) -> ()`
- **Summary:** Opens the directional curve editor in Studio for the provided `Class.AudioEmitter` or `Class.AudioListener` instances.

### `SoundService:PlayLocalSound(sound: [Instance](Instance.md)) -> ()`
- **Summary:** Plays a copy of a `Class.Sound` locally, such that it will only be heard by the client calling this method.

### `SoundService:SetListener(listenerType: ListenerType, listener: Tuple) -> ()`
- **Summary:** Sets the listener used by `Class.Sound|Sounds`.
