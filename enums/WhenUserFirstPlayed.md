# Enum.WhenUserFirstPlayed

Describes when a player first played the current experience, represented as a bucket.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Unknown` | 0 |  | Segment data is unavailable. |
| `Days0To30` | 1 |  | The player first played the experience within the last 30 days. |
| `Days31To90` | 2 |  | The player first played the experience between 31 and 90 days ago. |
| `Days91To180` | 3 |  | The player first played the experience between 91 and 180 days ago. |
| `Days181To365` | 4 |  | The player first played the experience between 181 and 365 days ago. |
| `Days366Plus` | 5 |  | The player first played the experience more than 365 days ago. |

**Valid values:** `Enum.WhenUserFirstPlayed.Unknown`, `Enum.WhenUserFirstPlayed.Days0To30`, `Enum.WhenUserFirstPlayed.Days31To90`, `Enum.WhenUserFirstPlayed.Days91To180`, `Enum.WhenUserFirstPlayed.Days181To365`, `Enum.WhenUserFirstPlayed.Days366Plus`
