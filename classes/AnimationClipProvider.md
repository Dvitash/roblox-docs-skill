# AnimationClipProvider

**Superclass:** [Instance](Instance.md)

This class provides functions to load and preview `Class.AnimationClip`s, replacing deprecated `Class.KeyframeSequenceProvider`.

## Tags
- NotCreatable
- Service
- NotReplicated

## Methods
### `AnimationClipProvider:GetAnimationClip(assetId: ContentId) -> [AnimationClip](AnimationClip.md)`
- **Tags:** Deprecated
- **Summary:** Returns a `Class.AnimationClip` from a given asset URL.

### `AnimationClipProvider:GetAnimationClipAsync(assetId: ContentId) -> [AnimationClip](AnimationClip.md)`
- **Tags:** Yields
- **Summary:** Returns a `Class.AnimationClip` based on the specified assetId asynchronously.

### `AnimationClipProvider:GetAnimationClipById(assetId: int64, useCache: boolean) -> [AnimationClip](AnimationClip.md)`
- **Tags:** Deprecated
- **Summary:** Returns a `Class.AnimationClip` from the supplied assetId.

### `AnimationClipProvider:GetAnimations(userId: int64) -> [Instance](Instance.md)`
- **Tags:** Yields, Deprecated
- **Summary:** This function returns an `Class.InventoryPages` object which can be used to iterate over animations owned by a specific user.

### `AnimationClipProvider:GetAnimationsAsync(userId: int64) -> [Instance](Instance.md)`
- **Tags:** Yields
- **Summary:** This function returns an `Class.InventoryPages` object which can be used to iterate over animations owned by a specific user.

### `AnimationClipProvider:GetClipEvaluatorAsync(assetId: ContentId) -> ClipEvaluator`
- **Tags:** Yields

### `AnimationClipProvider:RegisterActiveAnimationClip(animationClip: [AnimationClip](AnimationClip.md)) -> ContentId`
- **Summary:** Generates a temporary asset ID from a `Class.AnimationClip` that can be used for localized testing of an animation.

### `AnimationClipProvider:RegisterAnimationClip(animationClip: [AnimationClip](AnimationClip.md)) -> ContentId`
- **Summary:** Generates a temporary asset ID from a `Class.AnimationClip` that can be used for localized testing of an animation. Generates a hash.
