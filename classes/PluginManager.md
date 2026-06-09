# PluginManager

**Superclass:** [Instance](Instance.md)

PluginManager is a deprecated singleton used to create plugins, though it still has some functionality for creating `Class.Plugin` objects from the Command Bar.

## Tags
- NotCreatable

## Methods
### `PluginManager:CreatePlugin() -> [Instance](Instance.md)`
- **Tags:** Deprecated, CustomLuaState

### `PluginManager:ExportPlace(filePath: string) -> ()`
- **Summary:** Exports the place to an `.obj` file that is saved to the path chosen by the user in a file save dialogue.

### `PluginManager:ExportSelection(filePath: string) -> ()`
- **Summary:** Exports the current `Class.Selection` to an `.obj` file that is saved to the path chosen by the user in a file save dialogue.
