# Stats

**Superclass:** [Instance](Instance.md)

This class represents a service that provides real-time performance metrics for a game instance, including data received and sent by the server.

## Tags
- NotCreatable
- Service

## Properties
### `Stats.ContactsCount`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A measurement of how many parts are currently in contact with one another.

### `Stats.DataReceiveKbps`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** In a networked game, this describes roughly how many kilobytes of data are being received by the current instance, per second.

### `Stats.DataSendKbps`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** In a networked game, this describes roughly how many kilobytes of data are being sent by the current instance, per second.

### `Stats.FrameTime`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A measurement of how long it takes for the engine to process all tasks required to render a frame.

### `Stats.HeartbeatTime`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A measurement of the total amount of time it takes for the server to update its task scheduler jobs in seconds.

### `Stats.HeartbeatTimeMs`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated, Deprecated
- **Summary:** A measurement of the total amount of time it takes long it takes for Roblox to update all of its task scheduler jobs, in milliseconds.

### `Stats.InstanceCount`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A measurement of how many `Class.Instance` are currently in memory.

### `Stats.MemoryTrackingEnabled`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** An indication of whether memory tracking is enabled. This is guaranteed to be unchanged until the next time the Client is started.

### `Stats.MovingPrimitivesCount`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A measurement of how many physically simulated components are currently moving in the game world.

### `Stats.PhysicsReceiveKbps`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** In a networked game, this describes roughly how many kilobytes of physics data are being received by the current instance, per second.

### `Stats.PhysicsSendKbps`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** In a networked game, this describes roughly how many kilobytes of physics data are being sent by the current instance, per second.

### `Stats.PhysicsStepTime`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A measurement of how long it takes for the physics engine to update its current state.

### `Stats.PhysicsStepTimeMs`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated, Deprecated
- **Summary:** A measurement of how long it takes for the physics engine to update its current state, in milliseconds. If this value is high, then it means the game instance is under stress from the physics simulations taking place.

### `Stats.PrimitivesCount`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A measurement of how many physically simulated components currently exist in the game world.

### `Stats.RenderCPUFrameTime`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A measurement of how long it takes for the CPU to process all of its rendering tasks for a frame.

### `Stats.RenderGPUFrameTime`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A measurement of how long it takes for the GPU to process all of its tasks required to render a frame.

### `Stats.SceneDrawcallCount`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A measurement of the number of draw calls made by the game's current scene.

### `Stats.SceneTriangleCount`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A measurement of the number of triangles rendered by the game's current scene.

### `Stats.ShadowsDrawcallCount`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A measurement of the number of draw calls being made for shadows by the game's current scene.

### `Stats.ShadowsTriangleCount`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A measurement of the number of triangles rendered as shadows in the game's current scene.

### `Stats.UI2DDrawcallCount`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A measurement of the number of 2D draw calls made for UI elements in the game's current scene.

### `Stats.UI2DTriangleCount`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A measurement of the number of triangles that are being rendered for 2D UI elements in the game's current scene.

### `Stats.UI3DDrawcallCount`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A measurement of the number of 3D draw calls made for UI elements in the game's current scene.

### `Stats.UI3DTriangleCount`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A measurement of the number of triangles being rendered for 3D UI elements in the game's current scene.

## Methods
### `Stats:GetHarmonyQualityLevel() -> int`

### `Stats:GetMemoryCategoryNames() -> Array`

### `Stats:GetMemoryUsageMbAllCategories() -> Array`
- **Summary:** Returns the number of megabytes that are being consumed by all available categories, or an empty array if `Class.Stats.MemoryTrackingEnabled|MemoryTrackingEnabled` is `false`.

### `Stats:GetMemoryUsageMbForTag(tag: DeveloperMemoryTag) -> float`
- **Summary:** Returns the number of megabytes that are being consumed in the specified `Enum.DeveloperMemoryTag` category, or `0` if `Class.Stats.MemoryTrackingEnabled|MemoryTrackingEnabled` is `false`.

### `Stats:GetTotalMemoryUsageMb() -> float`
- **Summary:** Returns the total amount of memory being consumed by the current game session, in megabytes.

### `Stats:ResetHarmonyMemoryTarget() -> ()`

### `Stats:SetHarmonyMemoryTarget(targetMB: int) -> ()`
