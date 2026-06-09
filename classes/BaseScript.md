# BaseScript

**Superclass:** [LuaSourceContainer](LuaSourceContainer.md)

BaseScript is the base class for all script objects that run automatically, and it defines properties for controlling runtime behavior.

## Tags
- NotCreatable

## Properties
### `BaseScript.Disabled`
- **Type:** `boolean`
- **Summary:** Determines whether a `Class.BaseScript` will run or not.

### `BaseScript.Enabled`
- **Type:** `boolean`
- **Tags:** NotReplicated
- **Summary:** Determines whether a `Class.BaseScript` will run or not.

### `BaseScript.LinkedSource`
- **Type:** `ContentId`
- **Tags:** Deprecated
- **Summary:** The content ID of an uploaded script. When set binds the uploaded code to the script's `Class.Script.Source`.

### `BaseScript.RunContext`
- **Type:** `RunContext`
- **Summary:** Determines the context under which the script will run.
