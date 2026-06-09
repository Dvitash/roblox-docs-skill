# Enum.ActivePayerStatus

Describes a player's payer status bucket for the current experience.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Unknown` | 0 |  | Segment data is unavailable. |
| `Never` | 1 |  | The player has not made a qualifying purchase in the experience. |
| `Lapsed` | 2 |  | The player has previously spent in the experience but is not currently an active payer. |
| `Casual50Percent` | 3 |  | The player is in the casual payer bucket for the experience. |
| `Intermediate35Percent` | 4 |  | The player is in the intermediate payer bucket for the experience. |
| `Top15Percent` | 5 |  | The player is in the top payer bucket for the experience. |

**Valid values:** `Enum.ActivePayerStatus.Unknown`, `Enum.ActivePayerStatus.Never`, `Enum.ActivePayerStatus.Lapsed`, `Enum.ActivePayerStatus.Casual50Percent`, `Enum.ActivePayerStatus.Intermediate35Percent`, `Enum.ActivePayerStatus.Top15Percent`
