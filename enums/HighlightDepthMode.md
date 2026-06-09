# Enum.HighlightDepthMode

Controls how the `Class.Highlight` effect displays with respect to other objects in the world.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `AlwaysOnTop` | 0 |  | Allows the `Class.Highlight` to display regardless if there are objects between the camera and the highlighted object. This means the viewer is always able to see the highlight regardless of what is between the highlighted object and the camera. <img src="/assets/ui/highlighting-objects/DepthMode-AlwaysOnTop.jpg" /> |
| `Occluded` | 1 |  | Hides the `Class.Highlight` if there are objects between the camera and the highlighted object. This means the viewer is only able to see the object if there are no obstructing objects between the highlighted object and the camera's view. <img src="/assets/ui/highlighting-objects/DepthMode-Occluded.jpg" /> |

**Valid values:** `Enum.HighlightDepthMode.AlwaysOnTop`, `Enum.HighlightDepthMode.Occluded`
