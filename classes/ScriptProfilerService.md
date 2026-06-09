# ScriptProfilerService

**Superclass:** [Instance](Instance.md)

This file defines the `ScriptProfilerService` class, which is a script profiler service implemented as a class. It provides methods for reading and writing JSON data, and includes various methods for controlling the server's state.

## Tags
- NotCreatable
- Service

## Methods
### `ScriptProfilerService:ClientRequestData(player: [Player](Player.md)) -> ()`

### `ScriptProfilerService:ClientStart(player: [Player](Player.md), frequency: int?) -> ()`

### `ScriptProfilerService:ClientStop(player: [Player](Player.md)) -> ()`

### `ScriptProfilerService:DeserializeJSON(jsonString: string?) -> Dictionary`
- **Tags:** CustomLuaState

### `ScriptProfilerService:ServerRequestData() -> ()`

### `ScriptProfilerService:ServerStart(frequency: int?) -> ()`

### `ScriptProfilerService:ServerStop() -> ()`

## Events
### `ScriptProfilerService.OnNewData(player: [Player](Player.md), jsonString: string)`
