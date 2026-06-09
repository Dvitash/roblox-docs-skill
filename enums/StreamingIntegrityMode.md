# Enum.StreamingIntegrityMode

Determines how a user's client should handle not having enough content streamed in.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Default` | 0 |  | Default behavior (subject to change). |
| `Disabled` | 1 |  | Simulation of the replication focus is never paused, regardless of the amount of content streamed in on the client. |
| `MinimumRadiusPause` | 2 |  | All client-side simulation is paused when content is not streamed in up to the minimum radius. |
| `PauseOutsideLoadedArea` | 3 |  | Simulation of the replication focus is paused when any part of its bounding box is not in a streamed-in area. |

**Valid values:** `Enum.StreamingIntegrityMode.Default`, `Enum.StreamingIntegrityMode.Disabled`, `Enum.StreamingIntegrityMode.MinimumRadiusPause`, `Enum.StreamingIntegrityMode.PauseOutsideLoadedArea`
