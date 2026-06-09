# PartOperation

**Superclass:** [TriangleMeshPart](TriangleMeshPart.md)

This file defines `PartOperation` as an abstract class that all solid modeling parts inherit from, providing methods for adjusting rendering details and controlling color recoloration.

## Properties
### `PartOperation.RenderFidelity`
- **Type:** `RenderFidelity`
- **Summary:** The level of detail used to render the solid modeled part.

### `PartOperation.SmoothingAngle`
- **Type:** `float`
- **Summary:** An angle in degrees which affects the smooth shading of a solid modeled part.

### `PartOperation.TriangleCount`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The number of polygons in this solid model.

### `PartOperation.UsePartColor`
- **Type:** `boolean`
- **Summary:** Sets whether the `Class.PartOperation` can be recolored using inherited color properties.

## Methods
### `PartOperation:SubstituteGeometry(source: [Instance](Instance.md)) -> ()`
- **Summary:** Substitutes the geometry of this `Class.PartOperation` with the geometry of another `Class.PartOperation`.
