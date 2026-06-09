# Path

**Superclass:** [Instance](Instance.md)

Path objects store the result of `Class.PathfindingService:CreatePath()` and allow for path computation, waypoint retrieval, and blocking detection.

## Tags
- NotCreatable
- NotReplicated

## Properties
### `Path.Status`
- **Type:** `PathStatus`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The `Enum.PathStatus` of the generated `Path`.

## Methods
### `Path:CheckOcclusionAsync(start: int) -> int`
- **Tags:** Yields
- **Summary:** Checks if a path is blocked starting at a specific waypoint.

### `Path:ComputeAsync(start: Vector3, finish: Vector3) -> ()`
- **Tags:** Yields
- **Summary:** Computes a `Path` from a start position to an end position.

### `Path:GetPointCoordinates() -> Array`
- **Tags:** Deprecated
- **Summary:** Returns a table of `Path` instances.

### `Path:GetWaypoints() -> Array`
- **Summary:** Returns an array of points in the path.

## Events
### `Path.Blocked(blockedWaypointIdx: int)`
- **Summary:** Fires when the computed path becomes blocked.

### `Path.Unblocked(unblockedWaypointIdx: int)`
- **Summary:** Fires when a computed path that was blocked becomes unblocked.
