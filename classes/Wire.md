# Wire

**Superclass:** [Instance](Instance.md)

The `Class.Wire` class connects multiple `Class.Instance|Instances` to form a processing graph, supporting various audio stream types.

## Properties
### `Wire.Connected`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Denotes whether the `Class.Wire` is carrying a stream of data.

### `Wire.SourceInstance`
- **Type:** `[Instance](Instance.md)`
- **Summary:** The `Class.Instance` producing a stream to be carried over the wire.

### `Wire.SourceName`
- **Type:** `string`
- **Summary:** The name of the pin on `Class.Wire.SourceInstance|SourceInstance` that is producing a stream.

### `Wire.TargetInstance`
- **Type:** `[Instance](Instance.md)`
- **Summary:** The `Class.Instance` to receive a stream from `Class.Wire.SourceInstance|SourceInstance`.

### `Wire.TargetName`
- **Type:** `string`
- **Summary:** The name of the pin on `Class.Wire.TargetInstance|TargetInstance` that is receiving a stream.
