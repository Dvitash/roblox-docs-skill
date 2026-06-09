# UserGameSettings

**Superclass:** [Instance](Instance.md)

The `UserGameSettings` class is a singleton class that holds persistent settings related to user-configurable camera and character controls. These settings reflect user-facing options in in-experience settings and contextual state, intended for client use only.

## Tags
- NotCreatable
- Service
- NotReplicated

## Properties
### `UserGameSettings.AllTutorialsDisabled`
- **Type:** `boolean`
- **Summary:** Indicates whether all in-experience tutorials have been disabled by the user.

### `UserGameSettings.BadgeVisible`
- **Type:** `boolean`
- **Summary:** Indicates whether badge notifications are visible to the client.

### `UserGameSettings.CameraMode`
- **Type:** `CustomCameraMode`
- **Summary:** The custom camera mode currently in-use by the client.

### `UserGameSettings.ChatVisible`
- **Type:** `boolean`
- **Summary:** Indicates whether the in-experience chat is visible to the client.

### `UserGameSettings.ComputerCameraMovementMode`
- **Type:** `ComputerCameraMovementMode`
- **Summary:** The camera movement mode currently in-use by the client on desktop.

### `UserGameSettings.ComputerMovementMode`
- **Type:** `ComputerMovementMode`
- **Summary:** The type of controls being used by the client on desktop.

### `UserGameSettings.ControlMode`
- **Type:** `ControlMode`
- **Summary:** Toggles whether or not the client can use the Mouse Lock Switch mode.

### `UserGameSettings.Fullscreen`
- **Type:** `boolean`
- **Summary:** Indicates whether the client's window is currently in full screen mode.

### `UserGameSettings.GamepadCameraSensitivity`
- **Type:** `float`
- **Summary:** Describes how sensitive the camera is when using a gamepad.

### `UserGameSettings.GraphicsOptimizationMode`
- **Type:** `GraphicsOptimizationMode`
- **Summary:** The graphics optimization mode used by the client to balance visual quality and performance.

### `UserGameSettings.GraphicsQualityLevel`
- **Type:** `int`
- **Summary:** The current graphics quality level being used by the client.

### `UserGameSettings.HasEverUsedVR`
- **Type:** `boolean`
- **Summary:** Indicates whether the user has ever launched the client in VR mode.

### `UserGameSettings.MasterVolume`
- **Type:** `float`
- **Summary:** A float between 0 and 1 representing the volume of the game's client.

### `UserGameSettings.MasterVolumeStudio`
- **Type:** `float`
- **Summary:** A float between 0 and 1 representing the master volume used in Roblox Studio.

### `UserGameSettings.MaxQualityEnabled`
- **Type:** `boolean`
- **Summary:** Indicates whether the client's graphics quality is set to the maximum available level.

### `UserGameSettings.MouseSensitivity`
- **Type:** `float`
- **Summary:** A float between 0 and 4 representing the sensitivity of the client's camera sensitivity.

### `UserGameSettings.OnboardingsCompleted`
- **Type:** `string`
- **Summary:** A comma-separated list of onboarding IDs that the user has completed.

### `UserGameSettings.PartyVoiceVolume`
- **Type:** `float`
- **Summary:** A float between 0 and 1 representing the volume of party voice chat.

### `UserGameSettings.PeoplePageLayout`
- **Type:** `PeoplePageLayout`
- **Summary:** The layout style used to display the people page in the in-experience menu.

### `UserGameSettings.PlayerListVisible`
- **Type:** `boolean`
- **Summary:** Indicates whether the in-experience player list is visible to the client.

### `UserGameSettings.PlayerNamesEnabled`
- **Type:** `boolean`
- **Summary:** Indicates whether player names are displayed above characters in the experience.

### `UserGameSettings.RCCProfilerRecordFrameRate`
- **Type:** `int`
- **Summary:** Internal MicroProfiler setting specifying the frame rate used when capturing server-side RCC profiler data.

