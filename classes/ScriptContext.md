# ScriptContext

**Superclass:** [Instance](Instance.md)

This class is a service that controls `Class.BaseScript` objects, restricting access to properties and methods for internal use.

## Tags
- NotCreatable
- Service
- NotReplicated

## Methods
### `ScriptContext:EnableCoverage(instance: [Instance](Instance.md)) -> ()`

### `ScriptContext:GetCoverageStats() -> Array`

### `ScriptContext:SetTimeout(seconds: double) -> ()`
- **Summary:** Limits how long a script is allowed to run without yielding.

## Events
### `ScriptContext.Error(message: string, stackTrace: string, script: [Instance](Instance.md))`
- **Summary:** Fired when an error occurs.
