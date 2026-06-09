# SocialService

**Superclass:** [Instance](Instance.md)

The `SocialService` class provides methods for facilitating social functions on Roblox, including sending invites and managing game invites.

## Tags
- NotCreatable
- Service
- NotReplicated

## Methods
### `SocialService:CanSendCallInviteAsync(player: [Instance](Instance.md)) -> boolean`
- **Tags:** Yields
- **Summary:** Indicates whether the given `Class.Player` can invite other players to a call.

### `SocialService:CanSendGameInviteAsync(player: [Instance](Instance.md), recipientId: int64) -> boolean`
- **Tags:** Yields
- **Summary:** Indicates whether the given `Class.Player` can invite other players.

### `SocialService:GetEventRsvpStatusAsync(eventId: string) -> RsvpStatus`
- **Tags:** Yields
- **Summary:** Returns the local player's RSVP status for the given event.

### `SocialService:GetExperienceEventAsync(eventId: string) -> Dictionary?`
- **Tags:** Yields
- **Summary:** Returns details for the specified experience event or `nil` if it is unavailable.

### `SocialService:GetPartyAsync(partyId: string) -> Array`
- **Tags:** Yields
- **Summary:** Returns an array of dictionaries containing data for all members of the specified party who are currently in the experience.

### `SocialService:GetPlayersByPartyId(partyId: string) -> List<[Player](Player.md)>`
- **Summary:** Returns a table of all presently connected `Class.Player` objects whose `Class.Player.PartyId` property matches the passed `partyId`.

### `SocialService:GetUpcomingExperienceEventsAsync() -> Array`
- **Tags:** Yields
- **Summary:** Returns active and upcoming experience events for the current experience.

### `SocialService:HideSelfView() -> ()`
- **Summary:** Hides the calling player's self view.

### `SocialService:PromptFeedbackSubmissionAsync(options: Dictionary?) -> ()`
- **Tags:** Yields
- **Summary:** Prompts the player to submit feedback about the current experience.

### `SocialService:PromptGameInvite(player: [Instance](Instance.md), experienceInviteOptions: [Instance](Instance.md)) -> ()`
- **Summary:** Prompts the given `Class.Player` with the invite screen.

### `SocialService:PromptLinkSharing(player: [Player](Player.md), options: Dictionary) -> Tuple`
- **Tags:** Yields, Deprecated

### `SocialService:PromptLinkSharingAsync(player: [Player](Player.md), options: Dictionary) -> Tuple`
- **Tags:** Yields

### `SocialService:PromptPhoneBook(player: [Instance](Instance.md), tag: string) -> ()`
- **Summary:** Prompts the given `Class.Player` with the phone book.

### `SocialService:PromptRsvpToEventAsync(eventId: string) -> RsvpStatus`
- **Tags:** Yields
- **Summary:** Prompts the local `Class.Player` with a prompt to change their RSVP status to the given event.

### `SocialService:ShowSelfView(selfViewPosition: SelfViewPosition) -> ()`
- **Summary:** Shows the calling player's self view.

## Events
### `SocialService.CallInviteStateChanged(player: [Instance](Instance.md), inviteState: InviteState)`
- **Summary:** Fires when a player's call invite state changes.

### `SocialService.GameInvitePromptClosed(player: [Instance](Instance.md), recipientIds: Array)`
- **Summary:** Fires when a player closes an invite prompt.

### `SocialService.PhoneBookPromptClosed(player: [Instance](Instance.md))`
- **Summary:** Fires when a player closes the phone book prompt.

### `SocialService.ShareSheetClosed(player: [Player](Player.md))`
