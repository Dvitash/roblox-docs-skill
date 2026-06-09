# PluginToolbarButton

**Superclass:** [Instance](Instance.md)

A `PluginToolbarButton` object is created by calling `Class.PluginToolbar:CreateButton()` and inheriting from `Instance`. It allows users to initiate a single, one-off action in Roblox Studio.

## Tags
- NotCreatable

## Properties
### `PluginToolbarButton.ClickableWhenViewportHidden`
- **Type:** `boolean`
- **Tags:** NotReplicated
- **Summary:** Determines whether the button can be clicked when the 3D viewport is hidden, such as when a `Class.Script` is being edited in another tab.

### `PluginToolbarButton.Enabled`
- **Type:** `boolean`
- **Tags:** NotReplicated
- **Summary:** Determines whether the button is clickable in general.

### `PluginToolbarButton.Icon`
- **Type:** `ContentId`
- **Tags:** NotReplicated
- **Summary:** Determines what icon should represent the button.

## Methods
### `PluginToolbarButton:SetActive(active: boolean) -> ()`
- **Summary:** Sets the state of the plugin button.

## Events
### `PluginToolbarButton.Click()`
- **Summary:** Fires when the user presses and releases their cursor on the button.
