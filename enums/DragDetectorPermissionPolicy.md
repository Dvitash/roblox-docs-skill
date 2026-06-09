# Enum.DragDetectorPermissionPolicy

Used to control the permission level for which players can interact with a `Class.DragDetector`.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Nobody` | 0 |  | No players can interact with the `Class.DragDetector`. |
| `Everybody` | 1 |  | All players can interact with the `Class.DragDetector`. |
| `Scriptable` | 2 |  | Invokes the function registered via `Class.DragDetector:SetPermissionPolicyFunction()`, enabling/disabling the detector based on whether the function returns `true` or `false`. |

**Valid values:** `Enum.DragDetectorPermissionPolicy.Nobody`, `Enum.DragDetectorPermissionPolicy.Everybody`, `Enum.DragDetectorPermissionPolicy.Scriptable`
