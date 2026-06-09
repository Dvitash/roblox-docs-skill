# GeometryService

**Superclass:** [Instance](Instance.md)

GeometryService is a class containing geometric operations, including calculating constraints and attachments that preserve themselves. It is used for breaking down `Class.BasePart` into multiple `Class.MeshPart` instances based on the points passed in.

## Tags
- NotCreatable
- Service

## Methods
### `GeometryService:CalculateConstraintsToPreserve(source: [Instance](Instance.md), destination: Array, options: Dictionary) -> Array`
- **Summary:** Returns a table of `Class.Constraint|Constraints` and `Class.Attachment|Attachments` which you may choose to preserve, along with their respective parents.

### `GeometryService:FragmentAsync(part: [BasePart](BasePart.md), sites: Array, options: Dictionary) -> Array`
- **Tags:** Yields
- **Summary:** Breaks a `Class.BasePart` into multiple `Class.MeshPart` instances, according to the pattern of points passed in, by using voronoi decomposition.

### `GeometryService:GenerateFragmentSites(part: [BasePart](BasePart.md), options: Dictionary) -> Array`
- **Summary:** Provides an array of positions which can easily be passed into `FragmentAsync` to perform simple types of destruction.

### `GeometryService:IntersectAsync(part: [Instance](Instance.md), parts: Array, options: Dictionary) -> Array`
- **Tags:** Yields
- **Summary:** Creates one or more `Class.PartOperation|PartOperations` or `Class.MeshPart|MeshParts` from the intersecting geometry of multiple parts.

### `GeometryService:SubtractAsync(part: [Instance](Instance.md), parts: Array, options: Dictionary) -> Array`
- **Tags:** Yields
- **Summary:** Creates one or more `Class.PartOperation|PartOperations` or `Class.MeshPart|MeshParts` from one part minus the space occupied by other parts.

### `GeometryService:SweepPartAsync(part: [BasePart](BasePart.md), cframes: Array, options: Dictionary) -> [MeshPart](MeshPart.md)`
- **Tags:** Yields
- **Summary:** Creates a `Class.MeshPart` which has the shape of the input part stretched/dragged through the given set of `CFrame` positions.

### `GeometryService:UnionAsync(part: [Instance](Instance.md), parts: Array, options: Dictionary) -> Array`
- **Tags:** Yields
- **Summary:** Creates one or more `Class.PartOperation|PartOperations` or `Class.MeshPart|MeshParts` from one part plus the space occupied by other parts.
