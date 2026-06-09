# Teams

**Superclass:** [Instance](Instance.md)

The Teams service holds game objects like `Class.Team` that must be parented to the `Teams` service for developers to use built-in team behavior and optional extended features.

## Tags
- NotCreatable
- Service

## Methods
### `Teams:GetTeams() -> List<[Team](Team.md)>`
- **Summary:** Returns a table containing the game's `Class.Team` objects. Will only return `Class.Team` objects that are parented to the `Class.Teams` service.

### `Teams:RebalanceTeams() -> ()`
- **Tags:** Deprecated
- **Summary:** Evens the number of people on each team. This function does not work correctly and should not be used.
