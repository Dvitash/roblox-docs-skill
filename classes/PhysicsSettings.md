# PhysicsSettings

**Superclass:** [Instance](Instance.md)

The `PhysicsSettings` class is a singleton class in Roblox Studio settings that allows users to view debugging features in the physics engine. It is located under the `Physics` tab.

## Tags
- NotCreatable
- Service
- NotReplicated

## Properties
### `PhysicsSettings.AllowSleep`
- **Type:** `boolean`
- **Summary:** When set to true, physically simulated objects will stop being simulated if they have little to no motion for a set period of time.

### `PhysicsSettings.AreAnchorsShown`
- **Type:** `boolean`
- **Summary:** When set to true, parts that are `Class.BasePart.Anchored` will show a gray surface outline on the surface of the part's bounding box that is currently facing the ground.

### `PhysicsSettings.AreAssembliesShown`
- **Type:** `boolean`
- **Summary:** When set to true, each physics assembly is assigned a unique color and the `Class.Part` associated with the assembly are outlined with the color. Parts that are attached together by `Class.JointInstance` will share the same color.

### `PhysicsSettings.AreAssemblyCentersOfMassShown`
- **Type:** `boolean`

### `PhysicsSettings.AreAwakePartsHighlighted`
- **Type:** `boolean`
- **Summary:** When set to true, parts that are actively being physically simulated will have a red outline.

### `PhysicsSettings.AreBodyTypesShown`
- **Type:** `boolean`
- **Summary:** When set to true, `Class.Part` will be outlined with a specific color, depending on the state of its root simulation body.

### `PhysicsSettings.AreCollisionCostsShown`
- **Type:** `boolean`

### `PhysicsSettings.AreConstraintForcesShownForSelectedOrHoveredInstances`
- **Type:** `boolean`

### `PhysicsSettings.AreConstraintTorquesShownForSelectedOrHoveredInstances`
- **Type:** `boolean`

### `PhysicsSettings.AreContactForcesShownForSelectedOrHoveredAssemblies`
- **Type:** `boolean`

### `PhysicsSettings.AreContactIslandsShown`
- **Type:** `boolean`
- **Summary:** When set to true, each contact island will render `Class.SelectionBox` adorns on the parts in contact islands, where each contact island is assigned a random color.

### `PhysicsSettings.AreContactPointsShown`
- **Type:** `boolean`
- **Summary:** When set to true, sphere adorns will be drawn at the contact points of each part where physics interactions are occurring.

### `PhysicsSettings.AreGravityForcesShownForSelectedOrHoveredAssemblies`
- **Type:** `boolean`

### `PhysicsSettings.AreJointCoordinatesShown`
- **Type:** `boolean`
- **Summary:** When set to true, XYZ axes are rendered at the `Class.BasePart.CFrame` of every part.

### `PhysicsSettings.AreMagnitudesShownForDrawnForcesAndTorques`
- **Type:** `boolean`

### `PhysicsSettings.AreMechanismsShown`
- **Type:** `boolean`
- **Summary:** When set to true, every individual mechanism of parts is given a unique color.

### `PhysicsSettings.AreModelCoordsShown`
- **Type:** `boolean`
- **Summary:** An ancient property that hasn't work correctly since late 2007. It's supposed to render an XYZ axis on the root part of a `Class.Model`, but the axis rendering component doesn't work correctly.

### `PhysicsSettings.AreNonAnchorsShown`
- **Type:** `boolean`

### `PhysicsSettings.AreOwnersShown`
- **Type:** `boolean`
- **Summary:** When set to true, each player's character is outlined with a unique color, and each part that the player has network ownership over is outlined with the same color.

### `PhysicsSettings.ArePartCoordsShown`
- **Type:** `boolean`
- **Summary:** An ancient property that hasn't worked correctly since late 2007. It's supposed to render a large XYZ axis in the center of each `Class.BasePart`, but the axis rendering component doesn't work correctly.

### `PhysicsSettings.AreRegionsShown`
- **Type:** `boolean`
- **Summary:** When set to true, a cylinder is drawn around each player's character, representing their `Class.Player.SimulationRadius`.

