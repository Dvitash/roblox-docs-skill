# Enum.BorderMode

Used by `Class.GuiObject.BorderMode` to determine where borders are placed.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Outline` | 0 |  | As `Class.GuiObject.BorderSizePixel` increases, the border grows outward. The dimensions of the GuiObject's contents do not change. |
| `Middle` | 1 |  | As `Class.GuiObject.BorderSizePixel` increases, the border grows evenly inward and outward. The dimensions of the GuiObject's contents are reduced at a 1:1 ratio. |
| `Inset` | 2 |  | As `Class.GuiObject.BorderSizePixel` increases, the border grows evenly inward only. The dimensions of the GuiObject's contents are reduced at a 1:2 ratio. |

**Valid values:** `Enum.BorderMode.Outline`, `Enum.BorderMode.Middle`, `Enum.BorderMode.Inset`
