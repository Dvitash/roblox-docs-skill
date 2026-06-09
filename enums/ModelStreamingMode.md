# Enum.ModelStreamingMode

Controls stream in and out behavior of a model.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Default` | 0 |  | Default behavior (subject to change). |
| `Atomic` | 1 |  | The `Class.Model` and all of its descendants are streamed in/out together. For streaming in, this applies when **any** descendant `Class.BasePart` is eligible for streaming in. For streaming out, this applies when **all** descendant `Class.BasePart\|BaseParts` are eligible for streaming out. |
| `Persistent` | 2 |  | Persistent models are sent as a complete atomic unit soon after the player joins and before the `Class.Workspace.PersistentLoaded` event fires. Persistent models and their descendants are never streamed out. |
| `PersistentPerPlayer` | 3 |  | Behaves as a persistent model for players that have been added using `Class.Model:AddPersistentPlayer()`. For other players, behavior is the same as `Atomic`. You can revert a model from player persistence via `Class.Model:RemovePersistentPlayer()`. |
| `Nonatomic` | 4 |  | When a nonatomic model is streamed, descendants are also sent, except for part descendants. Nonatomic models that are not descendants of parts are sent during experience loading. |

**Valid values:** `Enum.ModelStreamingMode.Default`, `Enum.ModelStreamingMode.Atomic`, `Enum.ModelStreamingMode.Persistent`, `Enum.ModelStreamingMode.PersistentPerPlayer`, `Enum.ModelStreamingMode.Nonatomic`
