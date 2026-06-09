# ScriptEditorService

**Superclass:** [Instance](Instance.md)

This class is used to interact with `Class.ScriptDocument` instances, allowing for registering and managing autocomplete callbacks.

## Tags
- NotCreatable
- Service
- NotReplicated

## Methods
### `ScriptEditorService:DeregisterAutocompleteCallback(name: string) -> ()`
- **Summary:** Removes a previously registered callback with the name `name`.

### `ScriptEditorService:DeregisterScriptAnalysisCallback(name: string) -> ()`
- **Summary:** Removes a previously registered callback with the name `name`.

### `ScriptEditorService:FindScriptDocument(script: [LuaSourceContainer](LuaSourceContainer.md)) -> [ScriptDocument](ScriptDocument.md)`
- **Summary:** Returns the open `Class.ScriptDocument` corresponding to the given `Class.LuaSourceContainer`, or `nil` if the given script is not open.

### `ScriptEditorService:GetEditorSource(script: [LuaSourceContainer](LuaSourceContainer.md)) -> string`
- **Summary:** Returns the edit-time source for the given script.

### `ScriptEditorService:GetScriptDocuments() -> List<[ScriptDocument](ScriptDocument.md)>`
- **Summary:** Returns an array of the currently open script documents, including the command bar.

### `ScriptEditorService:OpenScriptDocumentAsync(script: [LuaSourceContainer](LuaSourceContainer.md), options: Dictionary) -> Tuple`
- **Tags:** Yields
- **Summary:** Requests that a Script Editor open the specified script. Returns (true, nil) if the request succeeds. Returns (false, string) if the request fails, with a string that describes the problem.

### `ScriptEditorService:RegisterAutocompleteCallback(name: string, priority: int, callbackFunction: Function) -> ()`
- **Summary:** Registers an autocomplete callback `callbackFunction` named `name` with priority `priority`.

### `ScriptEditorService:RegisterScriptAnalysisCallback(name: string, priority: int, callbackFunction: Function) -> ()`
- **Summary:** Registers a Script Analysis callback `callbackFunction` named `name` with `priority`.

### `ScriptEditorService:UpdateSourceAsync(script: [LuaSourceContainer](LuaSourceContainer.md), callback: Function) -> ()`
- **Tags:** Yields
- **Summary:** Generates new content from the old script and updates the script editor if it's open, or the `Class.Script` instance if the script editor is closed.

## Events
### `ScriptEditorService.TextDocumentDidChange(document: [ScriptDocument](ScriptDocument.md), changesArray: Variant)`
- **Summary:** Fires just after a `Class.ScriptDocument` changes.

### `ScriptEditorService.TextDocumentDidClose(oldDocument: [ScriptDocument](ScriptDocument.md))`
- **Summary:** Fires just before a `Class.ScriptDocument` object is destroyed, which happens right after the script editor closes.

### `ScriptEditorService.TextDocumentDidOpen(newDocument: [ScriptDocument](ScriptDocument.md))`
- **Summary:** Fires just after a `Class.ScriptDocument` object is created and parented to the service, which happens right after the script editor opens.
