# Workspace

**Superclass:** [WorldRoot](WorldRoot.md)

The `Class.Workspace` class holds 3D objects that are rendered in a 3D world, and it includes functions related to parts, positions, and joints. It automatically cleans up objects that require adornment and handles managing assets like `Class.ParticleEmitters` and `Class.BillboardGuis`.

## Tags
- NotCreatable
- Service

## Properties
### `Workspace.AirDensity`
- **Type:** `float`
- **Summary:** The air density at ground level, used in the aerodynamic force model.

### `Workspace.AirTurbulenceIntensity`
- **Type:** `float`
- **Summary:** Controls the strength of turbulence present in the wind velocity field, affecting the aerodynamic force model.

### `Workspace.AllowThirdPartySales`
- **Type:** `boolean`
- **Tags:** NotReplicated
- **Summary:** Determines whether assets created by other users can be sold in the game.

### `Workspace.AuthorityMode`
- **Type:** `AuthorityMode`
- **Summary:** Sets the server authority mode.

### `Workspace.AvatarUnificationMode`
- **Type:** `AvatarUnificationMode`
- **Tags:** NotScriptable
- **Summary:** Enables the R6 to R15 adapter, allowing R15 avatars to join R6 experiences.

### `Workspace.ClientAnimatorThrottling`
- **Type:** `ClientAnimatorThrottlingMode`
- **Summary:** Specifies the animation throttling mode for the local client.

### `Workspace.CurrentCamera`
- **Type:** `[Camera](Camera.md)`
- **Tags:** NotReplicated
- **Summary:** The `Class.Camera` object being used by the local player.

### `Workspace.DistributedGameTime`
- **Type:** `double`
- **Tags:** NotReplicated
- **Summary:** The amount of time, in seconds, that the game has been running.

### `Workspace.EnableSLIMAvatars`
- **Type:** `RolloutState`
- **Tags:** NotScriptable
- **Summary:** Controls whether SLIM rendering is used for avatars in the experience.

### `Workspace.FallenPartsDestroyHeight`
- **Type:** `float`
- **Summary:** Determines the height at which falling `Class.BasePart|BaseParts` and their ancestor `Class.Model|Models` are removed from `Class.Workspace`.

### `Workspace.FallHeightEnabled`
- **Type:** `boolean`
- **Summary:** Controls whether parts that fall below `Class.Workspace.FallenPartsDestroyHeight` are automatically destroyed.

### `Workspace.FilteringEnabled`
- **Type:** `boolean`
- **Tags:** Hidden, NotReplicated, Deprecated
- **Summary:** Determines whether changes made from the client will replicate to the server or not.

### `Workspace.FluidForces`
- **Type:** `FluidForces`
- **Tags:** NotScriptable
- **Summary:** Determines whether the physics engine computes aerodynamic forces on `Class.BasePart|BaseParts` whose `Class.BasePart.EnableFluidForces|EnableFluidForces` property is true.

### `Workspace.GlobalWind`
- **Type:** `Vector3`
- **Summary:** Specifies the global wind vector for animated terrain grass, dynamic clouds, and particles.

### `Workspace.Gravity`
- **Type:** `float`
- **Summary:** Determines the acceleration due to gravity applied to falling `Class.BasePart|BaseParts`.

### `Workspace.IKControlConstraintSupport`
- **Type:** `IKControlConstraintSupport`
- **Tags:** NotScriptable
- **Summary:** Enables support for constraints for IKControls. If disabled, IKControls ignore physics constraints.

### `Workspace.InsertPoint`
- **Type:** `Vector3`
- **Tags:** NotReplicated
- **Summary:** The world position at which new objects are placed when inserted from the toolbox.

### `Workspace.InterpolationThrottling`
- **Type:** `InterpolationThrottlingMode`
- **Tags:** Hidden, NotReplicated, Deprecated

### `Workspace.LayeredClothingCacheOptimizations`
- **Type:** `RolloutState`
- **Tags:** NotScriptable
- **Summary:** Controls whether layered clothing cache optimizations are enabled.

### `Workspace.LuauTypeCheckMode`
- **Type:** `LuauTypeCheckMode`
- **Summary:** Sets the Luau type checking mode for scripts in the experience.

