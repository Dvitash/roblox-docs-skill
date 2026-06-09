# Studio

**Superclass:** [Instance](Instance.md)

The Studio object is a settings object exclusive to Roblox Studio, accessible in Roblox Studio's settings under the "Studio" tab. It contains various color properties and has specific security and thread safety considerations.

## Tags
- NotCreatable
- Service
- NotReplicated

## Properties
### `Studio."function" Color`
- **Type:** `Color3`
- **Tags:** NotReplicated

### `Studio."local" Color`
- **Type:** `Color3`
- **Tags:** NotReplicated

### `Studio."nil" Color`
- **Type:** `Color3`
- **Tags:** NotReplicated

### `Studio."self" Color`
- **Type:** `Color3`
- **Tags:** NotReplicated

### `Studio."TODO" Color`
- **Type:** `Color3`
- **Tags:** NotReplicated

### `Studio.ActionOnAutoResumeSync`
- **Type:** `ActionOnAutoResumeSync`

### `Studio.ActionOnStopSync`
- **Type:** `ActionOnStopSync`

### `Studio.Active Color`
- **Type:** `Color3`

### `Studio.Active Hover Over Color`
- **Type:** `Color3`

### `Studio.Always Save Script Changes`
- **Type:** `boolean`
- **Summary:** If set to true, Roblox Studio will attempt to transfer script changes that were made during a Play Solo session to the opened place.

### `Studio.Animate Hover Over`
- **Type:** `boolean`
- **Summary:** If set to true, the hover selection box that is shown when mousing over selectable objects in the `Class.Workspace` will flash between `Hover Over Color` and `Select Color` based on the `Hover Animate Speed`.

### `Studio.Auto Clean Empty Line`
- **Type:** `boolean`

### `Studio.Auto Closing Brackets`
- **Type:** `boolean`

### `Studio.Auto Closing Quotes`
- **Type:** `boolean`

### `Studio.Auto Delete Closing Brackets and Quotes`
- **Type:** `boolean`

### `Studio.Auto Indent Rule`
- **Type:** `AutoIndentRule`

### `Studio.Auto-Recovery Enabled`
- **Type:** `boolean`

### `Studio.Auto-Recovery Interval (Minutes)`
- **Type:** `int`

### `Studio.AutocompleteAcceptanceBehavior`
- **Type:** `CompletionAcceptanceBehavior`

### `Studio.Automatically trigger AI Code Completion`
- **Type:** `boolean`

### `Studio.AutoResumeSyncOnPlaceOpen`
- **Type:** `boolean`

### `Studio.AutoUpdateEnabled`
- **Type:** `boolean`

### `Studio.Background Color`
- **Type:** `Color3`
- **Tags:** NotReplicated
- **Summary:** Specifies the background color of Roblox Studio's script editor.

### `Studio.Basic Objects Display Mode`
- **Type:** `ListDisplayMode`
- **Summary:** Sets the scrolling mode of the `Advanced Objects` tab in Roblox Studio.

### `Studio.Bool Color`
- **Type:** `Color3`
- **Tags:** NotReplicated

### `Studio.Bracket Color`
- **Type:** `Color3`
- **Tags:** NotReplicated

### `Studio.Built-in Function Color`
- **Type:** `Color3`
- **Tags:** NotReplicated
- **Summary:** Sets the color of built-in functions and keywords in the script editor.

### `Studio.Camera Mouse Wheel Speed`
- **Type:** `float`
- **Summary:** Sets how many studs the camera will move forward or backwards when using the mouse wheel.

### `Studio.Camera Pan Speed`
- **Type:** `float`

### `Studio.Camera Shift Speed`
- **Type:** `float`
- **Summary:** Sets the speed in studs/sec that the camera moves while holding down Shift with the movement keys.

### `Studio.Camera Speed`
- **Type:** `float`
- **Summary:** Sets the speed in studs/sec that the camera moves when movement keys are pressed.

### `Studio.Camera Speed Adjust Binding`
- **Type:** `CameraSpeedAdjustBinding`

### `Studio.Camera Zoom to Mouse Position`
- **Type:** `boolean`

