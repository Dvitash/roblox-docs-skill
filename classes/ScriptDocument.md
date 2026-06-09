# ScriptDocument

**Superclass:** [Instance](Instance.md)

This file defines `Class.ScriptDocument` as a proxy for the script editor's open document state, detailing its memory and behavior.

## Tags
- NotCreatable
- NotReplicated

## Methods
### `ScriptDocument:CloseAsync() -> Tuple`
- **Tags:** Yields
- **Summary:** Requests that the editor associated with this document close. Yields the current thread until the editor responds to the request.

### `ScriptDocument:EditTextAsync(newText: string, startLine: int, startCharacter: int, endLine: int, endCharacter: int) -> Tuple`
- **Tags:** Yields
- **Summary:** Replaces the text in the specified range from (`startLine`, `startColumn`) to (`endLine`, `endColumn`) with newText.

### `ScriptDocument:ForceSetSelectionAsync(cursorLine: int, cursorCharacter: int, anchorLine: int?, anchorCharacter: int?) -> Tuple`
- **Tags:** Yields
- **Summary:** Asks the editor to set its cursor selection to the argument values.

### `ScriptDocument:GetLine(lineIndex: int?) -> string`
- **Summary:** Returns the text of the specified line. When no argument is provided, returns the line of the current cursor position.

### `ScriptDocument:GetLineCount() -> int`
- **Summary:** Returns the number of lines in the document.

### `ScriptDocument:GetScript() -> [LuaSourceContainer](LuaSourceContainer.md)`
- **Summary:** Returns the underlying `Class.LuaSourceContainer` instance, if one exists, otherwise `nil`.

### `ScriptDocument:GetSelectedText() -> string`
- **Summary:** Gets the text selected in the editor, or an empty string if there is no selection.

### `ScriptDocument:GetSelection() -> Tuple`
- **Summary:** Returns the last known selection of the Script Editor in the format: `CursorLine, CursorChar, AnchorLine, AnchorChar`. If the Script Editor has no selection, `CursorLine == AnchorLine` and `CursorChar == AnchorChar`.

### `ScriptDocument:GetSelectionEnd() -> Tuple`
- **Summary:** Gets the larger of the cursor position and anchor. If the editor has no selection, they are the same value.

### `ScriptDocument:GetSelectionStart() -> Tuple`
- **Summary:** Gets the smaller of the cursor position and anchor. If the editor has no selection, they are the same value.

### `ScriptDocument:GetText(startLine: int?, startCharacter: int?, endLine: int?, endCharacter: int?) -> string`
- **Summary:** Returns text from the open editor.

### `ScriptDocument:GetViewport() -> Tuple`
- **Summary:** Returns the currently displayed line numbers in the editor change.

### `ScriptDocument:HasSelectedText() -> boolean`
- **Summary:** Returns whether or not the editor has any text selected.

### `ScriptDocument:IsCommandBar() -> boolean`
- **Summary:** Returns true if the `Class.ScriptDocument` represents the Command bar.

### `ScriptDocument:MultiEditTextAsync(edits: Array) -> Tuple`
- **Tags:** Yields

### `ScriptDocument:RequestSetSelectionAsync(cursorLine: int, cursorCharacter: int, anchorLine: int?, anchorCharacter: int?) -> Tuple`
- **Tags:** Yields
- **Summary:** Asks the editor to set its cursor selection to the argument values.

## Events
### `ScriptDocument.SelectionChanged(positionLine: int64, positionCharacter: int64, anchorLine: int64, anchorCharacter: int64)`
- **Summary:** Fires when the ScriptDocument changes, including immediately after a text change.

### `ScriptDocument.ViewportChanged(startLine: int64, endLine: int64)`
- **Summary:** Fires when the displayed line numbers in the editor change.