### `Workspace.MeshPartHeadsAndAccessories`
- **Type:** `MeshPartHeadsAndAccessories`
- **Tags:** NotScriptable
- **Summary:** Sets whether character Heads and Accessories should be downloaded as MeshParts.

### `Workspace.MeshStreamingAndImprovedLods`
- **Type:** `RolloutState`
- **Tags:** NotScriptable
- **Summary:** Controls whether the experience uses the new mesh streaming and improved LOD system.

### `Workspace.ModelStreamingBehavior`
- **Type:** `ModelStreamingBehavior`
- **Tags:** NotScriptable
- **Summary:** Controls how `Class.Model|Models` are replicated in experiences when instance streaming is enabled.

### `Workspace.NextGenerationReplication`
- **Type:** `RolloutState`
- **Tags:** NotScriptable
- **Summary:** When `true`, enables an alternate replication system that alters and improves how properties are replicated under the hood.

### `Workspace.NextGenerationReplicationAlias`
- **Type:** `RolloutState`
- **Tags:** NotReplicated, NotScriptable

### `Workspace.PathfindingUseImprovedSearch`
- **Type:** `PathfindingUseImprovedSearch`
- **Tags:** NotScriptable
- **Summary:** Controls whether an improved search algorithm is used by `Class.PathfindingService`.

### `Workspace.PhysicsImprovedSleep`
- **Type:** `RolloutState`
- **Tags:** NotScriptable
- **Summary:** Controls whether the improved partial physics sleep algorithm is enabled.

### `Workspace.PhysicsSteppingMethod`
- **Type:** `PhysicsSteppingMethod`
- **Tags:** NotScriptable
- **Summary:** Sets how the solver will advance the physics simulation forward in time.

### `Workspace.PlayerCharacterDestroyBehavior`
- **Type:** `PlayerCharacterDestroyBehavior`
- **Tags:** NotScriptable
- **Summary:** Controls whether the engine automatically calls `Destroy()` on a player's character when it is replaced and on the `Player` object when the player leaves.

### `Workspace.PlayerScriptsUseInputActionSystem`
- **Type:** `RolloutState`
- **Tags:** NotScriptable
- **Summary:** Controls internal behavior of the built-in `Class.Player` scripts.

### `Workspace.PlayerScriptsUseInputActionSystemAlias`
- **Type:** `RolloutState`
- **Tags:** NotReplicated, NotScriptable

### `Workspace.PrimalPhysicsSolver`
- **Type:** `PrimalPhysicsSolver`
- **Tags:** NotScriptable
- **Summary:** Controls whether the experimental Primal Physics Solver is enabled.

### `Workspace.RejectCharacterDeletions`
- **Type:** `RejectCharacterDeletions`
- **Tags:** NotScriptable
- **Summary:** Controls whether the server rejects attempts by clients to delete player characters from the workspace.

### `Workspace.RenderingCacheOptimizations`
- **Type:** `RenderingCacheOptimizationMode`
- **Tags:** NotScriptable
- **Summary:** Controls whether rendering cache optimizations are enabled.

### `Workspace.ReplicateInstanceDestroySetting`
- **Type:** `ReplicateInstanceDestroySetting`
- **Tags:** NotScriptable
- **Summary:** Controls how `Instance:Destroy()` calls are replicated from the server to clients.

### `Workspace.Retargeting`
- **Type:** `AnimatorRetargetingMode`
- **Summary:** Controls whether animation retargeting is enabled for character animations.

### `Workspace.SandboxedInstanceMode`
- **Type:** `SandboxedInstanceMode`
- **Tags:** NotScriptable
- **Summary:** Controls whether sandboxed instance mode (script capabilities) is enabled.

### `Workspace.SignalBehavior`
- **Type:** `SignalBehavior`
- **Tags:** NotScriptable
- **Summary:** Configures when the engine resumes event handlers.

### `Workspace.SignalBehaviorAlias`
- **Type:** `SignalBehavior`
- **Tags:** NotReplicated, NotScriptable

### `Workspace.StreamingEnabled`
- **Type:** `boolean`
- **Summary:** Whether content streaming is enabled for the place.

