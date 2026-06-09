# Enum.DebuggerPauseReason

Reason that the DataModel was paused.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Unknown` | 0 |  | Pausing for a reason not covered by other values. |
| `Requested` | 1 |  | Pause was requested by user. |
| `Breakpoint` | 2 |  | Pausing on a user breakpoint. |
| `Exception` | 3 |  | Pausing on error hit in the code. |
| `SingleStep` | 4 |  | Pausing on an internal breakpoint set by debugger command: e.g. step over, step into, step out of. |
| `Entrypoint` | 5 |  | Pausing at the entry on the script. |

**Valid values:** `Enum.DebuggerPauseReason.Unknown`, `Enum.DebuggerPauseReason.Requested`, `Enum.DebuggerPauseReason.Breakpoint`, `Enum.DebuggerPauseReason.Exception`, `Enum.DebuggerPauseReason.SingleStep`, `Enum.DebuggerPauseReason.Entrypoint`
