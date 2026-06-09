# RayValue

**Superclass:** [ValueBase](ValueBase.md)

A RayValue object stores a single ray, and it can be accessed via the Command bar or Studio properties. The text also notes that since rays cannot be edited in Studio, CFrameValues are often preferred for their ability to be reconstructed from a CFrame.

## Properties
### `RayValue.Value`
- **Type:** `Ray`
- **Summary:** The stored Ray.

## Events
### `RayValue.Changed(value: Ray)`
- **Summary:** Fired when `Class.RayValue.Value` is changed.

### `RayValue.changed(value: Ray)`
- **Tags:** Deprecated
