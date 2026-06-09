# Enum.AdEventType

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `VideoLoaded` | 0 | Deprecated |  |
| `VideoRemoved` | 1 | Deprecated |  |
| `UserCompletedVideo` | 2 | Deprecated |  |
| `RewardedAdLoaded` | 3 |  | The event is fired when a click-to-play video ad is being served. This can be used to communicate and promote the reward to users through the UI or signage. |
| `RewardedAdGrant` | 4 |  | The event is fired when a user has watched the click-to-play video ad for a certain time. This can be used to grant the player a reward such as an in-game item or in-game currency. The `RewardedAdGrant` enum will only be triggered once per ad rotation. |
| `RewardedAdUnloaded` | 5 |  | The event is fired when a click-to-play video ad is rotated out. This can be used to remove any UI or signage that is promoting the reward. |

**Valid values:** `Enum.AdEventType.VideoLoaded`, `Enum.AdEventType.VideoRemoved`, `Enum.AdEventType.UserCompletedVideo`, `Enum.AdEventType.RewardedAdLoaded`, `Enum.AdEventType.RewardedAdGrant`, `Enum.AdEventType.RewardedAdUnloaded`
