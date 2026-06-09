# Enum.AnalyticsProgressionStatus

This enum is used as an argument in `Class.AnalyticsService:FirePlayerProgressionEvent()` to describe the status of progression.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Default` | 0 |  | Default status. Used for an undefined status. |
| `Begin` | 1 |  | Indicates the beginning of progression. |
| `Complete` | 2 |  | Indicates the progression completed. |
| `Abandon` | 3 |  | Indicates the progression abandoned. |
| `Fail` | 4 |  | Indicates the progression failed. |

**Valid values:** `Enum.AnalyticsProgressionStatus.Default`, `Enum.AnalyticsProgressionStatus.Begin`, `Enum.AnalyticsProgressionStatus.Complete`, `Enum.AnalyticsProgressionStatus.Abandon`, `Enum.AnalyticsProgressionStatus.Fail`
