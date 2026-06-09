# ChangeHistoryService

**Superclass:** [Instance](Instance.md)

The `ChangeHistoryService` class is a method that plugins use to communicate how to undo and redo changes in the experience. It is required by plugins to tell Studio how to handle user-made changes.

## Tags
- NotCreatable
- Service

## Methods
### `ChangeHistoryService:FinishRecording(identifier: string, operation: FinishRecordingOperation, finalOptions: Dictionary?) -> ()`
- **Summary:** Communicates to Studio that the identified recording is finished and to take the final operation to complete the recording.

### `ChangeHistoryService:GetCanRedo() -> Tuple`
- **Summary:** Returns whether there are actions that can be redone, and, if there are, returns the last of them.

### `ChangeHistoryService:GetCanUndo() -> Tuple`
- **Summary:** Returns whether there are actions that can be undone, and, if there are, returns the last of them.

### `ChangeHistoryService:IsRecordingInProgress(identifier: string?) -> boolean`

### `ChangeHistoryService:Redo() -> ()`
- **Summary:** Executes the last action that was undone.

### `ChangeHistoryService:ResetWaypoints() -> ()`
- **Summary:** Clears the history, causing all undo/redo waypoints to be removed.

### `ChangeHistoryService:SetEnabled(state: boolean) -> ()`
- **Summary:** Sets whether or not the ChangeHistoryService is enabled.

### `ChangeHistoryService:SetWaypoint(name: string) -> ()`
- **Summary:** Sets a new waypoint which can be used as an undo or redo point.

### `ChangeHistoryService:TryBeginRecording(name: string, displayName: string?) -> string?`
- **Summary:** Begins tracking changes made to the data model into a recording.

### `ChangeHistoryService:Undo() -> ()`
- **Summary:** Undos the last action taken, for which there exists a waypoint.

## Events
### `ChangeHistoryService.OnRecordingFinished(name: string, displayName: string?, identifier: string?, operation: FinishRecordingOperation, finalOptions: Dictionary?)`
- **Summary:** Fired when the user completes an action. Parameters come from `Class.ChangeHistoryService:TryBeginRecording()|TryBeginRecording()` and `Class.ChangeHistoryService:FinishRecording()|FinishRecording()`.

### `ChangeHistoryService.OnRecordingStarted(name: string, displayName: string?)`
- **Summary:** Fired when the user begins an action. Parameters come from `Class.ChangeHistoryService:TryBeginRecording()|TryBeginRecording()`.

### `ChangeHistoryService.OnRedo(waypoint: string)`
- **Summary:** Fired when the user reverses the undo command. Waypoint describes the type action that has been redone.

### `ChangeHistoryService.OnUndo(waypoint: string)`
- **Summary:** Fired when the user undoes an action in studio. Waypoint describes the type action that has been undone.
