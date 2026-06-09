# MakeupDescription

**Superclass:** [Instance](Instance.md)

This file defines `MakeupDescription` class, which stores the description for a makeup item and is used to apply it to a `Class.HumanoidDescription`.

## Properties
### `MakeupDescription.AssetId`
- **Type:** `int64`
- **Summary:** The asset ID that should be applied when applying this `Class.MakeupDescription`.

### `MakeupDescription.Instance`
- **Type:** `[Instance](Instance.md)`
- **Summary:** A reference to the `Class.Instance` that should be used when applying this `Class.MakeupDescription`.

### `MakeupDescription.MakeupType`
- **Type:** `MakeupType`
- **Summary:** The `Enum.MakeupType` of the makeup item referred to by this description.

### `MakeupDescription.Order`
- **Type:** `int`
- **Summary:** The layering sort order for the makeup item.

## Methods
### `MakeupDescription:GetAppliedInstance() -> [Instance](Instance.md)`
- **Summary:** Returns the applied makeup `Class.Instance`.
