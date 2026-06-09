# AccessoryDescription

**Superclass:** [Instance](Instance.md)

The `AccessoryDescription` class defines how an `Instance` of `Class.Accessory` is applied when applying another `Class.HumanoidDescription`.

## Properties
### `AccessoryDescription.AccessoryType`
- **Type:** `AccessoryType`
- **Summary:** The `Enum.AccessoryType` of the `Class.Accessory` referred to by this description.

### `AccessoryDescription.AssetId`
- **Type:** `int64`
- **Summary:** The asset ID that should be applied when applying this `Class.AccessoryDescription`.

### `AccessoryDescription.Instance`
- **Type:** `[Instance](Instance.md)`
- **Summary:** A reference to the `Class.Instance` that should be applied when applying this `Class.AccessoryDescription`.

### `AccessoryDescription.IsLayered`
- **Type:** `boolean`
- **Summary:** Whether the `Class.Accessory` is layered or rigid.

### `AccessoryDescription.Order`
- **Type:** `int`
- **Summary:** The layered clothing sort order, if the `Class.Accessory` is layered.

### `AccessoryDescription.Position`
- **Type:** `Vector3`
- **Summary:** The accessory adjustment position offset, if the `Class.Accessory` is rigid.

### `AccessoryDescription.Puffiness`
- **Type:** `float`
- **Summary:** The layered clothing puffiness, if the `Class.Accessory` is layered.

### `AccessoryDescription.Rotation`
- **Type:** `Vector3`
- **Summary:** The accessory adjustment rotation offset, if the `Class.Accessory` is rigid.

### `AccessoryDescription.Scale`
- **Type:** `Vector3`
- **Summary:** The accessory adjustment scale, if the `Class.Accessory` is rigid.

## Methods
### `AccessoryDescription:GetAppliedInstance() -> [Instance](Instance.md)`
- **Summary:** Returns the applied `Class.Accessory`.
