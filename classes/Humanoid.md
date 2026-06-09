# Humanoid

**Superclass:** [Instance](Instance.md)

The Humanoid class provides methods for controlling character movement and interaction within Roblox experiences. It inherits from `Class.Model`, allowing it to be an assembly of `Class.BasePart` and `Class.Motor6D`.

## Properties
### `Humanoid.AutoJumpEnabled`
- **Type:** `boolean`
- **Summary:** Sets whether the character will automatically jump when they hit an obstacle as a player on a mobile device.

### `Humanoid.AutomaticScalingEnabled`
- **Type:** `boolean`
- **Summary:** When Enabled, AutomaticScalingEnabled causes the size of the character to change in response to the values in the humanoid's child scale values changing.

### `Humanoid.AutoRotate`
- **Type:** `boolean`
- **Summary:** AutoRotate sets whether or not the Humanoid will automatically rotate to face in the direction they are moving in.

### `Humanoid.BreakJointsOnDeath`
- **Type:** `boolean`
- **Summary:** Determines whether the humanoid's joints break when in the `Enum.HumanoidStateType.Dead` state.

### `Humanoid.CameraOffset`
- **Type:** `Vector3`
- **Summary:** An offset applied to the Camera's subject position when its CameraSubject is set to this Humanoid.

### `Humanoid.CollisionType`
- **Type:** `HumanoidCollisionType`
- **Tags:** Deprecated
- **Summary:** Selects the `Enum.HumanoidCollisionType` for R15 and Rthro non-player characters.

### `Humanoid.DisplayDistanceType`
- **Type:** `HumanoidDisplayDistanceType`
- **Summary:** Controls the distance behavior of the humanoid's name and health display.

### `Humanoid.DisplayName`
- **Type:** `string`
- **Summary:** Sets the text of a Humanoid, displayed above their head.

### `Humanoid.EvaluateStateMachine`
- **Type:** `boolean`
- **Summary:** Used to disable the internal physics and state machine of the Humanoid.

### `Humanoid.FloorMaterial`
- **Type:** `Material`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Describes the `Enum.Material` that the `Class.Humanoid` is currently standing on. If the `Class.Humanoid` isn't standing on anything, the value of this property will be _Air_.

### `Humanoid.Health`
- **Type:** `float`
- **Tags:** NotReplicated
- **Summary:** Describes the current health of the Humanoid on the range [0, `Class.Humanoid.MaxHealth`].

### `Humanoid.HealthDisplayDistance`
- **Type:** `float`
- **Summary:** Used in conjunction with the `Class.Humanoid.DisplayDistanceType|DisplayDistanceType` property to control the distance from which a humanoid's health bar can be seen.

### `Humanoid.HealthDisplayType`
- **Type:** `HumanoidHealthDisplayType`
- **Summary:** Controls when the humanoid's health bar is allowed to be displayed.

### `Humanoid.HipHeight`
- **Type:** `float`
- **Summary:** Determines the distance off the ground the `Class.Humanoid.RootPart` should be.

### `Humanoid.Jump`
- **Type:** `boolean`
- **Tags:** NotReplicated
- **Summary:** If `true`, the `Class.Humanoid` jumps with an upwards force.

### `Humanoid.JumpHeight`
- **Type:** `float`
- **Summary:** Provides control over the height that the `Class.Humanoid` jumps to.

### `Humanoid.JumpPower`
- **Type:** `float`
- **Summary:** Determines how much upwards force is applied to the `Class.Humanoid` when jumping.

### `Humanoid.LeftLeg`
- **Type:** `[BasePart](BasePart.md)`
- **Tags:** Hidden, NotReplicated, Deprecated
- **Summary:** A reference to the humanoid's _Left Leg_ part.

### `Humanoid.MaxHealth`
- **Type:** `float`
- **Summary:** The maximum value of a humanoid's `Class.Humanoid.Health|Health`.

### `Humanoid.maxHealth`
- **Type:** `float`
- **Tags:** NotReplicated, Deprecated

### `Humanoid.MaxSlopeAngle`
- **Type:** `float`
- **Summary:** The maximum slope angle that a humanoid can walk on without slipping.

### `Humanoid.MoveDirection`
- **Type:** `Vector3`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Describes the direction that the `Class.Humanoid` is walking in.

### `Humanoid.NameDisplayDistance`
- **Type:** `float`
- **Summary:** Used in conjunction with the `Class.Humanoid.DisplayDistanceType` property to control the distance from which a humanoid's name can be seen.

### `Humanoid.NameOcclusion`
- **Type:** `NameOcclusion`
- **Summary:** Controls whether a humanoid's name and health bar can be seen behind walls or other objects.

