# File

**Superclass:** [Instance](Instance.md)

An `Instance` class represents an asset loaded from a file on disk, which generates a temporary asset ID and is not shared across sessions.

## Tags
- NotCreatable
- NotReplicated

## Properties
### `File.Size`
- **Type:** `int64`
- **Tags:** Hidden, ReadOnly, NotReplicated
- **Summary:** The size of the file on disk, in bytes.

## Methods
### `File:GetBinaryContents() -> string`
- **Summary:** Reads the contents of the `Class.File` as a string.

### `File:GetTemporaryId() -> ContentId`
- **Summary:** Gets a `rbxtemp://` asset ID for this `Class.File`.
