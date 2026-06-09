# Enum.SelectionBehavior

Customization options for gamepad selection when `Class.GuiBase2d.SelectionGroup` is true.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Escape` | 0 |  | Prioritizes GuiObjects within the same SelectionGroup but allows the selection to move to other outside GuiObjects if no suitable button is found. |
| `Stop` | 1 |  | Constrains gamepad selection to the SelectionGroup. |

**Valid values:** `Enum.SelectionBehavior.Escape`, `Enum.SelectionBehavior.Stop`