### `Humanoid.PlatformStand`
- **Type:** `boolean`
- **Summary:** Determines whether the `Class.Humanoid` is currently in the `Enum.HumanoidStateType.PlatformStanding` state.

### `Humanoid.RequiresNeck`
- **Type:** `boolean`
- **Summary:** Allows developers to disable the behavior where a player `Character|character` dies if the Neck `Class.Motor6D` is removed or disconnected even momentarily.

### `Humanoid.RightLeg`
- **Type:** `[BasePart](BasePart.md)`
- **Tags:** Hidden, NotReplicated, Deprecated
- **Summary:** A reference to the humanoid's _Right Leg_ part.

### `Humanoid.RigType`
- **Type:** `HumanoidRigType`
- **Summary:** Describes whether this `Class.Humanoid` is utilizing the legacy R6 character rig, or the new R15 character rig.

### `Humanoid.RootPart`
- **Type:** `[BasePart](BasePart.md)`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A reference to the humanoid's `HumanoidRootPart` object.

### `Humanoid.SeatPart`
- **Type:** `[BasePart](BasePart.md)`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A reference to the seat that a `Class.Humanoid` is currently sitting in, if any.

### `Humanoid.Sit`
- **Type:** `boolean`
- **Summary:** Describes whether the `Class.Humanoid` is currently sitting.

### `Humanoid.TargetPoint`
- **Type:** `Vector3`
- **Summary:** Describes the 3D position where the `Class.Player` controlling the `Class.Humanoid` last clicked in the world while using a `Class.Tool`.

### `Humanoid.Torso`
- **Type:** `[BasePart](BasePart.md)`
- **Tags:** Hidden, NotReplicated, Deprecated
- **Summary:** A reference to a humanoid's root driving part.

### `Humanoid.UseJumpPower`
- **Type:** `boolean`
- **Summary:** Determines whether the `Class.Humanoid.JumpHeight|JumpHeight` (false) or `Class.Humanoid.JumpPower` (true) property is used.

### `Humanoid.WalkSpeed`
- **Type:** `float`
- **Summary:** Describes the humanoid's maximum movement speed in studs per second.

### `Humanoid.WalkToPart`
- **Type:** `[BasePart](BasePart.md)`
- **Summary:** A reference to a part whose position is trying to be reached by a humanoid.

### `Humanoid.WalkToPoint`
- **Type:** `Vector3`
- **Summary:** The position that a humanoid is trying to reach, after a call to `Class.Humanoid:MoveTo()` is made.

## Methods
### `Humanoid:AddAccessory(accessory: [Instance](Instance.md)) -> ()`
- **Summary:** Attaches the specified `Class.Accessory` to the humanoid's parent.

### `Humanoid:AddCustomStatus(status: string) -> boolean`
- **Tags:** Deprecated
- **Summary:** Adds a custom status to the Humanoid.

### `Humanoid:AddStatus(status: [Status](Status.md)) -> boolean`
- **Tags:** Deprecated
- **Summary:** Adds a BoolValue to the Humanoid's _Status_ object.

### `Humanoid:ApplyDescription(humanoidDescription: [HumanoidDescription](HumanoidDescription.md), assetTypeVerification: AssetTypeVerification) -> ()`
- **Tags:** Yields, Deprecated
- **Summary:** Makes the character's look match that of the passed in `Class.HumanoidDescription`.

### `Humanoid:ApplyDescriptionAsync(humanoidDescription: [HumanoidDescription](HumanoidDescription.md), assetTypeVerification: AssetTypeVerification) -> ()`
- **Tags:** Yields
- **Summary:** Makes the character's look match that of the passed in `Class.HumanoidDescription`. If `HumanoidDescription.UseAvatarSettings` is true, the Avatar Settings for the experience will also be applied to the character.

### `Humanoid:ApplyDescriptionReset(humanoidDescription: [HumanoidDescription](HumanoidDescription.md), assetTypeVerification: AssetTypeVerification) -> ()`
- **Tags:** Yields, Deprecated
- **Summary:** Makes the character's look match that of the passed in `Class.HumanoidDescription`, even after external changes.

### `Humanoid:ApplyDescriptionResetAsync(humanoidDescription: [HumanoidDescription](HumanoidDescription.md), assetTypeVerification: AssetTypeVerification) -> ()`
- **Tags:** Yields
- **Summary:** Makes the character's look match that of the passed in `Class.HumanoidDescription`, even after external changes.

### `Humanoid:BuildRigFromAttachments() -> ()`
- **Summary:** Assembles a tree of `Class.Motor6D` joints by attaching together `Class.Attachment` objects in a humanoid's character.

