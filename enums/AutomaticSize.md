# Enum.AutomaticSize

UI objects with `Class.GuiObject.AutomaticSize|AutomaticSize` enabled will increase in size up to maximum size allowed by the parent (if there is one) and no smaller than the `Class.GuiObject.Size|Size` property bounds.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `None` | 0 |  | Default sizing behavior. |
| `X` | 1 |  | Automatically resize element along the **X** axis to fit child contents. |
| `Y` | 2 |  | Automatically resize element along the **Y** axis to fit child contents. Text objects will only resize along the **Y** axis if their `TextWrapped` property is enabled. |
| `XY` | 3 |  | Automatically resize element along the **X** and **Y** axes to fit child contents. |

**Valid values:** `Enum.AutomaticSize.None`, `Enum.AutomaticSize.X`, `Enum.AutomaticSize.Y`, `Enum.AutomaticSize.XY`
