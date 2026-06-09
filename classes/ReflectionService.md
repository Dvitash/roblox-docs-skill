# ReflectionService

**Superclass:** [Instance](Instance.md)

The `ReflectionService` class allows scripts to query the Roblox API for details about an object's API, including required permissions and inheritance structure.

## Tags
- NotCreatable
- Service
- NotReplicated

## Methods
### `ReflectionService:GetClass(className: string, filter: Dictionary) -> Dictionary?`
- **Tags:** CustomLuaState
- **Summary:** Returns information about a class when given its name, assuming that class is accessible.

### `ReflectionService:GetClasses(filter: Dictionary) -> Array`
- **Tags:** CustomLuaState
- **Summary:** Returns a list of all classes accessible with filters applied.

### `ReflectionService:GetEventsOfClass(className: string, filter: Dictionary) -> Array`
- **Tags:** CustomLuaState
- **Summary:** Returns a list of events for a given class with filters applied.

### `ReflectionService:GetMethodsOfClass(className: string, filter: Dictionary) -> Array`
- **Tags:** CustomLuaState
- **Summary:** Returns a list of methods for a given class with filters applied.

### `ReflectionService:GetPropertiesOfClass(className: string, filter: Dictionary) -> Array`
- **Tags:** CustomLuaState
- **Summary:** Returns a list of properties for a given class with filters applied.
