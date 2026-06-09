# Plugin

**Superclass:** [Instance](Instance.md)

This file contains methods for creating and managing custom Studio widgets, including plugins, toolbars, and buttons.

## Tags
- NotCreatable

## Properties
### `Plugin.CollisionEnabled`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Returns whether the user has enabled **Collisions** in Studio's toolbar.

### `Plugin.DisableUIDragDetectorDrags`
- **Type:** `boolean`
- **Summary:** If `true`, toolbars and buttons for the plugin will ignore dragging related to a `Class.UIDragDetector` instance.

### `Plugin.GridSize`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Returns the grid snapping size the user has set in Studio.

### `Plugin.IsDebuggable`
- **Type:** `boolean`

## Methods
### `Plugin:Activate(exclusiveMouse: boolean) -> ()`
- **Summary:** Sets the state of the calling plugin to activated.

### `Plugin:CreateDockWidgetPluginGui(pluginGuiId: string, dockWidgetPluginGuiInfo: DockWidgetPluginGuiInfo) -> [DockWidgetPluginGui](DockWidgetPluginGui.md)`
- **Tags:** Yields, Deprecated
- **Summary:** Creates a `Class.DockWidgetPluginGui` given a `Datatype.DockWidgetPluginGuiInfo`.

### `Plugin:CreateDockWidgetPluginGuiAsync(pluginGuiId: string, dockWidgetPluginGuiInfo: DockWidgetPluginGuiInfo) -> [DockWidgetPluginGui](DockWidgetPluginGui.md)`
- **Tags:** Yields
- **Summary:** Creates a `Class.DockWidgetPluginGui` given a `Datatype.DockWidgetPluginGuiInfo`.

### `Plugin:CreatePluginAction(actionId: string, text: string, statusTip: string, iconName: string, allowBinding: boolean) -> [PluginAction](PluginAction.md)`
- **Summary:** Creates a `Class.PluginAction` which represents a generic performable action in Studio with no directly‑associated `Class.PluginToolbarButton`.

### `Plugin:CreatePluginMenu(id: string, title: string, icon: string) -> [PluginMenu](PluginMenu.md)`
- **Summary:** Creates a new plugin menu.

### `Plugin:CreateToolbar(name: string) -> [PluginToolbar](PluginToolbar.md)`
- **Summary:** Creates a new `Class.PluginToolbar` with the given name.

### `Plugin:Deactivate() -> ()`
- **Summary:** Deactivates the plugin.

### `Plugin:GetJoinMode() -> JointCreationMode`
- **Summary:** Returns the `Enum.JointCreationMode` the user has set in Studio's toolbar.

### `Plugin:GetMouse() -> [PluginMouse](PluginMouse.md)`
- **Summary:** Returns a `Class.Mouse` that can be used while the plugin is active.

### `Plugin:GetSelectedRibbonTool() -> RibbonTool`
- **Summary:** Returns the currently selected `Enum.RibbonTool`.

### `Plugin:GetSetting(key: string) -> Variant`
- **Summary:** Retrieves a previously stored value with the given key, or `nil` if the given key doesn't exist.

### `Plugin:GetStudioUserId() -> int64`
- **Tags:** Deprecated
- **Summary:** Returns the Studio user's userId if they're logged in, otherwise returns 0.

### `Plugin:ImportFbxAnimation(rigModel: [Instance](Instance.md), isR15: boolean) -> [Instance](Instance.md)`
- **Tags:** Yields, Deprecated
- **Summary:** Prompts the user to open a `.fbx` animation file that can be loaded onto the `rigModel`, then proceeds to insert the animation as a `Class.KeyframeSequence` in the `Class.Workspace`.

### `Plugin:ImportFbxAnimationAsync(rigModel: [Instance](Instance.md), isR15: boolean) -> [Instance](Instance.md)`
- **Tags:** Yields
- **Summary:** Prompts the user to open a `.fbx` animation file that can be loaded onto the `rigModel`, then proceeds to insert the animation as a `Class.KeyframeSequence` in the `Class.Workspace`.

