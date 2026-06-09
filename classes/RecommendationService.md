# RecommendationService

**Superclass:** [Instance](Instance.md)

The `RecommendationService` class provides an interface for managing and displaying personalized content recommendations, including creating, retrieving, updating, and deleting items, along with logging user interactions.

## Tags
- NotCreatable
- Service

## Methods
### `RecommendationService:GenerateItemListAsync(generateRecommendationItemListRequest: Dictionary) -> [RecommendationPages](RecommendationPages.md)`
- **Tags:** Yields

### `RecommendationService:GetRecommendationItemAsync(itemId: string) -> Dictionary`
- **Tags:** Yields

### `RecommendationService:LogActionEvent(actionType: RecommendationActionType, itemId: string, tracingId: string, actionEventDetails: Dictionary) -> ()`

### `RecommendationService:LogImpressionEvent(impressionType: RecommendationImpressionType, itemId: string, tracingId: string, impressionEventDetails: Dictionary) -> ()`

### `RecommendationService:LogPreferenceEvent(preferenceType: RecommendationPreferenceType, targetType: RecommendationPreferenceTargetType, targetId: string, tracingId: string, itemId: string) -> ()`

### `RecommendationService:RegisterItemAsync(player: [Player](Player.md), registerRecommendationItemsRequest: Dictionary) -> Dictionary`
- **Tags:** Yields

### `RecommendationService:RemoveItemAsync(itemId: string) -> ()`
- **Tags:** Yields

### `RecommendationService:UpdateItemAsync(updateRecommendationItemRequest: Dictionary) -> ()`
- **Tags:** Yields
