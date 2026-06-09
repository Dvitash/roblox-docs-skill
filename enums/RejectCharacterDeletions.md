# Enum.RejectCharacterDeletions

Controls whether the server rejects client attempts to delete player characters.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Default` | 0 |  | Uses the engine-default behavior (currently equivalent to `Enabled`). |
| `Disabled` | 1 |  | The server does not reject character deletion requests from clients. |
| `Enabled` | 2 |  | The server rejects client attempts to delete player characters. |

**Valid values:** `Enum.RejectCharacterDeletions.Default`, `Enum.RejectCharacterDeletions.Disabled`, `Enum.RejectCharacterDeletions.Enabled`
