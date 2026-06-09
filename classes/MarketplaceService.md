# MarketplaceService

**Superclass:** [Instance](Instance.md)

The `Class.MarketplaceService` manages in-experience transactions, handling receipt processing and passing player/bundle ownership data to `Class.DataStoreService`.

## Tags
- NotCreatable
- Service

## Methods
### `MarketplaceService:BindReceiptHandler(transactionType: ReceiptType, handler: Function, filter: Array?) -> RBXScriptConnection`
- **Summary:** Registers a callback to process receipts of a specific type.

### `MarketplaceService:GetDeveloperProductsAsync() -> [Instance](Instance.md)`
- **Tags:** Yields
- **Summary:** Returns a `Class.Pages` object which contains information for all of the current experience's developer products.

### `MarketplaceService:GetProductInfo(assetId: int64, infoType: InfoType) -> Dictionary`
- **Tags:** Yields, Deprecated
- **Summary:** Returns the product information of an asset using its asset ID.

### `MarketplaceService:GetProductInfoAsync(assetId: int64, infoType: InfoType) -> Dictionary`
- **Tags:** Yields
- **Summary:** Returns the product information of an asset using its asset ID.

### `MarketplaceService:GetRobloxSubscriptionDetailsAsync(user: [Player](Player.md)) -> Dictionary`
- **Tags:** Yields
- **Summary:** Returns the subscription details for the given user for the Roblox Subscription ecosystem.

### `MarketplaceService:GetSubscriptionProductInfoAsync(subscriptionId: string) -> Dictionary`
- **Tags:** Yields
- **Summary:** Returns the product information of a subscription for the given `subscriptionId`.

### `MarketplaceService:GetUsersPriceLevelsAsync(userIds: Array) -> Array`
- **Tags:** Yields
- **Summary:** Returns the regionalized price levels of users, representing the recommended price for an item in each user's regional market.

### `MarketplaceService:GetUserSubscriptionDetailsAsync(user: [Player](Player.md), subscriptionId: string) -> Dictionary`
- **Tags:** Yields
- **Summary:** Returns a table that contains the details of the user's subscription for a given `subscriptionId`.

### `MarketplaceService:GetUserSubscriptionPaymentHistoryAsync(user: [Player](Player.md), subscriptionId: string) -> Array`
- **Tags:** Yields
- **Summary:** Returns an `Library.table|Array` that contains up to one year of the user's subscription payment history for the given `subscriptionId`.

### `MarketplaceService:GetUserSubscriptionStatusAsync(user: [Player](Player.md), subscriptionId: string) -> Dictionary`
- **Tags:** Yields
- **Summary:** Returns a `Library.table` that contains the subscription status of the user for the given `subscriptionId`.

### `MarketplaceService:PlayerOwnsAsset(player: [Instance](Instance.md), assetId: int64) -> boolean`
- **Tags:** Yields, Deprecated
- **Summary:** Returns whether the given user has the given asset.

### `MarketplaceService:PlayerOwnsAssetAsync(player: [Instance](Instance.md), assetId: int64) -> boolean`
- **Tags:** Yields
- **Summary:** Returns whether the given user has the given asset.

### `MarketplaceService:PlayerOwnsBundle(player: [Player](Player.md), bundleId: int64) -> boolean`
- **Tags:** Yields, Deprecated
- **Summary:** Returns whether the given player owns the given bundle.

### `MarketplaceService:PlayerOwnsBundleAsync(player: [Player](Player.md), bundleId: int64) -> boolean`
- **Tags:** Yields
- **Summary:** Returns whether the given player owns the given bundle.

### `MarketplaceService:PromptBulkPurchase(player: [Player](Player.md), lineItems: Array, options: Dictionary) -> ()`
- **Summary:** Prompts a user to purchase multiple avatar items with the given `assetId` or `bundleId`.

### `MarketplaceService:PromptBundlePurchase(player: [Instance](Instance.md), bundleId: int64) -> ()`
- **Summary:** Prompts a user to purchase a bundle with the given `bundleId`.

### `MarketplaceService:PromptCancelSubscription(user: [Player](Player.md), subscriptionId: string) -> ()`
- **Summary:** Prompts a user to cancel a subscription for the given `subscriptionId`.

