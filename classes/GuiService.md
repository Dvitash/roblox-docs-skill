# GuiService

**Superclass:** [Instance](Instance.md)

This file contains methods and properties for working with `Class.GuiObject` and `Class.CoreGui` related to player preferences, navigation, and UI elements.

## Tags
- NotCreatable
- Service
- NotReplicated

## Properties
### `GuiService.AutoSelectGuiEnabled`
- **Type:** `boolean`
- **Summary:** If activated, the <kbd>Select</kbd> button on a gamepad or <kbd>Backslash</kbd> will automatically set a GUI as the selected object.

### `GuiService.CoreGuiNavigationEnabled`
- **Type:** `boolean`
- **Tags:** Hidden, NotReplicated
- **Summary:** Toggles whether or not objects in the `Class.CoreGui` can be navigated using a gamepad.

### `GuiService.GuiNavigationEnabled`
- **Type:** `boolean`
- **Summary:** Used to enable and disable the default controller GUI navigation.

### `GuiService.IsModalDialog`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated, Deprecated
- **Summary:** Indicates whether a modal dialog is visible.

### `GuiService.IsWindows`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated, Deprecated
- **Summary:** Indicates whether the user is playing on a computer running Windows.

### `GuiService.MenuIsOpen`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Returns `true` if any menu of `Class.CoreGui` is open.

### `GuiService.PreferredTextSize`
- **Type:** `PreferredTextSize`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Gets the player's preferred text size as an `Enum.PreferredTextSize` value.

### `GuiService.PreferredTransparency`
- **Type:** `float`
- **Tags:** Hidden, ReadOnly, NotReplicated
- **Summary:** Gets the player's preferred transparency as a number between `0` and `1`.

### `GuiService.ReducedMotionEnabled`
- **Type:** `boolean`
- **Tags:** Hidden, ReadOnly, NotReplicated
- **Summary:** Returns `true` if the player has enabled reduced motion.

### `GuiService.SelectedObject`
- **Type:** `[GuiObject](GuiObject.md)`
- **Summary:** Sets the `Class.GuiObject` currently being focused on by the GUI navigator.

### `GuiService.TopbarInset`
- **Type:** `Rect`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Used to determine the absolute size and position of unobstructed area within top bar space.

### `GuiService.TouchControlsEnabled`
- **Type:** `boolean`
- **Summary:** Used to enable and disable touch controls and touch control display UI. Defaults to `true`.

### `GuiService.ViewportDisplaySize`
- **Type:** `DisplaySize`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Read-only property which represents the physical rendering size of the viewport.

## Methods
### `GuiService:AddSelectionParent(selectionName: string, selectionParent: [Instance](Instance.md)) -> ()`
- **Tags:** Deprecated
- **Summary:** Creates a selection group where gamepad GUI navigation will only consider selectable objects that are within the group.

### `GuiService:AddSelectionTuple(selectionName: string, selections: Tuple) -> ()`
- **Tags:** Deprecated
- **Summary:** **AddSelectionTuple** works similarly to `Class.GuiService:AddSelectionParent()`, but you can give it a tuple of `Class.GuiObject` that you want to be contained in the group. Beware that the second argument is _not_ a table, but rather the first of several `Class.GuiObject` in the tuple. To pass the contents of a table, use `unpack`/`table.unpack`: ```lua local frame = script.Parent -- Passing various GuiObject individually GuiService:AddSelectionTuple("InventoryButtons", frame.Sort, frame.Trash, frame.Drop) -- Unpacking a table of GuiObject (unpack/table.unpack are equivalent) local inventoryButtons = { frame.Sort, frame.Trash, frame.Drop } GuiService:AddSelectionTuple("InventoryButtons", unpack(inventoryButtons)) ```

### `GuiService:CloseInspectMenu() -> ()`
- **Summary:** Closes the avatar inspection menu, if open.

### `GuiService:DismissNotification(notificationId: string) -> boolean`

### `GuiService:GetEmotesMenuOpen() -> boolean`
- **Summary:** Checks if the player emotes menu is open.

### `GuiService:GetGameplayPausedNotificationEnabled() -> boolean`
- **Summary:** Returns whether or not the `Class.Player.GameplayPaused` notification has been disabled.

### `GuiService:GetGuiInset() -> Tuple`
- **Summary:** Returns two `Datatype.Vector2` values representing the inset of user GUIs in pixels, from the top‑left corner of the screen and the bottom‑right corner of the screen respectively.

### `GuiService:GetInsetArea(screenInsets: ScreenInsets) -> Rect`
- **Summary:** Takes an `Enum.ScreenInsets` value and returns a `Datatype.Rect2D` describing the inset region, relative to the `Enum.ScreenInsets.CoreUISafeInsets|CoreUISafeInsets` area.

### `GuiService:GetInspectMenuEnabled() -> boolean`
- **Summary:** Returns whether the avatar inspection menu is enabled.

### `GuiService:InspectPlayerFromHumanoidDescription(humanoidDescription: [Instance](Instance.md), name: string) -> ()`
- **Summary:** Allows the avatar inspection menu to appear showing the assets listed in a `Class.HumanoidDescription` object.

### `GuiService:InspectPlayerFromUserId(userId: int64) -> ()`
- **Summary:** Allows the avatar inspection menu to appear showing the user that has the given `Class.Player.UserId|UserId`.

### `GuiService:IsTenFootInterface() -> boolean`
- **Summary:** Returns `true` if the client is using the ten foot interface, a special version of Roblox's UI exclusive to consoles.

### `GuiService:RemoveSelectionGroup(selectionName: string) -> ()`
- **Tags:** Deprecated
- **Summary:** Removes a group that was created with `Class.GuiService:AddSelectionParent()|AddSelectionParent()` or `Class.GuiService:AddSelectionTuple()|AddSelectionTuple()`.

### `GuiService:Select(selectionParent: [Instance](Instance.md)) -> ()`
- **Summary:** Sets `Class.GuiService.SelectedObject` to a child of a provided instance that is the `Class.PlayerGui` or its descendants.

### `GuiService:SendNotification(notificationInfo: Dictionary) -> string`

### `GuiService:SetEmotesMenuOpen(isOpen: boolean) -> ()`
- **Summary:** Opens or closes the player emotes menu.

### `GuiService:SetGameplayPausedNotificationEnabled(enabled: boolean) -> ()`
- **Summary:** Lets you disable the built-in notification when a player's gameplay is paused.

### `GuiService:SetInspectMenuEnabled(enabled: boolean) -> ()`
- **Summary:** Allows you to enable or disable the avatar inspection menu.

## Events
### `GuiService.MenuClosed()`
- **Summary:** Fires when the user **closes** the Roblox `Class.CoreGui` escape menu.

### `GuiService.MenuOpened()`
- **Summary:** Fires when the user **opens** the Roblox `Class.CoreGui` escape menu.
