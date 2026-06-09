# PVInstance

**Superclass:** [Instance](Instance.md)

This file defines the `PVInstance` class, which represents objects with a physical location in the world. It provides methods for moving these objects and details their inheritance and security.

## Tags
- NotCreatable
- NotBrowsable

## Properties
### `PVInstance.Origin`
- **Type:** `CFrame`
- **Tags:** NotReplicated, NotScriptable

### `PVInstance.Pivot Offset`
- **Type:** `CFrame`
- **Tags:** NotReplicated, NotScriptable

## Methods
### `PVInstance:GetPivot() -> CFrame`
- **Summary:** Gets the pivot of a `Class.PVInstance`.

### `PVInstance:PivotTo(targetCFrame: CFrame) -> ()`
- **Summary:** Transforms the `Class.PVInstance` along with all of its descendant `Class.PVInstance|PVInstances` such that the pivot is now located at the specified `Datatype.CFrame`.
