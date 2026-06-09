# Enum.PredictionStatus

Enum used with `Class.RunService:GetPredictionStatus()` to check the status of a specific instance.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Authoritative` | 0 |  | This instance is authoritative. |
| `Predicted` | 1 |  | This instance is being predicted. |
| `None` | 2 |  | The instance will not be resimulated; classic simulation rules apply instead. |

**Valid values:** `Enum.PredictionStatus.Authoritative`, `Enum.PredictionStatus.Predicted`, `Enum.PredictionStatus.None`
