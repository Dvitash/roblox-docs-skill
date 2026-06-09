# Enum.GraphicsMode

Used to set the graphics API that Roblox uses to render the game.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Automatic` | 1 |  | Roblox will automatically decide what graphics mode to use, depending on what best suits your device's specifications. |
| `Direct3D11` | 2 |  | Direct3D Version 11 (Microsoft). |
| `OpenGL` | 4 |  | OpenGL (Khronos Group). |
| `Metal` | 5 |  | Metal (Apple). |
| `Vulkan` | 6 |  | Vulkan (Khronos Group). |
| `NoGraphics` | 9 |  | Game will not be rendered, and instead a _Diagnostics_ window is rendered on screen. |

**Valid values:** `Enum.GraphicsMode.Automatic`, `Enum.GraphicsMode.Direct3D11`, `Enum.GraphicsMode.OpenGL`, `Enum.GraphicsMode.Metal`, `Enum.GraphicsMode.Vulkan`, `Enum.GraphicsMode.NoGraphics`
