# FlagStand

**Superclass:** [Part](Part.md)

The `FlagStand` class is a base class for creating 'Capture the Flag' style games, and it inherits from `Part`. The `Flag` and `FlagStand` objects allow developers to quickly create these types of games.

## Tags
- Deprecated

## Properties
### `FlagStand.TeamColor`
- **Type:** `BrickColor`
- **Summary:** The Team that owns the `Class.FlagStand`. Corresponds with the TeamColors in the `Class.Teams` service.

## Events
### `FlagStand.FlagCaptured(player: [Instance](Instance.md))`
- **Summary:** Fires when a player bearing an opposing flag, and having the same `Class.Player.TeamColor` as the stand, touches the `Class.FlagStand`.
