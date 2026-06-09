# Enum.RenderFidelity

Determines the level of detail that solid modeled and mesh parts will be shown in.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Automatic` | 0 |  | Object's level of detail is dynamically controlled by its distance from the camera (see table above). |
| `Precise` | 1 |  | Object is rendered in the highest fidelity regardless of its distance from the camera. |
| `Performance` | 2 |  | Push performance as much as possible, trying to maintain quality if possible, and discarding appearance if that's necessary to reach performance. This means that the performance will always be excellent, but mesh visuals may be affected negatively. |

**Valid values:** `Enum.RenderFidelity.Automatic`, `Enum.RenderFidelity.Precise`, `Enum.RenderFidelity.Performance`
