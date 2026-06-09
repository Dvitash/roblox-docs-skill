# Enum.ContextActionResult

Describes whether a contextual action should sink or pass input events.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Sink` | 0 |  | If `functionToBind` from `Class.ContextActionService:BindAction()` returns `Enum.ContextActionResult.Sink`, the input event will stop at that function and no other bound actions under it will be processed. This is the default behavior if `functionToBind` does not return anything or yields in any way. |
| `Pass` | 1 |  | If `functionToBind` from `Class.ContextActionService:BindAction()` returns `Enum.ContextActionResult.Pass`, the input event is considered to have not been handled by `functionToBind` and will continue being passed to actions bound to the same input type. |

**Valid values:** `Enum.ContextActionResult.Sink`, `Enum.ContextActionResult.Pass`
