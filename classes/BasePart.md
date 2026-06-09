# BasePart

**Superclass:** [PVInstance](PVInstance.md)

The `BasePart` class is the base class for objects that physically interact, and it defines the common behavior for these interactions.

## Tags
- NotCreatable
- NotBrowsable

## Properties
### `BasePart.Anchored`
- **Type:** `boolean`
- **Summary:** Determines whether a part is immovable by physics.

### `BasePart.AssemblyAngularVelocity`
- **Type:** `Vector3`
- **Tags:** NotReplicated
- **Summary:** The angular velocity of the part's assembly.

### `BasePart.AssemblyCenterOfMass`
- **Type:** `Vector3`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The center of mass of the part's assembly in world space.

### `BasePart.AssemblyLinearVelocity`
- **Type:** `Vector3`
- **Tags:** NotReplicated
- **Summary:** The linear velocity of the part's assembly.

### `BasePart.AssemblyMass`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The total mass of the part's assembly.

### `BasePart.AssemblyRootPart`
- **Type:** `[BasePart](BasePart.md)`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A reference to the root part of the assembly.

### `BasePart.AudioCanCollide`
- **Type:** `boolean`
- **Summary:** Determines whether the part will physically interact with audio simulation, similar to `Class.BasePart.CastShadow|CastShadow` for lighting.

### `BasePart.BackParamA`
- **Type:** `float`
- **Tags:** Hidden, Deprecated
- **Summary:** Determines the first parameter for the SurfaceType on the Back face of a part.

### `BasePart.BackParamB`
- **Type:** `float`
- **Tags:** Hidden, Deprecated
- **Summary:** Determines the second parameter for the SurfaceType on the Back face of a part.

### `BasePart.BackSurface`
- **Type:** `SurfaceType`
- **Summary:** Determines the type of surface for the back face of a part.

### `BasePart.BackSurfaceInput`
- **Type:** `InputType`
- **Tags:** Hidden, Deprecated
- **Summary:** Determines the kind of input for the Back face of a part.

### `BasePart.BottomParamA`
- **Type:** `float`
- **Tags:** Hidden, Deprecated
- **Summary:** Determines the first parameter for the SurfaceType on the Bottom face of a part.

### `BasePart.BottomParamB`
- **Type:** `float`
- **Tags:** Hidden, Deprecated
- **Summary:** Determines the second parameter for the SurfaceType on the Bottom face of a part.

### `BasePart.BottomSurface`
- **Type:** `SurfaceType`
- **Summary:** Determines the type of surface for the bottom face of a part.

### `BasePart.BottomSurfaceInput`
- **Type:** `InputType`
- **Tags:** Hidden, Deprecated
- **Summary:** Determines the kind of input for the Bottom face of a part.

### `BasePart.BrickColor`
- **Type:** `BrickColor`
- **Tags:** NotReplicated
- **Summary:** Determines the color of a part.

### `BasePart.brickColor`
- **Type:** `BrickColor`
- **Tags:** NotReplicated, Deprecated

### `BasePart.CanCollide`
- **Type:** `boolean`
- **Summary:** Determines whether a part may collide with other parts.

### `BasePart.CanQuery`
- **Type:** `boolean`
- **Summary:** Determines whether the part is considered during spatial query operations.

### `BasePart.CanTouch`
- **Type:** `boolean`
- **Summary:** Determines if `Class.BasePart.Touched|Touched` and `Class.BasePart.TouchEnded|TouchEnded` events fire on the part.

### `BasePart.CastShadow`
- **Type:** `boolean`
- **Summary:** Determines whether or not a part casts a shadow.

### `BasePart.CenterOfMass`
- **Type:** `Vector3`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Describes the world position in which a part's center of mass is located.

### `BasePart.CFrame`
- **Type:** `CFrame`
- **Summary:** Determines the position and orientation of the `Class.BasePart` in the world.

### `BasePart.CollisionGroup`
- **Type:** `string`
- **Tags:** NotReplicated
- **Summary:** Describes the name of a part's collision group.

### `BasePart.CollisionGroupId`
- **Type:** `int`
- **Tags:** NotReplicated, Deprecated
- **Summary:** Describes the automatically set ID number of a part's collision group.

### `BasePart.Color`
- **Type:** `Color3`
- **Tags:** NotReplicated
- **Summary:** Determines the color of a part.

### `BasePart.CurrentPhysicalProperties`
- **Type:** `PhysicalProperties`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Indicates the current physical properties of the part.

### `BasePart.CustomPhysicalProperties`
- **Type:** `PhysicalProperties`
- **Summary:** Determines several physical properties of a part.

### `BasePart.Elasticity`
- **Type:** `float`
- **Tags:** Hidden, NotReplicated, Deprecated
- **Summary:** Used to control the Elasticity of the part, but it no longer does anything.