### `Studio.CameraAdaptiveSpeed`
- **Type:** `boolean`

### `Studio.CameraNavigationModel`
- **Type:** `CameraNavigationModel`

### `Studio.CameraOrbitSensitivity`
- **Type:** `float`

### `Studio.CameraPanSensitivity`
- **Type:** `float`

### `Studio.CameraShiftFactor`
- **Type:** `float`

### `Studio.CameraTweenFocus`
- **Type:** `boolean`

### `Studio.CameraZoomSpeed`
- **Type:** `float`

### `Studio.Clear Output On Start`
- **Type:** `boolean`
- **Summary:** If set to true, the output will be automatically cleared when game sessions are switched.

### `Studio.CommandBarEnterExec`
- **Type:** `boolean`

### `Studio.CommandBarFont`
- **Type:** `QFont`

### `Studio.CommandBarLocalState`
- **Type:** `boolean`

### `Studio.Comment Color`
- **Type:** `Color3`
- **Tags:** NotReplicated
- **Summary:** Specifies the color of comments in Roblox Studio's script editor.

### `Studio.Current Line Highlight Color`
- **Type:** `Color3`
- **Tags:** NotReplicated

### `Studio.Debugger Current Line Color`
- **Type:** `Color3`
- **Tags:** NotReplicated

### `Studio.Debugger Error Line Color`
- **Type:** `Color3`
- **Tags:** NotReplicated

### `Studio.DefaultInstancesDir`
- **Type:** `QDir`

### `Studio.DefaultScriptSyncFileType`
- **Type:** `DefaultScriptSyncFileType`

### `Studio.DeprecatedObjectsShown`
- **Type:** `boolean`
- **Summary:** If set to true, deprecated objects will be shown in the Advanced Objects window, as well as the Object Browser.

### `Studio.DisplayLanguage`
- **Type:** `string`

### `Studio.DraggerActiveColor`
- **Type:** `Color3`

### `Studio.DraggerLengthFactor`
- **Type:** `float`

### `Studio.DraggerMajorGridIncrement`
- **Type:** `int`

### `Studio.DraggerMaxSoftSnaps`
- **Type:** `int`

### `Studio.DraggerPassiveColor`
- **Type:** `Color3`

### `Studio.DraggerScaleFactor`
- **Type:** `float`

### `Studio.DraggerShowAxisTicks`
- **Type:** `boolean`

### `Studio.DraggerShowHoverRuler`
- **Type:** `boolean`

### `Studio.DraggerShowMeasurement`
- **Type:** `boolean`

### `Studio.DraggerShowNegativeAxes`
- **Type:** `boolean`

### `Studio.DraggerShowPlanes`
- **Type:** `boolean`

### `Studio.DraggerShowTargetSnap`
- **Type:** `boolean`

### `Studio.DraggerShowTrackball`
- **Type:** `boolean`

### `Studio.DraggerShowWhileDragging`
- **Type:** `boolean`

### `Studio.DraggerSoftSnapMarginFactor`
- **Type:** `float`

### `Studio.DraggerSummonMarginFactor`
- **Type:** `float`

### `Studio.DraggerTiltRotateDuration`
- **Type:** `float`

### `Studio.Enable Autocomplete`
- **Type:** `boolean`
- **Summary:** When set to true, the script editor and command bar will show an autocomplete menu while writing.

### `Studio.Enable Autocomplete Doc View`
- **Type:** `boolean`

### `Studio.Enable CoreScript Debugger`
- **Type:** `boolean`

### `Studio.Enable Http Sandboxing`
- **Type:** `boolean`

### `Studio.Enable Internal Beta Features`
- **Type:** `boolean`

### `Studio.Enable Internal Features`
- **Type:** `boolean`

### `Studio.Enable Script Analysis`
- **Type:** `boolean`

### `Studio.Enable Scrollbar Markers`
- **Type:** `boolean`

### `Studio.Enable Signature Help`
- **Type:** `boolean`

### `Studio.Enable Signature Help Doc View`
- **Type:** `boolean`

