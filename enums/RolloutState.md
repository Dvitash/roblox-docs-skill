# Enum.RolloutState

A three-phase rollout state used to opt in or out of engine features.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Default` | 0 |  | Uses the engine-wide rollout default, which changes as the feature progresses through its rollout phases. |
| `Disabled` | 1 |  | Opts out of the feature regardless of the engine-wide rollout phase. |
| `Enabled` | 2 |  | Opts in to the feature regardless of the engine-wide rollout phase. |

**Valid values:** `Enum.RolloutState.Default`, `Enum.RolloutState.Disabled`, `Enum.RolloutState.Enabled`
