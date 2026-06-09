# Enum.LoadCharacterLayeredClothing

Indicates whether characters spawning into an experience will have layered clothing accessories equipped on them.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Default` | 0 |  | The behavior of the default setting is not constant. It can mean Disabled or Enabled depending on what the global back-end flag settings are currently. |
| `Disabled` | 1 |  | This means layered clothing will not be equipped on characters in the experience. |
| `Enabled` | 2 |  | This means layered clothing will be equipped on characters in the experience (Although `Enum.MeshPartHeadsAndAccessories` also need to be enabled for the experience). |

**Valid values:** `Enum.LoadCharacterLayeredClothing.Default`, `Enum.LoadCharacterLayeredClothing.Disabled`, `Enum.LoadCharacterLayeredClothing.Enabled`
