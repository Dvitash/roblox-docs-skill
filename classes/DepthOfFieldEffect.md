# DepthOfFieldEffect

**Superclass:** [PostEffect](PostEffect.md)

DepthOfFieldEffect is a post-processing effect that simulates a camera lens by blurring parts of a scene not in focus, allowing users to focus on specific objects.

## Properties
### `DepthOfFieldEffect.FarIntensity`
- **Type:** `float`
- **Summary:** Intensity of the far field blur.

### `DepthOfFieldEffect.FocusDistance`
- **Type:** `float`
- **Summary:** Distance away from the camera where objects are in focus.

### `DepthOfFieldEffect.InFocusRadius`
- **Type:** `float`
- **Summary:** Controls the distance away from the `Class.DepthOfFieldEffect.FocusDistance|FocusDistance` where no blur is applied.

### `DepthOfFieldEffect.NearIntensity`
- **Type:** `float`
- **Summary:** Intensity of the near field blur.
