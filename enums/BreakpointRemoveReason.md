# Enum.BreakpointRemoveReason

Reason that a breakpoint was removed.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Requested` | 0 |  | Breakpoint removal was requested by user or a command. |
| `ScriptChanged` | 1 |  | Script that contained the breakpoint has changed. |
| `ScriptRemoved` | 2 |  | Script that contained the breakpoint was removed. |

**Valid values:** `Enum.BreakpointRemoveReason.Requested`, `Enum.BreakpointRemoveReason.ScriptChanged`, `Enum.BreakpointRemoveReason.ScriptRemoved`
