# Enum.StreamingPauseMode

Determines how a client should handle not having enough content streamed in to continue playing properly.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Default` | 0 | Deprecated | Default behavior (subject to change). |
| `Disabled` | 1 | Deprecated | No change to gameplay due to streaming region availability. |
| `ClientPhysicsPause` | 2 | Deprecated | Client owned physics is paused. |

**Valid values:** `Enum.StreamingPauseMode.Default`, `Enum.StreamingPauseMode.Disabled`, `Enum.StreamingPauseMode.ClientPhysicsPause`
