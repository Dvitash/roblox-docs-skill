# Enum.ParticleFlipbookLayout

Determines the layout of the flipbook texture.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `None` | 0 |  | Disable flipbook features and use the texture as a single static texture over the particle's lifetime. |
| `Grid2x2` | 1 |  | 2&times;2 frames for a 4-frame animation. |
| `Grid4x4` | 2 |  | 4&times;4 frames for a 16-frame animation. |
| `Grid8x8` | 3 |  | 8&times;8 frames for a 64-frame animation. |
| `Custom` | 4 |  | A custom grid size defined by `Class.ParticleEmitter.FlipbookSizeX\|FlipbookSizeX` and `Class.ParticleEmitter.FlipbookSizeY\|FlipbookSizeY`. |

**Valid values:** `Enum.ParticleFlipbookLayout.None`, `Enum.ParticleFlipbookLayout.Grid2x2`, `Enum.ParticleFlipbookLayout.Grid4x4`, `Enum.ParticleFlipbookLayout.Grid8x8`, `Enum.ParticleFlipbookLayout.Custom`
