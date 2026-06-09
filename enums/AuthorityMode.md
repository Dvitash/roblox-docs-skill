# Enum.AuthorityMode

Enum used with `Class.Workspace.AuthorityMode`.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Server` | 0 |  | Server authority with client side prediction and rollback enabled. |
| `Automatic` | 1 |  | Traditional distributed authority model where, for each instance, the engine decides whether the server or a client should be the authority; `Class.BasePart:SetNetworkOwner()` can be used to influence the decision. |

**Valid values:** `Enum.AuthorityMode.Server`, `Enum.AuthorityMode.Automatic`