### `Humanoid:ChangeState(state: HumanoidStateType) -> ()`
- **Summary:** Sets the `Class.Humanoid` to enter the given `Enum.HumanoidStateType`.

### `Humanoid:EquipTool(tool: [Instance](Instance.md)) -> ()`
- **Summary:** Makes the `Class.Humanoid` equip the given `Class.Tool`.

### `Humanoid:GetAccessories() -> Array`
- **Summary:** Returns an array of `Class.Accessory` objects that the humanoid's parent is currently wearing.

### `Humanoid:GetAppliedDescription() -> [HumanoidDescription](HumanoidDescription.md)`
- **Summary:** Returns a copy of the humanoid's cached `Class.HumanoidDescription` which describes its current look.

### `Humanoid:GetBodyPartR15(part: [Instance](Instance.md)) -> BodyPartR15`
- **Summary:** Pass a body part to this method (the body part should be a sibling of Humanoid, and a child of a Model) to get the `Enum.BodyPartR15` of the `Class.Part`.

### `Humanoid:GetLimb(part: [Instance](Instance.md)) -> Limb`
- **Summary:** Returns the `Enum.Limb` enum that is associated with the given `Class.Part`.

### `Humanoid:GetMoveVelocity() -> Vector3`

### `Humanoid:GetPlayingAnimationTracks() -> Array`
- **Tags:** Deprecated
- **Summary:** Returns an array of all `Class.AnimationTrack|AnimationTracks` that are currently being played on the `Class.Humanoid`.

### `Humanoid:GetRelativeVelocityAtFloor() -> Vector3`
- **Summary:** Returns the humanoid's actual physical velocity relative to the surface it is standing on as a `Datatype.Vector3` in world-space orientation.

### `Humanoid:GetState() -> HumanoidStateType`
- **Summary:** Returns the humanoid's current `Enum.HumanoidStateType`.

### `Humanoid:GetStateEnabled(state: HumanoidStateType) -> boolean`
- **Summary:** Returns whether a `Enum.HumanoidStateType` is enabled for the `Class.Humanoid`.

### `Humanoid:GetStatuses() -> Array`
- **Tags:** Deprecated
- **Summary:** Returns a table of the Humanoid's statuses, and custom statuses.

### `Humanoid:HasCustomStatus(status: string) -> boolean`
- **Tags:** Deprecated
- **Summary:** Returns boolean based on if custom statuses exist.

### `Humanoid:HasStatus(status: [Status](Status.md)) -> boolean`
- **Tags:** Deprecated
- **Summary:** Returns a boolean based on if a status exists.

### `Humanoid:LoadAnimation(animation: [Animation](Animation.md)) -> [AnimationTrack](AnimationTrack.md)`
- **Tags:** Deprecated
- **Summary:** Loads an `Class.Animation` onto a `Class.Humanoid`, returning an `Class.AnimationTrack` that can be used for playback.

### `Humanoid:loadAnimation(animation: [Animation](Animation.md)) -> [AnimationTrack](AnimationTrack.md)`
- **Tags:** Deprecated

### `Humanoid:Move(moveDirection: Vector3, relativeToCamera: boolean) -> ()`
- **Summary:** Causes the `Class.Humanoid` to walk in the given direction.

### `Humanoid:MoveTo(location: Vector3, part: [Instance](Instance.md)) -> ()`
- **Summary:** Causes the `Class.Humanoid` to attempt to walk to the given location by setting the `Class.Humanoid.WalkToPoint` and `Class.Humanoid.WalkToPart` properties.

### `Humanoid:PlayEmote(emoteName: string) -> boolean`
- **Tags:** Yields, Deprecated
- **Summary:** Plays emotes and returns if was successfully ran.

### `Humanoid:PlayEmoteAsync(emoteName: string) -> boolean`
- **Tags:** Yields
- **Summary:** Plays emotes and returns if was successfully ran.

### `Humanoid:RemoveAccessories() -> ()`
- **Summary:** Removes all `Class.Accessory` objects worn by the humanoid's parent.

### `Humanoid:RemoveCustomStatus(status: string) -> boolean`
- **Tags:** Deprecated
- **Summary:** Removes the defined custom status from the Status model in the Humanoid..

### `Humanoid:RemoveStatus(status: [Status](Status.md)) -> boolean`
- **Tags:** Deprecated
- **Summary:** Removes the defined status from the Status model in the Humanoid.

### `Humanoid:ReplaceBodyPartR15(bodyPart: BodyPartR15, part: [BasePart](BasePart.md)) -> boolean`
- **Summary:** Dynamically replaces a Humanoid body part with a different part.

### `Humanoid:SetStateEnabled(state: HumanoidStateType, enabled: boolean) -> ()`
- **Summary:** Sets whether a given `Enum.HumanoidStateType` is enabled for the `Class.Humanoid`.

