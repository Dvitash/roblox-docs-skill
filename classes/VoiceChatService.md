# VoiceChatService

**Superclass:** [Instance](Instance.md)

VoiceChatService is a class responsible for controlling voice chat functionality, including setting default distance attenuation and enabling/disabling audio systems.

## Tags
- NotCreatable
- Service

## Properties
### `VoiceChatService.DefaultDistanceAttenuation`
- **Type:** `VoiceChatDistanceAttenuationType`
- **Summary:** Determines which distance attenuation curve the default voice chat setup uses when `Class.AudioDeviceInput` and `Class.AudioEmitter` objects are generated.

### `VoiceChatService.EnableDefaultVoice`
- **Type:** `boolean`
- **Summary:** Controls whether each voice-eligible player can be heard as though they were speaking through their character.

### `VoiceChatService.UseAudioApi`
- **Type:** `AudioApiRollout`
- **Summary:** Controls whether voice chat is represented and controlled by `Class.AudioDeviceInput` objects.

## Methods
### `VoiceChatService:GetChatGroupsAsync(players: Instances) -> Array`
- **Tags:** Yields
- **Summary:** Returns chat group IDs that indicate which players can voice chat together.

### `VoiceChatService:IsVoiceEnabledForUserIdAsync(userId: int64) -> boolean`
- **Tags:** Yields
- **Summary:** Returns whether or not the given user has voice enabled.
