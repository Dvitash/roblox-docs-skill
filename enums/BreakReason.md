# Enum.BreakReason

Reason for the breakpoint hit.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Other` | 0 |  | Pausing for a reason not covered by other values, for example if the user hit "Pause" button. |
| `Error` | 1 |  | Pausing on error hit in the code. |
| `SpecialBreakpoint` | 2 |  | Pausing on an internal breakpoint set by debugger command: e.g. step over, step into, step out of. |
| `UserBreakpoint` | 3 |  | Pausing on a user breakpoint. |

**Valid values:** `Enum.BreakReason.Other`, `Enum.BreakReason.Error`, `Enum.BreakReason.SpecialBreakpoint`, `Enum.BreakReason.UserBreakpoint`