### `PhysicsSettings.AreSolverIslandsShown`
- **Type:** `boolean`

### `PhysicsSettings.AreTerrainReplicationRegionsShown`
- **Type:** `boolean`

### `PhysicsSettings.AreTimestepsShown`
- **Type:** `boolean`

### `PhysicsSettings.AreUnalignedPartsShown`
- **Type:** `boolean`
- **Summary:** When set to true, parts that aren't aligned on the 1x1x1 grid will be outlined yellow.

### `PhysicsSettings.AreWorldCoordsShown`
- **Type:** `boolean`
- **Summary:** An ancient property that hasn't worked correctly since late 2007. It's supposed to render a large XYZ axis in the center of the world, but the axis rendering component doesn't work correctly.

### `PhysicsSettings.DisableCSGv2`
- **Type:** `boolean`
- **Summary:** When set to true, Roblox will fall back to using its legacy CSG solver when performing solid model operations.

### `PhysicsSettings.DisableCSGv3ForPlugins`
- **Type:** `boolean`

### `PhysicsSettings.DrawConstraintsNetForce`
- **Type:** `boolean`

### `PhysicsSettings.DrawContactsNetForce`
- **Type:** `boolean`

### `PhysicsSettings.DrawTotalNetForce`
- **Type:** `boolean`

### `PhysicsSettings.EnableForceVisualizationSmoothing`
- **Type:** `boolean`

### `PhysicsSettings.FluidForceDrawScale`
- **Type:** `float`
- **Summary:** Sets the scale of arrows drawn for aerodynamic force visualization.

### `PhysicsSettings.ForceCSGv2`
- **Type:** `boolean`
- **Tags:** Hidden, NotReplicated

### `PhysicsSettings.ForceDrawScale`
- **Type:** `float`

### `PhysicsSettings.ForceVisualizationSmoothingSteps`
- **Type:** `int`

### `PhysicsSettings.IsInterpolationThrottleShown`
- **Type:** `boolean`

### `PhysicsSettings.IsReceiveAgeShown`
- **Type:** `boolean`
- **Summary:** This property is supposed to show the `Class.BasePart.ReceiveAge` of a part, but it does not work correctly.

### `PhysicsSettings.IsTreeShown`
- **Type:** `boolean`
- **Summary:** When set to true, the joint connections of each part, and the states of their underlying primitive components are visualized as a spanning tree.

### `PhysicsSettings.PhysicsEnvironmentalThrottle`
- **Type:** `EnviromentalPhysicsThrottle`
- **Summary:** Controls the throttle rate of Roblox's physics engine.

### `PhysicsSettings.ShowDecompositionGeometry`
- **Type:** `boolean`
- **Summary:** When set to true, the underlying collision geometry for `Class.PartOperation` and `Class.MeshPart` is rendered.

### `PhysicsSettings.ShowFluidForcesForSelectedOrHoveredMechanisms`
- **Type:** `boolean`
- **Summary:** When set to true, enables aerodynamic visualization for selected or hovered mechanisms in Studio's play and run modes.

### `PhysicsSettings.ShowInstanceNamesForDrawnForcesAndTorques`
- **Type:** `boolean`

### `PhysicsSettings.SolverConvergenceMetricType`
- **Type:** `SolverConvergenceMetricType`

### `PhysicsSettings.SolverConvergenceVisualizationMode`
- **Type:** `SolverConvergenceVisualizationMode`

### `PhysicsSettings.ThrottleAdjustTime`
- **Type:** `double`
- **Summary:** If the `Class.PhysicsSettings.PhysicsEnvironmentalThrottle` is set to `DefaultAuto`, this specifies the maximum time that the physics environmental throttle has to wait before it is allowed to automatically change.

### `PhysicsSettings.TorqueDrawScale`
- **Type:** `float`

### `PhysicsSettings.UseCSGv2`
- **Type:** `boolean`
- **Summary:** If set to true, version 2 of Roblox's CSG solver will be used instead of version 1.
