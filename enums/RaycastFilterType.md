# Enum.RaycastFilterType

Used in a `Datatype.RaycastParams` object to determine how its `Datatype.RaycastParams.FilterDescendantsInstances|FilterDescendantsInstances` list will be used.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Exclude` | 0 |  | Every `Class.BasePart` in the raycast operation will be considered **except** those that are descendants of objects in the filter list. |
| `Include` | 1 |  | Only `Class.BasePart\|BaseParts` which are descendants of objects in the filter list will be considered in the raycast operation. |

**Valid values:** `Enum.RaycastFilterType.Exclude`, `Enum.RaycastFilterType.Include`
