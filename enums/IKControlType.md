# Enum.IKControlType

Used on `Class.IKControl` to specify their `Class.IKControl.Type|Type`, to change their behavior.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Transform` | 0 |  | It is a full 6-DoF constraint. Aligns the `Class.IKControl.EndEffector\|EndEffector` `Datatype.CFrame` to that of the `Class.IKControl.Target\|Target`. It is the default value. |
| `Position` | 1 |  | Aligns the `Class.IKControl.EndEffector\|EndEffector` position to that of the `Class.IKControl.Target\|Target` . |
| `Rotation` | 2 |  | Aligns the `Class.IKControl.EndEffector\|EndEffector` rotation to that of the `Class.IKControl.Target\|Target`. |
| `LookAt` | 3 |  | Moves and orients the whole chain to make the forward axis on the `Class.IKControl.EndEffector\|EndEffector` point at a position in the world specified by `Class.IKControl.Target\|Target`. |

**Valid values:** `Enum.IKControlType.Transform`, `Enum.IKControlType.Position`, `Enum.IKControlType.Rotation`, `Enum.IKControlType.LookAt`
