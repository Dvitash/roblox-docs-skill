# Enum.UIDragSpeedAxisMapping

Used with `Class.UIDragDetector.UIDragSpeedAxisMapping` to determine the **X**/**Y** dimension dragging speeds.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `XY` | 0 |  | Default setting for a detector's `Class.UIDragDetector.UIDragSpeedAxisMapping\|UIDragSpeedAxisMapping` where the **X** and **Y** axis speeds are based off the **X** and **Y** `Datatype.UDim.Scale\|Scale`/`Datatype.UDim.Offset\|Offset` values respectively. |
| `XX` | 1 |  | Both the **X** and **Y** axis speeds are based off the **X** axis for `Datatype.UDim.Scale\|Scale`, while the `Datatype.UDim.Offset\|Offset` values still apply to their respective axis. |
| `YY` | 2 |  | Both the **X** and **Y** axis speeds are based off the **Y** axis for `Datatype.UDim.Scale\|Scale`, while the `Datatype.UDim.Offset\|Offset` values still apply to their respective axis. |

**Valid values:** `Enum.UIDragSpeedAxisMapping.XY`, `Enum.UIDragSpeedAxisMapping.XX`, `Enum.UIDragSpeedAxisMapping.YY`
