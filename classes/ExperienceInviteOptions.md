# ExperienceInviteOptions

**Superclass:** [Instance](Instance.md)

Used to customize a player invite prompt by setting parameters for the sending friend and including launch data.

## Tags
- NotReplicated

## Properties
### `ExperienceInviteOptions.InviteMessageId`
- **Type:** `string`
- **Summary:** Asset ID that maps to a **Notification** asset type.

### `ExperienceInviteOptions.InviteUser`
- **Type:** `int64`
- **Summary:** Roblox `Class.Player.UserId|UserId` of the specific friend to invite.

### `ExperienceInviteOptions.LaunchData`
- **Type:** `string`
- **Summary:** Used to set a parameter in `Class.Player:GetJoinData()` when a friend joins from the invite notification.

### `ExperienceInviteOptions.PromptMessage`
- **Type:** `string`
- **Summary:** Custom text shown on the invite prompt for the sending player.
