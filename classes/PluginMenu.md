# PluginMenu

**Superclass:** [Instance](Instance.md)

The `PluginMenu` class is a context menu in Studio that displays a list of `Class.PluginAction` and supports submenus. It must be created using the `Class.Plugin:CreatePluginMenu()` method.

## Tags
- NotCreatable
- NotReplicated

## Properties
### `PluginMenu.Icon`
- **Type:** `string`
- **Tags:** NotReplicated
- **Summary:** The icon to be displayed when used as a submenu.

### `PluginMenu.Title`
- **Type:** `string`
- **Tags:** NotReplicated
- **Summary:** The text to be displayed when used as a submenu.

### `PluginMenu.Visible`
- **Type:** `boolean`

## Methods
### `PluginMenu:AddAction(action: [Instance](Instance.md)) -> ()`
- **Summary:** Adds the given action to the menu.

### `PluginMenu:AddMenu(menu: [Instance](Instance.md)) -> ()`
- **Summary:** Adds the given menu as a separator.

### `PluginMenu:AddNewAction(actionId: string, text: string, icon: string) -> [Instance](Instance.md)`
- **Summary:** Creates a temporary action that is hidden from Studio's customize shortcuts window.

### `PluginMenu:AddSeparator() -> ()`
- **Summary:** Adds a separator between items in the menu.

### `PluginMenu:Clear() -> ()`
- **Summary:** Clears the menu.

### `PluginMenu:ShowAsync() -> [Instance](Instance.md)`
- **Tags:** Yields
- **Summary:** Shows the menu at the mouse cursor. Yields until either an item is selected or the menu is closed.
