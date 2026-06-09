# MarkerCurve

**Superclass:** [Instance](Instance.md)

MarkerCurve is a class for storing a list of string markers at specific times on a timeline, enforcing strict character limits and time constraints.

## Properties
### `MarkerCurve.Length`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Returns the number of markers in the MarkerCurve.

## Methods
### `MarkerCurve:GetMarkerAtIndex(index: int) -> Dictionary`
- **Summary:** Returns the time and string value of the marker at the provided index.

### `MarkerCurve:GetMarkers() -> Array`
- **Summary:** Returns the time and string value of all markers in the MarkerCurve.

### `MarkerCurve:InsertMarkerAtTime(time: float, marker: string) -> Array`
- **Summary:** Inserts a marker with the provided string value at the provided time.

### `MarkerCurve:RemoveMarkerAtIndex(startingIndex: int, count: int) -> int`
- **Summary:** Remove several markers in the MarkerCurve starting at the provided index.
