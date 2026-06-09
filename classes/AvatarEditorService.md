# AvatarEditorService

**Superclass:** [Instance](Instance.md)

AvatarEditorService is a service that allows developers to modify player avatars, request inventory information, and request catalog information. It includes experience-level throttling for performance and handles item details responses in a shared format.

## Tags
- NotCreatable
- Service

## Methods
### `AvatarEditorService:CheckApplyDefaultClothing(humanoidDescription: [HumanoidDescription](HumanoidDescription.md)) -> [HumanoidDescription](HumanoidDescription.md)`
- **Tags:** Yields, Deprecated
- **Summary:** Used to apply default clothing to the `Class.HumanoidDescription` if necessary.

### `AvatarEditorService:CheckApplyDefaultClothingAsync(humanoidDescription: [HumanoidDescription](HumanoidDescription.md)) -> [HumanoidDescription](HumanoidDescription.md)`
- **Tags:** Yields
- **Summary:** Used to apply default clothing to the `Class.HumanoidDescription` if necessary.

### `AvatarEditorService:ConformToAvatarRules(humanoidDescription: [HumanoidDescription](HumanoidDescription.md)) -> [HumanoidDescription](HumanoidDescription.md)`
- **Tags:** Yields, Deprecated

### `AvatarEditorService:ConformToAvatarRulesAsync(humanoidDescription: [HumanoidDescription](HumanoidDescription.md)) -> [HumanoidDescription](HumanoidDescription.md)`
- **Tags:** Yields
- **Summary:** Returns a copy of the given `Class.HumanoidDescription` that conforms to the platform Avatar rules.

### `AvatarEditorService:GetAccessoryType(avatarAssetType: AvatarAssetType) -> AccessoryType`

### `AvatarEditorService:GetAvatarRules() -> Dictionary`
- **Tags:** Yields, Deprecated
- **Summary:** Returns the platform Avatar rules for things such as scaling, default shirts and pants, number of wearable assets.

### `AvatarEditorService:GetAvatarRulesAsync() -> Dictionary`
- **Tags:** Yields
- **Summary:** Returns the platform Avatar rules for things such as scaling, default shirts and pants, number of wearable assets.

### `AvatarEditorService:GetBatchItemDetails(itemIds: Array, itemType: AvatarItemType) -> Array`
- **Tags:** Yields, Deprecated
- **Summary:** Gets the item details for a list of items at once.

### `AvatarEditorService:GetBatchItemDetailsAsync(itemIds: Array, itemType: AvatarItemType) -> Array`
- **Tags:** Yields
- **Summary:** Gets the item details for a list of items at once.

### `AvatarEditorService:GetFavorite(itemId: int64, itemType: AvatarItemType) -> boolean`
- **Tags:** Yields, Deprecated
- **Summary:** Returns if the `Class.Players.LocalPlayer` has favorited the given bundle or asset.

### `AvatarEditorService:GetFavoriteAsync(itemId: int64, itemType: AvatarItemType) -> boolean`
- **Tags:** Yields
- **Summary:** Returns if the `Class.Players.LocalPlayer` has favorited the given bundle or asset.

### `AvatarEditorService:GetHeadShapesAsync() -> Array`
- **Tags:** Yields
- **Summary:** Returns an array of head shape names that the `Class.Players.LocalPlayer` owns.

### `AvatarEditorService:GetInventory(assetTypes: Array) -> [InventoryPages](InventoryPages.md)`
- **Tags:** Yields, Deprecated
- **Summary:** Returns an `Class.InventoryPages` object with information about owned items in the users inventory with the given AvatarAssetTypes.

### `AvatarEditorService:GetInventoryAsync(assetTypes: Array) -> [InventoryPages](InventoryPages.md)`
- **Tags:** Yields
- **Summary:** Returns an `Class.InventoryPages` object with information about owned items in the users inventory with the given AvatarAssetTypes.

### `AvatarEditorService:GetItemDetails(itemId: int64, itemType: AvatarItemType) -> Dictionary`
- **Tags:** Yields, Deprecated
- **Summary:** Returns the item details for the given item.

### `AvatarEditorService:GetItemDetailsAsync(itemId: int64, itemType: AvatarItemType) -> Dictionary`
- **Tags:** Yields
- **Summary:** Returns the item details for the given item.

### `AvatarEditorService:GetOutfitDetails(outfitId: int64) -> Dictionary`
- **Tags:** Yields, Deprecated
- **Summary:** Returns the outfit details for the given outfit.

### `AvatarEditorService:GetOutfitDetailsAsync(outfitId: int64) -> Dictionary`
- **Tags:** Yields
- **Summary:** Returns the outfit details for the given outfit.

### `AvatarEditorService:GetOutfits(outfitSource: OutfitSource, outfitType: OutfitType) -> [OutfitPages](OutfitPages.md)`
- **Tags:** Yields, Deprecated
- **Summary:** Returns outfit data for the `Class.Players.LocalPlayer`.

