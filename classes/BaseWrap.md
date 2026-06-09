# BaseWrap

**Superclass:** [Instance](Instance.md)

The `BaseWrap` class is the base class for `Class.WrapTarget` and `Class.WrapLayer`, and it defines the parent type for `Class.BaseWrap`. It inherits from `Instance` and has specific properties defined for `CageMeshContent` and `CageOrigin`.

## Tags
- NotCreatable

## Properties
### `BaseWrap.CageMeshContent`
- **Type:** `Content`

### `BaseWrap.CageMeshId`
- **Type:** `ContentId`
- **Summary:** Asset ID for cage mesh.

### `BaseWrap.CageOrigin`
- **Type:** `CFrame`
- **Summary:** Cage mesh offset relative to parent `Class.MeshPart`.

### `BaseWrap.CageOriginWorld`
- **Type:** `CFrame`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Cage mesh offset in world space.

### `BaseWrap.HSRAssetId`
- **Type:** `ContentId`

### `BaseWrap.ImportOrigin`
- **Type:** `CFrame`
- **Summary:** Describes where a global zero was while authoring the cage mesh in an asset creation tool.

### `BaseWrap.ImportOriginWorld`
- **Type:** `CFrame`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Describes where the origin (in world space) was while authoring the cage mesh in an asset creation tool.
