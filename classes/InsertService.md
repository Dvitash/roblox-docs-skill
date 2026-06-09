# InsertService

**Superclass:** [Instance](Instance.md)

The `InsertService` class is used to insert assets from the Roblox website, typically `Class.InsertService:LoadAsset()`. It requires access by the creator to load assets, and it should not be used for loading API keys or secrets.

## Tags
- NotCreatable
- Service

## Properties
### `InsertService.AllowInsertFreeModels`
- **Type:** `boolean`
- **Tags:** NotReplicated, NotBrowsable, Deprecated
- **Summary:** Indicates whether ''Free Models'' can be inserted into the game.

## Methods
### `InsertService:ApproveAssetId(assetId: int64) -> ()`
- **Tags:** Deprecated

### `InsertService:ApproveAssetVersionId(assetVersionId: int64) -> ()`
- **Tags:** Deprecated

### `InsertService:CreateMeshPartAsync(meshId: ContentId, collisionFidelity: CollisionFidelity, renderFidelity: RenderFidelity) -> [MeshPart](MeshPart.md)`
- **Tags:** Yields
- **Summary:** Creates a new `Class.MeshPart` with specified fidelity values.

### `InsertService:GetBaseCategories() -> Array`
- **Tags:** Yields, Deprecated

### `InsertService:GetBaseSets() -> Array`
- **Tags:** Yields, Deprecated
- **Summary:** Returns an array of dictionaries, containing information about various Roblox approved sets.

### `InsertService:GetCollection(categoryId: int64) -> Array`
- **Tags:** Yields, Deprecated
- **Summary:** Returns the most recently uploaded models in the specified category.

### `InsertService:GetFreeDecals(searchText: string, pageNum: int) -> Array`
- **Tags:** Yields, Deprecated
- **Summary:** Retrieves a list of free Decals from the Catalog.

### `InsertService:GetFreeDecalsAsync(searchText: string, pageNum: int) -> Array`
- **Tags:** Yields
- **Summary:** Retrieves a list of free Decals from the Catalog.

### `InsertService:GetFreeModels(searchText: string, pageNum: int) -> Array`
- **Tags:** Yields, Deprecated
- **Summary:** Retrieves a list of Free Models from the Catalog.

### `InsertService:GetFreeModelsAsync(searchText: string, pageNum: int) -> Array`
- **Tags:** Yields
- **Summary:** Retrieves a list of Free Models from the Catalog.

### `InsertService:GetLatestAssetVersionAsync(assetId: int64) -> int64`
- **Tags:** Yields
- **Summary:** Returns the latest AssetVersionId of an asset for assets created by the place creator. Can be used in combination with `Class.InsertService:LoadAssetVersion()` to load the latest version of a model, even if it gets updated while the game is running.

### `InsertService:GetUserCategories(userId: int64) -> Array`
- **Tags:** Yields, Deprecated

### `InsertService:GetUserSets(userId: int64) -> Array`
- **Tags:** Yields, Deprecated
- **Summary:** Returns an array of dictionaries, containing information about sets owned by the user.

### `InsertService:Insert(instance: [Instance](Instance.md)) -> ()`
- **Tags:** Deprecated
- **Summary:** Inserts `Class.Instance` into `Class.Workspace`.

### `InsertService:LoadAsset(assetId: int64) -> [Instance](Instance.md)`
- **Tags:** Yields
- **Summary:** Returns a `Class.Model` containing the asset.

### `InsertService:loadAsset(assetId: int64) -> [Instance](Instance.md)`
- **Tags:** Yields, Deprecated

### `InsertService:LoadAssetVersion(assetVersionId: int64) -> [Instance](Instance.md)`
- **Tags:** Yields
- **Summary:** Returns a model inserted into `Class.InsertService` containing the asset with the given assetVersionId.