### `BasePart.EnableFluidForces`
- **Type:** `boolean`
- **Summary:** Used to enable or disable aerodynamic forces on parts and assemblies.

### `BasePart.ExtentsCFrame`
- **Type:** `CFrame`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The `Datatype.CFrame` of the physical extents of the `Class.BasePart`.

### `BasePart.ExtentsSize`
- **Type:** `Vector3`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The actual physical size of the `Class.BasePart` as regarded by the physics engine.

### `BasePart.Friction`
- **Type:** `float`
- **Tags:** Hidden, NotReplicated, Deprecated
- **Summary:** Used to control the Friction of the part, but now it no longer does anything.

### `BasePart.FrontParamA`
- **Type:** `float`
- **Tags:** Hidden, Deprecated
- **Summary:** Determines the first parameter for the SurfaceType on the Front face of a part.

### `BasePart.FrontParamB`
- **Type:** `float`
- **Tags:** Hidden, Deprecated
- **Summary:** Determines the second parameter for the SurfaceType on the Front face of a part.

### `BasePart.FrontSurface`
- **Type:** `SurfaceType`
- **Summary:** Determines the type of surface for the front face of a part.

### `BasePart.FrontSurfaceInput`
- **Type:** `InputType`
- **Tags:** Hidden, Deprecated
- **Summary:** Determines the kind of input for the Front face of a part (-Z direction).

### `BasePart.LeftParamA`
- **Type:** `float`
- **Tags:** Hidden, Deprecated
- **Summary:** Determines the first parameter for the SurfaceType on the Left face of a part.

### `BasePart.LeftParamB`
- **Type:** `float`
- **Tags:** Hidden, Deprecated
- **Summary:** Determines the second parameter for the SurfaceType on the Left face of a part.

### `BasePart.LeftSurface`
- **Type:** `SurfaceType`
- **Summary:** Determines the type of surface for the left face of a part.

### `BasePart.LeftSurfaceInput`
- **Type:** `InputType`
- **Tags:** Hidden, Deprecated
- **Summary:** Determines the kind of input for the Left face of a part.

### `BasePart.LocalTransparencyModifier`
- **Type:** `float`
- **Tags:** Hidden, NotReplicated
- **Summary:** Determines a multiplier for `Class.BasePart.Transparency` that is only visible to the local client.

### `BasePart.Locked`
- **Type:** `boolean`
- **Summary:** Determines whether a part is selectable in Studio.

### `BasePart.Mass`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Describes the mass of the part, the product of its density and volume.

### `BasePart.Massless`
- **Type:** `boolean`
- **Summary:** Determines whether the part contributes to the total mass or inertia of its rigid body.

### `BasePart.Material`
- **Type:** `Material`
- **Summary:** Determines the texture and default physical properties of a part.

### `BasePart.MaterialVariant`
- **Type:** `string`
- **Tags:** NotReplicated
- **Summary:** The name of `Class.MaterialVariant`.

### `BasePart.Orientation`
- **Type:** `Vector3`
- **Tags:** Hidden, NotReplicated
- **Summary:** Describes the rotation of the part in the world.

### `BasePart.PivotOffset`
- **Type:** `CFrame`
- **Summary:** Specifies the offset of the part's pivot from its `Datatype.CFrame`.

### `BasePart.Position`
- **Type:** `Vector3`
- **Tags:** Hidden, NotReplicated
- **Summary:** Describes the position of the part in the world.

### `BasePart.ReceiveAge`
- **Type:** `float`
- **Tags:** Hidden, ReadOnly, NotReplicated
- **Summary:** Time since last recorded physics update.

### `BasePart.Reflectance`
- **Type:** `float`
- **Summary:** Determines how much a part reflects the skybox.

### `BasePart.ResizeableFaces`
- **Type:** `Faces`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Describes the faces on which a part may be resized.

### `BasePart.ResizeIncrement`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Describes the smallest change in size allowable by the `Class.BasePart:Resize()|Resize()` method.

### `BasePart.RightParamA`
- **Type:** `float`
- **Tags:** Hidden, Deprecated
- **Summary:** Determines the first parameter for the SurfaceType on the Right face of a part.

### `BasePart.RightParamB`
- **Type:** `float`
- **Tags:** Hidden, Deprecated
- **Summary:** Determines the second parameter for the SurfaceType on the Right face of a part.

### `BasePart.RightSurface`
- **Type:** `SurfaceType`
- **Summary:** Determines the type of surface for the right face of a part.

### `BasePart.RightSurfaceInput`
- **Type:** `InputType`
- **Tags:** Hidden, Deprecated
- **Summary:** Determines the kind of input for the Right face of a part (-X direction).

### `BasePart.RootPriority`
- **Type:** `int`
- **Summary:** The main rule in determining the root part of an assembly.

