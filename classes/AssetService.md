# AssetService

**Superclass:** [Instance](Instance.md)

The `AssetService` class is a non-replicated service that handles asset queries to the Roblox web API, controlling whether assets are loaded as owned or shared.

## Tags
- NotCreatable
- Service

## Properties
### `AssetService.AllowInsertFreeAssets`
- **Type:** `boolean`
- **Summary:** Controls whether `Class.AssetService:LoadAssetAsync()` can load assets that are not owned by the experience creator.

## Methods
### `AssetService:ComposeDecalAsync(decal: [Decal](Decal.md), layers: Array) -> ()`
- **Tags:** Yields
- **Summary:** Modifies an existing `Class.Decal` to contain a composite PBR textures created by layering the provided textures in the order they are provided in the `layers` array. Textures layer based on the alpha value of the color map.

### `AssetService:CreateAssetAsync(object: [Object](Object.md), assetType: AssetType, requestParameters: Dictionary) -> Tuple`
- **Tags:** Yields
- **Summary:** Uploads a new asset to Roblox from the given object.

### `AssetService:CreateAssetVersionAsync(object: [Object](Object.md), assetType: AssetType, assetId: int64, requestParameters: Dictionary) -> Tuple`
- **Tags:** Yields
- **Summary:** Uploads a new version for an existing asset from the given object.

### `AssetService:CreateDataModelContentAsync(content: Content, options: Dictionary?) -> Tuple`
- **Tags:** Yields
- **Summary:** Creates ephemeral, `Class.DataModel`-scoped content from the provided content input.

### `AssetService:CreateEditableImage(editableImageOptions: Dictionary?) -> [EditableImage](EditableImage.md)`
- **Summary:** Creates a new `Class.EditableImage`.

### `AssetService:CreateEditableImageAsync(content: Content, editableImageOptions: Dictionary?) -> [EditableImage](EditableImage.md)`
- **Tags:** Yields
- **Summary:** Creates a new `Class.EditableImage` object populated with the given image.

### `AssetService:CreateEditableMesh(editableMeshOptions: Dictionary?) -> [EditableMesh](EditableMesh.md)`
- **Summary:** Creates a new, empty `Class.EditableMesh`.

### `AssetService:CreateEditableMeshAsync(content: Content, editableMeshOptions: Dictionary?) -> [EditableMesh](EditableMesh.md)`
- **Tags:** Yields
- **Summary:** Returns a new `Class.EditableMesh` object created from an existing mesh content ID.

### `AssetService:CreateMeshPartAsync(meshContent: Content, options: Dictionary) -> [MeshPart](MeshPart.md)`
- **Tags:** Yields
- **Summary:** Creates a new `Class.MeshPart` with a specified mesh ID and an optional table of fidelity values.

### `AssetService:CreatePlaceAsync(placeName: string, templatePlaceID: int64, description: string) -> int64`
- **Tags:** Yields
- **Summary:** Clones a place through the given `templatePlaceID`.

### `AssetService:CreatePlaceInPlayerInventoryAsync(player: [Instance](Instance.md), placeName: string, templatePlaceID: int64, description: string) -> int64`
- **Tags:** Yields
- **Summary:** Clones a place through the given `templatePlaceID` and puts it into the inventory of the given player.

### `AssetService:CreateSurfaceAppearanceAsync(content: Dictionary) -> [SurfaceAppearance](SurfaceAppearance.md)`
- **Tags:** Yields
- **Summary:** Creates a new `Class.SurfaceAppearance` object using the provided content maps.

### `AssetService:GetAssetIdsForPackage(packageAssetId: int64) -> Array`
- **Tags:** Yields, Deprecated
- **Summary:** Returns an array of asset IDs that are contained in a specified package.

### `AssetService:GetAssetIdsForPackageAsync(packageAssetId: int64) -> Array`
- **Tags:** Yields
- **Summary:** Returns an array of asset IDs that are contained in a specified package.

### `AssetService:GetAudioMetadataAsync(idList: Array) -> Array`
- **Tags:** Yields
- **Summary:** Provides relevant metadata about a specific audio source.

### `AssetService:GetBundleDetailsAsync(bundleId: int64) -> Dictionary`
- **Tags:** Yields
- **Summary:** Returns details of the contents of specified bundle.

### `AssetService:GetCreatorAssetID(creationID: int64) -> int64`
- **Tags:** Yields, Deprecated
- **Summary:** Returns the UserId of the account who created the creationID asset.

### `AssetService:GetGamePlacesAsync() -> [Instance](Instance.md)`
- **Tags:** Yields
- **Summary:** Returns a `Class.StandardPages` object which contains the name and `Class.DataModel.PlaceId|PlaceId` of places within the current experience.

### `AssetService:LoadAssetAsync(assetId: int64) -> [Instance](Instance.md)`
- **Tags:** Yields
- **Summary:** Loads a `Class.Model` instance given its asset ID. This is the modern replacement for `Class.InsertService:LoadAsset()` and supports loading third-party assets.

### `AssetService:PromptCreateAssetAsync(player: [Player](Player.md), instance: [Instance](Instance.md), assetType: AssetType) -> Tuple`
- **Tags:** Yields
- **Summary:** Allows in-experience asset creation for users by prompting a publish dialog.

### `AssetService:PromptImportAnimationClipFromVideoAsync(player: [Player](Player.md), progressCallback: Function) -> Tuple`
- **Tags:** Yields

### `AssetService:SavePlaceAsync(requestParameters: Dictionary?) -> ()`
- **Tags:** Yields
- **Summary:** Saves the state of the current place.

### `AssetService:SearchAudio(searchParameters: [AudioSearchParams](AudioSearchParams.md)) -> [AudioPages](AudioPages.md)`
- **Tags:** Yields, Deprecated
- **Summary:** Finds audio assets matching a variety of search criteria.

### `AssetService:SearchAudioAsync(searchParameters: [AudioSearchParams](AudioSearchParams.md)) -> [AudioPages](AudioPages.md)`
- **Tags:** Yields
- **Summary:** Finds audio assets matching a variety of search criteria.
