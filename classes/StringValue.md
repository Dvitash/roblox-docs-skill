# StringValue

**Superclass:** [ValueBase](ValueBase.md)

A `StringValue` class is a container for a single string, defined by its length limit and partial display behavior. It is stored in the `Class.StringValue.Value` property and fires the `StringValue.Changed` event whenever it is modified.

## Properties
### `StringValue.Value`
- **Type:** `string`
- **Summary:** The stored string.

## Events
### `StringValue.Changed(value: string)`
- **Summary:** Fires whenever `Class.StringValue.Value` is changed.

### `StringValue.changed(value: string)`
- **Tags:** Deprecated
