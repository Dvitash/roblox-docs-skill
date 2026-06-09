# IntValue

**Superclass:** [ValueBase](ValueBase.md)

This file defines the `IntValue` class, which represents a single signed 64-bit integer stored in memory. It handles integer overflow and precision loss when large values are stored, and provides methods for value manipulation.

## Properties
### `IntValue.Value`
- **Type:** `int64`
- **Summary:** Used to hold an integer.

## Events
### `IntValue.Changed(value: int64)`
- **Summary:** Fires whenever the `Class.IntValue.Value` is changed.

### `IntValue.changed(value: int64)`
- **Tags:** Deprecated
