# Enum.RenderPriority

A list of standard reserved values in BindToRenderStep.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `First` | 0 |  | This should run first. |
| `Input` | 100 |  | This should run as second. |
| `Camera` | 200 |  | This should run after Input. |
| `Character` | 300 |  | This should run after Camera. |
| `Last` | 2000 |  | This should run as last, after Character. |

**Valid values:** `Enum.RenderPriority.First`, `Enum.RenderPriority.Input`, `Enum.RenderPriority.Camera`, `Enum.RenderPriority.Character`, `Enum.RenderPriority.Last`
