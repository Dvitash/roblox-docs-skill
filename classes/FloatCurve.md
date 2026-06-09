# FloatCurve

**Superclass:** [Instance](Instance.md)

The `FloatCurve` class is a data structure used to represent a sorted list of time-value pairs that define a curve, which can be used for animating numerical values.

## Properties
### `FloatCurve.Length`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Number of keys in the float curve.

## Methods
### `FloatCurve:GetKeyAtIndex(index: int) -> FloatCurveKey`
- **Summary:** Returns a copy of a key at a given index.

### `FloatCurve:GetKeyIndicesAtTime(time: float) -> Array`
- **Summary:** Returns the index of the last and first key of a period of time.

### `FloatCurve:GetKeys() -> Array`
- **Summary:** Returns a copy of all the keys in the FloatCurve as a Luau array of `Datatype.FloatCurveKey|FloatCurveKeys`.

### `FloatCurve:GetValueAtTime(time: float) -> float?`
- **Summary:** Samples the float curve at a given time passed as argument.

### `FloatCurve:InsertKey(key: FloatCurveKey) -> Array`
- **Summary:** Adds the key passed as an argument to this curve. If a key at the same time is found, it will be replaced.

### `FloatCurve:RemoveKeyAtIndex(startingIndex: int, count: int) -> int`
- **Summary:** Removes a given number of keys starting from a given index.

### `FloatCurve:SetKeys(keys: Array) -> int`
- **Summary:** Resets this curve's keys using the `Datatype.FloatCurveKey` array passed as an argument.