### `MarketplaceService:PromptGamePassPurchase(player: [Instance](Instance.md), gamePassId: int64) -> ()`
- **Summary:** Prompts a user to purchase a pass with the given `gamePassId`.

### `MarketplaceService:PromptPremiumPurchase(player: [Instance](Instance.md)) -> ()`
- **Tags:** Deprecated
- **Summary:** Prompts a user to purchase Roblox Premium.

### `MarketplaceService:PromptProductPurchase(player: [Instance](Instance.md), productId: int64, equipIfPurchased: boolean, currencyType: CurrencyType) -> ()`
- **Summary:** Prompts a user to purchase a developer product with the given `productId`.

### `MarketplaceService:PromptPurchase(player: [Instance](Instance.md), assetId: int64, equipIfPurchased: boolean, currencyType: CurrencyType) -> ()`
- **Summary:** Prompts a user to purchase an item with the given `assetId`. Does not work for USD Creator Store purchases.

### `MarketplaceService:PromptRobloxSubscriptionPurchase(user: [Player](Player.md)) -> ()`
- **Summary:** Prompts a user to purchase a Roblox Plus subscription.

### `MarketplaceService:PromptRobuxTransferAsync(sender: [Player](Player.md), receiverUserId: int64, amount: int64) -> string`
- **Tags:** Yields
- **Summary:** Initiates a Robux transfer from the sender to another user.

### `MarketplaceService:PromptSubscriptionPurchase(user: [Player](Player.md), subscriptionId: string) -> ()`
- **Summary:** Prompts a user to purchase a subscription for the given `subscriptionId`.

### `MarketplaceService:RankProductsAsync(productIdentifiers: Array) -> Array`
- **Tags:** Yields
- **Summary:** Takes a list of product IDs and returns a personalized ordered list of those products.

### `MarketplaceService:RecommendTopProductsAsync(infoTypes: Array) -> Array`
- **Tags:** Yields
- **Summary:** - Takes an array of `Enum.InfoType` and returns up to 50 items representing the products a user is most likely to engage with and purchase.

### `MarketplaceService:UserOwnsGamePassAsync(userId: int64, gamePassId: int64) -> boolean`
- **Tags:** Yields
- **Summary:** Returns true if the player with the given `Class.Player.UserId|UserId` owns the pass with the given `gamePassId`.

## Events
### `MarketplaceService.PromptBulkPurchaseFinished(player: [Instance](Instance.md), status: MarketplaceBulkPurchasePromptStatus, results: Dictionary)`
- **Summary:** Fires when a purchase prompt for bulk avatar items is closed.

### `MarketplaceService.PromptBundlePurchaseFinished(player: [Instance](Instance.md), bundleId: int64, wasPurchased: boolean)`

### `MarketplaceService.PromptGamePassPurchaseFinished(player: [Instance](Instance.md), gamePassId: int64, wasPurchased: boolean)`
- **Summary:** Fires when a purchase prompt for a pass is closed.

### `MarketplaceService.PromptPremiumPurchaseFinished()`
- **Summary:** Fires when a purchase prompt for Roblox Premium is closed.

### `MarketplaceService.PromptProductPurchaseFinished(userId: int64, productId: int64, isPurchased: boolean)`
- **Summary:** Fires when a purchase prompt for a developer product is closed. Do not use this event to process purchases.

### `MarketplaceService.PromptPurchaseFinished(player: [Instance](Instance.md), assetId: int64, isPurchased: boolean)`
- **Summary:** Fires when a purchase prompt for an affiliate gear sale or other asset is closed. Does **not** fire for developer product or pass prompts.

### `MarketplaceService.PromptRobloxSubscriptionPurchaseFinished(user: [Player](Player.md), didTryPurchasing: boolean)`
- **Summary:** Fires when a purchase prompt for Roblox Plus is closed.

### `MarketplaceService.PromptSubscriptionPurchaseFinished(user: [Player](Player.md), subscriptionId: string, didTryPurchasing: boolean)`
- **Summary:** Fires when a purchase prompt for a subscription is closed.
