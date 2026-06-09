# DoubleConstrainedValue

**Superclass:** [ValueBase](ValueBase.md)

The `DoubleConstrainedValue` class is a value that restricts a number to MinValue or MaxValue, and it is deprecated as `libmath.clamp()` functions are recommended for value constraining.

## Tags
- Deprecated

## Properties
### `DoubleConstrainedValue.ConstrainedValue`
- **Type:** `double`
- **Tags:** Hidden, NotReplicated

### `DoubleConstrainedValue.MaxValue`
- **Type:** `double`
- **Summary:** The highest number that the `Class.DoubleConstrainedValue.Value` property can be.

### `DoubleConstrainedValue.MinValue`
- **Type:** `double`
- **Summary:** The lowest number that the `Class.DoubleConstrainedValue.Value` property can be.

### `DoubleConstrainedValue.Value`
- **Type:** `double`
- **Tags:** NotReplicated
- **Summary:** Used to hold a number value between `Class.DoubleConstrainedValue.MinValue` and `Class.DoubleConstrainedValue.MaxValue`.

## Events
### `DoubleConstrainedValue.Changed(value: double)`
- **Summary:** Fired whenever the `Class.DoubleConstrainedValue.Value` of the `Class.DoubleConstrainedValue` is changed.

### `DoubleConstrainedValue.changed(value: double)`
- **Tags:** Deprecated
