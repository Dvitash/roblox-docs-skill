# Object

The `Object` class is the base class for all Roblox class hierarchies, and it defines the base members that all other classes inherit.

## Tags
- NotCreatable
- NotReplicated

## Properties
### `Object.ClassName`
- **Type:** `string`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A read-only string representing the class this `Class.Object` belongs to.

### `Object.className`
- **Type:** `string`
- **Tags:** ReadOnly, NotReplicated, Deprecated

## Methods
### `Object:GetPropertyChangedSignal(property: string) -> RBXScriptSignal`
- **Summary:** Get an event that fires when a given property of the object changes.

### `Object:IsA(className: string) -> boolean`
- **Tags:** CustomLuaState
- **Summary:** Returns true if an object's class matches or inherits from a given class.

### `Object:isA(className: string) -> boolean`
- **Tags:** Deprecated, CustomLuaState

## Events
### `Object.Changed(property: string)`
- **Summary:** Fires immediately after a property of the object changes, with some limitations.
