# Enum.ThreadPoolConfig

Thread pooling scheme for the task scheduler.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Auto` | 0 |  | Let task scheduler make a decision internally. |
| `Threads1` | 1 |  | Utilize 1 worker thread, ignore the physical CPU core count. |
| `Threads2` | 2 |  | Utilize 2 worker threads, ignore the physical CPU core count. |
| `Threads3` | 3 |  | Utilize 3 worker threads, ignore the physical CPU core count. |
| `Threads4` | 4 |  | Utilize 4 worker threads, ignore the physical CPU core count. |
| `Threads8` | 8 |  | Utilize 8 worker threads, ignore the physical CPU core count. |
| `Threads16` | 16 |  | Utilize 16 worker threads, ignore the physical CPU core count. |
| `PerCore1` | 101 |  | Utilize 1 worker thread per available physical CPU core. |
| `PerCore2` | 102 |  | Utilize 2 worker threads per available physical CPU core. |
| `PerCore3` | 103 |  | Utilize 3 worker threads per available physical CPU core. |
| `PerCore4` | 104 |  | Utilize 4 worker threads per available physical CPU core. |

**Valid values:** `Enum.ThreadPoolConfig.Auto`, `Enum.ThreadPoolConfig.Threads1`, `Enum.ThreadPoolConfig.Threads2`, `Enum.ThreadPoolConfig.Threads3`, `Enum.ThreadPoolConfig.Threads4`, `Enum.ThreadPoolConfig.Threads8`, `Enum.ThreadPoolConfig.Threads16`, `Enum.ThreadPoolConfig.PerCore1`, `Enum.ThreadPoolConfig.PerCore2`, `Enum.ThreadPoolConfig.PerCore3`, `Enum.ThreadPoolConfig.PerCore4`