### `Plugin:ImportFbxRig(isR15: boolean) -> [Instance](Instance.md)`
- **Tags:** Yields, Deprecated
- **Summary:** Prompts the user to open a `.fbx` file, uploads the individual components of the model as meshes, and generates a character rig for use in animation, which is loaded into the `Class.Workspace`.

### `Plugin:ImportFbxRigAsync(isR15: boolean) -> [Instance](Instance.md)`
- **Tags:** Yields
- **Summary:** Prompts the user to open a `.fbx` file, uploads the individual components of the model as meshes, and generates a character rig for use in animation, which is loaded into the `Class.Workspace`.

### `Plugin:Intersect(objects: Instances) -> [Instance](Instance.md)`
- **Summary:** Intersects the given parts and returns the resulting `Class.IntersectOperation`.

### `Plugin:IsActivated() -> boolean`
- **Summary:** Returns `true` if this plugin is currently active, after having been activated via the `Class.Plugin:Activate()|Activate()` function.

### `Plugin:IsActivatedWithExclusiveMouse() -> boolean`
- **Summary:** Returns `true` if this plugin is currently active with an exclusive mouse.

### `Plugin:Negate(objects: Instances) -> Instances`
- **Summary:** Negates the given parts and returns the resulting `Class.NegateOperation|NegateOperations`.

### `Plugin:OpenScript(script: [LuaSourceContainer](LuaSourceContainer.md), lineNumber: int) -> ()`
- **Tags:** Deprecated
- **Summary:** Used to open the given script instance in an editor window, in Roblox studio, at the given line. If no line is given as an argument it will default to 1.

### `Plugin:OpenWikiPage(url: string) -> ()`
- **Summary:** Opens the context help window to the wiki page that `url` links to.

### `Plugin:PromptForExistingAssetId(assetType: string) -> int64`
- **Tags:** Yields
- **Summary:** Opens a window in Roblox Studio which prompts the user to select an asset based on the `assetType` specified.

### `Plugin:PromptForExistingAssetIdAsync(assetType: string) -> int64`
- **Tags:** Yields
- **Summary:** Opens a window in Roblox Studio which prompts the user to select an asset based on the `assetType` specified.

### `Plugin:PromptSaveSelection(suggestedFileName: string) -> boolean`
- **Tags:** Yields, Deprecated
- **Summary:** Prompts the user to save their current selection with the specified file name.

### `Plugin:PromptSaveSelectionAsync(suggestedFileName: string) -> boolean`
- **Tags:** Yields
- **Summary:** Prompts the user to save their current selection with the specified file name.

### `Plugin:SaveSelectedToRoblox() -> ()`
- **Summary:** Opens an upload window for the user's current selection.

### `Plugin:SelectRibbonTool(tool: RibbonTool, position: UDim2) -> ()`
- **Summary:** Activates the specified Roblox Studio tool.

### `Plugin:Separate(objects: Instances) -> Instances`
- **Summary:** Separates the given `Class.UnionOperation|UnionOperations` and returns the resulting parts.

### `Plugin:SetSetting(key: string, value: Variant) -> ()`
- **Summary:** Stores a given value for later use under the given key. The value will persist even after Studio is closed.

### `Plugin:StartDrag(dragData: Dictionary) -> ()`
- **Summary:** Starts a drag action given a dictionary of parameters.

### `Plugin:Union(objects: Instances) -> [Instance](Instance.md)`
- **Summary:** Unions the given parts and returns the resulting `Class.UnionOperation`.

## Events
### `Plugin.Deactivation()`
- **Summary:** Fired when the plugin is deactivated.

### `Plugin.Unloading()`
- **Summary:** Fires immediately before the `Class.Plugin` stops running.
