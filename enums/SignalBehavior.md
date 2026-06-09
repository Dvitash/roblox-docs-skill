# Enum.SignalBehavior

Determines when the engine resumes event handlers.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Default` | 0 |  | The default behavior; currently equivalent to `Immediate` but this will eventually change to `Deferred`. |
| `Immediate` | 1 |  | Event handlers are resumed immediately when the event occurs. |
| `Deferred` | 2 |  | All events are deferred and their handlers resumed at specific resumptions points each frame. |
| `AncestryDeferred` | 3 |  | Equivalent to `Deferred` but only for events triggered by changes in ancestry. |

**Valid values:** `Enum.SignalBehavior.Default`, `Enum.SignalBehavior.Immediate`, `Enum.SignalBehavior.Deferred`, `Enum.SignalBehavior.AncestryDeferred`
