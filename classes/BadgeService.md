# BadgeService

**Superclass:** [Instance](Instance.md)

BadgeService is a class that provides information and functionality related to badges and awards them across the platform.

## Tags
- NotCreatable
- Service

## Methods
### `BadgeService:AwardBadge(userId: int64, badgeId: int64) -> boolean`
- **Tags:** Yields, Deprecated
- **Summary:** Award a badge to a player given the ID of each.

### `BadgeService:AwardBadgeAsync(userId: int64, badgeId: int64) -> boolean`
- **Tags:** Yields
- **Summary:** Award a badge to a player given the ID of each.

### `BadgeService:CheckUserBadgesAsync(userId: int64, badgeIds: Array) -> Array`
- **Tags:** Yields
- **Summary:** Checks a list of badge IDs against a `Class.Player.UserId|UserId` and returns a list of badge IDs that the player owns.

### `BadgeService:GetBadgeInfoAsync(badgeId: int64) -> Dictionary`
- **Tags:** Yields
- **Summary:** Fetch information about a badge given its ID.

### `BadgeService:IsDisabled(badgeId: int64) -> boolean`
- **Tags:** Yields, Deprecated
- **Summary:** Returns whether a given badge is disabled.

### `BadgeService:IsLegal(badgeId: int64) -> boolean`
- **Tags:** Yields, Deprecated
- **Summary:** Determines if a given badge is associated with the current game.

### `BadgeService:UserHasBadge(userId: int64, badgeId: int64) -> boolean`
- **Tags:** Yields, Deprecated
- **Summary:** Checks whether a user has the badge given the `Class.Player.UserId` and the badge ID.

### `BadgeService:UserHasBadgeAsync(userId: int64, badgeId: int64) -> boolean`
- **Tags:** Yields
- **Summary:** Checks whether a player has the badge given the `Class.Player.UserId` and the badge ID.
