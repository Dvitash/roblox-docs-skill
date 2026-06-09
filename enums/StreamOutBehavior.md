# Enum.StreamOutBehavior

Determines how content is streamed out from `Class.Player` clients.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Default` | 0 |  | Default behavior (subject to change). |
| `LowMemory` | 1 |  | Only stream out when memory is low. |
| `Opportunistic` | 2 |  | Stream out content that is significantly outside of the current `Class.Workspace.StreamingTargetRadius`. |

**Valid values:** `Enum.StreamOutBehavior.Default`, `Enum.StreamOutBehavior.LowMemory`, `Enum.StreamOutBehavior.Opportunistic`
