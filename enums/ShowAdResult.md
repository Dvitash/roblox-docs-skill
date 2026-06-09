# Enum.ShowAdResult

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `ShowCompleted` | 1 |  | The ad was successfully shown to completion. |
| `AdNotReady` | 2 |  | You are trying to show a full-screen ad before the ad has fully loaded. You might have failed to properly fetch the ad, or the ad might have expired. |
| `AdAlreadyShowing` | 3 |  | You are trying to show a full-screen ad while another full-screen ad is already playing. |
| `InternalError` | 4 |  | An unspecified internal error occurred. Try showing the ad again. |
| `ShowInterrupted` | 5 |  | The ad view of the user has been interrupted. The user might have closed the ad view or left the experience, and should not receive a reward. |
| `InsufficientMemory` | 6 |  |  |

**Valid values:** `Enum.ShowAdResult.ShowCompleted`, `Enum.ShowAdResult.AdNotReady`, `Enum.ShowAdResult.AdAlreadyShowing`, `Enum.ShowAdResult.InternalError`, `Enum.ShowAdResult.ShowInterrupted`, `Enum.ShowAdResult.InsufficientMemory`
