# StarterPlayer

**Superclass:** [Instance](Instance.md)

The `StarterPlayer` class is a service that allows setting defaults for properties in the `Class.Player` object, enabling custom animations and character behavior.

## Tags
- NotCreatable
- Service

## Properties
### `StarterPlayer.AllowCustomAnimations`
- **Type:** `boolean`
- **Tags:** Hidden
- **Summary:** Describes the current game's permission levels regarding custom avatar animations from the website.

### `StarterPlayer.AutoJumpEnabled`
- **Type:** `boolean`
- **Summary:** Sets whether the character will automatically jump when hitting an obstacle on a mobile device.

### `StarterPlayer.AvatarJointUpgrade`
- **Type:** `RolloutState`
- **Tags:** NotReplicated
- **Summary:** Controls whether avatars spawn with `Class.AnimationConstraint` joints for physical simulation.

### `StarterPlayer.CameraMaxZoomDistance`
- **Type:** `float`
- **Summary:** The maximum distance the player's default camera is allowed to zoom out in studs.

### `StarterPlayer.CameraMinZoomDistance`
- **Type:** `float`
- **Summary:** The minimum distance in studs the player's default camera is allowed to zoom in.

### `StarterPlayer.CameraMode`
- **Type:** `CameraMode`
- **Summary:** Changes the default camera's mode to either first or third person.

### `StarterPlayer.CharacterBreakJointsOnDeath`
- **Type:** `boolean`
- **Summary:** Determines the starting value of `Class.Humanoid.BreakJointsOnDeath` for `Class.Player.Character`.

### `StarterPlayer.CharacterJumpHeight`
- **Type:** `float`
- **Summary:** Determines the starting value of `Class.Humanoid.JumpHeight` for `Class.Player.Character`.

### `StarterPlayer.CharacterJumpPower`
- **Type:** `float`
- **Summary:** Determines the starting value of `Class.Humanoid.JumpPower` for `Class.Player.Character`.

### `StarterPlayer.CharacterMaxSlopeAngle`
- **Type:** `float`
- **Summary:** Determines the starting value of `Class.Humanoid.MaxSlopeAngle` for `Class.Player.Character`.

### `StarterPlayer.CharacterUseJumpPower`
- **Type:** `boolean`
- **Summary:** Determines the starting state of `Class.Humanoid.UseJumpPower` for `Class.Player.Character`.

### `StarterPlayer.CharacterWalkSpeed`
- **Type:** `float`
- **Summary:** Determines the starting value of `Class.Humanoid.WalkSpeed` for `Class.Player.Character`.

### `StarterPlayer.ClassicDeath`
- **Type:** `boolean`

### `StarterPlayer.CreateDefaultPlayerModule`
- **Type:** `boolean`
- **Tags:** NotScriptable
- **Summary:** Controls how the default player module and related scripts are handled.

### `StarterPlayer.DevCameraOcclusionMode`
- **Type:** `DevCameraOcclusionMode`
- **Summary:** Sets how the default camera handles objects between the camera and the player.

### `StarterPlayer.DevComputerCameraMovementMode`
- **Type:** `DevComputerCameraMovementMode`
- **Summary:** Lets you overwrite the player's camera mode on a computer.

### `StarterPlayer.DevComputerMovementMode`
- **Type:** `DevComputerMovementMode`
- **Summary:** Lets you overwrite the player's movement mode on a computer.

### `StarterPlayer.DevTouchCameraMovementMode`
- **Type:** `DevTouchCameraMovementMode`
- **Summary:** Lets you overwrite the player's camera mode on a touch-enabled device.

### `StarterPlayer.DevTouchMovementMode`
- **Type:** `DevTouchMovementMode`
- **Summary:** Lets you overwrite the player's movement mode on a touch-enabled device.

### `StarterPlayer.EnableDynamicHeads`
- **Type:** `LoadDynamicHeads`
- **Tags:** NotScriptable
- **Summary:** Sets the use of dynamic heads. When true, enables the use of avatar heads with facial animation data.

### `StarterPlayer.EnableMouseLockOption`
- **Type:** `boolean`
- **Summary:** Determines if a player can toggle mouse lock by default.

### `StarterPlayer.HealthDisplayDistance`
- **Type:** `float`
- **Summary:** Sets the distance at which this player will see other `Class.Humanoid` health bars. If set to 0, the health bars will not be displayed.

### `StarterPlayer.LoadCharacterAppearance`
- **Type:** `boolean`
- **Summary:** Whether or not the appearance of a player's character should be loaded.

### `StarterPlayer.LoadCharacterLayeredClothing `
- **Type:** `LoadCharacterLayeredClothing`
- **Tags:** NotReplicated, NotScriptable
- **Summary:** Indicates whether characters spawning into an experience will have layered clothing accessories equipped on them.

### `StarterPlayer.LuaCharacterController`
- **Type:** `CharacterControlMode`

### `StarterPlayer.NameDisplayDistance`
- **Type:** `float`
- **Summary:** Sets the distance at which this player will see other `Class.Humanoid` names.

### `StarterPlayer.UserEmotesEnabled`
- **Type:** `boolean`
- **Summary:** Determines if user-owned emotes are loaded when loading avatars.
