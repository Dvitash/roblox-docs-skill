# PathfindingService

**Superclass:** [Instance](Instance.md)

PathfindingService is a class used to find logical paths between two points, allowing characters to move freely without obstacles. It supports implementing pathfinding modifiers to compute smarter paths based on material or region.

## Tags
- NotCreatable
- Service
- NotReplicated

## Properties
### `PathfindingService.EmptyCutoff`
- **Type:** `float`
- **Tags:** NotReplicated, Deprecated
- **Summary:** Sets the percent of a voxel has to be occupied to be considered empty. Defaults to 0.16.

## Methods
### `PathfindingService:ComputeRawPathAsync(start: Vector3, finish: Vector3, maxDistance: float) -> [Path](Path.md)`
- **Tags:** Yields, Deprecated
- **Summary:** Computes and returns a `Class.Path` between two `Datatype.Vector3|Vector3s`. If the given MaxDistance is greater than 512, an error will be thrown. (MaxDistance is too large).

### `PathfindingService:ComputeSmoothPathAsync(start: Vector3, finish: Vector3, maxDistance: float) -> [Path](Path.md)`
- **Tags:** Yields, Deprecated
- **Summary:** Computes and returns a smooth `Class.Path` between two `Datatype.Vector3|Vector3s`.

### `PathfindingService:CreatePath(agentParameters: Dictionary) -> [Path](Path.md)`

### `PathfindingService:FindPathAsync(start: Vector3, finish: Vector3) -> [Path](Path.md)`
- **Tags:** Yields
- **Summary:** Finds a `Class.Path` between the two provided points.
