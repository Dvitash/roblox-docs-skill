# ModuleScript

**Superclass:** [LuaSourceContainer](LuaSourceContainer.md)

A `ModuleScript` is a script type that runs once when `Global.LuaGlobals.require()` is called, returning exactly one value to other scripts.

## Properties
### `ModuleScript.LinkedSource`
- **Type:** `ContentId`
- **Tags:** Deprecated
- **Summary:** Used to store a URL that points to an online script source. Binds the online code to the script's `Class.Script.Source`.

### `ModuleScript.Source`
- **Type:** `ProtectedString`
- **Summary:** The code to be executed.
