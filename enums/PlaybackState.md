# Enum.PlaybackState

Describes the current state of a `Class.Tween` in its `Class.Tween.PlaybackState` property.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Begin` | 0 |  | The tween has been created, but has yet to be played. After exiting this state, the tween never enters it again. |
| `Delayed` | 1 |  | The tween is waiting for the duration specified in its `Datatype.TweenInfo.DelayTime`. After the delay elapses, the tween plays. |
| `Playing` | 2 |  | The tween is currently in progress. |
| `Paused` | 3 |  | The tween is paused in the middle of playing. |
| `Completed` | 4 |  | The tween completed successfully. |
| `Cancelled` | 5 |  | The tween was cancelled before completion. |

**Valid values:** `Enum.PlaybackState.Begin`, `Enum.PlaybackState.Delayed`, `Enum.PlaybackState.Playing`, `Enum.PlaybackState.Paused`, `Enum.PlaybackState.Completed`, `Enum.PlaybackState.Cancelled`
