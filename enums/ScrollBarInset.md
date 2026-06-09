# Enum.ScrollBarInset

This enum is used with `Class.ScrollingFrame.HorizontalScrollBarInset` and `Class.ScrollingFrame.VerticalScrollBarInset` to indicate whether the canvas should be inset by `Class.ScrollingFrame.ScrollBarThickness|ScrollBarThickness` for the respective scroll bar.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `None` | 0 |  | The canvas will never be inset for the respective scroll bar. |
| `ScrollBar` | 1 |  | The canvas will only be inset if the respective scroll bar is showing. |
| `Always` | 2 |  | The canvas will always be inset for the respective scroll bar, regardless of whether that scroll bar is showing. |

**Valid values:** `Enum.ScrollBarInset.None`, `Enum.ScrollBarInset.ScrollBar`, `Enum.ScrollBarInset.Always`