### `Humanoid:TakeDamage(amount: float) -> ()`
- **Summary:** Lowers the `Class.Humanoid.Health` of the `Class.Humanoid` by the given _amount_ if it is not protected by a `Class.ForceField`.

### `Humanoid:takeDamage(amount: float) -> ()`
- **Tags:** Deprecated

### `Humanoid:UnequipTools() -> ()`
- **Summary:** Unequips any `Class.Tool` currently equipped by the `Class.Humanoid`.

## Events
### `Humanoid.AnimationPlayed(animationTrack: [AnimationTrack](AnimationTrack.md))`
- **Tags:** Deprecated
- **Summary:** Fires when an `Class.AnimationTrack` begins playing on the `Class.Humanoid`.

### `Humanoid.ApplyDescriptionFinished(description: [HumanoidDescription](HumanoidDescription.md))`

### `Humanoid.Climbing(speed: float)`
- **Summary:** Fires when the speed at which a `Class.Humanoid` is climbing changes.

### `Humanoid.CustomStatusAdded(status: string)`
- **Tags:** Deprecated
- **Summary:** Fired when a status is added to the Humanoid.

### `Humanoid.CustomStatusRemoved(status: string)`
- **Tags:** Deprecated
- **Summary:** Fired when a status is removed from the Humanoid.

### `Humanoid.Died()`
- **Summary:** Fires when the `Class.Humanoid` dies.

### `Humanoid.FallingDown(active: boolean)`
- **Summary:** Fires when the `Class.Humanoid` enters or leaves the `FallingDown` `Enum.HumanoidStateType`.

### `Humanoid.FreeFalling(active: boolean)`
- **Summary:** Fires when the `Class.Humanoid` enters or leaves the `Freefall` `Enum.HumanoidStateType`.

### `Humanoid.GettingUp(active: boolean)`
- **Summary:** Fires when the `Class.Humanoid` enters or leaves the `GettingUp` `Enum.HumanoidStateType`.

### `Humanoid.HealthChanged(health: float)`
- **Summary:** Fires when the `Class.Humanoid.Health` changes (or when the `Class.Humanoid.MaxHealth` is set).

### `Humanoid.Jumping(active: boolean)`
- **Summary:** Fires when the `Class.Humanoid` enters and leaves the `Jumping` `Enum.HumanoidStateType`.

### `Humanoid.MoveToFinished(reached: boolean)`
- **Summary:** Fires when the `Class.Humanoid` finishes walking to a goal declared by `Class.Humanoid:MoveTo()`.

### `Humanoid.PlatformStanding(active: boolean)`
- **Summary:** Fires when the `Class.Humanoid` enters or leaves the `PlatformStanding` `Enum.HumanoidStateType`.

### `Humanoid.Ragdoll(active: boolean)`
- **Summary:** Fires when the `Class.Humanoid` enters or leaves the `Ragdoll` `Enum.HumanoidStateType`.

### `Humanoid.Running(speed: float)`
- **Summary:** Fires when the speed at which a `Class.Humanoid` is running changes.

### `Humanoid.Seated(active: boolean, currentSeatPart: [BasePart](BasePart.md))`
- **Summary:** Fired when a `Class.Humanoid` either sits in a `Class.Seat` or `Class.VehicleSeat` or gets up.

### `Humanoid.StateChanged(old: HumanoidStateType, new: HumanoidStateType)`
- **Summary:** Fires when the state of the `Class.Humanoid` is changed.

### `Humanoid.StateEnabledChanged(state: HumanoidStateType, isEnabled: boolean)`
- **Summary:** Fires when `Class.Humanoid:SetStateEnabled()` is called on the `Class.Humanoid`.

### `Humanoid.StatusAdded(status: [Status](Status.md))`
- **Tags:** Deprecated
- **Summary:** Fired when a status is added to the Humanoid.

### `Humanoid.StatusRemoved(status: [Status](Status.md))`
- **Tags:** Deprecated
- **Summary:** Fired when a status is removed from the Humanoid.

### `Humanoid.Strafing(active: boolean)`
- **Summary:** Fires when the `Class.Humanoid` enters or leaves the `StrafingNoPhysics` `Enum.HumanoidStateType`.

### `Humanoid.Swimming(speed: float)`
- **Summary:** Fires when the speed at which a `Class.Humanoid` is swimming in `Class.Terrain` water changes.

### `Humanoid.Touched(touchingPart: [BasePart](BasePart.md), humanoidPart: [BasePart](BasePart.md))`
- **Summary:** Fires when one of the humanoid's limbs come in contact with another `Class.BasePart`.
