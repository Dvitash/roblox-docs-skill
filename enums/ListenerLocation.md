# Enum.ListenerLocation

Enum used with `Class.SoundService.DefaultListenerLocation` to determine where an `Class.AudioListener` is placed by default.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Default` | 0 |  | Behavior depends on the value of `Class.VoiceChatService.EnableDefaultVoice` and `Class.VoiceChatService.UseAudioApi`. When using the default voice setup with the audio API, this behaves similarly to `Camera`. |
| `None` | 1 |  | No `Class.AudioListener` will be created by default, but they can be created separately by scripts. |
| `Character` | 2 |  | All of the following, resulting in the world being heard from the position of your character while matching the orientation of your camera. - An `Class.Attachment` will be created and parented to the `Class.Model.PrimaryPart\|PrimaryPart` of the local player's `Class.Player.Character\|Character` model. - An `Class.AudioListener` will be created and parented to the `Class.Attachment`. - An `Class.AudioDeviceOutput` will be created and parented to `Class.SoundService`. - A `Class.Wire` will be created and parented to the previously-created `Class.AudioListener`. The wire's `Class.Wire.SourceInstance\|SourceInstance` will be set to the previously-created `Class.AudioListener` and its `Class.Wire.TargetInstance\|TargetInstance` will be set to the previously-created `Class.AudioDeviceOutput`. - The previously-created `Class.Attachment` will be updated once per frame to face the same direction as `Class.Workspace.CurrentCamera`. |
| `Camera` | 3 |  | All of the following, resulting in the world being heard from the perspective (postition and orientation) of the camera. - An `Class.AudioListener` will be created and parented to `Class.Workspace.CurrentCamera`. - An `Class.AudioDeviceOutput` will be created and parented to `Class.SoundService`. - A `Class.Wire` will be created and parented to the previously-created `Class.AudioListener`. The wire's `Class.Wire.SourceInstance\|SourceInstance` will be set to the previously-created `Class.AudioListener` and its `Class.Wire.TargetInstance\|TargetInstance` will be set to the previously-created `Class.AudioDeviceOutput`. |

**Valid values:** `Enum.ListenerLocation.Default`, `Enum.ListenerLocation.None`, `Enum.ListenerLocation.Character`, `Enum.ListenerLocation.Camera`
