# CommerceService

**Superclass:** [Instance](Instance.md)

This file defines `CommerceService` classes for managing real-world purchases and virtual item benefits, outlining their functionality, inheritance, and usage.

## Tags
- NotCreatable
- Service

## Methods
### `CommerceService:GetCommerceProductInfoAsync(commerceProductId: string) -> Dictionary`
- **Tags:** Yields
- **Summary:** Retrieves information about the commerce products you are selling in experience.

### `CommerceService:PromptCommerceProductPurchase(user: [Player](Player.md), commerceProductId: string) -> ()`
- **Summary:** Prompts a user to purchase a commerce product using the provided `commerceProductId`. Opens a webview that guides the user through the purchasing flow.

### `CommerceService:PromptRealWorldCommerceBrowser(player: [Player](Player.md), url: string) -> ()`

### `CommerceService:UserEligibleForRealWorldCommerceAsync() -> boolean`
- **Tags:** Yields

## Events
### `CommerceService.PromptCommerceProductPurchaseFinished(user: [Player](Player.md), productId: string)`
- **Summary:** Fires when commerce purchase webview has closed - not an indicator that a purchase was successful.
