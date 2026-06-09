# Pages

**Superclass:** [Instance](Instance.md)

Pages is an abstract class for pages objects, which are essentially tables of sorted key/value pairs. It provides methods to iterate through the current page and retrieve its current items.

## Tags
- NotCreatable
- NotReplicated

## Properties
### `Pages.IsFinished`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Whether or not the current page is the last page available.

## Methods
### `Pages:AdvanceToNextPageAsync() -> ()`
- **Tags:** Yields
- **Summary:** Iterates to the next page in the pages object, if possible.

### `Pages:GetCurrentPage() -> Array`
- **Summary:** Returns the items on the current page. The keys in the item are determined by the source of this object.
