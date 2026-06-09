# AnalyticsService

**Superclass:** [Instance](Instance.md)

The `AnalyticsService` class provides methods for tracking user interaction with experiences, including player progression, in-experience economy, funnels, and custom events.

## Tags
- NotCreatable
- Service
- NotReplicated

## Properties
### `AnalyticsService.ApiKey`
- **Type:** `string`
- **Tags:** Deprecated
- **Summary:** PlayFab API key. Must be set in order to use `Class.AnalyticsService:FireEvent()|FireEvent`.

## Methods
### `AnalyticsService:FireCustomEvent(player: [Instance](Instance.md), eventCategory: string, customData: Variant) -> ()`
- **Tags:** Deprecated
- **Summary:** Fires a custom event with a custom event name and data.

### `AnalyticsService:FireEvent(category: string, value: Variant) -> ()`
- **Tags:** Deprecated
- **Summary:** Report a custom event to PlayFab.

### `AnalyticsService:FireInGameEconomyEvent(player: [Instance](Instance.md), itemName: string, economyAction: AnalyticsEconomyAction, itemCategory: string, amount: int, currency: string, location: Variant, customData: Variant) -> ()`
- **Tags:** Deprecated
- **Summary:** Fire an event used to track player actions pertaining to the in-game economy.

### `AnalyticsService:FireLogEvent(player: [Instance](Instance.md), logLevel: AnalyticsLogLevel, message: string, debugInfo: Variant, customData: Variant) -> ()`
- **Tags:** Deprecated
- **Summary:** Fire a log event used to track errors and warnings experienced by players.

### `AnalyticsService:FirePlayerProgressionEvent(player: [Instance](Instance.md), category: string, progressionStatus: AnalyticsProgressionStatus, location: Variant, statistics: Variant, customData: Variant) -> ()`
- **Tags:** Deprecated
- **Summary:** Fire an event used to track player progression through the game.

### `AnalyticsService:GetPlayerSegmentsAsync(player: [Player](Player.md)) -> Dictionary`
- **Tags:** Yields
- **Summary:** Returns coarse player segment buckets for the current experience.

### `AnalyticsService:LogCustomEvent(player: [Player](Player.md), eventName: string, value: double, customFields: Dictionary) -> ()`
- **Summary:** Logs an event used to track custom metrics of a user in experience.

### `AnalyticsService:LogEconomyEvent(player: [Player](Player.md), flowType: AnalyticsEconomyFlowType, currencyType: string, amount: float, endingBalance: float, transactionType: string, itemSku: string, customFields: Dictionary) -> ()`
- **Summary:** Logs an event used to track player actions related in experience.

### `AnalyticsService:LogFunnelStepEvent(player: [Player](Player.md), funnelName: string, funnelSessionId: string, step: int, stepName: string, customFields: Dictionary) -> ()`
- **Summary:** Logs an event used to track user actions stepping through a pre-planned funnel.

### `AnalyticsService:LogOnboardingFunnelStepEvent(player: [Player](Player.md), step: int, stepName: string, customFields: Dictionary) -> ()`
- **Summary:** Logs an event used to track user actions stepping through an onboarding funnel.

### `AnalyticsService:LogProgressionCompleteEvent(player: [Player](Player.md), progressionPathName: string, level: int, levelName: string, customFields: Dictionary) -> ()`
- **Summary:** Logs an event for when a user has completed a level attempt.

### `AnalyticsService:LogProgressionEvent(player: [Player](Player.md), progressionPathName: string, status: AnalyticsProgressionType, level: int, levelName: string, customFields: Dictionary) -> ()`
- **Summary:** Logs an event for when a user has started, completed, or failed a level attempt.

### `AnalyticsService:LogProgressionFailEvent(player: [Player](Player.md), progressionPathName: string, level: int, levelName: string, customFields: Dictionary) -> ()`
- **Summary:** Logs an event for when a user has failed a level attempt.

### `AnalyticsService:LogProgressionStartEvent(player: [Player](Player.md), progressionPathName: string, level: int, levelName: string, customFields: Dictionary) -> ()`
- **Summary:** Logs an event for when a user has started a level attempt.