### `UserGameSettings.RCCProfilerRecordTimeFrame`
- **Type:** `int`
- **Summary:** Internal MicroProfiler setting specifying the duration over which server-side RCC profiler data is captured.

### `UserGameSettings.RotationType`
- **Type:** `RotationType`
- **Summary:** Controls how the client's character is rotated.

### `UserGameSettings.SavedQualityLevel`
- **Type:** `SavedQualitySetting`
- **Summary:** The graphics quality level set by the client.

### `UserGameSettings.StartMaximized`
- **Type:** `boolean`
- **Tags:** NotReplicated, NotScriptable
- **Summary:** Indicates whether Roblox Studio should launch in a maximized window.

### `UserGameSettings.StartScreenPosition`
- **Type:** `Vector2`
- **Tags:** NotReplicated, NotScriptable
- **Summary:** The screen position of the client's window when the application launches.

### `UserGameSettings.StartScreenSize`
- **Type:** `Vector2`
- **Tags:** NotReplicated, NotScriptable
- **Summary:** The size of the client's window when the application launches.

### `UserGameSettings.TouchCameraMovementMode`
- **Type:** `TouchCameraMovementMode`
- **Summary:** The camera type in-use by the client while on a mobile device.

### `UserGameSettings.TouchMovementMode`
- **Type:** `TouchMovementMode`
- **Summary:** The type of controls being used by the client on a mobile device.

### `UserGameSettings.UsedCoreGuiIsVisibleToggle`
- **Type:** `boolean`
- **Summary:** Indicates whether the user has toggled the visibility of core GUI elements.

### `UserGameSettings.UsedCustomGuiIsVisibleToggle`
- **Type:** `boolean`
- **Summary:** Indicates whether the user has toggled the visibility of custom GUI elements.

### `UserGameSettings.UsedHideHudShortcut`
- **Type:** `boolean`
- **Summary:** Indicates whether the user has used the keyboard shortcut for hiding the HUD.

### `UserGameSettings.VignetteEnabled`
- **Type:** `boolean`
- **Summary:** Indicates whether the VR vignette comfort effect is enabled.

### `UserGameSettings.VREnabled`
- **Type:** `boolean`
- **Summary:** Indicates whether the client is currently running in VR mode.

### `UserGameSettings.VRRotationIntensity`
- **Type:** `int`
- **Summary:** The intensity of camera rotation when turning in VR.

### `UserGameSettings.VRSmoothRotationEnabled`
- **Type:** `boolean`
- **Summary:** Indicates whether smooth rotation is used instead of snap rotation in VR.

## Methods
### `UserGameSettings:GetCameraYInvertValue() -> int`
- **Summary:** Returns the camera's Y-invert value.

### `UserGameSettings:GetOnboardingCompleted(onboardingId: string) -> boolean`
- **Summary:** Checks if onboarding has been completed.

### `UserGameSettings:InFullScreen() -> boolean`
- **Summary:** Returns true if the user's Roblox window is in full screen mode.

### `UserGameSettings:InStudioMode() -> boolean`
- **Summary:** Returns true if the client's game session is in Roblox Studio.

### `UserGameSettings:SetCameraYInvertVisible() -> ()`
- **Summary:** If called, Roblox toggles the menu option to invert the user's camera y axis.

### `UserGameSettings:SetGamepadCameraSensitivityVisible() -> ()`
- **Summary:** If called, Roblox toggles the menu option to control the camera sensitivity with gamepads.

### `UserGameSettings:SetOnboardingCompleted(onboardingId: string) -> ()`
- **Summary:** Sets onboarding as completed.

## Events
### `UserGameSettings.FullscreenChanged(isFullscreen: boolean)`
- **Summary:** Fires if the user's full screen mode is changed.

### `UserGameSettings.StudioModeChanged(isStudioMode: boolean)`
- **Summary:** Fired when the user's client switches between Studio mode and in-game mode. This gets fired periodically in Roblox Studio when a session starts.
