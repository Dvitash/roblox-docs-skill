# ValueCurve

**Superclass:** [Instance](Instance.md)

A ValueCurve class represents a sorted list of time-value pairs used to animate any type of value, with specific interpolation rules for different types.

## Properties
### `ValueCurve.Length`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Number of keys in the value curve.

### `ValueCurve.ValueType`
- **Type:** `string`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Read-only value indicating the type held in this curve.

## Methods
### `ValueCurve:GetKeyAtIndex(index: int) -> ValueCurveKey`
- **Summary:** Returns a copy of a key at a given index.

### `ValueCurve:GetKeyIndicesAtTime(time: float) -> Array`
- **Summary:** Returns the index of the last and first key of a period of time.

### `ValueCurve:GetKeys() -> Array`
- **Summary:** Returns a copy of all the keys in the ValueCurve as a Luau array of `Datatype.ValueCurveKey|ValueCurveKeys`.

### `ValueCurve:GetValueAtTime(time: float) -> Variant?`
- **Summary:** Samples the value curve at a given time passed as argument.

### `ValueCurve:InsertKey(key: ValueCurveKey) -> Array`
- **Summary:** Adds the key passed as an argument to this curve. If a key at the same time is found, it will be replaced.

### `ValueCurve:InsertKeyValue(time: float, value: Variant, Interpolation: KeyInterpolationMode) -> Array`
- **Summary:** Creates a key for the given value and inserts it at the given time. If a key at the same time is found, it will be replaced.

### `ValueCurve:RemoveKeyAtIndex(startingIndex: int, count: int) -> int`
- **Summary:** Removes a given number of keys starting from a given index.

### `ValueCurve:SetKeys(keys: Array) -> int`
- **Summary:** Resets this curve's keys using the `Datatype.ValueCurveKey` array passed as an argument.
