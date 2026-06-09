# Enum.FinishRecordingOperation

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Cancel` | 0 |  | Cancels the recording, automatically undoing any work in progress. |
| `Commit` | 1 |  | Commits the recorded work. |
| `Append` | 2 |  | Commits the recorded work and merges with the previous recording if possible. |

**Valid values:** `Enum.FinishRecordingOperation.Cancel`, `Enum.FinishRecordingOperation.Commit`, `Enum.FinishRecordingOperation.Append`