### `BasePart.Rotation`
- **Type:** `Vector3`
- **Tags:** NotReplicated
- **Summary:** The rotation of the part in degrees for the three axes.

### `BasePart.RotVelocity`
- **Type:** `Vector3`
- **Tags:** Hidden, Deprecated
- **Summary:** Determines a part's change in orientation over time.

### `BasePart.Size`
- **Type:** `Vector3`
- **Tags:** NotReplicated
- **Summary:** Determines the dimensions of a part (length, width, height).

### `BasePart.SpecificGravity`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated, Deprecated
- **Summary:** The ratio of the part's density to the density of water determined by the `Class.BasePart.Material`.

### `BasePart.TopParamA`
- **Type:** `float`
- **Tags:** Hidden, Deprecated
- **Summary:** Determines the first parameter for the SurfaceType on the Top face of a part.

### `BasePart.TopParamB`
- **Type:** `float`
- **Tags:** Hidden, Deprecated
- **Summary:** Determines the second parameter for the SurfaceType on the Top face of a part.

### `BasePart.TopSurface`
- **Type:** `SurfaceType`
- **Summary:** Determines the type of surface for the top face of a part.

### `BasePart.TopSurfaceInput`
- **Type:** `InputType`
- **Tags:** Hidden, Deprecated
- **Summary:** Determines the kind of input for the Top face of a part (+Y direction).

### `BasePart.Transparency`
- **Type:** `float`
- **Summary:** Determines how much a part can be seen through (the inverse of part opacity).

### `BasePart.Velocity`
- **Type:** `Vector3`
- **Tags:** Hidden, Deprecated
- **Summary:** Determines a part's change in position over time.

## Methods
### `BasePart:AngularAccelerationToTorque(angAcceleration: Vector3, angVelocity: Vector3) -> Vector3`
- **Summary:** Returns the torque needed to achieve a given angular acceleration on this part's assembly, optionally accounting for gyroscopic effects.

### `BasePart:ApplyAngularImpulse(impulse: Vector3) -> ()`
- **Summary:** Apply an angular impulse to the assembly.

### `BasePart:ApplyImpulse(impulse: Vector3) -> ()`
- **Summary:** Apply an impulse to the assembly at the assembly's `Class.BasePart.AssemblyCenterOfMass|center of mass`.

### `BasePart:ApplyImpulseAtPosition(impulse: Vector3, position: Vector3) -> ()`
- **Summary:** Apply an impulse to the assembly at specified position.

### `BasePart:BreakJoints() -> ()`
- **Tags:** Deprecated
- **Summary:** Breaks any surface connection with any adjacent part, including `Class.Weld` and other `Class.JointInstance`.

### `BasePart:breakJoints() -> ()`
- **Tags:** Deprecated

### `BasePart:CanCollideWith(part: [BasePart](BasePart.md)) -> boolean`
- **Summary:** Returns whether the parts can collide with each other.

### `BasePart:CanSetNetworkOwnership() -> Tuple`
- **Summary:** Checks whether you can set a part's network ownership.

### `BasePart:GetClosestPointOnSurface(position: Vector3) -> Vector3`
- **Summary:** Returns the closest point on the part's surface to the given point.

### `BasePart:GetConnectedParts(recursive: boolean) -> List<[BasePart](BasePart.md)>`
- **Summary:** Returns a table of parts connected to the object by any kind of rigid joint.

### `BasePart:GetJoints() -> Instances`
- **Summary:** Return all Joints or Constraints that is connected to this Part.

### `BasePart:GetMass() -> float`
- **Summary:** Returns the value of the `Class.BasePart.Mass|Mass` property.

### `BasePart:getMass() -> float`
- **Tags:** Deprecated

### `BasePart:GetNetworkOwner() -> [Instance](Instance.md)`
- **Summary:** Returns the current player who is the network owner of this part, or `nil` in case of the server.

### `BasePart:GetNetworkOwnershipAuto() -> boolean`
- **Summary:** Returns true if the game engine automatically decides the network owner for this part.

### `BasePart:GetNoCollisionConstraints() -> Instances`

### `BasePart:GetRenderCFrame() -> CFrame`
- **Tags:** Deprecated
- **Summary:** OBSOLETE. Returns a CFrame describing where the part is being rendered at.

### `BasePart:GetRootPart() -> [Instance](Instance.md)`
- **Tags:** Deprecated
- **Summary:** Returns the base part of an assembly of parts.

### `BasePart:GetTouchingParts() -> Instances`
- **Summary:** Returns a table of all `Class.BasePart.CanCollide` true parts that intersect with this part.

### `BasePart:GetVelocityAtPosition(position: Vector3) -> Vector3`
- **Summary:** Returns the linear velocity of the part's assembly at the given position relative to this part.

