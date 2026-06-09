# Enum.ReplicateInstanceDestroySetting

Controls how `Instance:Destroy()` calls are replicated from server to clients.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Default` | 0 |  | Uses the engine-default instance destroy replication behavior. |
| `Disabled` | 1 |  | Uses legacy instance destroy replication behavior. |
| `Enabled` | 2 |  | Uses improved instance destroy replication behavior. |

**Valid values:** `Enum.ReplicateInstanceDestroySetting.Default`, `Enum.ReplicateInstanceDestroySetting.Disabled`, `Enum.ReplicateInstanceDestroySetting.Enabled`
