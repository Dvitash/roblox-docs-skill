# Feature

**Superclass:** [Instance](Instance.md)

The `Feature` class is the base class for the legacy motor system, defining how features are positioned on their parent surfaces.

## Tags
- NotCreatable

## Properties
### `Feature.FaceId`
- **Type:** `NormalId`
- **Summary:** Sets what side of the Parent the object is on.

### `Feature.InOut`
- **Type:** `InOut`
- **Summary:** Controls how the Feature is positioned on it's parent's surface, in correspondence to the Feature's `Class.Feature.LeftRight` and `Class.Feature.TopBottom` properties.

### `Feature.LeftRight`
- **Type:** `LeftRight`
- **Summary:** Controls whether the feature is shifted to the left, center, or right on the surface.

### `Feature.TopBottom`
- **Type:** `TopBottom`
- **Summary:** Controls whether the feature is shifted to the top, center, or bottom on the surface.
