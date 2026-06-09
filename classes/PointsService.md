# PointsService

**Superclass:** [Instance](Instance.md)

The `PointsService` class controls the points award system in Roblox, where players can earn and manage points based on their achievements.

## Tags
- NotCreatable
- Service
- Deprecated

## Methods
### `PointsService:AwardPoints(userId: int64, amount: int) -> Tuple`
- **Tags:** Yields, Deprecated
- **Summary:** Attempts to award the user with the specified `Class.Player.UserId` the specified number of points.

### `PointsService:GetAwardablePoints() -> int`
- **Tags:** Deprecated
- **Summary:** Returns the number of points the current game has available to award to players.

### `PointsService:GetGamePointBalance(userId: int64) -> int`
- **Tags:** Yields, Deprecated
- **Summary:** Returns the total number of points a player has in the current game.

### `PointsService:GetPointBalance(userId: int64) -> int`
- **Tags:** Yields, Deprecated
- **Summary:** Returns the total number of points the given player has across all games.

## Events
### `PointsService.PointsAwarded(userId: int64, pointsAwarded: int, userBalanceInGame: int, userTotalBalance: int)`
- **Summary:** Fires when points have been successfully awarded to a player, while also passing along the updated balance of points the player has in the current game and all games.
