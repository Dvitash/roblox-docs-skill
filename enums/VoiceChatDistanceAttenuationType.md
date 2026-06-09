# Enum.VoiceChatDistanceAttenuationType

Enum used for preset distance attenuation curve options in the default voice chat setup.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Inverse` | 0 |  | Represents a distance attenuation curve that follows the inverse-squared law. This is identical to the default distance attenuation of an `Class.AudioEmitter` instance. |
| `Legacy` | 1 |  | Represents a linear-squared distance attenuation curve with a minimum distance of `7` and a maximum distance of `80`. This is identical to the distance attenuation used in the internal-only default voice setup that does not use `Class.AudioDeviceInput` and `Class.AudioEmitter` objects. |

**Valid values:** `Enum.VoiceChatDistanceAttenuationType.Inverse`, `Enum.VoiceChatDistanceAttenuationType.Legacy`
