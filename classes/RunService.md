# RunService

**Superclass:** [Instance](Instance.md)

RunService is a class in Roblox Scripting that manages runtime activity and context for scripts, including methods for managing client and server contexts.

## Tags
- NotCreatable
- Service
- NotReplicated

## Properties
### `RunService.ClientGitHash`
- **Type:** `string`
- **Tags:** ReadOnly, NotReplicated

### `RunService.RunState`
- **Type:** `RunState`
- **Tags:** NotReplicated

## Methods
### `RunService:BindToRenderStep(name: string, priority: int, function: Function) -> ()`
- **Summary:** Given a string name of a function and a priority, this method binds the function to `Class.RunService.PreRender`.

### `RunService:BindToSimulation(function: Function, frequency: StepFrequency, priority: int) -> RBXScriptConnection`
- **Summary:** Binds a custom function to be called at a fixed frequency which is independent of the frame rate.

### `RunService:GetPredictionStatus(context: [Instance](Instance.md)) -> PredictionStatus`
- **Summary:** Checks the `Enum.PredictionStatus` of a specific context instance, useful for debugging scripts affecting multiple instances where some might be predicted and others might not.

### `RunService:IsClient() -> boolean`
- **Summary:** Returns whether the current environment is running on the client.

### `RunService:IsEdit() -> boolean`
- **Summary:** Returns whether the current environment is in `Edit` mode.

### `RunService:IsRunMode() -> boolean`
- **Summary:** Returns whether a **Run** playtest has been initiated in Studio.

### `RunService:IsRunning() -> boolean`
- **Summary:** Returns whether the experience is currently running.

### `RunService:IsServer() -> boolean`
- **Summary:** Returns whether the current environment is running on the server.

### `RunService:IsStudio() -> boolean`
- **Summary:** Returns whether the current environment is running in Studio.

### `RunService:Pause() -> ()`
- **Summary:** Pauses the experience's simulation if it is running, suspending physics and scripts.

### `RunService:Reset() -> ()`
- **Tags:** Deprecated
- **Summary:** Resets the current game to a waypoint set when `Class.RunService:Run()` was called.

### `RunService:Run() -> ()`
- **Summary:** Runs the game's simulation, running physics and scripts.

### `RunService:SetPredictionMode(context: [Instance](Instance.md), mode: PredictionMode) -> ()`
- **Summary:** Sets the prediction mode for an `Class.Instance` to an `Enum.PredictionMode` value.

### `RunService:Stop() -> ()`
- **Summary:** Stops the experience's simulation if it is running.

### `RunService:UnbindFromRenderStep(name: string) -> ()`
- **Summary:** Unbinds a function that was bound to the render loop using `Class.RunService:BindToRenderStep()`.

## Events
### `RunService.Heartbeat(deltaTime: double)`
- **Summary:** Fires every frame, after the physics simulation has completed.

### `RunService.Misprediction(time: double, instances: Array, stats: Dictionary)`
- **Summary:** In the server authority model, fires during prediction when the engine detects that the client has diverged from the server's authoritative state. Intended for plugin-based debugging.

### `RunService.PostSimulation(deltaTimeSim: double)`
- **Summary:** Fires every frame, after the physics simulation has completed.

### `RunService.PreAnimation(deltaTimeSim: double)`
- **Summary:** Fires every frame, prior to the physics simulation but after rendering.

### `RunService.PreRender(deltaTimeRender: double)`
- **Summary:** Fires every frame, prior to the frame being rendered.

### `RunService.PreSimulation(deltaTimeSim: double)`
- **Summary:** Fires every frame, prior to the physics simulation.

### `RunService.RenderStepped(deltaTime: double)`
- **Summary:** Fires every frame, prior to the frame being rendered.

### `RunService.Rollback(time: double)`
- **Summary:** In the server authority model, this fires after rolling back the predicted state due to a misprediction, but before resimulation begins.

### `RunService.Stepped(time: double, deltaTime: double)`
- **Summary:** Fires every frame, prior to the physics simulation.
