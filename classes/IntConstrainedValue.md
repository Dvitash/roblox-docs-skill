# IntConstrainedValue

**Superclass:** [ValueBase](ValueBase.md)

An IntConstrainedValue class is used to store integer values between specific minimum and maximum limits, with deprecation warnings for using `Library.math.clamp()` instead of `int64`.

## Tags
- Deprecated

## Properties
### `IntConstrainedValue.ConstrainedValue`
- **Type:** `int64`
- **Tags:** Hidden, NotReplicated
- **Summary:** Hold an `Integer` value between `Class.IntConstrainedValue.MinValue` and `Class.IntConstrainedValue.MaxValue`. Replaced by `Class.IntConstrainedValue.Value`, but still functional.

### `IntConstrainedValue.MaxValue`
- **Type:** `int64`
- **Summary:** The highest number that the `Class.IntConstrainedValue.Value` property can be.

### `IntConstrainedValue.MinValue`
- **Type:** `int64`
- **Summary:** The lowest number that the `Class.IntConstrainedValue.Value` property can be.

### `IntConstrainedValue.Value`
- **Type:** `int64`
- **Tags:** NotReplicated
- **Summary:** Used to hold an integer value between `Class.IntConstrainedValue.MinValue` and `Class.IntConstrainedValue.MaxValue`.

## Events
### `IntConstrainedValue.Changed(value: int64)`
- **Summary:** Fired whenever the Value of the IntConstrainedValue is changed.

### `IntConstrainedValue.changed(value: int64)`
- **Tags:** Deprecated
