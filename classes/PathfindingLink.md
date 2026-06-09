# PathfindingLink

**Superclass:** [Instance](Instance.md)

PathfindingLink is a class used to connect two locations that are otherwise unconnected. It defines properties for attachment and bidirectional traversal, along with methods for accessing the label and generating waypoints.

## Properties
### `PathfindingLink.Attachment0`
- **Type:** `[Attachment](Attachment.md)`
- **Summary:** The originating attachment of the link.

### `PathfindingLink.Attachment1`
- **Type:** `[Attachment](Attachment.md)`
- **Summary:** The landing attachment of the link.

### `PathfindingLink.IsBidirectional`
- **Type:** `boolean`
- **Summary:** Enables a path to traverse a link in both directions. The default value is `true`.

### `PathfindingLink.Label`
- **Type:** `string`
- **Summary:** A classifying string to add additional information about the link.
