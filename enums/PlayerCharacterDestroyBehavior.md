# Enum.PlayerCharacterDestroyBehavior

Controls destruction behavior when a player character is removed.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Default` | 0 |  | Uses the engine-default behavior. |
| `Disabled` | 1 |  | Automatic `Destroy()` calls on character replacement and player removal are disabled. |
| `Enabled` | 2 |  | The engine automatically calls `Destroy()` on old characters when they are replaced (for example, on respawn) and on `Player` objects when players leave. |

**Valid values:** `Enum.PlayerCharacterDestroyBehavior.Default`, `Enum.PlayerCharacterDestroyBehavior.Disabled`, `Enum.PlayerCharacterDestroyBehavior.Enabled`