### `Studio.Enable Temporary Tabs`
- **Type:** `boolean`

### `Studio.Enable Temporary Tabs In Explorer`
- **Type:** `boolean`

### `Studio.Enable Type Hover`
- **Type:** `boolean`

### `Studio.EnableCodeAssist`
- **Type:** `boolean`

### `Studio.EnableFindOnType`
- **Type:** `boolean`

### `Studio.EnableIndentationRulers`
- **Type:** `boolean`

### `Studio.EnableSelectionTooltips`
- **Type:** `boolean`

### `Studio.EnableStudioStreaming`
- **Type:** `boolean`

### `Studio.Error Color`
- **Type:** `Color3`
- **Tags:** NotReplicated
- **Summary:** Specifies the color of the wavy underline shown when malformed code is detected in the script editor.

### `Studio.ExternalEditorMode`
- **Type:** `ExternalEditorMode`

### `Studio.ExternalEditorSelection`
- **Type:** `QDir`

### `Studio.Find Selection Background Color`
- **Type:** `Color3`
- **Tags:** NotReplicated
- **Summary:** Sets the highlight color of matches in the script editor's Find Selection operation (Ctrl+F).

### `Studio.Font`
- **Type:** `QFont`
- **Summary:** Specifies the font used in the script editor.

### `Studio.Format On Paste`
- **Type:** `boolean`

### `Studio.Format On Type`
- **Type:** `boolean`

### `Studio.Function Name Color`
- **Type:** `Color3`
- **Tags:** NotReplicated

### `Studio.Highlight Current Line`
- **Type:** `boolean`

### `Studio.Highlight Occurances`
- **Type:** `boolean`

### `Studio.HintColor`
- **Type:** `Color3`
- **Tags:** NotReplicated

### `Studio.Hover Animate Speed`
- **Type:** `HoverAnimateSpeed`
- **Summary:** Specifies how frequently the hover animation flashes when the mouse is hovering over a selectable object in the `Class.Workspace`.

### `Studio.Hover Box Thickness`
- **Type:** `float`

### `Studio.Hover Line Thickness`
- **Type:** `int`

### `Studio.Hover Over Color`
- **Type:** `Color3`
- **Summary:** Specifies the color that the hover selection box uses.

### `Studio.IconOverrideDir`
- **Type:** `QDir`

### `Studio.Indent Using Spaces`
- **Type:** `boolean`

### `Studio.IndentationRulerColor`
- **Type:** `Color3`
- **Tags:** NotReplicated

### `Studio.InformationColor`
- **Type:** `Color3`
- **Tags:** NotReplicated

### `Studio.Keyword Color`
- **Type:** `Color3`
- **Tags:** NotReplicated
- **Summary:** Sets the text color of built-in Luau keywords.

### `Studio.LargeFileLineCountThreshold`
- **Type:** `int`

### `Studio.LargeFileThreshold`
- **Type:** `int`

### `Studio.Line Thickness`
- **Type:** `float`
- **Summary:** Sets the thickness of the `Class.Model.PrimaryPart` selection adornee. This value is constrained between 0 and 0.05.

### `Studio.LoadAllBuiltinPluginsInRunModes`
- **Type:** `boolean`

### `Studio.LoadInternalPlugins`
- **Type:** `boolean`

### `Studio.LoadUserPluginsInRunModes`
- **Type:** `boolean`

### `Studio.LocalAssetsFolder`
- **Type:** `QDir`

### `Studio.LuaDebuggerEnabled`
- **Type:** `boolean`
- **Summary:** Specifies whether or not the Lua Debugger feature is enabled.

### `Studio.LuaDebuggerEnabledAtStartup`
- **Type:** `boolean`
- **Tags:** Hidden, ReadOnly, NotReplicated

### `Studio.Luau Keyword Color`
- **Type:** `Color3`
- **Tags:** NotReplicated

### `Studio.Main Volume`
- **Type:** `float`

### `Studio.Matching Word Background Color`
- **Type:** `Color3`
- **Tags:** NotReplicated
- **Summary:** Sets the highlight color of double-clicked variables in the script editor.

