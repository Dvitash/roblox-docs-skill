# KeyframeSequenceProvider

**Superclass:** [Instance](Instance.md)

### KeyframeSequenceProvider - Provides functions for loading and previewing `Class.KeyframeSequences` (enriching `Class.Animation|Animations`). - **Core Functionality** - **GetAnimations** - **GetAnimationsAsync** - **GetKeyframeSequence** - **GetKeyframeSequenceAsync** - **GetKeyframeSequenceById** - **KeyframeSequence** - **RegisterActiveKeyframeSequence** - **Deprecation Warnings** - The service is deprecated and does not support `Class.AnimationClip`. It is recommended to use…

## Tags
- NotCreatable
- Service
- NotReplicated

## Methods
### `KeyframeSequenceProvider:GetAnimations(userId: int64) -> [Instance](Instance.md)`
- **Tags:** Yields, Deprecated
- **Summary:** This function returns an `Class.InventoryPages` object which can be used to iterate over animations owned by a specific user.

### `KeyframeSequenceProvider:GetAnimationsAsync(userId: int64) -> [Instance](Instance.md)`
- **Tags:** Yields
- **Summary:** This function returns an `Class.InventoryPages` object which can be used to iterate over animations owned by a specific user.

### `KeyframeSequenceProvider:GetKeyframeSequence(assetId: ContentId) -> [Instance](Instance.md)`
- **Tags:** Deprecated
- **Summary:** Returns a `Class.KeyframeSequence` from a given asset URL.

### `KeyframeSequenceProvider:GetKeyframeSequenceAsync(assetId: ContentId) -> [Instance](Instance.md)`
- **Tags:** Yields
- **Summary:** Returns a KeyframeSequence based on the specified assetId asynchronously.

### `KeyframeSequenceProvider:GetKeyframeSequenceById(assetId: int64, useCache: boolean) -> [Instance](Instance.md)`
- **Tags:** Deprecated
- **Summary:** Returns a `Class.KeyframeSequence` from the supplied assetId.

### `KeyframeSequenceProvider:RegisterActiveKeyframeSequence(keyframeSequence: [Instance](Instance.md)) -> ContentId`
- **Summary:** Generates a temporary asset ID from a `Class.KeyframeSequence` that can be used for localized testing of an animation. Generates an _active://_ URL.

### `KeyframeSequenceProvider:RegisterKeyframeSequence(keyframeSequence: [Instance](Instance.md)) -> ContentId`
- **Summary:** Generates a temporary asset ID from a `Class.KeyframeSequence` that can be used for localized testing of an animation. Generates a hash.
