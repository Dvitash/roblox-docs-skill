# Enum.InstanceFileSyncStatus

Describes the file sync status of an Instance.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `NotSynced` | 0 |  | The `Class.Instance` is not being synced or errored. |
| `Errored` | 1 |  | The `Class.Instance` is a sync root that has errored and stopped syncing. |
| `SyncedAsRoot` | 2 |  | The `Class.Instance` is being synced as the root of a sync tree. |
| `SyncedAsDescendant` | 3 |  | The `Class.Instance` is being synced because it is a descendant of a sync root. |
| `AncestorErrored` | 4 |  | The `Class.Instance` is not currently being synced because the root of its sync tree is `Errored`. |

**Valid values:** `Enum.InstanceFileSyncStatus.NotSynced`, `Enum.InstanceFileSyncStatus.Errored`, `Enum.InstanceFileSyncStatus.SyncedAsRoot`, `Enum.InstanceFileSyncStatus.SyncedAsDescendant`, `Enum.InstanceFileSyncStatus.AncestorErrored`