### `Studio.MaxFindReplaceAllResults`
- **Type:** `int`

### `Studio.Maximum Output Lines`
- **Type:** `int`
- **Summary:** The maximum number of lines that can be displayed in the output.

### `Studio.Menu Item Background Color`
- **Type:** `Color3`
- **Tags:** NotReplicated

### `Studio.Method Color`
- **Type:** `Color3`
- **Tags:** NotReplicated

### `Studio.Number Color`
- **Type:** `Color3`
- **Tags:** NotReplicated
- **Summary:** Specifies the color of numbers in Roblox Studio's script editor.

### `Studio.Only Play Audio from Window in Focus`
- **Type:** `boolean`
- **Summary:** If set to true, audio being played will only be heard if the game window is being focused on.

### `Studio.Operator Color`
- **Type:** `Color3`
- **Tags:** NotReplicated
- **Summary:** Sets the text color of operator characters in the script editor.

### `Studio.Output Font`
- **Type:** `QFont`
- **Summary:** Specifies the font used by the output.

### `Studio.Output Layout Mode`
- **Type:** `OutputLayoutMode`
- **Summary:** Sets the layout mode of the output.

### `Studio.PermissionLevelShown`
- **Type:** `PermissionLevelShown`
- **Summary:** Sets the highest permission level that APIs have to have in order to be shown in the Object Browser. See `Enum.PermissionLevelShown` for more info.

### `Studio.Physical Draggers Select Scope By Default`
- **Type:** `boolean`

### `Studio.Pivot Snap To Geometry Color`
- **Type:** `Color3`

### `Studio.PluginDebuggingEnabled`
- **Type:** `boolean`

### `Studio.PluginsDir`
- **Type:** `QDir`
- **Summary:** The directory where local plugins are stored.

### `Studio.PreferredTextSize`
- **Type:** `PreferredTextSize`

### `Studio.Primary Text Color`
- **Type:** `Color3`
- **Tags:** NotReplicated

### `Studio.Property Color`
- **Type:** `Color3`
- **Tags:** NotReplicated

### `Studio.ReloadBuiltinPluginsOnChange`
- **Type:** `boolean`

### `Studio.ReloadLocalPluginsOnChange`
- **Type:** `boolean`

### `Studio.Respect Studio shortcuts when game has focus`
- **Type:** `boolean`
- **Summary:** When set to true, Roblox Studio shortcuts will take priority over inputs being captured in the game window.

### `Studio.Ruler Color`
- **Type:** `Color3`
- **Tags:** NotReplicated

### `Studio.Rulers`
- **Type:** `string`

### `Studio.RuntimeUndoBehavior`
- **Type:** `RuntimeUndoBehavior`

### `Studio.Script Editor Color Preset`
- **Type:** `StudioScriptEditorColorPresets`

### `Studio.Script Editor Scrollbar Background Color`
- **Type:** `Color3`
- **Tags:** NotReplicated

### `Studio.Script Editor Scrollbar Handle Color`
- **Type:** `Color3`
- **Tags:** NotReplicated

### `Studio.ScriptTimeoutLength`
- **Type:** `int`
- **Summary:** The time (in seconds) a script can wait to be resumed before timing out.

### `Studio.Scroll Past Last Line`
- **Type:** `boolean`

### `Studio.Secondary Text Color`
- **Type:** `Color3`
- **Tags:** NotReplicated

### `Studio.Select Color`
- **Type:** `Color3`
- **Summary:** The color of the selection box used with object selections in the `Class.Workspace`.

### `Studio.Select/Hover Color`
- **Type:** `Color3`
- **Summary:** Sets the color of the `Class.Model.PrimaryPart` selection box.

### `Studio.Selected Menu Item Background Color`
- **Type:** `Color3`
- **Tags:** NotReplicated

### `Studio.Selected Text Color`
- **Type:** `Color3`
- **Tags:** NotReplicated

### `Studio.Selection Background Color`
- **Type:** `Color3`
- **Tags:** NotReplicated
- **Summary:** Sets the background color of selected text in the script editor.

### `Studio.Selection Box Thickness`
- **Type:** `float`

