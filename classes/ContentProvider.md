# ContentProvider

**Superclass:** [Instance](Instance.md)

The `ContentProvider` class allows loading content and assets into a game, enabling preloading of assets before they are needed.

## Tags
- NotCreatable
- Service
- NotReplicated

## Properties
### `ContentProvider.BaseUrl`
- **Type:** `string`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Used by the `Class.ContentProvider` to download assets from the Roblox website.

### `ContentProvider.RequestQueueSize`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Gives the number of items in the `Class.ContentProvider` request queue that need to be downloaded.

## Methods
### `ContentProvider:GetAssetFetchStatus(contentId: ContentId) -> AssetFetchStatus`
- **Summary:** Gets the current `Enum.AssetFetchStatus` of the `contentId` provided.

### `ContentProvider:GetAssetFetchStatusChangedSignal(contentId: ContentId) -> RBXScriptSignal`
- **Summary:** A signal that fires when the `Enum.AssetFetchStatus` of the provided content changes.

### `ContentProvider:ListEncryptedAssets() -> Array`

### `ContentProvider:Preload(contentId: ContentId) -> ()`
- **Tags:** Deprecated
- **Summary:** Queues an asset to be downloaded by the `Class.ContentProvider`.

### `ContentProvider:PreloadAsync(contentIdList: Array, callbackFunction: Function) -> ()`
- **Tags:** Yields
- **Summary:** Yields until all of the assets associated with the given `Class.Instance|Instances` have loaded.

### `ContentProvider:RegisterDefaultEncryptionKey(encryptionKey: string) -> ()`

### `ContentProvider:RegisterDefaultSessionKey(sessionKey: string) -> ()`

### `ContentProvider:RegisterEncryptedAsset(assetId: ContentId, encryptionKey: string) -> ()`

### `ContentProvider:RegisterSessionEncryptedAsset(contentId: ContentId, sessionKey: string) -> ()`

### `ContentProvider:UnregisterDefaultEncryptionKey() -> ()`

### `ContentProvider:UnregisterEncryptedAsset(assetId: ContentId) -> ()`

## Events
### `ContentProvider.AssetFetchFailed(assetId: ContentId)`
