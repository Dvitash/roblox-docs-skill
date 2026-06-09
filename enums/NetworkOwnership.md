# Enum.NetworkOwnership

Defines how simulation authority is determined for the Network Ownership Unit/Mechanism this part is attached to.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Automatic` | 0 |  | Network ownership is determined automatically by the server. |
| `Manual` | 1 |  | Network ownership is set manually by the developer. |
| `OnContact` | 2 |  | The first player to touch a part is given ownership of that part for the server (network). Ownership will not change if another player touches that part unless network ownership has been released by the owner. |

**Valid values:** `Enum.NetworkOwnership.Automatic`, `Enum.NetworkOwnership.Manual`, `Enum.NetworkOwnership.OnContact`
