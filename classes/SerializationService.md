# SerializationService

**Superclass:** [Instance](Instance.md)

SerializationService is a class for deserializing `.rbxm` content from a library buffer, handling creation and deserialization for various objects.

## Tags
- NotCreatable
- Service

## Methods
### `SerializationService:DeserializeInstancesAsync(buffer: buffer) -> List<[Instance](Instance.md)>`
- **Tags:** Yields
- **Summary:** Deserializes a `Library.buffer` containing `.rbxm` content, returning a list of `Class.Instance|instances`.

### `SerializationService:SerializeInstancesAsync(inputInstances: List<[Instance](Instance.md)>) -> buffer`
- **Tags:** Yields
- **Summary:** Serializes a list of `Class.Instance|instances` to the `.rbxm` format, returning a `Library.buffer` or `.rbxm` content.
