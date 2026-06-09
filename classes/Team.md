# Team

**Superclass:** [Instance](Instance.md)

The `Class.Teams` class defines the base structure for defining factions in Roblox, allowing developers to program features that work 'out of the box' or implement checks for friendly fire.

## Properties
### `Team.AutoAssignable`
- **Type:** `boolean`
- **Summary:** This property determines whether `Class.Player|Players` will be automatically placed onto the `Class.Team` when joining. If multiple teams have this property set to true, Roblox will attempt to even the teams out when `Class.Player|Players` are added.

### `Team.AutoColorCharacters`
- **Type:** `boolean`
- **Tags:** NotReplicated, Deprecated
- **Summary:** Deprecated and no longer functional. Historically set whether or not `Class.Player` character models on a team would be colored to `Class.Team.TeamColor`.

### `Team.Score`
- **Type:** `int`
- **Tags:** NotReplicated, Deprecated
- **Summary:** This property can be used to store an integer value associated with the team. This property offers no additional functionality and is not used by any game services.

### `Team.TeamColor`
- **Type:** `BrickColor`
- **Summary:** This property sets the color of the `Class.Team`. Determines the `Class.Player.TeamColor` property of players who are a member of the team. Also determines the color displayed on the player list and above player's heads.

## Methods
### `Team:GetPlayers() -> List<[Player](Player.md)>`
- **Summary:** Returns a list of `Class.Player|Players` who are assigned to the `Class.Team`. A `Class.Player` is considered assigned if their `Class.Player.Team` property is equal to the `Class.Team` and `Class.Player.Neutral` is false.

## Events
### `Team.PlayerAdded(player: [Player](Player.md))`
- **Summary:** Fires whenever a `Class.Player` is assigned to the `Class.Team`. A player is considered assigned if their `Class.Player.Team` property is equal to the `Class.Team` and `Class.Player.Neutral` is false.

### `Team.PlayerRemoved(player: [Player](Player.md))`
- **Summary:** Fires whenever a `Class.Player` is removed from a `Class.Team`. This can be due to the `Class.Player` leaving the game, `Class.Player.Neutral` being set to true or the `Class.Player` joining a different team.
