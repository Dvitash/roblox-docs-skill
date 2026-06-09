# PluginAction

**Superclass:** [Instance](Instance.md)

PluginAction is a generic performable action in Studio that can be assigned a keyboard shortcut via the **File**&nbsp;⟩ **Customize Shortcuts** window.

## Tags
- NotReplicated

## Properties
### `PluginAction.ActionId`
- **Type:** `string`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A string that uniquely identifies this action.

### `PluginAction.AllowBinding`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Determines whether the action can be assigned a keyboard shortcut in Studio.

### `PluginAction.StatusTip`
- **Type:** `string`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The description of the action when viewing it from the keyboard shortcuts window in Roblox Studio.

### `PluginAction.Text`
- **Type:** `string`
- **Tags:** NotReplicated
- **Summary:** The text that is displayed when viewing this action in Roblox Studio.

## Events
### `PluginAction.Triggered()`
- **Summary:** Fires when the action is triggered.
