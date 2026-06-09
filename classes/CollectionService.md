# CollectionService

**Superclass:** [Instance](Instance.md)

The `CollectionService` class manages instance collections with assigned tags, allowing users to add and remove tags for specific instances.

## Tags
- NotCreatable
- Service

## Methods
### `CollectionService:AddTag(instance: [Instance](Instance.md), tag: string) -> ()`
- **Tags:** CustomLuaState
- **Summary:** Applies a tag to an `Class.Instance`.

### `CollectionService:GetAllTags() -> Array`
- **Summary:** Returns an array of all tags in the experience.

### `CollectionService:GetCollection(class: string) -> Instances`
- **Tags:** Deprecated
- **Summary:** Returns all instances of a given class which are in the `Class.DataModel`.

### `CollectionService:GetInstanceAddedSignal(tag: string) -> RBXScriptSignal`
- **Summary:** Returns a signal that fires when a given tag is added to an instance.

### `CollectionService:GetInstanceRemovedSignal(tag: string) -> RBXScriptSignal`
- **Summary:** Returns a signal that fires when a given tag is removed from an instance.

### `CollectionService:GetTagged(tag: string) -> Instances`
- **Summary:** Returns an array of instances in the game with a given tag.

### `CollectionService:GetTags(instance: [Instance](Instance.md)) -> Array`
- **Tags:** CustomLuaState
- **Summary:** Gets an array of all tags applied to a given instance.

### `CollectionService:HasTag(instance: [Instance](Instance.md), tag: string) -> boolean`
- **Tags:** CustomLuaState
- **Summary:** Check whether an instance has a given tag.

### `CollectionService:RemoveTag(instance: [Instance](Instance.md), tag: string) -> ()`
- **Tags:** CustomLuaState
- **Summary:** Removes a tag from an instance.

## Events
### `CollectionService.ItemAdded(instance: [Instance](Instance.md))`
- **Tags:** Deprecated
- **Summary:** Fires when a `Class.Configuration`, `Class.CustomEvent`, `Class.CustomEventReceiver`, `Class.Dialog`, or `Class.VehicleSeat` is added to the `Class.DataModel`.

### `CollectionService.ItemRemoved(instance: [Instance](Instance.md))`
- **Tags:** Deprecated
- **Summary:** Fires when a `Class.Configuration`, `Class.CustomEvent`, `Class.CustomEventReceiver`, `Class.Dialog`, or `Class.VehicleSeat` is removed from the `Class.DataModel`.

### `CollectionService.TagAdded(tag: string)`
- **Summary:** Fires when a tag is added to an instance and the added tag is the only occurrence of that tag in the place.

### `CollectionService.TagRemoved(tag: string)`
- **Summary:** Fires when a tag is removed from an instance and the removed tag is no longer used anywhere in the place.
