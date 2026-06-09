# Enum.Technology

Enum used by `Class.Lighting.Technology` to represent the different lighting systems available for rendering the 3D world.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Legacy` | 0 | Deprecated |  |
| `Voxel` | 1 |  | Uses a 4&times;4&times;4 voxel map for light and shadow calculation. |
| `Compatibility` | 2 |  | Simulates the removed legacy technology and is now deprecated. To achieve a similar look, use `Voxel` Lighting and add a `Class.ColorGradingEffect` post‑processing effect set to the `Enum.TonemapperPreset\|Retro` preset. |
| `ShadowMap` | 3 |  | Features shadow mapping that produces more realistic and crisp shadows from sunlight or directional light sources. |
| `Future` | 4 |  | Features the most advanced technology for high-fidelity lighting and shadows. |
| `Unified` | 5 | Deprecated |  |

**Valid values:** `Enum.Technology.Legacy`, `Enum.Technology.Voxel`, `Enum.Technology.Compatibility`, `Enum.Technology.ShadowMap`, `Enum.Technology.Future`, `Enum.Technology.Unified`
