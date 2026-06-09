# Selection

**Superclass:** [Instance](Instance.md)

The `Selection` class controls the selection of objects in Roblox Studio, allowing developers to access and manipulate selected instances.

## Tags
- NotCreatable
- Service

## Properties
### `Selection.SelectionThickness`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The thickness of the selection highlight outline drawn around selected `Class.Instance|Instances` in Roblox Studio's viewport.

## Methods
### `Selection:Add(instancesToAdd: Instances) -> ()`
- **Summary:** Adds the given `Class.Instance|Instances` to the current selection in Roblox Studio.

### `Selection:Get() -> Instances`
- **Summary:** Returns an array of currently selected `Class.Instance|Instances` in Roblox Studio.

### `Selection:Remove(instancesToRemove: Instances) -> ()`
- **Summary:** Removes the given `Class.Instance|Instances` from the current selection in Roblox Studio.

### `Selection:Set(selection: Instances) -> ()`
- **Summary:** Sets the currently selected objects in Roblox Studio to `Class.Instance|Instances` in the given array.

## Events
### `Selection.SelectionChanged()`
- **Summary:** Fires when the `Class.Instance|Instances` selected in Roblox Studio changes.
