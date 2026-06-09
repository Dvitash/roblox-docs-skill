# Enum.FrameStyle

Used to set the style of a `Class.Frame`.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Custom` | 0 |  | Uses the frame's `Class.GuiObject.BackgroundColor3`, `Class.GuiObject.BorderColor3`, and `Class.GuiObject.BackgroundTransparency` properties to determine the frame's appearance. It has no padding; elements with the position `Datatype.UDim2.new(0, 0, 0, 0)` will appear at the frame's top-left corner. |
| `ChatBlue` | 1 |  | Causes the frame to appear similar to a `Class.Dialog` with its `Class.Dialog.Tone\|Tone` property set to `Enum.DialogTone.Neutral`. Like **ChatGreen** and **ChatRed**, this has a padding of fifteen pixels on all sides. |
| `RobloxSquare` | 2 |  | Causes the frame to appear as a translucent dark gray rectangle with a padding of five pixels on all sides. |
| `RobloxRound` | 3 |  | Causes the frame to appear as a translucent dark gray rectangle with rounded edges. Like **RobloxSquare**, this has a padding of five pixels on all sides. |
| `ChatGreen` | 4 |  | Causes the frame to appear similar to a `Class.Dialog` with its `Class.Dialog.Tone\|Tone` property set to `Enum.DialogTone.Friendly`. Like **ChatBlue** and **ChatRed**, this has a padding of fifteen pixels on all sides. |
| `ChatRed` | 5 |  | Causes the frame to appear similar to a `Class.Dialog` with its `Class.Dialog.Tone\|Tone` property set to `Enum.DialogTone.Enemy`. Like **ChatBlue** and **ChatGreen**, this has a padding of fifteen pixels on all sides. |
| `DropShadow` | 6 |  | Causes the frame to appear as a translucent gray rectangle with blurred sides. The blur is more apparent on the bottom edge. It has a padding of eight pixels on all sides. |

**Valid values:** `Enum.FrameStyle.Custom`, `Enum.FrameStyle.ChatBlue`, `Enum.FrameStyle.RobloxSquare`, `Enum.FrameStyle.RobloxRound`, `Enum.FrameStyle.ChatGreen`, `Enum.FrameStyle.ChatRed`, `Enum.FrameStyle.DropShadow`