### `AvatarEditorService:GetOutfitsAsync(outfitSource: OutfitSource, outfitType: OutfitType) -> [OutfitPages](OutfitPages.md)`
- **Tags:** Yields
- **Summary:** Returns outfit data for the `Class.Players.LocalPlayer`.

### `AvatarEditorService:GetRecommendedAssets(assetType: AvatarAssetType, contextAssetId: int64) -> Array`
- **Tags:** Yields, Deprecated
- **Summary:** Returns a list of recommended assets based on a given `Enum.AssetType` and asset ID.

### `AvatarEditorService:GetRecommendedAssetsAsync(assetType: AvatarAssetType, contextAssetId: int64) -> Array`
- **Tags:** Yields
- **Summary:** Returns a list of recommended assets based on a given `Enum.AssetType` and asset ID.

### `AvatarEditorService:GetRecommendedBundles(bundleId: int64) -> Array`
- **Tags:** Yields, Deprecated
- **Summary:** Returns a list of recommended bundles for a given bundle id.

### `AvatarEditorService:GetRecommendedBundlesAsync(bundleId: int64) -> Array`
- **Tags:** Yields
- **Summary:** Returns a list of recommended bundles for a given bundle id.

### `AvatarEditorService:PromptAllowInventoryReadAccess() -> ()`
- **Summary:** Prompts the `Class.Players.LocalPlayer` to allow the developer to read what items the user has in their inventory and other avatar editor related information.

### `AvatarEditorService:PromptCreateOutfit(outfit: [HumanoidDescription](HumanoidDescription.md), rigType: HumanoidRigType, outfitOptions: Dictionary, outfitType: Variant) -> ()`
- **Summary:** Prompts the `Class.Players.LocalPlayer` to save the given `Class.HumanoidDescription` as an outfit.

### `AvatarEditorService:PromptDeleteOutfit(outfitId: int64) -> ()`
- **Summary:** Prompts the `Class.Players.LocalPlayer` to delete the given outfit.

### `AvatarEditorService:PromptRenameOutfit(outfitId: int64) -> ()`
- **Summary:** Prompts the `Class.Players.LocalPlayer` to rename the given outfit.

### `AvatarEditorService:PromptSaveAvatar(humanoidDescription: [HumanoidDescription](HumanoidDescription.md), rigType: HumanoidRigType) -> ()`
- **Summary:** Prompts the `Class.Players.LocalPlayer` to update their avatar based on the given `Class.HumanoidDescription` and `Enum.RigType` of R6 or R15.

### `AvatarEditorService:PromptSetFavorite(itemId: int64, itemType: AvatarItemType, shouldFavorite: boolean) -> ()`
- **Summary:** Prompts the `Class.Players.LocalPlayer` to favorite or unfavorite the given asset or bundle.

### `AvatarEditorService:PromptUpdateOutfit(outfitId: int64, updatedOutfit: [HumanoidDescription](HumanoidDescription.md), rigType: HumanoidRigType) -> ()`
- **Summary:** Prompts the `Class.Players.LocalPlayer` to update the given outfit.

### `AvatarEditorService:SearchCatalog(searchParameters: CatalogSearchParams) -> [CatalogPages](CatalogPages.md)`
- **Tags:** Yields, Deprecated
- **Summary:** Returns a `Class.CatalogPages` object containing the result of the given search.

### `AvatarEditorService:SearchCatalogAsync(searchParameters: CatalogSearchParams) -> [CatalogPages](CatalogPages.md)`
- **Tags:** Yields
- **Summary:** Returns a `Class.CatalogPages` object containing the result of the given search.

## Events
### `AvatarEditorService.PromptAllowInventoryReadAccessCompleted(result: AvatarPromptResult)`
- **Summary:** Fires when the `Class.AvatarEditorService:PromptAllowInventoryReadAccess()` prompt is responded to by the user.

### `AvatarEditorService.PromptCreateOutfitCompleted(result: AvatarPromptResult, failureType: Variant)`
- **Summary:** Fires when the PromptSaveOutfit operation is completed.

### `AvatarEditorService.PromptDeleteOutfitCompleted(result: AvatarPromptResult)`
- **Summary:** Fires when the PromptDeleteOutfit operation is completed.

### `AvatarEditorService.PromptRenameOutfitCompleted(result: AvatarPromptResult)`
- **Summary:** Fires when the PromptRenameOutfit operation is completed.

### `AvatarEditorService.PromptSaveAvatarCompleted(result: AvatarPromptResult, humanoidDescription: [HumanoidDescription](HumanoidDescription.md))`
- **Summary:** Fires when the `Class.AvatarEditorService:PromptSaveAvatar()` operation is completed.

### `AvatarEditorService.PromptSetFavoriteCompleted(result: AvatarPromptResult)`
- **Summary:** Fires when the `Class.AvatarEditorService:PromptSetFavorite()` operation is completed.

### `AvatarEditorService.PromptUpdateOutfitCompleted(result: AvatarPromptResult)`
- **Summary:** Fires when the `Class.AvatarEditorService:PromptUpdateOutfit()` operation is completed.
