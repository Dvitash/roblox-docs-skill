# WorldRoot

**Superclass:** [Model](Model.md)

The `WorldRoot` class is a base class for handling physics simulation and spatial queries, providing an API for interacting with `Class.Workspace` and `Class.WorldModel`.

## Tags
- NotCreatable

## Methods
### `WorldRoot:ArePartsTouchingOthers(partList: Instances, overlapIgnored: float) -> boolean`
- **Summary:** Returns true if any of the given `Class.BasePart` are touching any other parts.

### `WorldRoot:Blockcast(cframe: CFrame, size: Vector3, direction: Vector3, params: RaycastParams) -> RaycastResult?`
- **Summary:** Casts a block shape in a given direction and returns a `Datatype.RaycastResult` if the shape hits a `Class.BasePart` or `Class.Terrain` cell.

### `WorldRoot:BulkMoveTo(partList: Instances, cframeList: Array, eventMode: BulkMoveMode) -> ()`
- **Summary:** Moves a table of `Class.BasePart|BaseParts` to a table of `Datatype.CFrame|CFrames`.

### `WorldRoot:FindPartOnRay(ray: Ray, ignoreDescendantsInstance: [Instance](Instance.md), terrainCellsAreCubes: boolean, ignoreWater: boolean) -> Tuple`
- **Tags:** Deprecated
- **Summary:** Returns the first `Class.BasePart` or `Class.Terrain` cell intersecting with the given `Datatype.Ray`.

### `WorldRoot:findPartOnRay(ray: Ray, ignoreDescendantsInstance: [Instance](Instance.md), terrainCellsAreCubes: boolean, ignoreWater: boolean) -> Tuple`
- **Tags:** Deprecated

### `WorldRoot:FindPartOnRayWithIgnoreList(ray: Ray, ignoreDescendantsTable: Instances, terrainCellsAreCubes: boolean, ignoreWater: boolean) -> Tuple`
- **Tags:** Deprecated
- **Summary:** Returns the first `Class.BasePart` or `Class.Terrain` cell intersecting with the given `Datatype.Ray` that isn't in, nor is a descendant of an object in, the given ignore list.

### `WorldRoot:FindPartOnRayWithWhitelist(ray: Ray, whitelistDescendantsTable: Instances, ignoreWater: boolean) -> Tuple`
- **Tags:** Deprecated
- **Summary:** Returns the first `Class.BasePart` or `Class.Terrain` cell intersecting with the given `Datatype.Ray` that is in, or is a descendant of an object in, the given inclusion list.

### `WorldRoot:FindPartsInRegion3(region: Region3, ignoreDescendantsInstance: [Instance](Instance.md), maxParts: int) -> List<[BasePart](BasePart.md)>`
- **Tags:** Deprecated
- **Summary:** Returns an array of `Class.BasePart|BaseParts` in the given `Datatype.Region3`.

### `WorldRoot:findPartsInRegion3(region: Region3, ignoreDescendantsInstance: [Instance](Instance.md), maxParts: int) -> List<[BasePart](BasePart.md)>`
- **Tags:** Deprecated

### `WorldRoot:FindPartsInRegion3WithIgnoreList(region: Region3, ignoreDescendantsTable: Instances, maxParts: int) -> List<[BasePart](BasePart.md)>`
- **Tags:** Deprecated
- **Summary:** Returns an array of `Class.BasePart|BaseParts` in the given `Datatype.Region3` that aren't in, or a descendant of an entry in, the given ignore list.

### `WorldRoot:FindPartsInRegion3WithWhiteList(region: Region3, whitelistDescendantsTable: Instances, maxParts: int) -> List<[BasePart](BasePart.md)>`
- **Tags:** Deprecated
- **Summary:** Returns an array of `Class.BasePart|BaseParts` in the given `Datatype.Region3` that are in, or descendant of an entry in, the given inclusion list.

### `WorldRoot:GetPartBoundsInBox(cframe: CFrame, size: Vector3, overlapParams: OverlapParams) -> List<[BasePart](BasePart.md)>`
- **Tags:** CustomLuaState
- **Summary:** Returns an array of parts whose **bounding boxes** overlap a given box.

### `WorldRoot:GetPartBoundsInRadius(position: Vector3, radius: float, overlapParams: OverlapParams) -> List<[BasePart](BasePart.md)>`
- **Tags:** CustomLuaState
- **Summary:** Returns an array of parts whose **bounding boxes** overlap a given sphere.

### `WorldRoot:GetPartsInPart(part: [BasePart](BasePart.md), overlapParams: OverlapParams) -> List<[BasePart](BasePart.md)>`
- **Tags:** CustomLuaState
- **Summary:** Returns an array of parts whose occupied space is shared with the given part.

### `WorldRoot:IKMoveTo(part: [BasePart](BasePart.md), target: CFrame, translateStiffness: float, rotateStiffness: float, collisionsMode: IKCollisionsMode) -> ()`
- **Summary:** Moves the specified part to the specified location via inverse kinematics rather than moving it there directly, to ensure any joints, constraints, or collisions that part is participating in remain physically satisfied.

### `WorldRoot:IsRegion3Empty(region: Region3, ignoreDescendentsInstance: [Instance](Instance.md)) -> boolean`
- **Tags:** Deprecated
- **Summary:** Returns a bool indicating whether there are no `Class.BasePart|BaseParts` within the given `Datatype.Region3`.

### `WorldRoot:IsRegion3EmptyWithIgnoreList(region: Region3, ignoreDescendentsTable: Instances) -> boolean`
- **Tags:** Deprecated
- **Summary:** Returns a boolean indicating whether there are no `Class.BasePart|BaseParts` within the given `Datatype.Region3`, ignoring any `Class.BasePart|BaseParts` that are descendants of the objects within the given ignore list.

### `WorldRoot:Raycast(origin: Vector3, direction: Vector3, raycastParams: RaycastParams) -> RaycastResult?`
- **Summary:** Casts a ray using an origin, direction, and optional `Datatype.RaycastParams`, then returns a `Datatype.RaycastResult` if an eligible object or terrain intersects the ray.

### `WorldRoot:Shapecast(part: [BasePart](BasePart.md), direction: Vector3, params: RaycastParams) -> RaycastResult?`

### `WorldRoot:Spherecast(position: Vector3, radius: float, direction: Vector3, params: RaycastParams) -> RaycastResult?`
- **Summary:** Casts a spherical shape in a given direction and returns a `Datatype.RaycastResult` if the shape hits a `Class.BasePart` or `Class.Terrain` cell.

### `WorldRoot:StepPhysics(dt: float, parts: Instances) -> ()`
- **Summary:** Advances the simulation for parts in the world forward based on a specified time increment and an optional set of `Class.BasePart|BaseParts`.