### `BasePart:IntersectAsync(parts: Instances, collisionfidelity: CollisionFidelity, renderFidelity: RenderFidelity) -> [Instance](Instance.md)`
- **Tags:** Yields
- **Summary:** Note: It is highly recommended to use the newer `Class.GeometryService:IntersectAsync` instead of this function. As well as having better performance and more features, the new function differs as follows: - The output is an array of instances rather than a single instance. - The input parts do not need to be parented to the scene, allowing for background operations. - When the `SplitApart` option is set to `true` (default), each distinct body will be returned in its own `Class.PartOperation`. - All the returned parts are in the coordinate space of the main part, so their `Class.PVInstance.Origin` positions are the same as the main part's. This keeps the vertices of the mesh in the same position relative to the object as before the operation, but it does also mean the `(0, 0, 0)` of a returned part is not necessarily at the center of its body. Creates a new `Class.IntersectOperation` from the overlapping geometry of the part and the other parts in the given array.

### `BasePart:IsGrounded() -> boolean`
- **Summary:** Returns true if the object is connected to a part that will hold it in place (eg an `Class.BasePart.Anchored|Anchored` part), otherwise returns false.

### `BasePart:MakeJoints() -> ()`
- **Tags:** Deprecated
- **Summary:** Creates a joint on any side of the object that has a surface ID that can make a joint.

### `BasePart:makeJoints() -> ()`
- **Tags:** Deprecated

### `BasePart:Resize(normalId: NormalId, deltaAmount: int) -> boolean`
- **Summary:** Changes the size of an object just like using the Studio resize tool.

### `BasePart:resize(normalId: NormalId, deltaAmount: int) -> boolean`
- **Tags:** Deprecated

### `BasePart:SetNetworkOwner(playerInstance: [Player](Player.md)) -> ()`
- **Summary:** Sets the given player as network owner for this and all connected parts.

### `BasePart:SetNetworkOwnershipAuto() -> ()`
- **Summary:** Lets the game engine dynamically decide who will handle the part's physics (one of the clients or the server).

### `BasePart:SubtractAsync(parts: Instances, collisionfidelity: CollisionFidelity, renderFidelity: RenderFidelity) -> [Instance](Instance.md)`
- **Tags:** Yields
- **Summary:** Note: It is highly recommended to use the newer `Class.GeometryService:UnionAsync` instead of this function. As well as having better performance and more features, the new function differs as follows: - The output is an array of instances rather than a single instance. - The input parts do not need to be parented to the scene, allowing for background operations. - When the `SplitApart` option is set to `true` (default), each distinct body will be returned in its own `Class.PartOperation`. - All the returned parts are in the coordinate space of the main part, so their `Class.PVInstance.Origin` positions are the same as the main part's. This keeps the vertices of the mesh in the same position relative to the object as before the operation, but it does also mean the `(0, 0, 0)` of a returned part is not necessarily at the center of its body. Creates a new `Class.UnionOperation` from the part, minus the geometry occupied by the parts in the given array.

### `BasePart:TorqueToAngularAcceleration(torque: Vector3, angVelocity: Vector3) -> Vector3`
- **Summary:** Returns the angular acceleration that would result from applying a given torque to this part's assembly, optionally accounting for gyroscopic effects.

### `BasePart:UnionAsync(parts: Instances, collisionfidelity: CollisionFidelity, renderFidelity: RenderFidelity) -> [Instance](Instance.md)`
- **Tags:** Yields
- **Summary:** Note: It is highly recommended to use the newer `Class.GeometryService:UnionAsync` instead of this function. As well as having better performance and more features, the new function differs as follows: - The output is an array of instances rather than a single instance. - The input parts do not need to be parented to the scene, allowing for background operations. - When the `SplitApart` option is set to `true` (default), each distinct body will be returned in its own `Class.PartOperation`. - All the returned parts are in the coordinate space of the main part, so their `Class.PVInstance.Origin` positions are the same as the main part's. This keeps the vertices of the mesh in the same position relative to the object as before the operation, but it does also mean the `(0, 0, 0)` of a returned part is not necessarily at the center of its body. Creates a new `Class.UnionOperation` from the part, plus the geometry occupied by the parts in the given array.

## Events
### `BasePart.LocalSimulationTouched(part: [BasePart](BasePart.md))`
- **Tags:** Deprecated

### `BasePart.OutfitChanged()`
- **Tags:** Deprecated

### `BasePart.StoppedTouching(otherPart: [BasePart](BasePart.md))`
- **Tags:** Deprecated

### `BasePart.Touched(otherPart: [BasePart](BasePart.md))`
- **Summary:** Fires when a part touches another part as a result of physical movement.

### `BasePart.TouchEnded(otherPart: [BasePart](BasePart.md))`
- **Summary:** Fires when a part stops touching another part as a result of physical movement.
