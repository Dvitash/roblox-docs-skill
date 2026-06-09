# RotationCurve

**Superclass:** [Instance](Instance.md)

RotationCurve is a class representing a sequence of rotations and an interpolation curve between them, determined by the `Datatype.RotationCurveKey` type.

## Properties
### `RotationCurve.Length`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Number of rotation keys in this curve.

## Methods
### `RotationCurve:GetKeyAtIndex(index: int) -> RotationCurveKey`
- **Summary:** Returns a copy of a key at a given index.

### `RotationCurve:GetKeyIndicesAtTime(time: float) -> Array`
- **Summary:** Returns the index of the last and first key of a period of time.

### `RotationCurve:GetKeys() -> Array`
- **Summary:** Returns a copy of all the keys in the rotation curve as a Luau array of `Datatype.RotationCurveKey|RotationCurveKeys`.

### `RotationCurve:GetValueAtTime(time: float) -> CFrame?`
- **Summary:** Samples the rotation curve at a given time and returns the corresponding rotation as a `Datatype.CFrame`.

### `RotationCurve:InsertKey(key: RotationCurveKey) -> Array`
- **Summary:** Adds the key passed as an argument to this curve. If a key at the same time is found, it will be replaced.

### `RotationCurve:RemoveKeyAtIndex(startingIndex: int, count: int) -> int`
- **Summary:** Removes a given number of keys starting from a given index.

### `RotationCurve:SetKeys(keys: Array) -> int`
- **Summary:** Resets this curve's keys using the `Datatype.RotationCurveKey` array passed as an argument.
