# Enum.TextChatMessageStatus

Indicates the status of a `Class.TextChatMessage`.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Unknown` | 1 |  | Generic failed status for any other `Class.TextChannel:SendAsync()` failures. |
| `Success` | 2 |  | Message has no issues. |
| `Sending` | 3 |  | Message is sending. |
| `TextFilterFailed` | 4 |  | Text filter failed to process the message. |
| `Floodchecked` | 5 |  | Message is from a user sending messages too frequently. |
| `InvalidPrivacySettings` | 6 |  | Message can't be sent because of the user's chat privacy settings. |
| `InvalidTextChannelPermissions` | 7 |  | Message's `Class.TextSource` is either not in the intended `Class.TextChannel` or `Class.TextSource.CanSend` is `false`. |
| `MessageTooLong` | 8 |  | Message is too long. |
| `ModerationTimeout` | 9 |  |  |

**Valid values:** `Enum.TextChatMessageStatus.Unknown`, `Enum.TextChatMessageStatus.Success`, `Enum.TextChatMessageStatus.Sending`, `Enum.TextChatMessageStatus.TextFilterFailed`, `Enum.TextChatMessageStatus.Floodchecked`, `Enum.TextChatMessageStatus.InvalidPrivacySettings`, `Enum.TextChatMessageStatus.InvalidTextChannelPermissions`, `Enum.TextChatMessageStatus.MessageTooLong`, `Enum.TextChatMessageStatus.ModerationTimeout`
