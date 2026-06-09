# Enum.AlphaMode

Used by `Class.SurfaceAppearance.AlphaMode` to determine how the alpha channel of the `Class.SurfaceAppearance.ColorMap` of a `Class.SurfaceAppearance` is used.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Overlay` | 0 |  | Overlays the `Class.SurfaceAppearance.ColorMap\|ColorMap` on top of the underlying part color based on the map's alpha channel. |
| `Transparency` | 1 |  | Uses the `Class.SurfaceAppearance.ColorMap\|ColorMap` alpha channel to control the transparency of the surface. |
| `TintMask` | 2 |  | Uses the `Class.SurfaceAppearance.ColorMap\|ColorMap` alpha channel to control the amount of `Class.SurfaceAppearance.Color` tinting. |
| `Opaque` | 3 | NotBrowsable | Ignores the `Class.SurfaceAppearance.ColorMap\|ColorMap` alpha channel and assumes an opacity value of 1 everywhere. |

**Valid values:** `Enum.AlphaMode.Overlay`, `Enum.AlphaMode.Transparency`, `Enum.AlphaMode.TintMask`, `Enum.AlphaMode.Opaque`