### `Workspace.StreamingEnabledAlias`
- **Type:** `boolean`
- **Tags:** NotReplicated, NotScriptable

### `Workspace.StreamingIntegrityMode`
- **Type:** `StreamingIntegrityMode`
- **Tags:** NotScriptable
- **Summary:** Determines whether streaming integrity mode is active.

### `Workspace.StreamingMinRadius`
- **Type:** `int`
- **Tags:** NotScriptable
- **Summary:** Minimum distance that content will be streamed to players with high priority.

### `Workspace.StreamingTargetRadius`
- **Type:** `int`
- **Tags:** NotScriptable
- **Summary:** Maximum distance that content will be streamed to players.

### `Workspace.StreamOutBehavior`
- **Type:** `StreamOutBehavior`
- **Tags:** NotScriptable
- **Summary:** Configures how the engine decides when to stream content away from players.

### `Workspace.Terrain`
- **Type:** `[Terrain](Terrain.md)`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A reference to the `Class.Terrain` object parented to the `Class.Workspace`.

### `Workspace.TouchesUseCollisionGroups`
- **Type:** `boolean`
- **Tags:** NotScriptable
- **Summary:** Determines whether `Class.BasePart|parts` in different groups set to not collide will ignore collisions and touch events.

### `Workspace.UseFixedSimulation`
- **Type:** `RolloutState`
- **Tags:** NotScriptable
- **Summary:** When `true`, enables `Class.RunService:BindToSimulation()` which calls a function at a fixed frequency, updates physics stepping logic, and makes the `Global.RobloxGlobals.time()` function return the fixed stepped frame time.

### `Workspace.UseFixedSimulationAlias`
- **Type:** `RolloutState`
- **Tags:** NotReplicated, NotScriptable

### `Workspace.UseNewLuauTypeSolver`
- **Type:** `RolloutState`
- **Tags:** NotScriptable
- **Summary:** Controls whether the new Luau type solver is used for type inference.

### `Workspace.ValidateEnabledProximityPrompt`
- **Type:** `RolloutState`
- **Tags:** NotScriptable

## Methods
### `Workspace:BreakJoints(objects: Instances) -> ()`
- **Tags:** Deprecated
- **Summary:** Goes through all `Class.BasePart|BaseParts` given, breaking any joints connected to these parts.

### `Workspace:GetNumAwakeParts() -> int`
- **Summary:** Returns the number of `Class.BasePart|BaseParts` that are deemed physically active, due to being recently under the influence of physics.

### `Workspace:GetPhysicsThrottling() -> int`
- **Summary:** Returns an integer, between 0 and 100, representing the percentage of real time that physics simulation is currently being throttled to.

### `Workspace:GetRealPhysicsFPS() -> double`
- **Summary:** Returns the number of frames per second that physics is currently being simulated at.

### `Workspace:GetServerTimeNow() -> double`
- **Summary:** Returns the server's Unix time in seconds.

### `Workspace:JoinToOutsiders(objects: Instances, jointType: JointCreationMode) -> ()`
- **Summary:** Creates joints between the specified `Class.BasePart|Parts` and any touching parts depending on the parts' surfaces and the specified joint creation mode.

### `Workspace:MakeJoints(objects: Instances) -> ()`
- **Tags:** Deprecated
- **Summary:** Goes through all `Class.BasePart|BaseParts` given. If any part's side has a `Enum.SurfaceType` that can make a joint it will create a joint with any adjacent parts.

### `Workspace:PGSIsEnabled() -> boolean`
- **Summary:** Returns `true` if the game has the PGS Physics solver enabled.

### `Workspace:UnjoinFromOutsiders(objects: Instances) -> ()`
- **Summary:** Breaks all joints between the specified `Class.BasePart|BaseParts` and other `Class.BasePart|BaseParts`.

### `Workspace:ZoomToExtents() -> ()`
- **Summary:** Positions and zooms the `Class.Workspace.CurrentCamera` to show the extent of `Class.BasePart|BaseParts` currently in the `Class.Workspace`.

## Events
### `Workspace.PersistentLoaded(player: [Player](Player.md))`
- **Summary:** Fires when persistent models have been sent to the specified player.
