# SpawnLocation

**Superclass:** [Part](Part.md)

SpawnLocations determine where a `Class.Player` respawns when it dies, controlling team changes, and setting the behavior for how `Class.ForceField` is set up.

## Properties
### `SpawnLocation.AllowTeamChangeOnTouch`
- **Type:** `boolean`
- **Summary:** Allows a `Class.Player` to join the team by touching the `Class.SpawnLocation`. When set to true, if a `Class.Player` character comes into contact with the `Class.SpawnLocation`, the player's `Class.Player.TeamColor` will be set to `Class.SpawnLocation.TeamColor`.

### `SpawnLocation.Duration`
- **Type:** `int`
- **Summary:** The length of time, in seconds, that a `Class.ForceField` will be applied to a `Class.Player` character spawning at this `Class.SpawnLocation`. If Duration is zero, the `Class.ForceField` is never created, and it will not trigger the `Class.Instance.DescendantAdded` or `Class.Instance.ChildAdded` events.

### `SpawnLocation.Enabled`
- **Type:** `boolean`
- **Summary:** Sets whether or not the `Class.SpawnLocation` is enabled. When disabled players cannot spawn at the `Class.SpawnLocation` and the AllowTeamChangeOnTouch functionality is disabled.

### `SpawnLocation.Neutral`
- **Type:** `boolean`
- **Summary:** Whether or not a `Class.SpawnLocation` is affiliated with a specific team. This means that any `Class.Player`, of any `Class.Team`, can spawn on it if this property is set to true.

### `SpawnLocation.TeamColor`
- **Type:** `BrickColor`
- **Summary:** Sets what team the `Class.SpawnLocation` is affiliated to. If `Class.SpawnLocation.Neutral` property is false, only `Class.Player|Players` with the same `Class.Player.TeamColor` as the spawn's TeamColor will be able to spawn there.
