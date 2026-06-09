# Enum.DeveloperMemoryTag

A memory tracking category.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Internal` | 0 |  | General data that doesn't have any categorization. This could be due to either internal reasons, or because it simply isn't being tracked categorically. |
| `HttpCache` | 1 |  | A cache of HTTP responses. |
| `Instances` | 2 |  | All the Instances present in memory. |
| `Signals` | 3 |  | Events, signals, connections, etc. |
| `LuaHeap` | 4 |  | All of the data in Luau, including everything happening in core scripts, built-in data types, etc. |
| `Script` | 5 |  | All memory being manipulated and referenced by scripts. |
| `PhysicsCollision` | 6 |  | Collision detection in the `Class.Workspace`. |
| `BaseParts` | 7 |  | 3D parts used for simulation. |
| `GraphicsSolidModels` | 8 |  | Rendering solid models (stuff made with Union, Negate, etc.). |
| `GraphicsMeshParts` | 10 |  | Rendering of mesh parts. |
| `GraphicsParticles` | 11 |  | Rendering of particles from ParticleEmitters. |
| `GraphicsParts` | 12 |  | Rendering of regular parts. |
| `GraphicsSpatialHash` | 13 |  | Spatial hash lookup tables of the game world that are used for rendering. |
| `GraphicsTerrain` | 14 |  | Rendering of terrain geometry. |
| `GraphicsTexture` | 15 |  | Rendering of textures in the game world. |
| `GraphicsTextureCharacter` | 16 |  | Rendering of texture composition maps that are generated for Humanoids. |
| `Sounds` | 17 |  | Data of sounds in-game. |
| `StreamingSounds` | 18 |  | Playback of sounds in-game. |
| `TerrainVoxels` | 19 |  | Occupancy/Material data of the Terrain. |
| `Gui` | 21 |  | Gui element data and rendering. |
| `Animation` | 22 |  | Playback of Animations on Humanoids and AnimationControllers. |
| `Navigation` | 23 |  | Pathfinding for Humanoids via the PathfindingService. |
| `GeometryCSG` | 24 |  |  |
| `GraphicsSlimModels` | 25 |  |  |

**Valid values:** `Enum.DeveloperMemoryTag.Internal`, `Enum.DeveloperMemoryTag.HttpCache`, `Enum.DeveloperMemoryTag.Instances`, `Enum.DeveloperMemoryTag.Signals`, `Enum.DeveloperMemoryTag.LuaHeap`, `Enum.DeveloperMemoryTag.Script`, `Enum.DeveloperMemoryTag.PhysicsCollision`, `Enum.DeveloperMemoryTag.BaseParts`, `Enum.DeveloperMemoryTag.GraphicsSolidModels`, `Enum.DeveloperMemoryTag.GraphicsMeshParts`, `Enum.DeveloperMemoryTag.GraphicsParticles`, `Enum.DeveloperMemoryTag.GraphicsParts`, `Enum.DeveloperMemoryTag.GraphicsSpatialHash`, `Enum.DeveloperMemoryTag.GraphicsTerrain`, `Enum.DeveloperMemoryTag.GraphicsTexture`, `Enum.DeveloperMemoryTag.GraphicsTextureCharacter`, `Enum.DeveloperMemoryTag.Sounds`, `Enum.DeveloperMemoryTag.StreamingSounds`, `Enum.DeveloperMemoryTag.TerrainVoxels`, `Enum.DeveloperMemoryTag.Gui`, `Enum.DeveloperMemoryTag.Animation`, `Enum.DeveloperMemoryTag.Navigation`, `Enum.DeveloperMemoryTag.GeometryCSG`, `Enum.DeveloperMemoryTag.GraphicsSlimModels`
