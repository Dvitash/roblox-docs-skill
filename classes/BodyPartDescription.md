# BodyPartDescription

**Superclass:** [Instance](Instance.md)

BodyPartDescription is an object used to store the description for avatar body parts, such as `Class.BodyPartDescription.Color|Color`. It is intended to be placed underneath `Class.HumanoidDescription` when applying `Class.ApplyDescriptionAsync()`.

## Properties
### `BodyPartDescription.AssetId`
- **Type:** `int64`
- **Summary:** The asset ID that should be applied when applying this `Class.BodyPartDescription`.

### `BodyPartDescription.BodyPart`
- **Type:** `BodyPart`
- **Summary:** The type of body part.

### `BodyPartDescription.Color`
- **Type:** `Color3`
- **Summary:** The `Datatype.Color3` for this body part.

### `BodyPartDescription.HeadShape`
- **Type:** `string`
- **Summary:** Specifies the head shape identifier to apply to a Dynamic Head when this `Class.BodyPartDescription` is applied.

### `BodyPartDescription.Instance`
- **Type:** `[Instance](Instance.md)`
- **Summary:** A reference to the `Class.Instance` that should be applied when applying this `Class.BodyPartDescription`.