### `Studio.Selection Color`
- **Type:** `Color3`
- **Tags:** NotReplicated
- **Summary:** Sets the text color of selected text in the script editor.

### `Studio.Selection Line Thickness`
- **Type:** `int`

### `Studio.Set Pivot of Imported Parts`
- **Type:** `boolean`

### `Studio.Show Core GUI in Explorer while Playing`
- **Type:** `boolean`
- **Summary:** If set to true, the `Class.CoreGui` will be visible in the Explorer while the game is running.

### `Studio.Show Diagnostics Bar`
- **Type:** `boolean`
- **Summary:** If set to true, basic diagnostic information is shown in the bottom right.

### `Studio.Show FileSyncService`
- **Type:** `boolean`

### `Studio.Show Hidden Objects in Explorer`
- **Type:** `boolean`

### `Studio.Show Hover Over`
- **Type:** `boolean`
- **Summary:** If set to true, hovering over an object in the `Class.Workspace` will show a selection box.

### `Studio.Show Light Guides`
- **Type:** `boolean`

### `Studio.Show Navigation Labels`
- **Type:** `boolean`

### `Studio.Show Navigation Mesh`
- **Type:** `boolean`
- **Summary:** When set to true, the navigation mesh used by the `Class.PathfindingService` will be visualized.

### `Studio.Show Pathfinding Links`
- **Type:** `boolean`

### `Studio.Show Plugin GUI Service in Explorer`
- **Type:** `boolean`
- **Summary:** When set to true, the `Class.PluginGuiService` will be shown in Roblox Studio's explorer.

### `Studio.Show plus button on hover in Explorer`
- **Type:** `boolean`

### `Studio.Show Singly Selected Attachment Parent Frame`
- **Type:** `boolean`

### `Studio.Show Whitespace`
- **Type:** `boolean`

### `Studio.ShowCorePackagesInExplorer`
- **Type:** `boolean`

### `Studio.Skip Closing Brackets and Quotes`
- **Type:** `boolean`

### `Studio.String Color`
- **Type:** `Color3`
- **Tags:** NotReplicated
- **Summary:** Specifies the color of strings in the script editor.

### `Studio.Tab Width`
- **Type:** `int`
- **Summary:** Specifies how many spaces are used to represent a tab in the script editor.

### `Studio.Text Color`
- **Type:** `Color3`
- **Tags:** NotReplicated
- **Summary:** Specifies the color of normal text in the script editor.

### `Studio.Text Wrapping`
- **Type:** `boolean`
- **Summary:** If set to true, text in the script editor will be wrapped.

### `Studio.Theme`
- **Type:** `[Instance](Instance.md)`
- **Summary:** Used to get/set current `Class.StudioTheme|theme` used by Studio.

### `Studio.TypeColor`
- **Type:** `Color3`
- **Tags:** NotReplicated

### `Studio.UI Theme`
- **Type:** `UITheme`
- **Tags:** Hidden, ReadOnly, NotReplicated, Deprecated
- **Summary:** Specifies the color scheme of Roblox Studio.

### `Studio.Use Bounding Box Move Handles`
- **Type:** `boolean`

### `Studio.UseDefaultExternalEditor`
- **Type:** `boolean`

### `Studio.VAxisColor`
- **Type:** `Color3`

### `Studio.Warning Color`
- **Type:** `Color3`
- **Tags:** NotReplicated
- **Summary:** Specifies the color of the wavy underline shown when the script analyzer picks up a problem that should be addressed in the script editor.

### `Studio.Whitespace Color`
- **Type:** `Color3`
- **Tags:** NotReplicated

### `Studio.XAxisColor`
- **Type:** `Color3`

### `Studio.YAxisColor`
- **Type:** `Color3`

### `Studio.ZAxisColor`
- **Type:** `Color3`

## Methods
### `Studio:GetAvailableThemes() -> Array`
- **Summary:** Returns a list of `Class.StudioTheme|themes` available in Studio.

## Events
### `Studio.ThemeChanged()`
- **Summary:** Event called when Studio's `Class.StudioTheme|theme` changes.
