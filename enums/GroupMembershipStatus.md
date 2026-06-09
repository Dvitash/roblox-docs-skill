# Enum.GroupMembershipStatus

Defines the possible outcomes of the `Class.GroupService:PromptJoinAsync()` method.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `None` | 0 |  | The player chose not to join, cancelled the prompt, or was not eligible to join the group. |
| `Joined` | 1 |  | The player successfully joined the group during the prompt. |
| `JoinRequestPending` | 2 |  | The player submitted a request to join the group, or already had a pending join request prior to prompting. |
| `AlreadyMember` | 3 |  | The player was already a member of the group. |

**Valid values:** `Enum.GroupMembershipStatus.None`, `Enum.GroupMembershipStatus.Joined`, `Enum.GroupMembershipStatus.JoinRequestPending`, `Enum.GroupMembershipStatus.AlreadyMember`
