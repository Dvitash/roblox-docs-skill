# TextFilterResult

**Superclass:** [Instance](Instance.md)

TextFilterResult is a class used to distribute filtered strings based on user IDs, applicable in contexts like chats.

## Tags
- NotCreatable
- NotReplicated

## Methods
### `TextFilterResult:GetChatForUserAsync(toUserId: int64) -> string`
- **Tags:** Yields, Deprecated
- **Summary:** Returns the text in a properly filtered manner for the specified `Class.Player.UserId`.

### `TextFilterResult:GetNonChatStringForBroadcastAsync() -> string`
- **Tags:** Yields
- **Summary:** Returns the text in a properly filtered manner for all users.

### `TextFilterResult:GetNonChatStringForUserAsync(toUserId: int64) -> string`
- **Tags:** Yields
- **Summary:** Returns the text in a properly filtered manner for the specified `Class.Player.UserId` based on age and other details.
