# AdService

**Superclass:** [Instance](Instance.md)

The AdService class is a class for displaying mobile video ads as a form of monetization, allowing users to implement rewarded video ads within their experiences.

## Tags
- NotCreatable
- Service

## Methods
### `AdService:CreateAdRewardFromDevProductId(devProductId: int64) -> AdReward`
- **Summary:** Creates a reward to give users who watch an entire video ad.

### `AdService:GetAdAvailabilityNowAsync(adFormat: AdFormat) -> Dictionary`
- **Tags:** Yields
- **Summary:** Checks if a video ad is available to be played to the current user inside the experience.

### `AdService:GetCampaignEligibilityAsync(campaignId: string, player: [Player](Player.md)?) -> Dictionary`
- **Tags:** Yields

### `AdService:RegisterAdOpportunityAsync(instance: [Instance](Instance.md), placementId: int64?) -> ()`
- **Tags:** Yields
- **Summary:** Tracks how many times a user had the chance to watch a video ad and the rate at which they actually watched the ad.

### `AdService:RegisterDisclosureButton(disclosureButton: [GuiButton](GuiButton.md), adIntegrationPlacementId: string) -> ()`

### `AdService:ShowRewardedVideoAdAsync(player: [Player](Player.md), reward: AdReward, placementId: int64?) -> ShowAdResult`
- **Tags:** Yields
- **Summary:** Plays the video ad to the current user inside the experience.

### `AdService:ShowVideoAd() -> ()`
- **Tags:** Deprecated
- **Summary:** Show mobile video advertisements.

### `AdService:UnregisterAdOpportunity(instance: [Instance](Instance.md)) -> ()`

## Events
### `AdService.VideoAdClosed(adShown: boolean)`
- **Tags:** Deprecated
- **Summary:** Fires when an `Class.AdService` video closes.
